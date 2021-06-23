# Create and deploy a Node.js + Cloudant application

In this sample application, you will create a basic web application using Express to serve web pages in Node.js integrated complete with standard best practices. In addition, this sample includes integration with Cloudant, a fully managed NoSQL database.

## Steps

You can [Deploy to IBM Cloud]() or [Build it Locally](#building-locally) by cloning this repo first.

### Building locally

To get started building this application locally, you can either run the application natively or use the [IBM Cloud Developer Tools](https://cloud.ibm.com/docs/cli?topic=cloud-cli-getting-started) for containerization and easy deployment to IBM Cloud.

#### Native application development

- Install the latest [Node.js](https://nodejs.org/en/download/) 14+ LTS version.

Once the Node toolchain has been installed, you can download the project dependencies with:

```bash
npm install
```

To run your application locally:

```bash
npm run start
```

Rename or copy `env.sample` to `.env`:

```bash
cp env.sample .env
```

Update the `CLOUDANT_URL` field:

```ini
CLOUDANT_URL=https://user:password@cloudanturl.com
```

Your application will be running at `http://localhost:3000`.

## License

This sample application is licensed under the Apache License, Version 2. Separate third-party code objects invoked within this code pattern are licensed by their respective providers pursuant to their own separate licenses. Contributions are subject to the [Developer Certificate of Origin, Version 1.1](https://developercertificate.org/) and the [Apache License, Version 2](https://www.apache.org/licenses/LICENSE-2.0.txt).

[Apache License FAQ](https://www.apache.org/foundation/license-faq.html#WhatDoesItMEAN)
