## 参考サイト
- Django Girls のチュートリアル  
https://tutorial.djangogirls.org/ja/

- 【丁寧解説】秒速でもDjango 3アプリをAWS EC2で公開【Nginx, gunicorn, postgresqlデプロイ】  
https://qiita.com/Bashi50/items/d5bc47eeb9668304aaa2

- [Django] django-environで環境変数を管理してみる  
https://e-tec-memo.herokuapp.com/article/172/
 => SECRET_KEY 等は.envに格納しGitHubにアップロードしないようにしている  
.envファイル内はアルファベット等のみ、スペースも禁止  
https://teratail.com/questions/150870

- AWSでのデプロイに参考になる書籍 プロフェッショナルWebプログラミング  
https://www.amazon.co.jp/dp/B08Z3PQ6J6/ref=dp-kindle-redirect?_encoding=UTF8&btkr=1

- 上記書籍 P267 に記載ないが、eb init を実行するためには、awsebcli のインストールも必要
https://docs.aws.amazon.com/ja_jp/elasticbeanstalk/latest/dg/eb-cli3-install-advanced.html