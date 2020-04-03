# Octo Template

<small>_Optimized for python 3.6_</small>

This is a project template. Used in other repositories.

----------------------

## Dependencies

For installing the requirements, in your ___venv___ or ___anaconda env___, 
just run the following command:

```shell script
pip install -r requirements.txt
```
----------------

## Project's Structure

```bash 
.
└── octo-template
    ├── data
    │   ├── data.csv
    │   ├── data.db
    │   └── data.xlsx
    ├── docs
    │   └── CREDITS
    ├── src
    │   ├── __init__.py
    │   └── settings.json
    ├── tests
    │   └── unittests
    │       └── __init__.py
    ├── .gitignore
    ├── LICENSE
    ├── README.md
    └── requirements.txt
```

#### Directory description

- __data:__ The data dir. Group of non-script support files.
- __docs:__ The documentation dir.
- __src:__ The scripts & source code dir.
- __tests:__ The unittests dir.

----------------

## Usage Notes

Section aimed on clarifying some running issues.

### Running

For running it, at the `~/src` directory just run:

```shell script
python octo-template.py
``` 

or, if importing it as a module, just run:
````python
from octo-template import Template

if __name__ == '__main__':
    Template('args', 'kwargs').__call__()
````

### JSON structure

````json
{
  "API_URL": "",
  "API_KEY" : "",
  "API_PROXY": {
    "http": "",
    "https": ""
  }
}
````

_obs: in order to run this application you must have a json file at `~/src/settings.json`. This json must follow the structure above._

---------------
