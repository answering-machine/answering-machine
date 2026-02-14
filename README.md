# Answering Machine
A machine that answers questions coming through a pipe.
```bash
  echo '[{"role": "user", "content": "I have a question...?"}]' \
    | uvx answering-machine \
        --PROVIDER_API_KEY=sk-ant-api... \
        --GITHUB_TOKEN=ghp_... \
        --mode=single
```
Or:
```bash
  pip install answering-machine
```
Then:
```Python
  # Python
  import answering_machine
```