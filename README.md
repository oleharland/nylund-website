# Offical Nylund website

👋🏻 Welcome to the source code of the offical [nylund website](http://insertfinalurlhere.com)

## 🛠 Installation

1. Clone the repository
2. Open your terminal and run: `Yarn install`
3. To run the website local: `gulp serve`
4. To build the website: `gulp build`

## 📦 Deployment
To deploy the website run: `gulp deploy`

Currently it can be accessed at: nylund-website.s3-website.eu-west-2.amazonaws.com. The credentials are expected
in a configuration file called aws_config.json. Documentation here:
https://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/loading-node-credentials-json-file.html

## Templates

[Handlebars](https://handlebarsjs.com)is used to achieve the following:
* A page will be created for every context inside app/contexts, allowing modular creation of landing pages or facilitating  A/B comparisons
* Factoring out components into app/components. Each .hbs file inside that directory will be available as a partial inside index.html

In the future we might like to add support for multiple templates, but currently only index.hbs is used. 

## 📝 Feedback
Have any thoughts? Say hello over twitter [@oleharland](http://www.twitter.com/oleharland)
