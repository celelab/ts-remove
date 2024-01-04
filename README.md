# ts-remove
Learn how to effectively remove TypeScript from your projects without dying trying. With this detailed and easy-to-follow documentation.

# CLI
```sh
find ./src/* -type f ! -name "*.ts" ! -name "*.tsx" -exec cp --parents {} ./dist \
```
