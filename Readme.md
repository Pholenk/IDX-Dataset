# IDX Dataset

This repository contains machine-readable datasets derived
from files published by the Indonesia Stock Exchange (IDX).

## Files

```
.
├── dataset/                           # Directory of dataset
    ├── indices/                       # Directory of index dataset
        └── csv                        # csv files from .xlsx file for each index
        └── json                       # json files from .csv file for each index
    ├── stocks/                        # Directory of stock ticker dataset
        └── csv                        # csv files from .xlsx file for each stock ticker
        └── json                       # json files from .csv file for each stock ticker
    └── dataset-metadata.json          # metadata for kaggle
├── licenses                           # Directory of code and data license
└── metadata.json                      # metadata for entire project
```

---

## Source

The original data belongs to [Indonesia Stock Exchange](https://www.idx.co.id).

Last visited: [same as stated in last_updated](https://github.com/Pholenk/IDX-Dataset/blob/976d334295f39452d8331e4e7da2bbe3d3ebf556/metadata.json#L5)

**_Please note that you may find data missing on some dates even if those dates are not listed as market holidays.
You can verify this by visiting the website and entering the dates manually._**

---

## Format

Datasets are provided in:

- CSV
- JSON

---

## Update Frequency

Daily

---

## License

This dataset is licensed under the Open Database License (ODbL) v1.0.

You are free to:
- Share
- Adapt
- Use commercially

As long as you:
- Attribute the source
- Share any derivative databases under the same license

Full license text:
https://opendatacommons.org/licenses/odbl/odbl-10.txt

---

## Support

If you find this dataset helps your research / project:

[Saweria](https://saweria.co/pholenkadi17)

_PS: Because I'm Indonesian and live here I can't find any other method to receive foreign financial support._
