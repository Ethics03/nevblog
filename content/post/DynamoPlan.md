
+++
title = "Dynamo Plan"
date = "2025-07-16T09:30:00+05:30"
draft = false
+++

Plan for Dynamo MVP

<!--more-->

Okay! 

So as I explained about my project idea *Dynamo* in the previous blog. I was thinking of what tech-stack to use, AI-Model to use and also how should I connect multiple services together.


That's when I thought about MCP! **Model Context Protocol**

MCP - is basically a set of protocols that lets your AI-Model connect to various services through a context provided. Stuff like 
- Fetching APIs
- Querying DBs
- Interacting with tools like gmail, google calendar etc. 

So I thought as **dynamo** will connect with the user through natural language and track their progress with the micro-goals for the main goal they give to complete in a certain amount of time.

I will use GPT-4o mini (as of now) and Composio MCP for connecting the model with the services I want to use.

Composio is a really sweet MCP implementation. It has integration of mostly all the tools I need.

- Mira
- Gmail
- Google Calendar and many more.

- For the MVP, I'll probably use GPT-4o mini as its free as of now and will pivot to better models in the future.

- Though Claude has more structured answers when it comes to dividing that big goal into smaller sub-goals in a structured manner, but as **Composio** has better support for OpenAI models. I'll use that for now.


- Going to start working on the MVP let's see how it goes.

- This might solve a really important problem of structuring any idea or goal for companies or in general anyone. 

- Dynamo will let them edit the structure as they want but also give them a sweet structure to play around and experiment with in order to finish their goal.


