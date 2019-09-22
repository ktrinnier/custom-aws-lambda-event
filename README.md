# custom-aws-lambda-event

This is a custom struct that allows unmarshaling the details of an AWS CloudWatch event into this struct. You can then use this struct to easily parse the data.  

I am currently using this to detect when an EC2 instance is created and is missing required tags.