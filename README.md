# UID
Generate (almost) unique ids.

## Install
`npm i thesuitcase-uid`

## Usage
```js
import uid from 'thesuitcase-uid';

let id = uid(); // Output: an id which is 6 characters long.
let longId = uid(3); // Output: an id which is 18 characters long (3 * 6)
```

## Quality
[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)
