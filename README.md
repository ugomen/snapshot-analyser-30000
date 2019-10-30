# snapshot-analyser-30000
DEMO project to manage AWS EC2 instances

##About

This project is a demo, and uses boto3 to manage AWS EC2 instance snapshots

## Configuring

shotty uses the configuration file created by the AWS CLI .e.g

`aws configure --profile shotty`

##Running

`pipenv run python shotty.py <commands> <--project=PROJECT>"`

*command* is list, start, or stop
*project* is optional
