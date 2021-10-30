### Bug Report 
- This repo demonstrates the **app crash** when importing a folder component that contains a `index.tsx` and `index.css` for a _React_ frontend with _typescript_.
   - Steps to reproduce:
      - In Terminal, `git pull` this repo
      - Run `meteor npm i` to install dependencies
      - Run `meteor run`
      - Open `localhost:3000` in browser and look at the console logs.  
      - In _imports/ui/Component_, if you rename the `index.css` file to something else, such as `indexx.css` the app then no longer crashes

Meteor version: 2.4 </br>
OS: Fedora 34 KDE 5.22