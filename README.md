# docker-ansible
dockerが動く環境をansibleで自動構築したい

```
ansible-playbook site.yml
```

## 実行内容
- user `lapi` を password `password` で作成。sudoerにする。
- 公開鍵をコピー
- パスワード認証の無効化
- git, docker, docker-composeのインストール

## 別途やるべきこと
- hostnameの変更
- `lapi` passwordの変更
- (`pi` passwordの変更)