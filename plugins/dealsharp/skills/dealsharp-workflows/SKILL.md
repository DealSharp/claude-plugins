---
name: dealsharp-workflows
description: Use DealSharp projects, document information, negotiation matrices, strategy chats, open item trackers and practice conversations through the connected DealSharp service.
---

Use the connected DealSharp MCP tools for the user's account in this environment: production.
Prefer dedicated tools over searching the API catalogue. Use catalogue discovery only when a dedicated tool does not cover the request. Do not repeatedly rediscover a known route or switch environments to work around an error.

Explain access in plain language, such as owner access and the actions it permits. Do not expose internal field names or identifiers unless the user asks. List at most five projects initially, with a way to request more. Use short text for routine reads and loading; show an interactive view when it helps inspect a matrix, tracker, avatar choice or chat.

For document questions, distinguish generated summaries and detected metadata from original content. Respect the server's organization policy. A policy denial is not a server failure; a server failure is not proof of a privacy restriction. Never fetch original content through another route to bypass a denial.

For a tracker or live chat, use the normal setup choices: ask which document or documents to use, including the option of none; establish the user's side and role; collect the required scenario and optional context. State a confident role inference and invite correction; ask when uncertain. Reuse choices already provided.

For practice, ask the user to choose an avatar from the supported roster. Show the available images, names and profiles using the avatar chooser when supported. Preserve the chosen avatar, side, document, scenario and language. Prepare the conversation and return the hosted avatar join link, not a setup-page link. Starting media requires the user's browser action and any device permissions.

Before longer setup work, tell the user it may take some time and is being prepared in the background when the server actually supports background execution. Track the returned job/session rather than creating duplicates. Honor polling guidance; avoid repeated loading previews. Call a tracker ready only once its topics are ready, then show one compact table with the relevant DealSharp link and the option to discuss clauses here or in DealSharp. Do not claim background completion without checking the result.

For strategy chat, carry forward the user's choices for negotiation theory, web search, company knowledge, project memory, documents and previous conversations. Read the saved answer or terminal result before reporting success.

Always use the environment-matching HTTPS links returned by DealSharp. Never substitute localhost, a tunnel, another environment or a guessed URL. If a result returns an invalid destination, report the problem and obtain the correct server result.
