# Voice Coach (skill only)

This folder is the version of the plugin submitted to the Claude plugin directory. It ships only
the `voice-coach` coaching skill: the directory accepts local MCP servers only from Verified
organizations, so the server is installed separately.

The skill needs the `voice-coach` MCP server (microphone recording and local audio analysis). To
install it, follow the [install guide](https://github.com/FabianIMV/voice-coach-mcp#install).
The full plugin (server and skill) is available from this repository's marketplace:

    /plugin install voice-coach --marketplace FabianIMV/voice-coach-mcp

`skills/voice-coach` is a copy of the repository's `skills/voice-coach`; CI checks that both stay
identical.
