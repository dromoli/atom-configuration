# atom-configuration
My atom configuration

## Export

Copy from ${user}/.atom:

config.cson
keymap.cson
snippets.cson
styles.less

Save installed packages list apm list --installed --bare > packages.list


## Import

Replace files from Backup 1 part in 

${user}/.atom

Restore packages from packages.list mentioned in Backup 2 by:

`apm install --packages-file packages.list` 

or

`apm install 'cat packages.list'`
