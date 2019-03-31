# Front-End-FAQ
It's a simple repository to share the questions that cross my mind in my journy to learn Front end dev.

## FAQ

### TypeScript vs ES6
Typescript is just a javascript. It's an extension of ES6 with additional features like :
1. Type Annotations
eg:
```
 name: String = ‘xyz’
 number: Number = ‘123’;
```
2. Interfaces
3. Enums
and many more…
Now your browser is not yet advanced to understand Typescript, so typescript’s compiler converts your code to plain JS so that browser can understand it.
### What's the difference between concat and uglify and minify?
* Concatenation is just appending all of the static files into one large file.
* Minification is just removing unnecesary whitespace and redundant / optional tokens like curlys and semicolons, and can be reversed by using a linter.
* Uglification is the act of transforming the code into an "unreadable" form, that is, renaming variables/functions to hide the original intent... It is, also, irreversable.
