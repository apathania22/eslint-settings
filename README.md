## Install Packages
- npm i -D eslint prettier eslint-plugin-prettier eslint-config-prettier eslint-plugin-node eslint-config-node
- npx install-peerdeps --dev eslint-config-airbnb

## VS-Code setting.json
{
    "git.ignoreLimitWarning": true,
    "editor.formatOnSave": true,
    "editor.codeActionsOnSave": { "source.fixAll.eslint": true }
}
