# blub
testing whack-a-mole in a README 

## 1. Include: Failed
![](./foo.svg)

## 2. base64: Failed
![](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMDAiIGhlaWdodD0iMTAwIj48c2NyaXB0PmZ1bmN0aW9uIGluY3JlbWVudCgpIHsgdmFyIHQgPSBkb2N1bWVudC5nZXRFbGVtZW50QnlJZCgidGV4dCIpOyB0LnRleHRDb250ZW50ID0gcGFyc2VJbnQodC50ZXh0Q29udGVudCkgKyAxOyB9PC9zY3JpcHQ+PHJlY3Qgd2lkdGg9IjIwMCIgaGVpZ2h0PSIxMDAiIGZpbGw9ImxpZ2h0Ymx1ZSIgb25jbGljaz0iaW5jcmVtZW50KCkiLz48dGV4dCBpZD0idGV4dCIgeD0iNTAiIHk9IjU1IiBmb250LWZhbWlseT0iQXJpYWwiIGZvbnQtc2l6ZT0iMTYiIGZpbGw9Im5hdnkiPjA8L3RleHQ+PC9zdmc+)

## 3. Embed: Failed

---
<svg xmlns="http://www.w3.org/2000/svg" width="300" height="200">
  <style>
    :root { --count: 0; }
    #counter::after { content: var(--count); }
  </style>
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
      <button onclick="this.style.setProperty('--count', parseInt(getComputedStyle(this).getPropertyValue('--count')) + 1)">
        Clicks: <span id="counter"></span>
      </button>
    </div>
  </foreignObject>
</svg>


---
