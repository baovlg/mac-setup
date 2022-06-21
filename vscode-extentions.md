# -- VSCODE --

touch vscode-extensions.txt

## write to vscode-extensions.txt
formulahendry.auto-close-tag
formulahendry.auto-rename-tag
streetsidesoftware.code-spell-checker
adpyke.codesnap
ms-azuretools.vscode-docker
ms-vsliveshare.vsliveshare
PKief.material-icon-theme
esbenp.prettier-vscode
dbaeumer.vscode-eslint
ms-vscode-remote.remote-ssh
TabNine.tabnine-vscode
GitHub.copilot
redhat.vscode-yaml
EditorConfig.EditorConfig
mhutchie.git-graph
GitHub.vscode-pull-request-github
eamodio.gitlens

### php
xdebug.php-debug
bmewburn.vscode-intelephense-client


### JS
dsznajder.es7-react-js-snippets
burkeholland.simple-react-snippets
octref.vetur

## run command on terminal
while read line; do code --install-extension "$line"; done < vscode-extensions.txt