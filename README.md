# Curl commands to test webapp endpoints
```
 curl -X GET http://server_ip_addr/
 
 curl -X POST -H "Content-Type: application/json" -d '{"msg": "my-message"}' http://server-ip-addr/my-message
```
# Cheatsheet for taking better README.md notes
- [github notes for basic formating for md](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- Linux command for printing directory of folder
        ```bash
        foo@bar:~$ tree -L 2
        ├── index.js
        ├── model
        │   └── model.js
        ├── node_modules
        ├── Notes.txt
        ├── package.json
        ├── package-lock.json
        ├── routes
        │   └── routes.js
        └── temp.txt
        ```
    - tree for 'express-generator --view=pug my-app'
    - recommended folder structure for webapps in which MVC is compartmentalized
        ```
        ├── app.js
        ├── bin
        │   └── www
        ├── node_modules
        │   └── .
        ├── package.json
        ├── package-lock.json
        ├── public
        │   ├── images
        │   ├── javascripts
        │   └── stylesheets
        │       └── style.css
        ├── routes
        │   ├── index.js
        │   └── users.js
        └── views
            ├── error.pug
            ├── index.pug
            └── layout.pug
        ```

## examples
 - **\*\*BOLD\*\* \_\_text\_\_**
 - *\*Italicized\* \_text\_*
 - **_\*\*\_Bold and Italicized text\_\*\* and \_\_\*Bold and Italicized text\*\_\__**
 - ***\*\*\*All Bold and Italicized\*\*\****
 - ~~Strke Through~~ \~\~text\~\~
 - <sup>super-script</sup> \<sup> text \</sup>
 - ````
    showing code
    ```(blank)|python|shell|bash|powershell|DOS|python
    code
    ```
   ````
   [list of supported languages in .md](https://docs.readme.com/rdmd/docs/code-blocks)
- Quoting text
    > \> adding quotes 
- create unordered list by doing: [space] * | + | -
- create ordered list by doing: [space] [any number] . exa 0.
    
    1. my
    2. tiny
    3. list


 


# Notes
- [The Express API documentation - should read!](https://expressjs.com/en/4x/api.html)
- [Understanding NodeJS folder structure](https://www.geeksforgeeks.org/folder-structure-for-a-node-js-project/)
- [Understanding purpose of package-lock.json](https://stackoverflow.com/questions/44297803/what-is-the-role-of-the-package-lock-json)
- [The git documentation](https://git-scm.com/doc)
