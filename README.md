# actions-test
インフラチームのGithub Actionsのテスト

このリポジトリでは、インフラチーム内でGithub Actionsの挙動をテストします。

## 設定ファイルの作成に伴っての注意事項
YAMLファイルの「on:」の部分には自身のブランチ名をトリガーイベントに指定してください。

```yaml
on:
  push:
    branches: 
      - <自身のブランチ名>
```
こうすることでブランチごとにworkflowの実行を確認できるようになります。
