# DEMO-AWS
# Deploying a Linux EC2 instance and connecting via SSH

-In This project, the goal is to launch an EC2 (elastic cloud compute) Linux instance on AWS (amazon web services) and establish a secure connection to it using the command line interface and SSH (secure shell) protocol.

# STEP 1:-

-Sign in to AWS management console.

![Screenshot (58)](https://github.com/user-attachments/assets/aa7bfa3c-547c-48c1-a146-f7f79249df0f)

# STEP 2:-

-Sign in to the AWS management console and search the EC2 service.

![Screenshot (59)](https://github.com/user-attachments/assets/ae65c904-ab4f-4c80-ad05-a97a93d37935)

# STEP 3:-

-From EC2 dashboard, go and select the Launch Instance.

![Screenshot (60)](https://github.com/user-attachments/assets/788af95a-1432-4960-b9ff-3e418ca38427)


# STEP 4:-

-Name your instance, choose an Amazon Machine Image (AMI) for linux server. You can choose from various linux distributions available.

![Screenshot (62)](https://github.com/user-attachments/assets/1a0179ba-94bc-4756-b6fb-8160e27d52e1)


# STEP 5:- 

-Select the instance type that suits your requirements. Consider the CPU memory, storage and network capacity you need.

![Screenshot (63)](https://github.com/user-attachments/assets/11ed0e57-93ab-45d0-9bd9-a2fcba246062)

# STEP 6:- 

-Int the key pair, select create new pair. Give unique name to your key pair. This key pair will be used to securely connect to the instance via SSH. (make sure to download and securely store the private key file (.pem) in a safe location.)

![Screenshot (64)](https://github.com/user-attachments/assets/249ec777-f3d9-422a-89aa-1a27bebe4f78)

-Here is your downloaded key pair file.

![Screenshot (65)](https://github.com/user-attachments/assets/920c9d9a-09cf-4663-ad19-8b858c1e6d3c)


# STEP 7:-

-Configure the network setting include subnet, security group, etc. If you are not sure, you can use default settings (Allow SSH (port 22) access. By default, incoming SSH traffic is blocked for security reasons.)

![Screenshot (66)](https://github.com/user-attachments/assets/7817d4cf-9535-4d84-8102-092584b02e91)


# STEP 8:-

-Configure the storage options for your instance. You can specify the size of the root volume and add the additional volumes if needed. Review all the configurations details youn have set for the instance. If everything looks good, click on "Launch Instance" to start the instance.

![Screenshot (67)](https://github.com/user-attachments/assets/701cb6bc-4426-47a9-9262-cf9f9ff5d902)

-Successfully initiated launch of "INSTANCE".

![Screenshot (68)](https://github.com/user-attachments/assets/ee5cd684-c580-46a7-a56a-6f9373abaaed)


# STEP 9:-

-Once the instance is running, you can connect it to using the CLI. Open your terminal or command prompt and navigate to the directory where your key pair is file is stored.

![Screenshot (69)](https://github.com/user-attachments/assets/cdf3f8ef-97ad-4291-ab85-2dd37ef4b874)


# STEP 10:-

-Go to the EC2 instance. At the bottom of the screen, you will see the section called "Connect". Click on the connect button. In the connection dialog, you will see different options for connecting to your instance such as EC2 Instance Connect, Session Manager and SSH. Select the "SSH Client" tab. Here you will find the SSH command that you can copy and paste into your CLI and then press enter to connect to your EC2 instance.

![Screenshot (70)](https://github.com/user-attachments/assets/ef19eed7-0fb1-4c2b-ad2f-b854030efa97)

![Screenshot (72)](https://github.com/user-attachments/assets/3b4e6e86-9461-4f47-aae0-3ce5ed80925b)

![Screenshot (73)](https://github.com/user-attachments/assets/79ecc240-1ce9-43e5-bb4e-e524aebec5af)

# That's it! You have successfully Deployed a Linux EC2 Instance and Connected via SSH.
