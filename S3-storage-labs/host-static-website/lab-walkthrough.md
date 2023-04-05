# Hosting a basic Static Website on AWS - using AWS console
## Create bucket
- Sign in to the AWS Management Console and open the Amazon S3 console at [AWS Console](https://console.aws.amazon.com/s3/)
- Choose **Create bucket**.
- Enter the **Bucket name** (for example, example.com).
- Choose the *Region* where you want to create the bucket.
- Choose a Region that is geographically close to you to minimize latency and costs, or to address regulatory requirements.
- To accept the default settings and create the bucket, choose **Create**.
## Enable static website hosting
- In the Buckets list, choose the name of the bucket that you want to enable static website hosting for.
- Choose **Properties**.
- Scroll down to *Static Website hosting*
- Under **Static website hosting**, choose **Edit**.
- Choose Use this bucket to host a website.
- Under Static website hosting, choose Enable.
- In Index document, enter the file name of the index document, typically index.html.</br>
 *The index document name is case sensitive and must exactly match the file name of the HTML index document that you plan to upload to your S3 bucket. When you configure a bucket for website hosting, you must specify an index document. Amazon S3 returns this index document when requests are made to the root domain or any of the subfolders.*
- Choose Save changes.
Amazon S3 enables static website hosting for your bucket. At the bottom of the page, under Static website hosting, you see the website endpoint for your bucket.</br>
Under Static website hosting, note the Endpoint - *The Endpoint is the Amazon S3 website endpoint for your bucket. After you finish configuring your bucket as a static website, you can use this endpoint to test your website.*




