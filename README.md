# 📙 Storybook on ZEIT Now

Storybook for React components

## deploy on Now

```
yarn deploy
```

## GitHub integration

You can use the GitHub integration, but you have to change the `now.json` removing

```
"github": {
    "enabled": false
  }
```

remove `/storybook-static` from the `.gitignore` and

```
yarn build-storybook
```
