---
title: "The Nylas CLI, Nylas skill, and Claude Code plugin are live"
url: "https://www.nylas.com/blog/nylas-cli-skill-claude-code-plugin/"
date: "Wed, 29 Apr 2026 18:36:13 +0000"
author: "Nick Barraclough"
feed_url: "https://www.nylas.com/blog/feed/"
---
<h2 id="nylas-is-now-native-in-the-coding-agents-youre-already-using"><strong>Nylas is now native in the coding agents you&#8217;re already using</strong></h2>



<p>If you&#8217;re building with Claude Code, Cursor, Codex, or any other coding agent, you&#8217;ve probably already felt the friction: the agent knows how to write code, but when it hits anything involving email or calendar APIs, it slows down. It guesses at endpoints, writes boilerplate auth code from memory, and asks you questions it shouldn&#8217;t have to ask.</p>



<p>That friction is gone, thanks to Nylas.</p>



<p>Nylas is now native in the coding agents you&#8217;re already using. Three ways to install, depending on how you work.</p>



<h2 id="the-nylas-cli"><strong>The Nylas CLI</strong></h2>



<p>The Nylas CLI runs in your terminal. Any agent with shell access can use it directly. That includes Claude Code, Cursor, Codex, and open source coding agents. You don&#8217;t have to install an SDK or set up OAuth to use it.</p>



<p>Install it in one command:</p>




<div class="nylas-code">
    <button class="copy-code" title="Copy Code"></button>
    <pre class="shiki andromeeda" style="background-color: #23262E; color: #D5CED9;" tabindex="0"><code><span class="line"><span style="color: #00E8C6;">brew</span><span style="color: #00E8C6;"> install</span><span style="color: #00E8C6;"> nylas</span><span style="color: #EE5D43;">/</span><span style="color: #00E8C6;">nylas</span><span style="color: #EE5D43;">-</span><span style="color: #00E8C6;">cli</span><span style="color: #EE5D43;">/</span><span style="color: #00E8C6;">nylas</span></span></code></pre></div>



<p></p>



<p>No Homebrew? Use the install script instead:</p>



<div class="nylas-code">
    <button class="copy-code" title="Copy Code"></button>
    <pre class="shiki andromeeda" style="background-color: #23262E; color: #D5CED9;" tabindex="0"><code><span class="line"><span style="color: #00E8C6;">curl</span><span style="color: #EE5D43;"> -</span><span style="color: #00E8C6;">fsSL</span><span style="color: #D5CED9;"> https:</span><span style="color: #A0A1A7CC;">//cli.nylas.com/install.sh | bash</span></span></code></pre></div>



<p></p>



<p>Run nylas init once to authenticate, and your agent can immediately start sending email, listing calendar events, creating meetings, managing contacts, and spinning up webhooks — all from the terminal, all with structured JSON output it can parse and act on.</p>



<p>For coding agents specifically, the most useful part is credential discovery. Before writing a line of code, your agent can run nylas auth whoami &#8211;json to check whether credentials already exist on the machine, extract the API key and grant ID automatically, and write them to .env  without ever asking you to copy-paste anything.</p>



<p>For autonomous agents that need their own identity — a sales agent, a support bot, a shared service mailbox — the CLI provisions Agent Accounts directly:</p>



<div class="nylas-code">
    <button class="copy-code" title="Copy Code"></button>
    <pre class="shiki andromeeda" style="background-color: #23262E; color: #D5CED9;" tabindex="0"><code><span class="line"><span style="color: #00E8C6;">nylas</span><span style="color: #00E8C6;"> agent</span><span style="color: #00E8C6;"> account</span><span style="color: #00E8C6;"> create</span><span style="color: #00E8C6;"> outreach</span><span style="color: #D5CED9;">@</span><span style="color: #F39C12;">yourcompany</span><span style="color: #D5CED9;">.</span><span style="color: #00E8C6;">com</span></span></code></pre></div>



<p></p>



<p>One command. The agent has its own Nylas-hosted email address and calendar. No OAuth, no shared inbox, no credentials tied to a human account that can expire when someone leaves.</p>



<p><a href="https://developer.nylas.com/docs/v3/getting-started/cli-for-agents/"><strong>Quickstart: Autonomous AI agents →</strong></a></p>



<h2 id="the-nylas-skill"><strong>The Nylas skill</strong></h2>



<p>The Nylas skill pre-loads your coding agent with current Nylas API, CLI, and SDK context. Instead of exploring the docs mid-task or guessing at endpoint shapes, the agent already knows the right patterns before it writes the first line.</p>



<p>Install both skills — API and CLI — in one command:</p>



