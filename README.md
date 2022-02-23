# docker-ansible

docker が動く環境を ansible で自動構築したい

```
ansible-playbook -b site.yml
```

## 実行内容

- user `lapi` を password `password` で作成。sudoer にする。
- 公開鍵をコピー
- パスワード認証の無効化
- git, docker, docker-compose のインストール

## 別途やるべきこと

- hostname の変更
- `lapi` password の変更
- (`pi` password の変更)

## 補足

- centos8 では `podman` と `podman-compose` を入れます。
