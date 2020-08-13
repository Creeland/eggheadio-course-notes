
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-13-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

<h1 align="center"><a href="https://egghead.io/courses/build-an-app-with-the-aws-cloud-development-kit?af=4cexzz">Build an App with React Suspense</a></h1>

<p align="center"><img src="https://d2eip9sf3oo6c2.cloudfront.net/series/square_covers/000/000/399/full/React_Suspense_Final.png" width="340"></p>


---

## About 🔍

This repo contains notes from [Michael Chan](https://twitter.com/chantastic)'s Egghead course [Build an App with React Suspense](https://egghead.io/courses/build-an-app-with-the-aws-cloud-development-kit?af=4cexzz).

These notes contain the same structure as the transcriptions, along with additional rewrites, links to resources, and personal takes on the lesson. Feel free to submit additions to these notes, but please don't remove anything (unless we messed up or misunderstood something).

Generally, there is one document for each lesson in the course. If there are related lessons, the notes will be in the same document.

## Course Objective 💪

You've probably already heard of React Suspsense and the big change that this new API will create in the way that we develop our React apps. This course serve as an introduction to the current state of this yet EXPERIMENTAL API.

React Suspense gives us a new way of describing with fine-grain controls how users experience should look based on data we have or don’t have.

You'll learn what changes this new API add to React and how to leverage the power that brings with it to create better applications and UX.


By the end of the course you'll not only have a good understanding of (some of) Suspense features, you'll also have a working application to show off.


## Prerequisites ✅

During this course we're going to talk quite a bit about React current API. So is required that you already know about how to create an application with React. 


## Who is Michel Chan? 👨‍💻

Senior Frontend Engineer at OLX Group. His interests include React, AWS, testing, Svelte, VR, app performance and... jQuery, which he still thinks is the best library ever.

[Other Egghead content](https://egghead.io/instructors/tomasz-lakomy) created by Tomasz.

## Notes - Table of Contents 📜

- [00-Intro and Welcome](notes/00-intro-and-welcome.md)
- [01-Install AWS Cloud Development Kit (CDK) and create a new project](notes/01-install-aws-cloud-development-kit-cdk-and-create-a-new-project.md)
- [02-Build and deploy a sample AWS Cloud Development Kit stack to AWS](notes/02-build-and-deploy-a-sample-aws-cloud-development-kit-stack-to-aws.md)
- [03-Review an AWS CloudFormation stack deployed with AWS CDK](notes/03-review-an-aws-cloud-formation-stack-deployed-with-aws-cdk.md)
- [04-Clear an initial AWS CDK stack to start building an app from scratch](notes/04-clear-an-initial-aws-cdk-stack-to-start-building-an-app-from-scratch.md)
- [05-Create and deploy a lambda function with AWS CDK](notes/05-create-and-deploy-a-lambda-function-with-aws-cdk.md)
- [06-Review and execute a lambda function deployed with CDK in AWS Console](notes/06-review-and-execute-a-lambda-function-deployed-with-cdk-in-aws-console.md)
- [07-Change the properties of a lambda function deployed with AWS CDK](notes/07-change-the-properties-of-a-lambda-function-deployed-with-aws-cdk.md)
- [08-Attach an API Gateway to a lambda function deployed with AWS CDK](notes/08-attach-an-api-gateway-to-a-lambda-function-deployed-with-aws-cdk.md)
- [09-Pass environment variables to a lambda function deployed with AWS CDK](notes/09-pass-environment-variables-to-a-lambda-function-deployed-with-aws-cdk.md)
- [10-Run lambda functions built with CDK locally using AWS SAM](notes/10-run-lambda-functions-built-with-cdk-locally-using-aws-sam.md)
- [11-Create and deploy an S3 bucket with AWS CDK](notes/11-create-and-deploy-an-s3-bucket-with-aws-cdk.md)
- [12-Make the contents of an S3 bucket deployed with CDK public](notes/12-make-the-contents-of-an-s3-bucket-deployed-with-cdk-public.md)
- [13-Create an S3 event notification to trigger a lambda function on file upload](notes/13-create-an-s3-event-notification-to-trigger-a-lambda-function-on-file-upload.md)
- [14-Use a bucket deployment to upload a file to S3 when deploying a CDK stack](notes/14-use-a-bucket-deployment-to-upload-a-file-to-s3-when-deploying-a-cdk-stack.md)
- [15-Create a custom AWS CDK construct](notes/15-create-a-custom-aws-cdk-construct.md)
- [16-Create a DynamoDB table with AWS CDK](notes/16-create-a-dynamo-db-table-with-aws-cdk.md)
- [17-Get all items from a DynamoDB table deployed with CDK using DocumentClient API](notes/17-get-all-items-from-a-dynamo-db-table-deployed-with-cdk-using-document-client-api.md)
- [18-Debug permission issues and allow a lambda function to access data from a DynamoDB table](notes/18-debug-permission-issues-and-allow-a-lambda-function-to-access-data-from-a-dynamo-db-table.md)
- [19-Adding data to a DynamoDB table with put operation](notes/19-adding-data-to-a-dynamo-db-table-with-put-operation.md)
- [20-Delete an item from a DynamoDB table with delete operation](notes/20-delete-an-item-from-a-dynamo-db-table-with-delete-operation.md)
- [21-Add external dependencies to an AWS Lambda function deployed with CDK](notes/21-add-external-dependencies-to-an-aws-lambda-function-deployed-with-cdk.md)
- [22-Connect React app to a serverless backend deployed with CDK and fix CORS issues](notes/22-connect-react-app-to-a-serverless-backend-deployed-with-cdk-and-fix-cors-issues.md)
- [23-Add a custom CloudFormation stack output with CDK](notes/23-add-a-custom-cloud-formation-stack-output-with-cdk.md)
- [24-Deploy a static website to S3 with AWS CDK](notes/24-deploy-a-static-website-to-s3-with-aws-cdk.md)
- [25-Deploy a site with HTTPS support behind a CDN with CDK](notes/25-deploy-a-site-with-https-support-behind-a-cdn-with-cdk.md)
- [26-Destroy an AWS CDK stack](notes/26-destroy-an-aws-cdk-stack.md)

## Emoji Legend 🧠

| emoji |        explanation        |
| ----- | :-----------------------: |
| 📹    | links to the course video |
| 💻    |     course repository     |
| ⌨️    |     keyboard shortcut     |
| 🤔    |   additional resources    |
| 👍    |       good practice       |

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):
<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://laurosilva.com"><img src="https://avatars2.githubusercontent.com/u/57044804?v=4" width="100px;" alt=""/><br /><sub><b>Lauro Silva</b></sub></a><br /><a href="https://github.com/eggheadio-projects/build-an-app-with-the-AWS-cloud-development-kit-notes/pulls?q=is%3Apr+reviewed-by%3Alaurosilvacom" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="http://includejs.dev"><img src="https://avatars3.githubusercontent.com/u/17270662?v=4" width="100px;" alt=""/><br /><sub><b>edieblu</b></sub></a><br /><a href="#content-edieblu" title="Content">🖋</a> <a href="#userTesting-edieblu" title="User Testing">📓</a></td>
    <td align="center"><a href="http://maggieappleton.com"><img src="https://avatars0.githubusercontent.com/u/5599295?v=4" width="100px;" alt=""/><br /><sub><b>Appleton</b></sub></a><br /><a href="#design-MaggieAppleton" title="Design">🎨</a></td>
    <td align="center"><a href="https://github.com/lsminter"><img src="https://avatars1.githubusercontent.com/u/26470581?v=4" width="100px;" alt=""/><br /><sub><b>Lucas Minter</b></sub></a><br /><a href="https://github.com/eggheadio-projects/build-an-app-with-the-AWS-cloud-development-kit-notes/pulls?q=is%3Apr+reviewed-by%3Alsminter" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="http://darkwark.com"><img src="https://avatars0.githubusercontent.com/u/1868217?v=4" width="100px;" alt=""/><br /><sub><b>Kamil Khadeyev</b></sub></a><br /><a href="#design-darkwark" title="Design">🎨</a></td>
    <td align="center"><a href="https://github.com/Creeland"><img src="https://avatars2.githubusercontent.com/u/518406?v=4" width="100px;" alt=""/><br /><sub><b>Creeland A. Provinsal </b></sub></a><br /><a href="#content-Creeland" title="Content">🖋</a></td>
    <td align="center"><a href="https://zacjones.io"><img src="https://avatars2.githubusercontent.com/u/6188161?v=4" width="100px;" alt=""/><br /><sub><b>Zac Jones</b></sub></a><br /><a href="#content-zacjones93" title="Content">🖋</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://williamjohnson.dev/"><img src="https://avatars2.githubusercontent.com/u/40403549?v=4" width="100px;" alt=""/><br /><sub><b>William Johnson</b></sub></a><br /><a href="https://github.com/eggheadio-projects/build-an-app-with-the-AWS-cloud-development-kit-notes/pulls?q=is%3Apr+reviewed-by%3Awjohnson85" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://ianjones.us/"><img src="https://avatars2.githubusercontent.com/u/4407263?v=4" width="100px;" alt=""/><br /><sub><b>Ian Jones</b></sub></a><br /><a href="#userTesting-theianjones" title="User Testing">📓</a></td>
    <td align="center"><a href="https://github.com/pixelsortr"><img src="https://avatars0.githubusercontent.com/u/54180211?v=4" width="100px;" alt=""/><br /><sub><b>Pixel</b></sub></a><br /><a href="#content-pixelsortr" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/MrZakos"><img src="https://avatars2.githubusercontent.com/u/999613?v=4" width="100px;" alt=""/><br /><sub><b>Zakos</b></sub></a><br /><a href="https://github.com/eggheadio-projects/build-an-app-with-the-AWS-cloud-development-kit-notes/issues?q=author%3AMrZakos" title="Bug reports">🐛</a></td>
    <td align="center"><a href="http://bendaniel.io"><img src="https://avatars0.githubusercontent.com/u/6035934?v=4" width="100px;" alt=""/><br /><sub><b>Ben</b></sub></a><br /><a href="#content-codeandcats" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/pgrimaud"><img src="https://avatars1.githubusercontent.com/u/1866496?v=4" width="100px;" alt=""/><br /><sub><b>Pierre Grimaud</b></sub></a><br /><a href="#content-pgrimaud" title="Content">🖋</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

