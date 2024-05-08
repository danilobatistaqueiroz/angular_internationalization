# Localizations

To remove pnpm-lock.yaml from the git change detection: `git update-index --assume-unchanged pnpm-lock.yaml`  

To add localize: `ng add @angular/localize`  

To export the messages file: `ng extract-i18n localizations`  

To build the project localized: `ng build --localize`  

Running using another localization: `pnpm run start:en`
