# Kanban Tasker for Cursor Desktop

Connect Cursor to the Kanban Tasker workspaces you choose. This plugin contains the configuration for the hosted MCP server. Installation requires no local service, API key or client secret.

## Connect

Enable the plugin’s MCP server in Cursor Desktop and choose **Authenticate**. On Kanban’s consent page, select a workspace and the actions you want to allow. Read is selected initially. Create, edit and complete, move, and continuing access are optional. Approve once and return to Cursor.

Try asking Cursor to list your workspaces. If you selected **Create tasks**, try creating a task on a board in an approved workspace. Cursor may ask for confirmation before running a tool.

To use the configuration manually, copy the server entry from [mcp.json](mcp.json) into the `mcpServers` object in your Cursor MCP settings. The client ID identifies Cursor Desktop and can be shared. Review and disconnect your grants in **Kanban Tasker → Account → Connected apps**.

## Requirements and support

A Kanban Tasker account with a cloud workspace is required. MCP is available on Free and Personal plans, subject to each plan's limits. Select only the workspaces and actions you want Cursor to access.

Visit [Kanban Tasker](https://kanbantasker.app/) for the app, [support](https://kanbantasker.app/support) for help, and our [privacy policy](https://kanbantasker.app/privacy) and [terms](https://kanbantasker.app/terms) for information about the service.
