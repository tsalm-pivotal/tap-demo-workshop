Configure Git username and email address for commits to your temporary repository
```execute
git config --global user.email "{{ENV_GIT_USER}}@vmware.com"
git config --global user.name {{ENV_GIT_USER}}
```

Create a public repository with the following name for GIT user `{{ ENV_GIT_USER }}` here:
```copy
{{ session_namespace }}
```