# FDAP Sample Data Files

GitHub requires that files be less than 100MB (50MB recommended). Note that by default GitHub does not turn `csv` files into downloads, so you may have to choose `Save As…` in your web browser.

**Caution:**
1. Data may not be up to date (and may be inaccurate for other reasons); do not rely on materials in this repository for any critical analysis
2. Data is undocumented, and variables may not be what you expect

## Daily S&P 500 data (`sp500d.csv`)
[Download](sp500d.csv)

Source: CRSP via WRDS
```python
wrds_username = "YOUR_USERNAME"
db = wrds.Connection(wrds_username = wrds_username)
sp500d = db.get_table("crsp", "dsp500", columns=['caldt', 'spindx', 'sprtrn', 'vwretd', 'vwretx'], date_cols=['caldt'], index_col=['caldt'])
db.close()
sp500d.to_csv(r'sp500d.csv')
```

## Monthly S&P 500 data (`sp500m.csv`)
[Download](sp500m.csv)

Source: CRSP via WRDS
```python
wrds_username = "YOUR_USERNAME"
db = wrds.Connection(wrds_username = wrds_username)
sp500m = db.get_table("crsp", "msp500", columns=['caldt', 'spindx', 'sprtrn', 'vwretd', 'vwretx'], date_cols=['caldt'], index_col=['caldt'])
db.close()
sp500m.to_csv(r'sp500m.csv')
```

## Monthly tech stock returns (`monthly-tech.csv`)
[Download](monthly-tech.csv)

Source: [Cameron Pfiffer](https://cameron.pfiffer.org)


### Additional submissions welcome!