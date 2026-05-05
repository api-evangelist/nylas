---
title: "The things AI agents still can’t do"
url: "https://www.nylas.com/blog/ai-agents-limitations-production/"
date: "Tue, 10 Mar 2026 19:53:56 +0000"
author: "Allen Warner"
feed_url: "https://www.nylas.com/blog/feed/"
---
<p><em>AI agents are getting better at reasoning, but most still struggle to act inside the real systems where work happens. The biggest constraint in agentic AI today isn’t intelligence. It’s execution across inboxes, calendars, and identity systems.</em></p>



<hr class="wp-block-separator has-alpha-channel-opacity" />



<p>AI agents are getting better at reasoning, which is why interest in agentic AI systems has exploded over the past year. They can draft emails, summarize meetings, extract next steps, and plan multi-step workflows. In controlled demos they increasingly appear autonomous.</p>



<p>In production environments, however, most agents still run into the same constraint: they can&#8217;t reliably interact with the systems where people actually coordinate work. Most agentic AI systems still rely on integrations with real email APIs, calendar APIs, and identity systems to take action inside real workflows.</p>



<p>That limitation rarely appears in demos. It becomes obvious the moment an agent attempts to operate inside real software used by real teams.</p>



<p>Because most business workflows don&#8217;t end with reasoning. They end with communication. Someone sends an email, schedules a meeting, updates a system of record, or replies to a conversation already in progress.</p>



<p>Until an agent can operate inside those communication systems, it can&#8217;t actually execute the workflow it reasoned about.</p>



<p><em>That distinction is quietly becoming one of the most important constraints shaping the next phase of agentic AI.</em></p>



<h3 class="wp-block-heading">Why reasoning is no longer the hard problem in agentic AI</h3>



<p>Large language models have dramatically lowered the cost of reasoning. Generating a follow-up email, summarizing a conversation, or identifying the next action in a workflow is now relatively straightforward, and many applications already do this well.</p>



<p>Execution is harder.</p>



<p>An agent that drafts an email isn&#8217;t the same as an agent that can send it from a real inbox, maintain the thread across replies, and react when the recipient responds.</p>



<p>An agent that suggests meeting times isn&#8217;t the same as one that can coordinate availability across calendars, handle time zones, send invitations, and update the event when someone reschedules.</p>



<p>Reasoning about a workflow is one problem. Acting inside the systems where that workflow actually happens is another.</p>



<p>Most agents today can do the first. And far fewer can do the second.</p>



<h3 class="wp-block-heading">Where work actually happens</h3>



<p>If you look closely at where work moves forward inside orgs, you&#8217;ll notice a clear pattern.</p>



<p><em>The coordination layer is almost always communication infrastructure.</em></p>



<p>Deals advance through email conversations, support issues move through shared inboxes, interviews are coordinated through calendars, and projects move forward through meetings and follow-ups.</p>



<p>Even highly automated SaaS products still rely on these systems because they connect software to people.</p>



<p>That means an agent can&#8217;t fully execute most real workflows unless it can operate inside those environments — not simulated ones, but real inboxes, real calendars, and real identities.</p>



<h3 class="wp-block-heading">Where AI agents break in production</h3>



<p>This gap becomes obvious when teams attempt to deploy agents in production.</p>



<p>Take a sales workflow as an example. An agent might correctly identify the next step after a customer call. It drafts a follow-up email, suggests a meeting, and recommends updating the CRM.</p>



<p>Without access to the actual inbox and calendar involved in that conversation, none of those actions can happen automatically. The system can only make suggestions.</p>



<p>The same pattern appears in support operations. Classifying an incoming message is easy. Routing it, responding from the correct shared inbox, tracking replies, and escalating issues requires interacting with the real mailbox where those conversations live.</p>



<p>Recruiting coordination exposes the same limitation. Suggesting interview times is trivial. Actually scheduling interviews across multiple calendars, handling time zones, managing reschedules, and sending confirmations requires operating inside live calendar systems.</p>



