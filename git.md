# New git

Add user:

```
git config --global user.email "teemuka90@gmail.com"
git config --global user.name "Tman Nen"
```

SSH shit, add to ~/.ssh/config (TODO: add creation of SSH and so on). Docs for creating key: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent?platform=linux

```
Host github.com
  HostName github.com
  User git
  IdentityFile ~/.ssh/github
```