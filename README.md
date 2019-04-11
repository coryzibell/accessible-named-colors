# Accessible Named Colors
## WCAG Level AA Compliant Named CSS Colors

I used Cloudflare Design's awesome tool to generate this list:

https://cloudflare.design/color

https://github.com/cloudflare-design/color

### Usage
```const colors = require('accessibleNamedColors')```

or

```import colors from 'accessibleNamedColors'```

What you get is an array of array pairs of named colors like this:

```
[
  ['midnightblue', 'violet'],
  ['midnightblue', 'wheat'],
  ['midnightblue', 'white'],
  ['midnightblue', 'whitesmoke'],
  ['midnightblue', 'yellow'],
  ['midnightblue', 'yellowgreen'],
  ['mintcream', 'navy'],
  ['mintcream', 'purple'],
  ['mintcream', 'rebeccapurple']
]
```

^ That's extremely shortened. The full set is over 1500 pairs.

*Important to note that the list is deduped.*

So you won't get `['mintcream', 'navy']` and `['navy', 'mintcream']`