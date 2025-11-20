# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-

# Name: Rohan j
# Register Number: 212223040171

# Aim
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS.  

# Procedure

## a) Steps to Create a First S3 Bucket

1. **Sign in to the AWS Management Console**  
   Go to [AWS S3 Console](https://console.aws.amazon.com/s3).

2. **Open the S3 Service**  
   In the console, type **S3** in the search bar and select **S3** to open the service dashboard.

3. **Create Bucket**  
   Click the **Create bucket** button.

4. **Configure Bucket Settings**  
   - **Bucket name:** Choose a globally unique name.  
   - **AWS Region:** Select the region where you want to store your data.

5. **Object Ownership**  
   Choose between:  
   - **ACLs disabled (recommended):** Bucket owner has full control.  
   - **ACLs enabled:** Control access via access control lists.

6. **Block Public Access Settings**  
   By default, all public access is blocked. Leave it as-is unless you need public access.

7. **Bucket Versioning (optional)**  
   Choose whether to enable versioning for objects in the bucket.

8. **Encryption (optional)**  
   Select encryption options: **SSE-S3**, **SSE-KMS**, or **none**.

9. **Advanced Settings (optional)**  
   Add tags, configure logging, etc.

10. **Create the Bucket**  
    Click **Create bucket** at the bottom of the page.

---

## b) Steps to Launch an EC2 Instance

1. Go to the **EC2 Dashboard** in AWS Console.  
2. Click on **Launch Instance**.  
3. Choose an **Amazon Machine Image (AMI)** (e.g., Amazon Linux).  
4. Select an **instance type** (e.g., `t2.micro` for Free Tier).  
5. Create or choose a **key pair** for SSH access.  
6. Configure **network settings** (use default VPC/subnet).  
7. Configure **storage** (default root volume is fine).  
8. Review the settings and click **Launch Instance**.  
9. Wait for the instance to enter the **running state**.

---

## c) Connect to Your Instance

- **Linux:** Use SSH command with your `.pem` key.  
- **Windows:** Use RDP with decrypted admin password.

---

## d) Steps to Clean Up (Terminate the Instance)

1. Go to **EC2 Instances**.  
2. Select your instance → **Instance State** → **Terminate**.

---

# Snapshots

**Snapshot 1:** Simple Storage Service (S3)  
<img width="1920" height="868" alt="output-1" src="https://github.com/user-attachments/assets/397639e1-cc81-4b5c-83d8-40adef8cdd67" />


**Snapshot 2:** EC2 (Elastic Compute Cloud) – Instance  
<img width="1920" height="1516" alt="output-2" src="https://github.com/user-attachments/assets/e70929ef-0c85-49f0-bc9c-4226ff9843ce" />


---

# Result
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) instance has been successfully created and launched in AWS.
 
