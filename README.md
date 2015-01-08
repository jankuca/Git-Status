# Get Status

Ever wanted to get the status of repos in multiple sub directories? Yeah, me 
too. So I knocked this up.

## Installation

Create a link to the file at `/usr/local/bin`

```bash
$ link -s show_status /usr/local/bin/show_status
```

## Usage

The command loops through direct subdirectories.

```bash
$ show_status [options]
```

- `-h, --help` – show this help message and exit
- `-d DIRNAME, --dir=DIRNAME` – The directory to parse sub dirs from
- `-v, --verbose` – Show the full detail of git status
- `--sync` – Sync the repository (pull, rebase, push). Changes are stashed.
- `--pull` – Pull
