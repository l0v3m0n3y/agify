# agify
api for agify.io 
# Example
```nim
import asyncdispatch, agify, json, strutils
let data = waitFor age_by_name("name")
echo data
```

# Launch (your script)
```
nim c -d:ssl -r  your_app.nim
```
