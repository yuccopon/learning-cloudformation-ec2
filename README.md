## 実行する際はshellに以下を入力する

```powershell
aws cloudformation deploy `
  --template-file template.yaml `
  --stack-name yuiko-vpc `
  --parameter-overrides "PublicKeyMaterial=$(cat id_rsa.pub)"
```

