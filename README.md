# aws-cloudwatch-windows

1: The CloudWatch plug-in for EC2Config is disabled by default, so the first step that needs to be taken is to enable it.  Search EC2ConfigService Settings  and enable cloudwatch logging

2: Go to C:\Program Files\Amazon\Ec2ConfigService\Settings\ and edit this AWS.EC2.Windows.CloudWatch.json script from following attached script . Script is tricky

3: We can attache the IAM role with the instance at the time of creation or IAM access and Screct key in the script

4: Now restart the ec2config from Services
