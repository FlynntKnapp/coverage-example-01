# `coverage --help`

```bash
(coverage-example-01) PS C:\Users\FlynntKnapp\Programming\coverage-example-01> coverage --help    
Coverage.py, version 7.2.1 with C extension
Measure, collect, and report on code coverage in Python programs.

usage: coverage <command> [options] [args]

Commands:
    annotate    Annotate source files with execution information.
    combine     Combine a number of data files.
    debug       Display information about the internals of coverage.py
    erase       Erase previously collected coverage data.
    help        Get help on using coverage.py.
    html        Create an HTML report.
    json        Create a JSON report of coverage results.
    lcov        Create an LCOV report of coverage results.
    report      Report coverage stats on modules.
    run         Run a Python program and measure code execution.
    xml         Create an XML report of coverage results.

Use "coverage help <command>" for detailed help on any command.
Full documentation is at https://coverage.readthedocs.io/en/7.2.1
(coverage-example-01) PS C:\Users\FlynntKnapp\Programming\coverage-example-01>
```

## Assortment of Commands

* `coverage run` - Run a Python program and measure code coverage
* `coverage report` - Report coverage stats
* `coverage html` - Generate an HTML report
* `coverage run .\manage.py test things -v 2` - Run tests and measure code coverage
* `coverage run --omit='**/migrations/*' .\manage.py test things -v 2`
* `coverage report -m` - Report coverage stats with missing lines
