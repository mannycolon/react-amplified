# Documentation

## Amplify

### AWS AppSync (a managed GraphQL service)

### Commands

- Install and configure the Amplify CLI

```bash
npm install -g @aws-amplify/cli
```

```bash
amplify configure
```

```bash
```

- Initialize a new Amplify backend

```bash
amplify init
```

- Add a GraphQL API to your app and automatically provision a database by running the the following command from the root of your application directory:

```bash
amplify add api
```

- To deploy this backend, run the push command:

```bash
amplify push
```

- Run the following command to check Amplify’s status:

```bash
amplify status
```

- To view the GraphQL API in the AppSync console at any time, run the following command:

```bash
amplify console api
```

- To view your entire app in the Amplify console at any time, run the following command:

```bash
amplify console
```

- Test your API

```bash
amplify mock api
```

> This will open the GraphiQL explorer on a local port. From the test environment you can try out different operations locally, like queries and mutations.
