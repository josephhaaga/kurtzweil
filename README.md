# kurtzweil

A reference setup for PEP-518 packages

* Uses `setup.cfg` for declarative metadata
* Uses `pyproject.toml` because that's the future
* Doesn't require `src` layout

Note that running `python3 -m pytest` from the root will test the source code in `kurtzweil`. Running `pytest` from elsewhere may test your installed version of the package

## Usage

```sh
$ python3 setup.py sdist bdist_wheel
```
