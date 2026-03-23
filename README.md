# Devising-Machine
A Machine that devises plans.

In order to launch it with OpenAI as LLM provider:
```bash
  echo "Theodotos-Alexandreus: Devise a plan of action, Machine." \
    | uvx devising-machine \
        --provider-api-key=sk-proj-... \
        --github-token=ghp_... 
```
Or with Anthropic:
```bash
  echo "Theodotos-Alexandreus: Devise a plan of action, Machine." \
    | uvx --with "devising-machine[anthropic]" devising-machine \
        --provider-api-key=sk-ant-... \
        --github-token=ghp_... 
```
Or with Gemini:
```bash
  echo "Theodotos-Alexandreus: Devise a plan of action, Machine." \
    | uvx --with "devising-machine[gemini]" devising-machine \
        --provider-api-key=AIzaSy... \
        --github-token=ghp_... 
```
Or:
```bash
  pip install devising-machine
```
Then:
```Python
  # Python
  import devising_machine
```
