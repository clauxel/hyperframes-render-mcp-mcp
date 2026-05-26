# Quickstart

HyperFrames Render MCP is a hosted remote MCP for HyperFrames.

## Fast Path

1. Open HyperFrames Render MCP and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://hyperframesrender.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call render_hyperframe_video with public-safe sample data.
5. Save the returned receipt or export for human review.

## Useful Links

- https://hyperframesrender.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=hyperframesrender_public_docs&utm_content=quickstart_home
- https://hyperframesrender.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=hyperframesrender_public_docs&utm_content=quickstart_pricing
- https://hyperframesrender.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=hyperframesrender_public_docs&utm_content=quickstart_checkout

## MCP Endpoint

```text
https://hyperframesrender.clauxel.com/mcp
```

Use bearer-token authentication for production calls. Keep the token in the MCP client's secret mechanism.
