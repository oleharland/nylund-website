Clone the repository
Open your terminal and run:
`Yarn install`

When you want to preview the site on localhost run:
`gulp serve`
and go to localhost:8080 or localhost:3000

To deploy the website. run:
`gulp deploy`
Currently it can be accessed at: nylund-website.s3-website.eu-west-2.amazonaws.com. The credentials are expected
in a configuration file called aws_config.json. Documentation here:
https://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/loading-node-credentials-json-file.html
