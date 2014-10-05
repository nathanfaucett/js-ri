Context
=======

response and request helpers


```javascript
var context = require("context"),
    config = {
        "json spaces": 4
    };

server.on("request", function(req, res) {
    context.init(req, res, config);
    req.app = res.app = app;
});
```