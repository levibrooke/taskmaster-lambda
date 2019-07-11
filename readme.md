#Task Master Lambda
AWS Lambda function to resize image uploads

## Link
http://levibrooke-taskmaster-frontend.s3-website-us-west-2.amazonaws.com/

## Directions
- Visit the website
- Choose a task that doesn't have an image already uploaded.
- Upload image
- Revisit website and see both fullsize and resized image.

## Challenges
- I had difficulty getting my resized images to have public access. I found the parameter that I needed to add for the S3 putObject method and that fixed it.

## Resources
- [AWS tutorial](https://docs.aws.amazon.com/lambda/latest/dg/with-s3-example.html)