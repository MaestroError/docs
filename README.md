# Mintlify Starter Kit

Click on `Use this template` to copy the Mintlify starter kit. The starter kit contains examples including

- Guide pages
- Navigation
- Customizations
- API Reference pages
- Use of popular components

### Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where docs.json is)

```
mintlify dev
```

### Publishing Changes

Install our Github App to auto propagate changes from your repo to your deployment. Changes will be deployed to production automatically after pushing to the default branch. Find the link to install on your dashboard. 

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `docs.json`

## To Do

- Add tab for extensibility, including custom driver, storage and other creation flows (Like guides, but separate) and reference link in main doc pages

- review merged inline and class tools doc page: v1/tools/other-tools.mdx +

- Update MCP with mcp_tool_caching https://github.com/MaestroError/LarAgent/pull/105 +

- Context pages + RAG
    - Maybe we should add truncation and usage tracking inside chat history page? Try it, check the size
        - Trancation in history, usage separately

- Add other section in menu and add Events & Hooks page pointing to the extensibility tab where we will have all details and guides around events. Move context and identity storage events from v1/context/overview.mdx to there

- Where to put All commands page?

- Merge old events and hooks pages as Agent hooks, move event setup guide in extensibility tab and add one page per events type