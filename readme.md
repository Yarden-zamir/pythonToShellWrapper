
https://github.com/Yarden-zamir/homebrew-tap
# Concept 
...
## Installation
```bash
brew install yarden-zamir/tap/wrap
wrap install
```
## Example
```
 Usage: wrap [OPTIONS] COMMAND [ARGS]...
╭─ Options ────────────────────────────────────────────────────────────────────────────╮
│ --install-completion        [bash|zsh|fish|powershell|p  Install completion for the  │
│                             wsh]                         specified shell.            │
│                                                          [default: None]             │
│ --show-completion           [bash|zsh|fish|powershell|p  Show completion for the     │
│                             wsh]                         specified shell, to copy it │
│                                                          or customize the            │
│                                                          installation.               │
│                                                          [default: None]             │
│ --help                                                   Show this message and exit. │
╰──────────────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────────────╮
│ gen      The main function of wrap, this will process all files in the input path    │
│          using the processors in the processor path and output the results to the    │
│          output path                                                                 │
│ install  Installs a default configuration for wrap using the base processors and     │
│          some sensible defaults (wrap can be used without this) also imports         │
│          examples :param install_to_shell: the shell to install to                   │
╰──────────────────────────────────────────────────────────────────────────────────────╯



```

## Terminology

- inputs
- wraps
- processors


