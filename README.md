# PyrestTest_Repo

## What is Pyresttest?

* A REST testing and API microbenchmarking tool.
* Tests are defined in basic YAML or JSON config files, no code needed
* Minimal dependencies (pycurl, pyyaml, optionally future), making it easy to deploy on-server for smoketests/healthchecks
* Supports generate/extract/validate mechanisms to create full test scenarios
* Returns exit codes on failure, to slot into automated configuration management/orchestration tools (also supplies parseable logs)
* Logic is written and extensible in Python

## Command to Run yaml file using Pyresttest:
```
pyresttest <http://url> yamlfile
```

## References:

* [Learn about Pyresttest](https://github.com/svanoort/pyresttest)
