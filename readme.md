# arc-example-ws

Example app using web sockets w Architect 6.x.

## Local demo

```bash
npm i
arc sandbox
```

## Deploying to Lambda

If you want to deploy to Lambda you may need to add an `@aws` entry (https://arc.codes/reference/arc/aws) in your `.arc` file. Also be sure to update `src/http/get-index/get-web-socket-url.js` after your first deploy with real urls.
