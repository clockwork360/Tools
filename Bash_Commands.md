## Rsync
### Copy files to another location while also deleting from the source as you go.
rsync -azv --ignore-existing --remove-source-files --progress /source/ /destination/
