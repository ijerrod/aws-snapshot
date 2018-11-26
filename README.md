# aws-snapshot
Manage AWS EC2 instance snapshots

## About
Uses Boto3 to manage AWS EC2 instance snapshots

## Configure
script uses the configuration file created by AWS cli

`aws configure --profile snapshot`

## Running

`pipenv run "python snapshot\snap.py <command> <--project=PROJECT>"`
*command* list, stop, start, or snapshots
*subcommand* - depends on command
*project* optional
