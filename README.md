

### YouTube
- ```javascript
  JSON.stringify([...new Set(Array.from(document.getElementById("contents").getElementsByTagName("a")).filter(a => a.href.indexOf("watch?v=") > -1).map(a => a.href))])
  ```
