# AWS_lambdafinction
this repo to let you know how to deploy a mount point to S3 storage from local file system and keep the backup updated.

$sudo apt install s3fs
$sudo apt update
$ echo <access_key>:<secret_access_key>~./passwd-s3fs
$ s3fs <bucket_name> <the_desired_folder> -o passwd_file=~/.passwd-s3fs
then it will show you the mount volumes by using this command
$ mount
