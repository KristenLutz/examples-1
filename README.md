# Flex.io Examples

This repository contains a collection of ready-to-deploy serverless data feeds and demo applications that utilize the [Flex.io API](https://www.flex.io) for moving, processing and integrating data in the cloud.

## Introduction

Please fork and utilize these examples at will; we hope you find them useful.  All code is available under the [MIT License](http://opensource.org/licenses/MIT); any other content is available under the [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

If you have question or would like more information, please feel free to email the Flex.io developer support team at [support@flex.io](mailto:support@flex.io?subject=Flex.io%20Examples%20Repo) or use the chat button at the bottom of the [Flex.io website](https://www.flex.io).

## Examples

Each example contains a `README.md` with an explanation of what it does and how it works. Each example also includes at least one `pipe.js` file that can be used to install the pipe in your Flex.io account:

```
node pipe.js
```

**Have an example?** Submit a PR or [open an issue](https://github.com/flexiodata/examples/issues).

### Demo App Examples

| Example | Demo App | Source |
|:--------|:---------|:------:|
| **Chicago Crime Map** <br/> Read a table from local storage in Flex.io, filter its rows by year and output the result in JSON. | [Chicago Crime Map](https://flexiodata.github.io/examples/demo-chicago-crime-map/) | [Source](https://github.com/flexiodata/examples/tree/master/demo-chicago-crime-map) |
| **Contact Refinement** <br/> Request a CSV from GitHub, convert it to a table, select a subset of columns, transform the result to uppercase and output the result in JSON. | [Contact Refinement](https://flexiodata.github.io/examples/demo-contact-refinement/) | [Source](https://github.com/flexiodata/examples/tree/master/demo-contact-refinement) |
| **Saastr Podcast Search** <br/> Request a CSV from GitHub, convert it to a table, select a subset of columns, filter it based on a search string from an HTML input and output the result in JSON. | [Saastr Podcast Search](https://flexiodata.github.io/examples/demo-saastr-podcast-search/) | [Source](https://github.com/flexiodata/examples/tree/master/demo-saastr-podcast-search) |
| **Webpage Thumbnail Generator** <br/> Load the HTML contents of the webpage, reduce it in size to a thumbnail and output it as a PNG image. | [Webpage Thumbnail Generator](https://flexiodata.github.io/examples/demo-webpage-thumbnail-generator/) | [Source](https://github.com/flexiodata/examples/tree/master/demo-webpage-thumbnail-generator) |
| **Webpage Word Cloud Generator** <br/> Parse the HTML contents of the webpage and return a wordcloud of the words on that page. | [Webpage Word Cloud Generator](https://flexiodata.github.io/examples/demo-webpage-word-cloud-generator/) | [Source](https://github.com/flexiodata/examples/tree/master/demo-webpage-word-cloud-generator) |
| **Upload to Amazon S3** <br/> Upload to Amazon S3. | [Upload to Amazon S3](https://flexiodata.github.io/examples/demo-upload-to-amazon-s3/) | [Source](https://github.com/flexiodata/examples/tree/master/demo-upload-to-amazon-s3) |

### Transfer Examples

| Example | Source |
|:--------|--------|
| **Copy Files Between Cloud Storage** <br/> Copy files between cloud storage providers such as AWS S3 and Dropbox. Filter the file transfer based on file name, file size and modified date. | [Source](https://github.com/flexiodata/examples/tree/master/transfer-copy-files-between-cloud-storage) |
| **Bulk Load CSV Files into Elasticsearch** <br/> Copy CSV files cloud storage providers into Elasticsearch. Load from an API, like Twilio or a database, like Postgres. | [Source](https://github.com/flexiodata/examples/tree/master/transfer-csv-to-elasticsearch) |

### Community Examples

| Example | Location | Source |
|:--------|:---------|:------:|

## Contributing

Do you have an example you'd like to share? We are happy to accept more examples from the community.

### Adding a community example

We love hearing about projects happening in the community. Feel free to add your serverless project to our growing list.

1. Fork this repo.

2. Add `example`, `location`, and optionally a link to the `source` to the [Community Examples](#Community-Examples) section above. Always add your examples to the end of the list. To be fair, the order is first-come-first-serve.

3. Open a new pull request with your example.
