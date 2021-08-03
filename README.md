# magma-5g-test

add magma repository:
```bash
echo "deb https://artifactory.magmacore.org/artifactory/debian-test stretch-5g main" > /etc/apt/sources.list.d/magma.list

echo 'Acquire::https::artifactory.magmacore.org::Verify-Peer "false";' > /etc/apt/apt.conf.d/99magmacore-cert
```


https://docs.magmacore.org/docs/1.5.0/lte/deploy_install


