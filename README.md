# magma-5g-test

add magma repository:
```bash
echo "deb https://artifactory.magmacore.org/artifactory/debian-test stretch-5g main" > /etc/apt/sources.list.d/magma.list

echo 'Acquire::https::artifactory.magmacore.org::Verify-Peer "false";' > /etc/apt/apt.conf.d/99magmacore-cert
```

install AGW 1.5.0 on debian:
```bash
su
wget https://raw.githubusercontent.com/magma/magma/master/lte/gateway/deploy/agw_install.sh
bash agw_install.sh
```
> Ref: https://docs.magmacore.org/docs/1.5.0/lte/deploy_install

https://github.com/magma/magma/blob/master/lte/gateway/deploy/agw_install.sh



