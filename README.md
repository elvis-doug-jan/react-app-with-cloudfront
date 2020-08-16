# Example of SPA on CloudFront with Serverless

This is an example of a SPA application made in React for use in AWS CloudFront using the Serverless framework as a tool.

## Installation

Use ``npm i`` or ``yarn`` in the root folder to install the dependencies used on serverless, repeat the process inside the demo-app folder to install the React dependencies.

## Usage

To upload the app to CloudFront, have the serverless configured with your account credentials, in addition, also change the **bucketName** attribute in the **custom** section to use a bucket not yet used by someone else.

That done, just run the command ``sls deploy`` and wait for the process, which after, check on the AWS panel if your project is on CloudFront. To access, just copy the link generated in CloudFront followed by **/index.html**.

## License
[MIT](https://choosealicense.com/licenses/mit/)