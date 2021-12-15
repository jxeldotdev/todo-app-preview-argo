## Creating a new instance of the application:
1. Checkout new Git branch to match backend or frontend branch
2. Copy `argo/test-environment.yaml` to `argo/branchname-environment.yml`
3. Copy `Charts/todo-app-preview/values.yaml` to `Charts/todo-app-preview/branchname-values.yaml`
2. Modify files as required, updating branchname-environment to use the new values file 
5. Commit and push to remote 
6. Create a PR and get it merged.
7. ArgoCD will automatically deploy the new environmnent

## REMOVE THE FILES WHEN YOU ARE DONE.

