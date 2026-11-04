# Skillsync

The hub for your skills.

Skillsync is where you keep all your skills in one place. With this connector, your assistant can find the right skill from your library while you work and use it on your task. You add and edit skills on app.skillsync.com.

This plugin connects Cursor to the Skillsync MCP server at `https://app.skillsync.com/mcp`.

## Tools

All five tools are read-only. They can't create, change, or delete anything.

- `find_skills`: searches your library for skills that fit what you asked for.
- `list_skills`: lists every skill in your library, when you ask to see them all.
- `get_skill`: loads a skill's instructions and its list of files, so your assistant can use it on your task.
- `read_skill_file`: reads one file from a skill, such as a reference or a template.
- `download_skill`: gives a link to the whole skill as a .tar.gz file. The link works for one hour.

## How to connect

1. Install the Skillsync plugin in Cursor.
2. When Cursor asks, sign in to your Skillsync account. You only do this once.

That's it. There are no keys to copy or settings to fill in.

## Things to ask

- "Find my skill for reviewing pull requests and use it on this diff."
- "What skills do I have in Skillsync?"
- "Use my release notes skill to write notes for these commits."

## Requirements

A free account at [app.skillsync.com](https://app.skillsync.com) with skills in its library.

## Links

- Docs: https://app.skillsync.com/docs/mcp
- Privacy: https://app.skillsync.com/privacy
- Terms: https://app.skillsync.com/terms
- Support: founders@skillsync.com
