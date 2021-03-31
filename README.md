# yarn-node-linker-bin-issue
 ## To reproduce run
 ```cli
  yarn install && cd apps/app-workspace-2 && yarn node_modules node_modules-path
 ````
Note that it logs
`apps\app-workspace-3\node_modules` instead of the current workspace node_modules folder.