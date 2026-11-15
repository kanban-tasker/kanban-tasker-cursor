# Kanban Tasker for Cursor Desktop

Connect Cursor to the Kanban Tasker workspaces you choose. This plugin contains the configuration for the hosted MCP server. Installation requires no local service, API key or client secret.

## Connect

[![Add to Cursor](https://cursor.com/deeplink/mcp-install-dark.svg)](https://cursor.com/install-mcp?name=kanban-tasker&config=eyJ1cmwiOiJodHRwczovL2FwaS5rYW5iYW50YXNrZXIuYXBwL21jcCIsImF1dGgiOnsiQ0xJRU5UX0lEIjoia2FuYmFuLWN1cnNvci1wcm9kdWN0aW9uIiwic2NvcGVzIjpbImthbmJhbi5jb25uZWN0Iiwib2ZmbGluZV9hY2Nlc3MiXX19)

1. Click **Add to Cursor**, choose **Open Cursor** if your browser asks, and review and install the `kanban-tasker` server. You do not need to copy JSON or wait for the marketplace listing.
2. Enable the server if needed and choose **Authenticate**. If you already installed the plugin, start here.
3. On Kanban’s consent page, select your workspaces and the actions you want to allow. Read is selected initially. Create, edit and complete, move, and continuing access are optional and start unchecked. Select **Create tasks** now if you want the first create to work after this approval.
4. Approve once and return to Cursor. Choose **Open Cursor** if your browser offers it.

See the [setup guide for Cursor and VS Code](https://kanbantasker.app/mcp). VS Code uses only the HTTP server URL, `https://api.kanbantasker.app/mcp`.

Try asking Cursor to list your workspaces. If you selected **Create tasks**, try creating a task on a board in an approved workspace. Cursor may ask for confirmation before running a tool.

Continuing access lets Cursor renew its access token automatically. Without it, reconnect when the access token expires. Review and disconnect your grants in **Kanban Tasker → Account → Connected apps**.

### Manual setup (optional)

Copy the server entry from [mcp.json](mcp.json) into the `mcpServers` object in your project’s `.cursor/mcp.json` or your user’s `~/.cursor/mcp.json`, keeping any existing servers. The public client ID identifies Cursor Desktop; it is not a secret. No API key, access token, or client secret belongs in that file.

## Requirements and support

A Kanban Tasker account with a cloud workspace is required. MCP is available on Free and Personal plans, subject to each plan's limits. Select only the workspaces and actions you want Cursor to access.

Visit [Kanban Tasker](https://kanbantasker.app/) for the app, [support](https://kanbantasker.app/support) for help, and our [privacy policy](https://kanbantasker.app/privacy) and [terms](https://kanbantasker.app/terms) for information about the service.
