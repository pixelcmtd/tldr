# grub-script-check

> The program `grub-script-check` takes a GRUB script file and checks it for syntax errors.
> It may take a path as a non-option argument. If none is supplied, it will read from `stdin`.
> More information: <https://www.gnu.org/software/grub/manual/grub/html_node/Invoking-grub_002dscript_002dcheck.html>.

- Check a specific script file for syntax errors:

`grub-script-check {{path/to/grub_config_file}}`

- Display each line of input after reading it:

`grub-script-check {{[-v|--verbose]}}`

- Display help:

`grub-script-check --help`

- Display version:

`grub-script-check --version`
