# Static Game Website Project
 This project shows a step by step guide to hosting a static game website ion AWS S3.
## Creating S3 Bucket
A bucket was created to host the static game website. 
### Steps
1. Choose your region, the closer your client is to a region the faster the access. 
2. Search S3 Bucket in the search bar.
![Image showing region selection and search bar](/Creating%20S3.png)
3. Click on Create Bucket.
4. Set bucket type to general purpose, give your bucket a name, and set object ownership to ACL disabled.
5. Uncheck block public access to allow public access.
6. Disable bucket versioning and leave default encryption as default. 
7. Create Bucket 
![Image of created S3 bucket](/Created%20S3%20Bucket.png)
8. Click on the created bucket, edit properties to enable static website hosting.
![Image showing how to edit S3 properties](/Edit%20S3%20Properties.png)
9. Scroll to the bottom of the properties page, enable static website, name static website with the same name of your code file or file to be hosted e.g index.html as well as the error file e.g error.html.
![Image showing how to enable static website](/Enable%20Static%20Website%20hosting.png)
10. Click on the created bucket and click on upload to upload files or folder. 
![Image showing how to upload files](/Uploading%20Object.png)
![image showing files uploading](/S3%20Add%20a%20file.png)
![image of uploaded file](/Uploaded%20S3%20File.png)
11. On the same page in the previous step, go to properties to choose storage class.
![Image on storage class selection](/S3%20Storage%20Class.png)
12. Click on the uploaded file and click on open. This will open your site on the browser.
![image to open file in browser](/Open%20file%20via%20browser.png)
13. Click on created bucket, go to properties and scroll to the bottom(Static Website Hosting). Copy the  bucket website hosting for your client to open the website on their browser.
14. You will get this game page once the link is copied to the browser.
![Image of game app](/Game%20App%20live.png)

