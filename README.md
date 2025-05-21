This is JavaScript implementation inspired by Ajax.

<h2>Use It</h2>

```
fetch('File Name or ID').then(data => {
  data.text().then(txt => {
    document.getElementById("ID Element You Would Like To Attach To").innerHTML = txt;
  })
})
```
