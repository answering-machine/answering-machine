# Answering Machine
A machine that answers questions.
<pre>
  pip install answering-machine
</pre>
Then:
```Python
  # Python
  import answering_machine
```
Or:
```bash
  echo '[{"role": "user", "content": "I have a question..."}]' | \
  uvx answering-machine \
    --PROVIDER_API_KEY=sk-ant-api... \
    --GITHUB_TOKEN=ghp_... \
    --mode=single
```