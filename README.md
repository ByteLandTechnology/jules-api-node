# jules-api-node

The **unofficial** TypeScript client for the Jules API.

This client is automatically generated from the [Jules OpenAPI specification](./jules-openapi.yaml) using [@hey-api/openapi-ts](https://heyapi.vercel.app/openapi-ts/).

## Installation

```bash
npm install jules-api-node
```

## Usage

The client is pre-configured with the base URL for the Jules API. To make requests, you need to import the desired API method and call it with the necessary parameters. Authentication is handled by passing an API key in the headers of each request.

Here's an example of how to create a new session:

```typescript
import { createSession } from "jules-api-node";

async function initializeSession() {
  try {
    const response = await createSession({
      headers: {
        // Replace with your actual API key
        "X-Goog-Api-Key": "YOUR_API_KEY_HERE",
      },
      body: {
        // session data
      },
    });

    console.log("Session created:", response.data);
    return response.data;
  } catch (error) {
    console.error("Error creating session:", error);
  }
}

initializeSession();
```

## API Reference

This library exports functions that map directly to the Jules API operations.

### Available Methods

- `approvePlan`
- `listSessions`
- `createSession`
- `getSession`
- `sendMessage`
- `getActivity`
- `listActivities`
- `getSource`
- `listSources`

For details on the parameters and return types for each function, please refer to the TypeScript definitions included in this package or the source [OpenAPI specification](./jules-openapi.yaml).

## Building from Source

To build the client from the source OpenAPI specification, you'll need to install the development dependencies and run the build script.

```bash
# Install all dependencies
npm install

# Run the build process
# This will regenerate the client from jules-openapi.yaml and bundle the code
npm run build
```
