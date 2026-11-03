# superagent

Workspaces for the dsh-superagent prototype: an agent that takes requests from
GitHub Issues and comments, evaluates them under a Policy, and executes each
approved request in its own DSH Session.

Requests are made by mentioning the agent account in an Issue or comment.

## Invoking the agent

Open an Issue or add a comment that describes what you want and mention the
agent account. The request is evaluated under a Policy, and each approved
request is executed in its own DSH Session. The agent then reports the result
back in the same thread.
