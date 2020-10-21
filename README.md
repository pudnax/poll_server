# poll_server

```Bash
while true; do curl --location --request POST 'http://localhost:8000/upload' \--form 'file=@/home/<user>/<file>' -w ' Total: %{time_total}' && echo '\n'; done;
```
