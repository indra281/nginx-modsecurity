# nginx-module-sticky

- nginx modsecurity dynamic module


## How to build

```
rpmdev-setuptree
rpm -Uvh https://nginx.org/packages/centos/7/SRPMS/nginx-1.20.1-1.el7.ngx.src.rpm
git clone https://github.com/indra281/nginx-modsecurity.git
cd nginx-modsecurity
rpmbuild -ba nginx-module-modsecurity.spec

```

*See Also

- [Converting the config file for dynamic module](https://bitbucket.org/nginx-goodies/nginx-sticky-module-ng/issues/25/converting-the-config-file-for-dynamic)
- https://bitbucket.org/LeMovieStoreGuy/nginx-sticky-module-ng
- https://github.com/shigechika/nginx-module-pagespeed

## NO WARRANTY

Good Luck :-)
