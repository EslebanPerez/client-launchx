# vue-3-crud

```mermaid
graph TD;
F(Server)
A(Axios http-common.js)
B(explorerService)
C(Componets)
D(Router)
E(main.js)
F-->|conect|A
A-->|import|B
B-->|import methods|C
C-->|import componets|D
D-->|import|E
```
```mermaid
graph TD;
Component(Component)
addExplorer(addExplorer)
explorer(explorer)

saveExplorer(saveExplorer)
deleteExplorer(deleteExplorer)
editExplorer(editExplorer)
updateExplorer(updateExplorer)
getAllExplorer(getAllExplorer)

explorerList(explorerList)
Component --> addExplorer
Component --> explorer
Component --> explorerList

addExplorer --> saveExplorer

explorer --> deleteExplorer
explorer --> editExplorer
explorer --> updateExplorer

explorerList --> getAllExplorer
```

```
## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
