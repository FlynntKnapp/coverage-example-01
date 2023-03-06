# `coverage report --help`

```bash
(coverage-example-01) PS C:\Users\FlynntKnapp\Programming\coverage-example-01> coverage report --help
Usage: coverage report [options] [modules]

Report coverage statistics on modules.

Options:
  --contexts=REGEX1,REGEX2,...
                        Only display data from lines covered in the given
                        contexts. Accepts Python regexes, which must be
                        quoted.
  --data-file=INFILE    Read coverage data for report generation from this
                        file. Defaults to '.coverage'. [env: COVERAGE_FILE]
  --fail-under=MIN      Exit with a status of 2 if the total coverage is less
                        than MIN.
  --format=FORMAT       Output format, either text (default), markdown, or
                        total.
  -i, --ignore-errors   Ignore errors while reading source files.
  --include=PAT1,PAT2,...
                        Include only files whose paths match one of these
                        patterns. Accepts shell-style wildcards, which must be
                        quoted.
  --omit=PAT1,PAT2,...  Omit files whose paths match one of these patterns.
                        Accepts shell-style wildcards, which must be quoted.
  --precision=N         Number of digits after the decimal point to display
                        for reported coverage percentages.
  --sort=COLUMN         Sort the report by the named column: name, stmts,
                        miss, branch, brpart, or cover. Default is name.
  -m, --show-missing    Show line numbers of statements in each module that
                        weren't executed.
  --skip-covered        Skip files with 100% coverage.
  --no-skip-covered     Disable --skip-covered.
  --skip-empty          Skip files with no code.
  --debug=OPTS          Debug options, separated by commas. [env:
                        COVERAGE_DEBUG]
  -h, --help            Get help on this command.
  --rcfile=RCFILE       Specify configuration file. By default '.coveragerc',
                        'setup.cfg', 'tox.ini', and 'pyproject.toml' are
                        tried. [env: COVERAGE_RCFILE]

Full documentation is at https://coverage.readthedocs.io/en/7.2.1
(coverage-example-01) PS C:\Users\FlynntKnapp\Programming\coverage-example-01>
```