<div class="nylas-code">
    <button class="copy-code" title="Copy Code"></button>
    <pre class="shiki andromeeda" style="background-color: #23262E; color: #D5CED9;" tabindex="0"><code><span class="line"><span style="color: #00E8C6;">npx</span><span style="color: #00E8C6;"> skills</span><span style="color: #00E8C6;"> add</span><span style="color: #00E8C6;"> nylas</span><span style="color: #EE5D43;">/</span><span style="color: #00E8C6;">skills</span></span></code></pre></div>



<p></p>



<p>Or install them individually:</p>



<div class="nylas-code">
    <button class="copy-code" title="Copy Code"></button>
    <pre class="shiki andromeeda" style="background-color: #23262E; color: #D5CED9;" tabindex="0"><code><span class="line"><span style="color: #00E8C6;">npx</span><span style="color: #00E8C6;"> skills</span><span style="color: #00E8C6;"> add</span><span style="color: #00E8C6;"> nylas</span><span style="color: #EE5D43;">/</span><span style="color: #00E8C6;">skills</span><span style="color: #EE5D43;">/</span><span style="color: #00E8C6;">nylas</span><span style="color: #EE5D43;">-</span><span style="color: #00E8C6;">api</span></span>
<span class="line"><span style="color: #00E8C6;">npx</span><span style="color: #00E8C6;"> skills</span><span style="color: #00E8C6;"> add</span><span style="color: #00E8C6;"> nylas</span><span style="color: #EE5D43;">/</span><span style="color: #00E8C6;">skills</span><span style="color: #EE5D43;">/</span><span style="color: #00E8C6;">nylas</span><span style="color: #EE5D43;">-</span><span style="color: #00E8C6;">cli</span></span></code></pre></div>



<p></p>



<p>The nylas-api skill covers authentication, email, calendar, contacts, webhooks, Scheduler, Notetaker, and SDK usage across Node.js, Python, Ruby, and Java/Kotlin. The nylas-cli skill covers every CLI command, flag, and expected output shape.</p>



<p>Skills work with Claude Code, Cursor, Codex , and 40+ other agents. Install once and the agent writes correct Nylas code on the first try.</p>



<p><a href="https://developer.nylas.com/docs/v3/getting-started/coding-agents/"><strong>Guide for AI coding agents</strong></a></p>



<h2 id="the-claude-code-plugin"><strong>The Claude Code plugin</strong></h2>



<p>If you work in Claude Code, the plugin installs the skills and wires up the MCP server in one step.</p>



<div class="nylas-code">
    <button class="copy-code" title="Copy Code"></button>
    <pre class="shiki andromeeda" style="background-color: #23262E; color: #D5CED9;" tabindex="0"><code><span class="line"><span style="color: #EE5D43;">/</span><span style="color: #00E8C6;">plugin</span><span style="color: #00E8C6;"> marketplace</span><span style="color: #00E8C6;"> add</span><span style="color: #00E8C6;"> nylas</span><span style="color: #EE5D43;">/</span><span style="color: #00E8C6;">skills</span></span>
<span class="line"><span style="color: #EE5D43;">/</span><span style="color: #00E8C6;">plugin</span><span style="color: #00E8C6;"> install</span><span style="color: #00E8C6;"> nylas</span><span style="color: #EE5D43;">-</span><span style="color: #00E8C6;">skills</span></span>
<span class="line"></span></code></pre></div>



<p></p>



<p>Once installed, Claude Code has email, calendar, and contacts as native tools it can call at any point in a session, not just when you point it at the docs. The plugin covers slash commands, MCP tool definitions, and the full Nylas CLI context.</p>



<p>For teams already using Claude Code as their primary coding environment, this is the fastest path from zero to a working Nylas integration.</p>



<h2 id="which-one-to-install"><strong>Which one to install</strong></h2>



<p>If you&#8217;re using Claude Code: start with the plugin. It handles everything.</p>



<p>If you&#8217;re using Cursor, Codex, or another agent: install the skill with npx skills add nylas/skills. The CLI comes along with it.</p>



<p>If you&#8217;re building an autonomous agent that needs its own email identity: install the CLI directly and use nylas agent account create to provision Agent Accounts.</p>



<p>All three are live today. Install the one that matches your setup and start building.</p>



<p><a href="https://developer.nylas.com/docs/v3/getting-started/coding-agents/"><strong>For AI coding agents </strong></a> |<a href="https://developer.nylas.com/docs/v3/getting-started/cli-for-agents/"> <strong>For autonomous agents</strong></a></p>
<p>The post <a href="https://www.nylas.com/blog/nylas-cli-skill-claude-code-plugin/">The Nylas CLI, Nylas skill, and Claude Code plugin are live</a> appeared first on <a href="https://www.nylas.com">Nylas</a>.</p>
