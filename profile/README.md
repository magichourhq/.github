# Build with Magic Hour

[Magic Hour](https://magichour.ai) provides tools and APIs for creating and editing images, video, and audio. This organization maintains our official SDKs, API documentation, and hosted MCP integration.

## Start with a working example

- **Explore requests:** fork the [official Postman collection](https://www.postman.com/magichourai/magic-hour-api) for image generation, image editing, product-image animation, face swap, lip sync, uploads, and result retrieval.
- **Build an integration:** follow the [API quickstart](https://docs.magichour.ai/get-started/quickstart), then use the SDK for your language below.
- **Connect an agent:** use the [hosted MCP server](https://magichour.ai/mcp) to work with Magic Hour from a compatible MCP client.

## Official libraries and documentation

| Resource | Purpose |
| --- | --- |
| [Python](https://github.com/magichourhq/magic-hour-python) | Python SDK and examples |
| [TypeScript / Node.js](https://github.com/magichourhq/magic-hour-node) | JavaScript and TypeScript applications |
| [Go](https://github.com/magichourhq/magic-hour-go) | Go applications |
| [Rust](https://github.com/magichourhq/magic-hour-rust) | Rust applications |
| [API documentation](https://github.com/magichourhq/docs) | REST reference, integration guides, and recipes |
| [MCP](https://github.com/magichourhq/magic-hour-mcp) | Hosted server setup and supported clients |

## From request to finished media

Media generation is asynchronous. Submit a job, keep the returned project ID, and retrieve its status until it completes. A local timeout does not establish that a render failed: check the original project before creating another billable job. Use [webhooks](https://docs.magichour.ai/integration/webhook/overview) when your application needs completion notifications.

Keep API keys and private media out of public repositories, shared environments, and issue reports. Use source media you have permission to process.

## Get help or contribute

For a reproducible SDK or documentation issue, use the issue tracker in the relevant repository. Include the package version and a minimal example with credentials and private inputs removed. For account-specific questions, visit the [help center](https://help.magichour.ai) or contact support@magichour.ai privately.
