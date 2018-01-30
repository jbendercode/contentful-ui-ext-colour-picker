# Colour picker UI Extension

[https://www.contentful.com](Contentful) is a content management platform for web applications, mobile apps and connected devices. It allows you to create, edit & manage content in the cloud and publish it anywhere via powerful API. Contentful offers tools for managing editorial teams and enabling cooperation between organizations.

The **colour picker UI** extension offers a colour picker tool for short text fields, returning the hex value.

## Installation and usage

[Check you have the requirements needed](https://github.com/contentful/ui-extensions-sdk).

Install the dependencies needed with `npm install`.

To use first export CMA token, followed by creating the extension.

```bash
export CONTENTFUL_MANAGEMENT_ACCESS_TOKEN=<content-management-access-token>
contentful-extension create --space-id $SPACE_ID
```

## Update the extension

If you want to update the extension without updating the versioning, run:

```bash
contentful-extension update --space-id $SPACE_ID --force
```

## Using the extension in the Contentful web app

Enable the extension in the Contentful web app for a "Short text" field by opening the _Settings_ for a field and selecting the extension in the _appearance_ tab.
