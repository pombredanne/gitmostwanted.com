[![wercker status](https://app.wercker.com/status/7767a5325ebf378ede0ac3016c992ebc/s "wercker status")](https://app.wercker.com/project/bykey/7767a5325ebf378ede0ac3016c992ebc)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/kkamkou/gitmostwanted.com/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/kkamkou/gitmostwanted.com/?branch=master)
[![Code Coverage](https://scrutinizer-ci.com/g/kkamkou/gitmostwanted.com/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/kkamkou/gitmostwanted.com/?branch=master)

# gitmostwanted
Advanced explorer of github.com. The main goal is to highlight the most interesting repositories and exclude others. You can find some concepts in the [Wiki](https://github.com/kkamkou/gitmostwanted.com/wiki).

## Donation
If you would like to help the project, please consider these topics:
- GMW uses [Google BigQuery](https://cloud.google.com/bigquery/pricing) and the service is pretty expensive.
- GMW is located on a private machine and hosted by [ProfitBricks](https://www.profitbricks.de/).

## Run (Python3)

```bash
# export PYTHONPATH="`pwd`:${PYTHONPATH}"
export GMW_APP_SETTINGS=/path/to/instance.cfg
python gitmostwanted/web.py
```

## Tests

```bash
py.test --pep8 --clearcache --cov gitmostwanted tests/unit
```

## Docker

```bash
[sudo] docker-compose up -d  # The first time it'll fail
```
