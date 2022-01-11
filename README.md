# ts-blank-template

This is a [starter template][ts-blank-template] for a simple typescript project.

## How to setup

- `git clone https://github.com/Open-Source-Ghana/ts-blank-template.git`
- `cd ts-starter-template`
- `npm i` to install the packages
- `npm run prepare` to setup husky for git pre-commit
    add the following at the end of `.husky/pre-commit`
    ```
    npm run format
    npm run prettier
    npm run lint
    npm test
    ```
- `npm run dev` to run the project in development mode
- `npm run format` to format code
- `npm run git` to format, add and commit in the interactive mode

#

[ts-blank-template]: https://github.com/Open-Source-Ghana/ts-blank-template
