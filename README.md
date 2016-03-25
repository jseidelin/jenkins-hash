hash-jenkins
============

Bob Jenkins lookup2 and one-at-a-time hash functions

## Usage

```javascript
var Jenkins = require("hash-jenkins");

// one-at-a-time hash
Jenkins.oaat("hello world"); // 1045060183

// lookup2 hash
Jenkins.lookup2("hello world"); // 447289830
```