<p align="center">
  <img width="180px" src="https://github.com/gabriedev/ts-remove/assets/93480406/740d1d94-1b06-4cd6-934e-bc5681022b0f" />
  <br />
  Learn how to effectively remove TypeScript from your projects without dying trying. With this detailed and easy-to-follow documentation.
</p>

# CLI
```sh
find ./src/* -type f ! -name "*.ts" ! -name "*.tsx" -exec cp --parents {} ./dist \
```
