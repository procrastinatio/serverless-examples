# quickstart


From the [quickstart](https://serverless.com/framework/docs/providers/aws/guide/quick-start/)

A _python3_ REST API example

Create the files

    serverless create --template  aws-python3 --path quickstart

Modifying _serverless.yaml_ to incorporate _staging_ using different AWS credential _profile_

    serverless deploy --stage dev

Deploy and test the function

    serverless deploy function -f hello

    serverless invoke -f hello -l
