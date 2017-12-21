# planetbot

Welcome! To get started on development:

### Slack - we use Slack for communication:
+ Sign up for Code for San Francisco Slack https://sfbrigade.slack.com
+ Join #planetbot

### AWS - we use Lex, Lambda etc.
+ Ask Senthil (me@sent-hil.com) for AWS access
+ Once you’ve access, you can log into: https://097545936362.signin.aws.amazon.com/console

### Golang (optional)
We use GoLang for writing lambda functions. If you’ve Go already installed you don’t need the following:
+ Install Brew from https://brew.sh
+ `$ brew install golang`

### Docker - it’s used for the AWS Lambda Go shim
+ `$ brew install docker`

### Clone the repo:
+ `$ go get -u github.com/sfbrigade/planetbot`

### Build
This'll build the zip file that you can upload to AWS Lambda

+ `make`

### Links
+ https://console.aws.amazon.com/lambda/home?region=us-east-1#/functions/baaqmpd?tab=graph
+ https://console.aws.amazon.com/lex/home?region=us-east-1#bots:
