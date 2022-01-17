# CS561SoftwareEngineeringMethods
API mocking using EC2 instance
URL to check the apimocking: http://3.87.240.235:7878/data/2.5/weather

The following steps are the process of apimocking in an EC2 instance of AWS

Step 1: Create a new EC2 instance in your AWS.
Step 2: Now, connect the EC2 instance once it's in the running state. 
Step 3: Install node and apimocker along with git which will aid you in cloning the repository
Step 4: use command sudo yum install git -y to install git
Step 5: follow https://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/setting-up-node-on-ec2-instance.html to install node
Step 6: use command npm install -g apimocker to install apimocker.
Step 7: Use git clone to clone your repository into your desired directory
Step 8: Now, go to the config.json file and edit mockdirectory path to your pwd path and save it.
Step 9: Finally, run the command apimocker -c config.json
Step 10: Now, open other terminal from EC2 instance and run the command curl "your url"
Step 11: FInally, it displays the information of the weather at corvallis and verfies that the api is successfully mocked.

