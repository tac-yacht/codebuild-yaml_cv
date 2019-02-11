# codebuild-yaml_cv

# origin
https://qiita.com/kaityo256/items/e3884d0109223c324baf

# required CodeBuild configuration
## Source
* common

    |field name|value|
    |---|---|
    |Source provider|GitHub|
* Primary

    |field name|value|
    |---|---|
    |Repository|Public repository|
    |Repository URL|https://github.com/tac-yacht/codebuild-yaml_cv.git|
* Source2

    |field name|value|
    |---|---|
    |Source identifier|script|
    |Repository|Public repository|
    |Repository URL|https://github.com/ikasam/yaml_cv.git|
* Source3

    |field name|value|
    |---|---|
    |Source identifier|data|
    |Repository|Public repository|
    |Repository URL|{your resume repository}|
    * required repository root have data.yaml
    * you can choose from S3

## Environment

|field name|value|
|---|---|
|New environment image|Managed image|
|Operating system|Ubuntu|
|Runtime|Ruby|
|Runtime version|aws/codebuild/ruby:2.5.3|
