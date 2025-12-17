## man page installation
To install the manpages move or copy the contents of the `man` directory into `/usr/local/man` (e.g. `man/man1` -> `/usr/local/man/man1`.

Use for example
```bash
sudo cp -r man /usr/local/man
```

When the manpages are installed you can simply call them with the `man` command
```bash
man jsh
```

## Viewing without installation
When you want to view/read the manpages without installing them on your system, you have to call them with the `man` command while specifying their path.
```bash
man ./man/man1/jsh.1
```
