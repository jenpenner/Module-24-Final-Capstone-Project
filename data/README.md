# Data

The raw BRFSS data file is not committed to this repository due to its size (~64 MB zipped).

## How to Download

1. Go to the CDC BRFSS 2023 data page:  
   https://www.cdc.gov/brfss/annual_data/annual_2023.html

2. Click **"2023 BRFSS Data (SAS Transport Format)"** to download the ZIP file.

3. Unzip the file — you will get a file named `LLCP2023.XPT`.

4. Place `LLCP2023.XPT` in this `data/` folder.

Your directory should look like this:
```
data/
├── README.md        ← this file
└── LLCP2023.XPT    ← place the downloaded file here
```

The notebook will look for the file at `data/LLCP2023.XPT` relative to the `notebooks/` directory,
so make sure the folder structure matches.

## About the Dataset

| Property | Value |
|---|---|
| Source | CDC Behavioral Risk Factor Surveillance System (BRFSS) |
| Year | 2023 |
| Format | SAS Transport (.XPT) |
| Records | 433,323 |
| Variables | 345 |
| License | Public domain (U.S. Government) |
