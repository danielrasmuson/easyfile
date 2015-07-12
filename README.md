A simple file reader and writer.

```javascript
var file = require('easy-file');

// Will create missing directories
file.write('tmp/hello.txt', 'hello world')

file.read('tmp/hello.txt', function(contents){
  console.log(contents);
})
```

Pull Requests Welcome