# CLISetup Installer + Compiler + GUI Editor
This repo hosts the source code of:
* The `clisc` compiler for CLISetup scripts
* The GUI editor for CLISetup (`clisgui`)
* Code that generates the installers
## Usage
To start a GUI editor from your command-line, type `clisgui` and press <kbd>Enter</kbd>.

Click "Save and Compile" to compile the script and save it for future editing.
## License
CLISetup is licensed under the [Apache License version 2.0](./LICENSE).

Note that some libraries incoporated into this program may be licensed under different terms.
This program may contain GPL-licensed libraries, so you may not be able to distribute binaries
of CLISetup without first removing and re-implementing the GPLed libraries. (To do this, run
`cleanup-clisetup.py`.)

For compatibility reasons, changes made by pull requests must not require any GPLv2-licensed
libraries. However, adding GPLv3ed libraries are OK.
