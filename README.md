# snapshot-analyzere-30000
Demo to project to analyze AWS EC2 Instance snapshots


## About

This is a project demo and uses boto3 to manage
AWS EC2 instance snapshots

## Configuring
shotty uses the config file created by the AWS cli e.g

`aws configure --profile shotty`


## Running

`pipenv run "python shotty/shotty.py"`

*command* is list, start or stop_instances
*project* is optional
