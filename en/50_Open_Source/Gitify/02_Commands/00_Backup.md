`Gitify backup`

Added in 0.7. Creates a backup of your full MySQL database. The backup will be written to the directory specified by the `backup_directory` option in your `.gitify` file. 

````
Usage:
 backup [name]

Arguments:
 name                  Optionally the name of the backup file, useful for milestone backups. If not specified the file name will be a full timestamp.

Options:
 --help (-h)           Display this help message.
 --verbose (-v|vv|vvv) Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug.
 --version (-V)        Display the Gitify version.

````
