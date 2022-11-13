# The website links
Link via static config from s3 bucket:

http://my-11151017372-bucket.s3-website-us-east-1.amazonaws.com/

Link of the object from s3 bucket:

https://my-11151017372-bucket.s3.amazonaws.com/index.html

Link through the CDN (Cloud Front) distro:

https://d2uvhfxm0ruujf.cloudfront.net/

## The process
- create the S3 bucket

![Image](S3_bucket_created.png)

- Upload the files to the bucket

![Image](Project_files_uploaded_to_the_bucket.png)

- Bucket Polices applied

![Image](Bucket_Polices.png)

- Allow the Static Hosting via Bucket config

![image](S3_config_to_host_static_websites.png)

- create the CDN through the Cloud front service AWS

![image](CDN(CloudFront).png)

- Links through different access

![image](Link_through_the_bucket_static_hosting_config.png)

![image](Link_of_the_CDN_distro.png)

![image](Object_link_through_the_bucket.png)

![image] 
## Thanks 
- Mahmoud Galal
