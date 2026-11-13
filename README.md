# Kanban Tasker for Cursor Desktop

Connect Cursor to the Kanban Tasker workspaces you choose. This plugin contains the configuration for the hosted MCP server. Installation requires no local service, API key or client secret.

## Connect

Enable the plugin’s MCP server in Cursor Desktop and choose **Authenticate**. On Kanban’s consent page, select a workspace and the actions you want to allow. Read is selected initially. Create, edit and complete, move, and continuing access are optional. Approve once and return to Cursor.

Try asking Cursor to list your workspaces. If you selected **Create tasks**, try creating a task on a board in an approved workspace. Cursor may ask for confirmation before running a tool.

To use the configuration manually, copy the server entry from [mcp.json](mcp.json) into the `mcpServers` object in your Cursor MCP settings. The client ID identifies Cursor Desktop and can be shared. Review and disconnect your grants in **Kanban Tasker → Account → Connected apps**.

## Distribution

Private preview for the one-screen consent release. Marketplace publication is pending owner approval.
