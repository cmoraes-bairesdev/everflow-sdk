[![npm (scoped)](https://img.shields.io/npm/v/@everflow/everflow-sdk)](https://www.npmjs.com/package/@everflow/everflow-sdk)

## Usage

Get the latest version of the SDK on npm [here](https://www.npmjs.com/package/@everflow/everflow-sdk).

Configure the SDK before doing any tracking.

```javascript
EF.configure({
    // You only need to set the tracking domain you want to use
    tracking_domain: 'https://<tracking-domain>.com',
})
```

If using the NPM module, the Everflow SDK instance is exported as default.

```javascript
const EverflowSDK = require('@everflow/everflow-sdk');

EverflowSDK.configure({
    // You only need to set the tracking domain you want to use
    tracking_domain: 'https://<tracking-domain>.com',
})
```

## [Documentation](https://developers.everflow.io/docs/everflow-sdk)
Usage directives and examples can be found on our developer hub
