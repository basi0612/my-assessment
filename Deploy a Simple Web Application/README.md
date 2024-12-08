Hosting on AWS S3 

Step 1: Create an S3 Bucket
Log in to your AWS Management Console.
Navigate to S3 > Create Bucket.
Provide a globally unique name (e.g., my-open-source-app).
Select a region (e.g., us-east-2).
Uncheck Block all public access for public website hosting.
Click Create Bucket.

Step 2: Upload Your Files
Open the S3 bucket and click Upload.
Drag and drop all your static files (e.g., index.html, assets/ folder) into the bucket and confirm upload.

Step 3: Set Permissions
Go to the Permissions tab of the bucket.
Under Block Public Access, ensure the bucket allows public access by unchecking restrictions.
Add a Bucket Policy for public access

Step 4: Enable Static Website Hosting
Go to the Properties tab and scroll to Static website hosting.
Enable the feature and specify:
Index document: index.html.

Step 5 : Enable the ACL Access.
Go to edit bucket ownership and enable ACL and Make the objects in the bucket public.

Here is the Link for the static website hosted in the s3 : https://my-website-basith.s3.us-east-2.amazonaws.com/index.html

Conclusion
By using AWS S3 (free-tier) and open-source tools, you can deploy and manage static websites efficiently while ensuring they are publicly accessible. This approach balances cost, scalability, and ease of use, making it ideal for small to medium-sized projects.


