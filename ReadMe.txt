Microsoft Windows [Version 10.0.19042.1165]
(c) Microsoft Corporation. All rights reserved.

C:\Users\User>cd desktop

C:\Users\User\Desktop>cd node

C:\Users\User\Desktop\Node>dir
 Volume in drive C has no label.
 Volume Serial Number is 4E06-2DC1

 Directory of C:\Users\User\Desktop\Node

28/08/2021  07:51 PM    <DIR>          .
28/08/2021  07:51 PM    <DIR>          ..
27/08/2021  09:28 PM    <DIR>          nodejs_server
               0 File(s)              0 bytes
               3 Dir(s)  55,048,302,592 bytes free

C:\Users\User\Desktop\Node>mkdir whatabyte-portal

C:\Users\User\Desktop\Node>cd whatabyte-portal

C:\Users\User\Desktop\Node\whatabyte-portal>npm init -y
Wrote to C:\Users\User\Desktop\Node\whatabyte-portal\package.json:

{
  "name": "whatabyte-portal",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC"
}



C:\Users\User\Desktop\Node\whatabyte-portal>touch index.js
'touch' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\User\Desktop\Node\whatabyte-portal>type nul > index.js

C:\Users\User\Desktop\Node\whatabyte-portal>dir
 Volume in drive C has no label.
 Volume Serial Number is 4E06-2DC1

 Directory of C:\Users\User\Desktop\Node\whatabyte-portal

28/08/2021  08:44 PM    <DIR>          .
28/08/2021  08:44 PM    <DIR>          ..
28/08/2021  08:44 PM                 0 index.js
28/08/2021  07:54 PM               230 package.json
28/08/2021  07:55 PM                 0 ReadMe.txt
               3 File(s)            230 bytes
               2 Dir(s)  55,016,513,536 bytes free

C:\Users\User\Desktop\Node\whatabyte-portal>npm i -D nodemon

added 119 packages, and audited 120 packages in 31s

11 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities

C:\Users\User\Desktop\Node\whatabyte-portal>dir
 Volume in drive C has no label.
 Volume Serial Number is 4E06-2DC1

 Directory of C:\Users\User\Desktop\Node\whatabyte-portal

28/08/2021  08:51 PM    <DIR>          .
28/08/2021  08:51 PM    <DIR>          ..
28/08/2021  08:44 PM                 0 index.js
28/08/2021  08:51 PM    <DIR>          node_modules
28/08/2021  08:51 PM            83,785 package-lock.json
28/08/2021  08:51 PM               283 package.json
28/08/2021  07:55 PM                 0 ReadMe.txt
               4 File(s)         84,068 bytes
               3 Dir(s)  55,038,509,056 bytes free

C:\Users\User\Desktop\Node\whatabyte-portal>npm i express

added 56 packages, and audited 176 packages in 4s

11 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities

C:\Users\User\Desktop\Node\whatabyte-portal>npm run dev
npm ERR! Missing script: "dev"
npm ERR!
npm ERR! To see a list of scripts, run:
npm ERR!   npm run

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\User\AppData\Local\npm-cache\_logs\2021-08-28T12_57_11_876Z-debug.log

C:\Users\User\Desktop\Node\whatabyte-portal>npm run dev
npm ERR! Missing script: "dev"
npm ERR!
npm ERR! To see a list of scripts, run:
npm ERR!   npm run

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\User\AppData\Local\npm-cache\_logs\2021-08-28T13_10_24_899Z-debug.log

C:\Users\User\Desktop\Node\whatabyte-portal>npm run dev

> whatabyte-portal@1.0.0 dev
> index.js


C:\Users\User\Desktop\Node\whatabyte-portal>npm run dev

> whatabyte-portal@1.0.0 dev
> node index.js

Listening to requests on http://localhost:8000
Terminate batch job (Y/N)? y

C:\Users\User\Desktop\Node\whatabyte-portal>npm i pug

added 42 packages, and audited 218 packages in 12s

18 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities

C:\Users\User\Desktop\Node\whatabyte-portal>mkdir views

C:\Users\User\Desktop\Node\whatabyte-portal>touch views/layout.pug
'touch' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\User\Desktop\Node\whatabyte-portal>type ul > views/layout.pug
The system cannot find the file specified.

C:\Users\User\Desktop\Node\whatabyte-portal>type nul > views/layout.pug

C:\Users\User\Desktop\Node\whatabyte-portal>type nul > views/index.pug

C:\Users\User\Desktop\Node\whatabyte-portal>npm run dev

> whatabyte-portal@1.0.0 dev
> node index.js

Listening to requests on http://localhost:8000
Terminate batch job (Y/N)? y

C:\Users\User\Desktop\Node\whatabyte-portal>npm i -D browser-sync
npm WARN deprecated debug@4.1.1: Debug versions >=3.2.0 <3.2.7 || >=4 <4.3.1 have a low-severity ReDos regression when used in a Node.js environment. It is recommended you upgrade to 3.2.7 or 4.3.1. (https://github.com/visionmedia/debug/issues/797)
npm WARN deprecated debug@4.1.1: Debug versions >=3.2.0 <3.2.7 || >=4 <4.3.1 have a low-severity ReDos regression when used in a Node.js environment. It is recommended you upgrade to 3.2.7 or 4.3.1. (https://github.com/visionmedia/debug/issues/797)
npm WARN deprecated debug@4.1.1: Debug versions >=3.2.0 <3.2.7 || >=4 <4.3.1 have a low-severity ReDos regression when used in a Node.js environment. It is recommended you upgrade to 3.2.7 or 4.3.1. (https://github.com/visionmedia/debug/issues/797)

added 132 packages, and audited 350 packages in 45s

22 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities

C:\Users\User\Desktop\Node\whatabyte-portal>browser-sync init
'browser-sync' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\User\Desktop\Node\whatabyte-portal>browser-sync init
'browser-sync' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\User\Desktop\Node\whatabyte-portal>