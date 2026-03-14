# kintone-devcontainer

```
bun install
bun x cli-kintone customize init --output customize-manifest.json
```

```
mkdir my-custom-app
cd my-custom-app
bun init -y
bun add -d @kintone/rest-api-client @kintone/eslint-plugin typescript
```

```
kintone-dts-gen --host https://xxx.cybozu.com --app-id 1 --api-token yyy
```

```
kintone app customize upload --domain xxx.cybozu.com --app 1 --api-token yyy ./src/index.js
```

```
kintone-create-plugin my-new-plugin
cd my-new-plugin
bun install
```

```
bun run build
kintone-plugin-packer src --ppk private.ppk
```

```
kintone-plugin-uploader --domain xxx.cybozu.com --username user --password pass dist/plugin.zip
```
