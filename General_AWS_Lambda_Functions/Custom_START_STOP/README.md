# Start-Stop-Script

This applies to multiple services and can be setup by writing same block for different service

For example : 

EC2 servers are tagged with "Env : UAT"

You will setup a event bridge with for stop with your cron expression and will pass a json with 3 key-value pairs

```batch
{
  "tagname": "ENV",
  "tagvalue": "UAT",
  "action": "stop"
}```

A second trigger will be there for start will will contain the same time but the action will be start

```batch
{
  "tagname": "ENV",
  "tagvalue": "UAT",
  "action": "start"
}```