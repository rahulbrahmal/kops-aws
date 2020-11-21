## Environment Setup
1. Ensure that you have Homebrew and the AWS CLI set up on your local machine
   a. run `brew install awscli`
   b. run `brew install kops`
   c. run `brew install kubectl`

   NOTE: Should you not be able to install Homebrew - please install these packages manually

2. Navigate to `./aws/creds` and insert your AWS Access Key, AWS Secret Access Key and Region (where you want the cluster deployed) into the file. I would recommend using an admin-level key for this step to ensure there are no permissions errors.

3. Run `source aws.env` to load your environment varialbles into your environment

4. You are now ready to create your cluster! Please refer to the `./create` folder for more information