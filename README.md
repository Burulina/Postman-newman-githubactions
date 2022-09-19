# Postman + newman + github actions (Simple project)
## Setup
1. Before run this project, you need to download and install:
- [last version of VS Code](https://code.visualstudio.com/) or any other IDE (for your choice);
- [at least Node.js 14](https://nodejs.org/uk/download/).
2. Clone git repository:
``` console
git clone https://github.com/Burulina/Postman-newman-githubactions.git
```
- and install node.js dependencies:
``` console
npm i
```
## Steps to run
1. Run testing server locally in bash terminal in VS Code or any other IDE:
``` console
npm run tern-on-api
```
2. Upload `storeLast.collection.json` in Postman app.
3. Run tests for folder `Products` from `storeLast.collection.json` in Postman app:
``` console
right click on `Products` folder -> Run collection
```