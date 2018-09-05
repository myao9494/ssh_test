# SSH_test
SSHのテスト

以下の手順でできた

https://qiita.com/shizuma/items/2b2f873a0034839e47ce

1. ssh-keygen -t rsa
1. 3回エンターを押す
1. 公開鍵をgitHubにアップする
2. 接続を確かめる 下記コマンドを打って、その下のコメントが帰ってきたらOK
   > ssh -T git@github.com  
   Hi (account名)! You've successfully authenticated, but GitHub does not provide shell access.
1. sshでgitからクローンしたら、普通にpushできた！

# .ssh内をuserprofileにコピーすれば、そのまま使える
# userprofileの.gitconfigが変だと動かないので注意！
# 