<p>Even meeting intelligence products follow the same pattern. Generating a transcript is now table stakes. Triggering recap emails, scheduling follow-ups, and updating downstream systems requires acting within the communication infrastructure where the meeting participants already operate.</p>



<p>Across these workflows, the useful part isn&#8217;t reasoning about what should happen next. It&#8217;s executing the next step inside the systems where the conversation continues.</p>



<h3 class="wp-block-heading">The real constraint in agentic AI</h3>



<p>This is why many teams find that moving from a working demo to a reliable production agent is harder than expected.</p>



<p>The challenge is rarely intelligence. More often, it&#8217;s integration.</p>



<p>Agents need to operate inside real inboxes, real calendars, and real identity boundaries. They need to maintain thread continuity, respond to events, and respect permission models across providers.</p>



<p>Those requirements introduce complexity that doesn&#8217;t appear in model benchmarks or demo environments.</p>



<p>But they are exactly what make the difference between a system that suggests actions and one that actually performs them.</p>



<h3 class="wp-block-heading">What this means for builders</h3>



<p>For teams building agentic workflows, this shifts where the real work happens.</p>



<p>The hard problem is no longer just improving reasoning. It&#8217;s building systems that allow agents to interact safely and reliably with the environments where human coordination occurs.</p>



<p>That means connecting to live communication systems, respecting identity and permission boundaries, maintaining context across conversations, and reacting to real-time events such as replies or calendar updates.</p>



<p>In other words, enabling agents to act inside the infrastructure where work already moves.</p>



<p>Because an agent that can&#8217;t communicate with people through the systems they already use isn&#8217;t truly autonomous; it&#8217;s simply suggesting what someone else should do next.</p>



<h3 class="wp-block-heading">The next phase of agentic AI</h3>



<p>LLMs made reasoning widely accessible.</p>



<p>The next phase of agentic AI will be defined by something more practical: which systems allow agents to reliably take action in the real workflows where work happens.</p>



<p>That means interacting with inboxes, calendars, meetings, and the identity layers behind them — not simulated data or isolated APIs, but real communication environments.</p>



<p>Until agents can operate there, their intelligence will remain partially constrained.</p>



<p>Once they can, the difference between suggesting a workflow and executing one begins to disappear.</p>



<hr class="wp-block-separator has-alpha-channel-opacity" />



<h3 class="wp-block-heading"><strong>Agentic AI guides from Nylas</strong></h3>



<p><strong>Industry insights</strong></p>



<ul class="wp-block-list">
<li><a href="https://www.nylas.com/blog/the-state-of-agentic-ai-in-2026/">The state of agentic AI in 2026: What teams are actually shipping</a></li>



<li><a href="https://www.nylas.com/blog/agentic-ai-production-stack/">The production stack for agentic AI</a></li>



<li><a href="https://www.nylas.com/blog/the-infrastructure-race-behind-agentic-ai/">The infrastructure race behind agentic AI</a></li>



<li><a href="https://www.nylas.com/blog/how-agentic-ai-adoption-is-scaling-from-the-inside-out/" rel="noreferrer noopener" target="_blank">How agentic AI adoption is scaling from the inside out</a></li>



<li><a href="https://www.nylas.com/agentic-ai-report-2026/">The 2026 State of&nbsp;Agentic AI Report</a> [Full ungated report]</li>
</ul>



<p><strong>Build guides</strong></p>



<ul class="wp-block-list">
<li><a href="https://www.nylas.com/blog/how-to-build-an-ai-agent-for-your-crm/">How to build an AI agent for your CRM</a></li>



<li><a href="https://www.nylas.com/blog/how-to-build-an-ai-agent-for-your-ats/">How to build an AI agent for your ATS</a></li>



<li><a href="https://www.nylas.com/blog/building-ai-agents-why-reliable-communications-data-matters/">Building AI Agents: Why reliable communications data matters</a></li>
</ul>
<p>The post <a href="https://www.nylas.com/blog/ai-agents-limitations-production/">The things AI agents still can’t do</a> appeared first on <a href="https://www.nylas.com">Nylas</a>.</p>
