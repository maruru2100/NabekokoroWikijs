# Wikijs + ElasticSearch + Docker

WikijsをDockerで立ち上げ。  
ElasticSearchを利用した日本語検索を実施。

## 始め方

`./config/.env` を編集し各種設定値を設定。  
設定後以下コマンド実行。

```docker
docker compose --env-file ./config/.env  up -d
```