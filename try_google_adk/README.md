### Trial Running Google ADK

The quickstart in the
[docs](https://google.github.io/adk-docs/get-started/quickstart/)
does a great job in getting the agent UI up and
running.

Need to give attention to the followin

- Need to use the python virtual environment for
  setup. UV doesn't work out of the box

- If planning to use different AI models then
  refer
  [this](https://google.github.io/adk-docs/agents/models/)

- The \_\_init\_\_.py file needs to have the from
  . import agent line in it.

- The Google AI studio Models would be the best
  for the quick start

Rest of the process is straight forward leading to
spawn the UI
