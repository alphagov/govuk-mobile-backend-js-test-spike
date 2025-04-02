# Introduction
The purpose of this repository is to compare different JavaScript unit tests frameworks within the context of an AWS SAM application. There are 2 example apps to enable the comparision which will answer the question:

>Which JavaScript test framework to use for [govuk-mobile-backend](https://github.com/alphagov/govuk-mobile-backend)?

## sam-api-jest
This is the default that the SAM CLI configures and includes jest as part of its `package.json`.


## sam-api-vitest
This is a modified version that the SAM CLI default, with jest replaced with vitest in `package.json`, and the same default tests updated to use vitest.

## Test
From the root of each of the app's directories, run the following:

```
npm install
npm test
```






