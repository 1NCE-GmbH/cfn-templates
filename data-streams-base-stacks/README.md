# Overview

## data-streams-base-stack-s3.yaml
This template creates a Bucket and a role. The Role has a permission policy allowing `PutObject`, given the conditions are satisfied, to the identity that will assume it.

[<img src="https://raw.githubusercontent.com/buildkite/cloudformation-launch-stack-button-svg/master/launch-stack.svg" width="100"/>](https://eu-central-1.console.aws.amazon.com/cloudformation/home?region=eu-central-1#/stacks/create/review?templateURL=https://648536613203-public-cfn-templates.s3.eu-central-1.amazonaws.com/data-streams-base-stacks/data-streams-base-stack-s3.yaml&stackName=1NCEDataStreamS3)

## data-streams-base-stack-kinesis.yaml
This template creates a Kinesis Stream and a role. The Role has a permission policy allowing `PutRecord` and `PutRecords`, given the conditions are satisfied, to the identity that will assume it.

[<img src="https://raw.githubusercontent.com/buildkite/cloudformation-launch-stack-button-svg/master/launch-stack.svg" width="100"/>](https://eu-central-1.console.aws.amazon.com/cloudformation/home?region=eu-central-1#/stacks/create/review?templateURL=https://648536613203-public-cfn-templates.s3.eu-central-1.amazonaws.com/data-streams-base-stacks/data-streams-base-stack-kinesis.yaml&stackName=1NCEDataStreamKinesis)
