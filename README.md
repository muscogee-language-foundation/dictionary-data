# Data for Mvskoke Dictionary
Using [Mother Tongues Dictionary](https://www.mothertongues.org)

[![license](https://img.shields.io/github/license/MotherTongues/mtd-starter.svg)](LICENSE)
[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

For more info about Mother Tongues Dictionary, visit the [repo](https://github.com/MotherTongues/mothertongues) or [docs](https://docs.mothertongues.org)

## Usage
Use alongside the flutter frontend for [Mvskoke Dictionary App](https://github.com/muscogee-language-foundation/mvskoke-dictionary) 

To run:
- First clone this repo.  
- Then follow the docs to install the [mothertongues](https://docs.mothertongues.org/latest/developer/prerequisites/) repo and python package.
- Build the .json file: `poetry run mothertongues build-and-run <repo_location>/config.mtd.json `
- Export the `dictionary_data.json` file from `<MTD_repo>/mothertongues/ui/assets/dictionary_data.json` and copy it to the `assets` folder in the repo for the UI [mvskoke-dictionary](https://github.com/muscogee-language-foundation/mvskoke-dictionary)
- Continue following the instructions there for building and deploying the flutter app. 

## Contributing

If something is not working, or you'd like to see another feature added, feel free to dive in! [Open an issue](https://github.com/MotherTongues/mothertongues/issues/new) or submit PRs. Help writing and clarifying documentation is also very welcome.

This repo follows the [Contributor Covenant](http://contributor-covenant.org/version/1/3/0/) Code of Conduct.

## Acknowledgements

Thank you to both Patrick Littell & Mark Turin for their contributions, guidance and support as well as institutional support from the [First Peoples&#39; Cultural Council](http://www.fpcc.ca/) and SSHRC Insight Grant 435-2016-1694, ‘Enhancing Lexical Resources for BC First Nations Languages’.

Thank you to all other contributors for support with improving MotherTongues, finding bugs and writing documentation.

### Contributors

This project exists thanks to all the people who contribute.  Thank you to Aidan Pine for all his work.
