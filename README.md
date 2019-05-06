
# Nervos CKB Documentation Website

This is the Nervos CKB documentation website. 

It is built with [docusaurus](https://docusaurus.io/).

## Dependencies
Install [yarn](https://yarnpkg.com/en/).

In `website` folder:
```shell
yarn install
```

## Preview
In `website` folder:
```shell
yarn start
```

## Build
In `website` folder:
```shell
yarn build
```

The generated static files will be in `website/build`

## Docs
All the documents go into the `docs` folder. All the images should be in the `docs/assets` folder.

To add a document:
* add the the document to `docs`
* add [header](https://docusaurus.io/docs/en/next/adding-blog#adding-posts) to the document (id and title is required)
* add the path of the folder to the `website/sidebars.json` file
