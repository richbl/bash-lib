# Bash-Lib

## [<img src="https://github.com/user-attachments/assets/4dc1e16e-3fd3-481c-9a43-b027c029dd27" width="150" />](https://github.com/richbl/a-bash-template)[Developed for a Bash Template (BaT)](https://github.com/richbl/a-bash-template)

**Bash-Lib** is a library of common [Bash](https://en.wikipedia.org/wiki/Bash_%28Unix_shell%29) shell routines used in projects based on the [A-Bash-Template (BaT)](https://github.com/richbl/a-bash-template) project. This library is broken into two files:

- `general`
    - Routines created to:
        - Check program dependencies
        - Check file dependencies
        - From a JSON configuration file, dynamically format and display a program banner, e.g.

    ```bash
    |
    | A bash template (BaT) to ease argument parsing and management
    |
    | Usage:
    |   bash_template.sh -a alpha -b bravo [-c charlie] -d delta
    |
    |   -a, --alpha    alpha (something descriptive)
    |   -b, --bravo    bravo (something descriptive)
    |   -c, --charlie  charlie (this is optional)
    |   -d, --delta    delta (something descriptive)
    |
    ```

- `args`
    - Routines created to:
        - Parse a JSON file for program configuration details
        - Scan command-line arguments for accuracy and completeness

For details on how the various routines of this library project are used, see the [A-Bash-Template (BaT)](https://github.com/richbl/a-bash-template#a-bash-template) project.

## Yes, We Are [Dogfooding](https://en.wikipedia.org/wiki/Eating_your_own_dog_food) This Project

Of course we are! Otherwise, what value does a BaT offer if it doesn't get used often enough to warrant the time to develop a BaT?

All of our bash scripts have been written to use this project. It's cut our development time, and made it easier to provide updates and added functionality without having to spend time reinventing the wheel every time. Check out all of our projects here on [Github](https://github.com/richbl).


## <picture><source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/2356369f-c752-4e55-8443-49f4174df4b5" width="30"><source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/2356369f-c752-4e55-8443-49f4174df4b5" width="30"><img src="https://github.com/user-attachments/assets/2356369f-c752-4e55-8443-49f4174df4b5" width="30"></picture>  This Project Uses Git Submodules <picture><source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/2356369f-c752-4e55-8443-49f4174df4b5" width="30"><source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/2356369f-c752-4e55-8443-49f4174df4b5" width="30"><img src="https://github.com/user-attachments/assets/2356369f-c752-4e55-8443-49f4174df4b5" width="30"></picture>

This project is managed as a [Git submodule project(s)](https://git-scm.com/book/en/v2/Git-Tools-Submodules) to keep projects that use this library stable while this library is periodically updated.