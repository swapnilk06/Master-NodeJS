## 3] Hello World NodeJS

- [x] NodeJS execute only `js file`

```bash
node hello.js
// OR
node hello
```

#### DOM related elements

- [x] DOM related elements or window related elements are not include in NodeJS

```js
console.log(window); // Error : window is not defined

console.log(alert("Hey")); // Error : alert is not defined
```

> - [!NOTE]
> - DOM related elements work in **Inspect Mode** of browser.
> - But, JavaScript some functions that are not work in terminal.

#### Facts DOM related elements

-[x] `V8 engine not directly embedded withh C++`(No include DOM related elements or Window related elements).

- [x] **NodeJS** can only run on -> `Server side`
- [x] `UI related work` or `DOM manipulation related work` that in JavaScript are removed from that.
- [x] All over **windows objects** (like document.element-by-id, navigator...) are not available
- [x] It includes only `CORE Functionality of JavaScript`that are needed in server side.

> - [!NOTE]
> - In V8 engine NodeJS some features are not includes & some extra feature also added in that.
> - It includes Cryptography like encryption, decryption, file handling like features additional.
> - But excludes, UI DOM related work that not required in server side that removed.

- [x] For creating new project that create files that run your project

```bash
npm init
```

- [x] After that autmoatically created **package.json** configuration file for that project.

- [x] In **package.json** make your own script & run with `npm start`

```json
	...
	...
"start": "node hello.js"
	...
	...
```


-----
