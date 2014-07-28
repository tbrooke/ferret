ferret
======

Javascript Platform Agnostic Free Law Ferret

Extract reporter citations from a block of text.

#### Basic Example
```javascript
var
    Ferret = require('path/to/ferret')
  , fs = require('fs')


var file = fs.readFileSync('test.txt', 'utf-8');
var citations = Ferret.get_citations(file);
console.log(citations);

```

Original by Frank Bennett (*See* https://bitbucket.org/fbennett/free-law-ferret)
