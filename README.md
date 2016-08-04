# dokku-git-https
A plugin for Dokku that configures git to use https:// instead of git://

## installation

```shell
# on 0.3.x
cd /var/lib/dokku/plugins
git clone https://github.com/miguelcobain/dokku-git-https.git dokku-git-https
dokku plugins-install

# on 0.4.x
dokku plugin:install https://github.com/miguelcobain/dokku-git-https.git dokku-git-https
```