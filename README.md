- š Hi, Iām @the-one-with-raspberry
- š Iām interested in javascript
- š± Iām currently learning nothing
- š« victorstefan.costin@gmail.com
- ![Youtube](https://emojipedia-us.s3.amazonaws.com/content/2020/04/05/yt.png) https://www.youtube.com/channel/UCxGHpsV2VBI4fNgM7VMnflg

a cool script that i wrote:
```js
function mapCharStringToJSON(string) {
    const strCharArray = string.split('');
    let JSONobj = new Object();
    let i = 0;
    for (let char of strCharArray) {
        JSONobj[char] = i;
        i = i + 1;
    }
    return JSONobj;
}

const exampleStr = 'henlo';

console.log(JSON.stringify(mapCharStringToJSON(exampleStr)));
// returns: {"h":0,"e":1,"n":2,"l":3,"o":4}
// strings with repeated characters dont work :(
```

<!---
the-one-with-raspberry/the-one-with-raspberry is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
