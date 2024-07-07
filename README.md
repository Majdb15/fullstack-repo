# fullstack-repo
Here are the followed steps:
---
1-Created a frontend repo
---
2-Created a backend repo
---
3-Created a fullstack repo
---
4-Cloned both frontend and backend repo as submodules of the fullstack repo (git submodule add repo-link)
---
5-Created the config.yaml file, added variables to this config file tha should be read by both submodule repos
---
6-Created a github workflow that ensures that any change applied to one of the frontend-repo or backend-repo is directly reflected to the repo specific file inside the fullstack-repo, then all we have to do is one push on the main repo and all changes will be synced or activate the workflow from the github actions
---
7-update client.py file in frontend-repo and comfirm that the updates are automated and shown in fullstack-repo aswell ✔
---
8-update server.py file in backend-repo and comfirm that the updates are automated and shown in fullstack-repo aswell ✔
---
9-run client.py and server.py to ensure that they both can read the variable in the config.yaml file ✔