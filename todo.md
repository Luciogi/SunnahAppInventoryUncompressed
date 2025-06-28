- Python function to output ref tag
```py
def createChapter(str):
     c,v = str.replace("(","").replace(")","").split(":")
     return f"<ref chapter=\\\"{c}\\\" verses=\\\"{v}\\\">{str}</ref>"

```


- [ ] grep -P  ' ([0-9]+:[0-9]+)' -R . inventory/collections/1
- [ ] grep -P  ' ([0-9]+:[0-9]+)' -R . inventory/collections/{2..6}
