## Rsync
### Copy files to another location while also deleting from the source as you go.
rsync -a --ignore-existing --remove-source-files /source/ /destination/
