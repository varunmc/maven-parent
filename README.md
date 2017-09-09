# parent
_Parent to all Maven projects_

This is the parent to all Maven projects on the platform. It imports the [Bill Of Materials](https://github.com/varunmc/bill-of-materials) and specifies defaults for build plugins.

## Getting Started
The [AWS CodeFormation](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stack/detail?stackId=arn:aws:cloudformation:us-east-1:497513737772:stack%2FParent%2F63ea9940-92e3-11e7-892d-50d501eb4c17) template _stack.yml_ will create an [AWS CodePipeline](https://console.aws.amazon.com/codepipeline/home?region=us-east-1#/view/Parent) with an [AWS CodeBuild](https://console.aws.amazon.com/codebuild/home?region=us-east-1#/projects/Parent/view) builder as defined in _buildspec.yml_. The continuous build pipeline will package and publish the artifact to [AWS S3](https://s3.console.aws.amazon.com/s3/buckets/maven.varun.mc/mc/varun/parent/?region=us-east-1&tab=overview).
