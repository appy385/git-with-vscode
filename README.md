# git-with-vscode
1. cloning
2. stage,unstage, commit and  discard changes
3. history(extension) - View history ,compare branch and previous commits (Git History extension)
4. branch - create, merge
5. tag  - capture a point in git history for release version
6. push , pull, fetch ,commit, revert 
7. Eslint - Setup link https://www.digitalocean.com/community/tutorials/linting-and-formatting-with-eslint-in-vs-code  
ESlint is a tool to make code more consistent and avoid bugs. Three style guides are - Airnbn, Standard & Google: All of them enforce these rules:
``` 
Tabs (indent): Two-spaces.
Quotes (quotes): Single.
Brace style for control blocks (brace-style): Same line.
Prefer const/let over var (no-var): True.
No trailing spaces (no-trailing-spaces): True.
Array bracket spacing (array-bracket-spacing): No spaces. 
```
Airbnb’s style guide is generally considered the best option for React development.  

Complete list of all rules in eslint :- https://eslint.org/docs/rules/  
 Code Actions on Save (Edit in settings.json) - to automatically fix syntax and formatting issues every time you save
 ```
 "editor.codeActionsOnSave": {
  "source.fixAll.eslint": true
},
"eslint.validate": ["javascript"]
```
.eslintrc.json file ("rules" object) - To customize the errors or disable ESLint triggers

package.json file - add in script
```
script:{
    "lint":"eslint"
}
```
Now you can also run ```npm run lint <filname>```