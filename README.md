# Common Voice Sentence Collector [![Build Status](https://travis-ci.com/Common-Voice/sentence-collector.svg?branch=master)](https://travis-ci.com/Common-Voice/sentence-collector)

## Prerequisites

 * [yarn](https://yarnpkg.com/docs/install)
 * [docker](https://docs.docker.com/install/)
 * [docker-compose](https://docs.docker.com/compose/install/)

## Local Development

```
cp .env_template .env
docker-compose up
yarn
yarn start
```

## Deployment

The website is hosted on GitHub Pages. Contributors with write access to the repository can deploy to production by running the following command:

```
yarn run deploy
```

This assumes that your `origin` is pointing to this repository. If not, you can specify the remote name with:

```
yarn run deploy -- -o <remotename>
```

## Get involved

- Fork the project and test that you can run the environment locally following the instructions.
- Is everything working as expected? If not, submit [a new issue](https://github.com/Common-Voice/sentence-collector/issues/new).
- Review the pending issues on the [MVP milestone](https://github.com/Common-Voice/sentence-collector/milestone/1).
- Create a [new PR](https://github.com/Common-Voice/sentence-collector/compare) to fix any of the existing issues in the MVP milestone.
- Get involved in the [development discussion topic] and ask any questions.
