## tanzu login completion fish

generate the autocompletion script for fish

### Synopsis


Generate the autocompletion script for the fish shell.

To load completions in your current shell session:
$ login completion fish | source

To load completions for every new session, execute once:
$ login completion fish > ~/.config/fish/completions/login.fish

You will need to start a new shell for this setup to take effect.


```
tanzu login completion fish [flags]
```

### Options

```
  -h, --help              help for fish
      --no-descriptions   disable completion descriptions
```

### SEE ALSO

* [tanzu login completion](tanzu_login_completion.md)	 - generate the autocompletion script for the specified shell

###### Auto generated by spf13/cobra on 5-Nov-2021