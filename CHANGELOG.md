# Changelog

This file summarizes the main changes for each release.

### <a name="0.11.0"></a>Version 0.11.0

 - Remove dependency to the unmaintained `dwhjames/aws-wrap` by including the necessary code
 - Split the project in three : `commons-aws-cloudwatch`, `commons-aws-s3`  and `commons-aws-sqs`
 - Upgrade dependencies including `aws-java-sdk` and `akka-stream-extensions`
 - Remove `CloudwatchAkkaHeartbeat`
 - Replace `AmazonCloudwatchClient` and `AmazonS3AsyncClient` constructors by an `apply` with default values.