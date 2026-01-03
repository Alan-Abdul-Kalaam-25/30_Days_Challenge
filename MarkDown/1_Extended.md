The below in the code sample in single line:-  
`const port = process.env.PORT || 3000;`  

Code sample in multiple lines:-  
```
import express from "express"

const port = process.env.PORT || 5000

const app = express()

app.get("/", (req, res) => {
    res.end("It's JS in Express.JS")
})

app.listen(port, {} => {
    console.log(`Listening on http://localhost:${port}`)
})
```

Code with syntax highlighting:-
```javascript
import express from "express"

const port = process.env.PORT || 5000

const app = express()

app.get("/", (req, res) => {
    res.end("It's JS in Express.JS")
})

app.listen(port, {} => {
    console.log(`Listening on http://localhost:${port}`)
})
```

```c
#include<stdio.h>

void main() {
    char name[] = "Alan Abdul Kalaam";
    printf("My name is %s\n");
}
```
```py
from os import *
import http

def name:
    nme = "alan"
    print(name)

print(f"OS name: {name}")
```

## Links:-
Now [click](https://localhost:3000/) this link  
Also a link: <https://google.com/gemini/>  
Also another link: https://amazon.in/products/  

## Lists:-

This is an ordered list  
1. Item
   1. subitem
   2. subitem
      1. sub-sub item
      2. sub-sub item
   3. subitem
2. Item
3. Item
---
This is unordered list  
- item
  - subitem
    - sub-sub item
    - sub-sub item
  - subitem
- item
- item
---
* Apple
  * iphone
  * ipad
* Samsung
  * galaxy phone
    * galaxy a55 5g
  * galaxy laptop
  * battle tank
* Google
* Xiaomi
---
+ one
  + one.one
    + one.one.one
      + one.one.one.one
    + one.one.two
  + one.two
  + one.three
+ two
+ three
+ four
---

> This is block quote  

> This is nested
> > Block quote  

## Images:-  
![Alt text here!](/link-to-image)  
![Alt text here!](https://a.com/link-to-image)

## Checklist:-
- [x] Complete the datascience course
  - [ ] Nested check
- [ ] Go to shopping for fruits
- [x] Replace the old RAM sticks  

