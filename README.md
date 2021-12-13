# Bash-Lib

## [<img src="https://user-images.githubusercontent.com/10182110/145758715-b127adfc-710b-49d3-9ede-151adc83ae76.png" width="150" />](https://github.com/richbl/a-bash-template)[Developed for a Bash Template (BaT)](https://github.com/richbl/a-bash-template)

**Bash-Lib** is a library of common [bash](https://en.wikipedia.org/wiki/Bash_%28Unix_shell%29) routines used in projects based on the [a-bash-template (BaT)](https://github.com/richbl/a-bash-template) project. This library is broken into two files:

- `general`: Routines created to:
  - Check program dependencies
  - Check file dependencies
  - Format and display a program banner, e.g.,
>>
    |
    | A bash template (BaT) to ease argument parsing and management
    |   0.2.0
    |
    | Usage:
    |   bash_template.sh -a alpha -b bravo [-c charlie] -d delta
    |
    |   -a, --alpha    alpha (something descriptive)
    |   -b, --bravo    bravo (something descriptive)
    |   -c, --charlie  charlie (this is optional)
    |   -d, --delta    delta (something descriptive)
    |

- `args`: Routines created to:
  - Parse a JSON file for program configuration details
  - Scan command-line arguments for accuracy and completeness

For details on how the various routines of this library project are used, see the [A-Bash-Template (BaT)](https://github.com/richbl/a-bash-template#a-bash-template) project.

> Note that this project is managed as a Git [submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules) project specifically to keep projects that use this library up-to-date without manual intervention.
