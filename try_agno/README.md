### Setup Process

1. Get basic Agno Agent script

```
uv init try_agno

cd try_agno

uv add agno anthropic 'fastapi[standard]' yfinance
```

2. Add the UI code classes and functions to the
   agent script

from agno.playground import Playground,

serve_playground_app

3. Install the Agent-UI open source front end
   package

Refer to
https://docs.agno.com/introduction/playground#open-source-agent-ui

npx create-agent-ui@latest (You need npx
installed)

4. Run the agent and the UI

```
# in the try_agno folder
uv run main.py

# The above command will spawn a server and terminal will not have a prompt

# Open a different terminal to run the front-end
cd agent-ui

npm run dev

open the browser to http://localhost:3000

Don't use the 192.168.1.x address as it will not work
```
