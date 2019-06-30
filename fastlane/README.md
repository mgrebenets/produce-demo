fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew cask install fastlane`

# Available Actions
## iOS
### ios create_app_id
```
fastlane ios create_app_id
```
Create new App ID(s) in developer portal

Options:

- username: Developer portal username.

- team_id: Development team ID.

- config: Pattern for Produce.yml lookup, e.g. '**/Produce.yml'.
### ios update_app_id
```
fastlane ios update_app_id
```
Update existing App ID(s) in developer portal

Options:

- username: Developer portal username.

- team_id: Development team ID.

- config: Pattern for Produce.yml lookup, e.g. '**/Produce.yml'.

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
