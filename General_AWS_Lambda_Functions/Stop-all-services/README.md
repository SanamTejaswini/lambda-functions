# Start-All-Services

This applies to multiple services and can be setup by writing same logic block for different service

For example : 

You will setup a event bridge with for stop with your cron expression and will pass a json with  key-value for stop

```batch
{
  "action": "stop"
}```

I have the code written for below services 

1. EC2
2. RDS
3. ECS
4. Autoscaling group

the lamblda will loop through all the regions and will stop the above mentioned services.