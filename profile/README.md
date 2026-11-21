# Build with Magic Hour

[Magic Hour](https://magichour.ai) provides tools and APIs for creating and editing images, video, and audio. This organization maintains our official SDKs, integrations, API documentation, and hosted MCP integration.

## Start with a working example

- **Explore requests:** fork the [official Postman collection](https://www.postman.com/magichourhq/magic-hour-api) for image generation, image editing, product-image animation, face swap, lip sync, uploads, and result retrieval.
- **Build an integration:** follow the [API quickstart](https://docs.magichour.ai/get-started/quick-start), then use the SDK for your language below.
- **Connect an agent:** use the [hosted MCP server](https://magichour.ai/mcp) to work with Magic Hour from a compatible MCP client.
- **Work in Codex or Claude Code:** install the [official Magic Hour skills](https://github.com/magichourhq/skills) for image, video and audio workflows. Skills are free to install; generation uses credits.

## Official libraries and documentation

| Resource                                                               | Purpose                                         |
| ---------------------------------------------------------------------- | ----------------------------------------------- |
| [Python](https://github.com/magichourhq/magic-hour-python)             | Python SDK and examples                         |
| [TypeScript / Node.js](https://github.com/magichourhq/magic-hour-node) | JavaScript and TypeScript applications          |
| [Go](https://github.com/magichourhq/magic-hour-go)                     | Go applications                                 |
| [Rust](https://github.com/magichourhq/magic-hour-rust)                 | Rust applications                               |
| [API documentation](https://github.com/magichourhq/docs)               | REST reference, integration guides, and recipes |
| [MCP](https://github.com/magichourhq/magic-hour-mcp)                   | Hosted server setup and supported clients       |
| [CLI](https://github.com/magichourhq/magic-hour-cli)                   | Using terminal to generate outputs.             |

## Integrations

Use Magic Hour from workflow tools, AI frameworks and design apps.

<details>
<summary>Show all integrations</summary>

**Workflow automation**

| Integration                                                                          | Purpose                                           |
| ------------------------------------------------------------------------------------ | ------------------------------------------------- |
| [n8n](https://github.com/magichourhq/n8n-nodes-magichour)                            | Community node for n8n workflows                  |
| [Make](https://github.com/magichourhq/magic-hour-make)                               | Custom app for Make scenarios                     |
| [Activepieces](https://github.com/magichourhq/activepieces-magic-hour)               | Piece for Activepieces flows and MCP agents       |
| [Power Automate](https://github.com/magichourhq/magic-hour-power-platform-connector) | Connector for Power Automate and Azure Logic Apps |
| [Dify](https://github.com/magichourhq/magic-hour-dify)                               | Tools for Dify agents and workflows               |

**AI frameworks**

| Integration                                                                            | Purpose                                         |
| -------------------------------------------------------------------------------------- | ----------------------------------------------- |
| [Vercel AI SDK](https://github.com/magichourhq/ai-sdk-provider)                        | Image and video provider for the AI SDK         |
| [LiteLLM](https://github.com/magichourhq/magic-hour-litellm)                           | Image generation from the LiteLLM SDK and proxy |
| [Haystack](https://github.com/magichourhq/magic-hour-haystack)                         | Image generation components for pipelines       |
| [ComfyUI](https://github.com/magichourhq/comfyui-magic-hour)                           | Custom nodes for ComfyUI workflows              |
| [Cloudflare Workflows](https://github.com/magichourhq/magic-hour-cloudflare-workflows) | Example of durable image and video jobs         |

**Design apps**

| Integration                                                              | Purpose                                      |
| ------------------------------------------------------------------------ | -------------------------------------------- |
| [Canva](https://github.com/magichourhq/magic-hour-canva)                 | Turn an image or brief into a video in Canva |
| [Adobe Express](https://github.com/magichourhq/magic-hour-adobe-express) | Turn an image or page into a video           |
| [Framer](https://github.com/magichourhq/magic-hour-framer)               | Add a generated video to a Framer project    |
| [Webflow](https://github.com/magichourhq/magic-hour-webflow)             | Generate images into a site's assets         |

**More**

| Integration                                                                       | Purpose                                       |
| --------------------------------------------------------------------------------- | --------------------------------------------- |
| [Hugging Face Space](https://github.com/magichourhq/magic-hour-huggingface-space) | Try image and video generation in the browser |
| [Browser client](https://github.com/magichourhq/browser-client)                   | API client for apps that run in a web page    |

</details>

## From request to finished media

Media generation is asynchronous. Submit a job, keep the returned project ID, and retrieve its status until it completes. A local timeout does not establish that a render failed: check the original project before creating another billable job. Use [webhooks](https://docs.magichour.ai/integration/webhook/overview) when your application needs completion notifications.

Keep API keys and private media out of public repositories, shared environments, and issue reports. Use source media you have permission to process.

## Get help or contribute

For a reproducible SDK or documentation issue, use the issue tracker in the relevant repository. Include the package version and a minimal example with credentials and private inputs removed. For account-specific questions, visit the [help center](https://help.magichour.ai) or contact support@magichour.ai privately.
