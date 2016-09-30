ZSH Emojis
==========

Contains numerous ascii emojis stored as shell variables.

```
$ echo $shrug
¯\_(ツ)_/¯
```

On linux you can echo the variables straight into your clipboard with `xsel` package.

```
$ echo $shrug | xsel -i -b
```

You can easily see a list of current ascii emojis within the `emojis.plugin.zsh` file.

:tada: **Contributions are welcomed!** :tada:

Installation
------------

zsh-emojis is really easy to install using `antigen`. Just add the following command to your `.zshrc` file

```
antigen bundle MichaelAquilina/zsh-emojis
```

Same applies to installing from `zgen`

```
zgen bundle MichaelAquilina/zsh-emojis
```
