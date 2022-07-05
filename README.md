# rfc3339-validator

A pure python RFC3339 validator


[![image](https://img.shields.io/pypi/v/rfc3339_validator.svg)](https://pypi.python.org/pypi/rfc3339_validator)
[![CI](https://github.com/naimetti/rfc3339-validator/actions/workflows/ci.yml/badge.svg)](https://github.com/naimetti/rfc3339-validator/actions/workflows/ci.yml)

# Install

```shell script
pip install rfc3339-validator
```

# Usage

```python
from rfc3339_validator import validate_rfc3339

validate_rfc3339('1424-45-93T15:32:12.9023368Z')
>>> False

validate_rfc3339('2001-10-23T15:32:12.9023368Z')
>>> True
```


  - Free software: MIT license
