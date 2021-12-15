---
title: Code Test
date: 2021-11-26
layout: layouts/post.njk
---

All we did there was create a new class for each element that spaces when the elements start animating, using animation-delay values that are just a tenth of a second apart.

```
.delay-1 { animation-delay: 0.6s; }
.delay-2 { animation-delay: 0.7s; }
.delay-3 { animation-delay: 0.8s; }
```

Everything else is exactly the same. And remember that our base delay is 0.5s, so these helper classes count up from there.
