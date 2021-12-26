# Security Policy

## Supported Versions

Currently the project is in version 1.0.0, and is being supported and maintained.

| Version | Supported          |
| ------- | ------------------ |
| 1.0.0   | :white_check_mark: |

## Reporting a Vulnerability

To report a vulnerability, please contact the discord admins of the server. They will be denoted with "admin" roles. 

## Security for Users

When using the ERT-Bot, note that within the code "os.environ["SOMETHING"]" is used quite often. These variables are dependant on the spreadsheet, server, channels, webhooks, and other variables that you set up, and each unique item will have its own criteria that go within these variables. Do not let these variables be public, as anyone with access to the variables will be able to manipulate the workings of the bot.
