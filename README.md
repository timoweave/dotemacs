# tim dot emacs

- setenv REPO_USER
- setenv REPO_NAME
- curl -u "$REPO_USER" https://api.github.com/user/repos -d "{\"name\":\"$REPO_NAME\"}"
- git remote add origin https://github.com/${REPO_USER}/${REPO_NAME}.git