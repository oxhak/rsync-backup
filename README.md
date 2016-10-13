# rsync-backup
Backup Your Whole System Into A Folder

Maintains the rights and properties of files when copying.

How to restore from this backup ?

$DESTINATION="/"
$SOURCE="/backup"
sudo rsync -aAXvH --ignore-errors --numeric-ids --delete-excluded --progress $SOURCE $DESTINATION;
