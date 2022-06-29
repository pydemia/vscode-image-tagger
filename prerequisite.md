# vscode-image-tagger

## Pre-requisite

### Generate from vscode extension template

```bash
npm install -g yo generator-code
yo code
```

```console

     _-----_     ╭──────────────────────────╮
    |       |    │   Welcome to the Visual  │
    |--(o)--|    │   Studio Code Extension  │
   `---------´   │        generator!        │
    ( _´U`_ )    ╰──────────────────────────╯
    /___A___\   /
     |  ~  |     
   __'.___.'__   
 ´   `  |° ´ Y ` 

? What type of extension do you want to create? (Use arrow keys)
❯ New Extension (TypeScript) 
  New Extension (JavaScript) 
  New Color Theme 
  New Language Support 
  New Code Snippets 
  New Keymap 
  New Extension Pack 
  New Language Pack (Localization) 
  New Web Extension (TypeScript) 
  New Notebook Renderer (TypeScript)

? What type of extension do you want to create? New Extension (TypeScript)
? What's the name of your extension? () image-tagger
? What's the description of your extension? easy tagging tool
? Initialize a git repository? No
? Bundle the source code with webpack? Yes
? Which package manager to use? npm

Writing in /mnt/hdc1/data/git/vscode-image-tagger/image-tagger...
   create image-tagger/.vscode/extensions.json
   create image-tagger/.vscode/launch.json
   create image-tagger/.vscode/settings.json
   create image-tagger/.vscode/tasks.json
   create image-tagger/package.json
   create image-tagger/tsconfig.json
   create image-tagger/.vscodeignore
   create image-tagger/webpack.config.js
   create image-tagger/vsc-extension-quickstart.md
   create image-tagger/README.md
   create image-tagger/CHANGELOG.md
   create image-tagger/src/extension.ts
   create image-tagger/src/test/runTest.ts
   create image-tagger/src/test/suite/extension.test.ts
   create image-tagger/src/test/suite/index.ts
   create image-tagger/.eslintrc.json

Changes to package.json were detected.

Running npm install for you to install the required dependencies.
npm notice Beginning October 4, 2021, all connections to the npm registry - including for package installation - must use TLS 1.2 or higher. You are currently using plaintext http to connect. Please visit the GitHub blog for more information: https://github.blog/2021-08-23-npm-registry-deprecating-tls-1-0-tls-1-1/
npm notice Beginning October 4, 2021, all connections to the npm registry - including for package installation - must use TLS 1.2 or higher. You are currently using plaintext http to connect. Please visit the GitHub blog for more information: https://github.blog/2021-08-23-npm-registry-deprecating-tls-1-0-tls-1-1/

added 300 packages in 11s

53 packages are looking for funding
  run `npm fund` for details

Your extension image-tagger has been created!

To start editing with Visual Studio Code, use the following commands:

     code image-tagger

Open vsc-extension-quickstart.md inside the new extension for further instructions
on how to modify, test and publish your extension.

To run the extension you need to install the recommended extension 'amodio.tsl-problem-matcher'.

For more information, also visit http://code.visualstudio.com and follow us @code.

? Do you want to open the new folder with Visual Studio Code? 
  Open with `code` 
❯ Skip 
```