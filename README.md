# JSON Datasets 🌎

> Example of various datasets in JSON format for different usages.

## Programming languages

### 1. Programming languages and their keywords

JSON file of programming languages and their keywords. Additionally it contains a summary and extensions fields. Originally adapted from https://github.com/leighmcculloch/keywords.

__File:__ [programming_languages_keywords.json](./json/programming-languages/programming_languages_keywords.json)

__Structure:__

```json
{
    "name": "Rust",
    "version": 1.31,
    "summary": "A programming language that empowers everyone to build reliable and efficient software.",
    "extensions": [
        "rs",
        "rlib"
    ],
    "keywords": [ "trait", "impl", "struct", "pub", "let" ],
    "sources": [
        "https://doc.rust-lang.org/grammar.html#keywords"
    ]
}
```

## Currencies

### 1. Current JSON list of all currency symbols

Current JSON list of all currency symbols from the [Currency Code Services – ISO 4217 / Currency & funds code list](https://www.currency-iso.org/en/home/tables.html)

__File:__ [currencies_medium.json](./json/currencies/currencies_medium.json)

__Structure:__

```json
{
    "country_name": "PERU",
    "currency_name": "Sol",
    "currency_iso_code": "PEN",
    "currency_number": "604",
    "currency_mnr_unts": "2"
},
```

### 2. Simple current JSON list of currency symbols

Current JSON list of all currency symbols from the [Open Exchange Rates API](https://docs.openexchangerates.org/docs/currencies-json).

__File:__ [currencies_simple.json](./json/currencies/currencies_simple.json)

__Structure:__

```json
{
    "EUR": "Euro",
    "FJD": "Fijian Dollar",
    "FKP": "Falkland Islands Pound",
    "GBP": "British Pound Sterling",
    "GEL": "Georgian Lari",
},
```

### 3. Historic denominations of currencies

Historic denominations of currencies and funds by [Currency Code Services – ISO 4217](https://www.currency-iso.org/en/home/tables/table-a3.html)

__File:__ [currencies_historical.json](./json/currencies/currencies_historical.json)

__Structure:__

```json
{
    "country_name": "GERMANY",
    "currency_name": "Deutsche Mark",
    "currency_iso_code": "DEM",
    "currency_number": "276",
    "currency_wthdrwl_dt": "2002-03"
},
```

## Contributions

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in current work by you, as defined in the Apache-2.0 license, shall be dual licensed as described below, without any additional terms or conditions.

Feel free to send some [Pull request](https://github.com/joseluisq/json-datasets/pulls) or [issue](https://github.com/joseluisq/json-datasets/issues).

## License

This work is primarily distributed under the terms of both the [MIT license](LICENSE-MIT) and the [Apache License (Version 2.0)](LICENSE-APACHE).

© 2020-present [Jose Quintana](https://git.io/joseluisq)
