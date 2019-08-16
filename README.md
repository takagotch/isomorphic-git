### isomorphic-git
---
https://github.com/isomorphic-git/isomorphic-git

```js
BrowserFS.configure({ fs: "IndexDB", options: {} }, function (err) {
  if (err) return console.log(err);
  window.fs = BrowserFS.BFSRequire("fs");
  git.plugins.set('fs', window.fs);
});

import * as git from 'isomorphic-git'
import {plugins, clone, commit, push} from 'isomorphic-git'
```

```sh
npm install --save isomorphic-git
```

```
```



