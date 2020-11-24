# bash-base-command-sample
This repository is a bash base command sample.

## Example

### Not enough arguments.

```bash
$./example
Usage: example [ARGS1] [OPTIONS]...

Args1:
  Args1 is an example argument.

Options:
  -h, --help  Show this message and exit.
  -o, --optional  Optional is an example option
  -i, --is-true  Is-true is an example boolean option
```

### Specify the help option.

```bash
$./example --help
Usage: example [ARGS1] [OPTIONS]...

Args1:
  Args1 is an example argument.

Options:
  -h, --help  Show this message and exit.
  -o, --optional  Optional is an example option
  -i, --is-true  Is-true is an example boolean option
```

### Execute

```bash
$./example args1
args1

false
```

```bash
$./example args1 --optional option --is-true
args1
option
true
```

