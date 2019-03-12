[![goodtables.io](https://goodtables.io/badge/github/ricklupton/uk-worldsteel-statistics.svg)](https://goodtables.io/github/ricklupton/uk-worldsteel-statistics)

Statistics on UK steel production from worldsteel for the period 1978--2008.

This repository is a [Data Package](https://frictionlessdata.io/data-packages/):
use the viewer to [browse the metadata and
data](https://data.okfn.org/tools/view?url=https%3A%2F%2Fgithub.com%2Fricklupton%2Fuk-worldsteel-statistics).

## Data

This data is reproduced from the [World Steel Association's statistical
yearbooks](https://www.worldsteel.org/steel-by-topic/statistics/steel-statistical-yearbook.html).

## Checking the data package

Install [Pipenv](https://pipenv.readthedocs.io/en/latest/), and then use it to
set up a Python environment with the *goodtables* package:

```
pipenv install
```

Check the validity of the `datapackage.json` and the data files:

```
pipenv run goodtables datapackage.json
```
