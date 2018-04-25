# rpm

## InfluxDB

### install
```
sudo rpm -ivh influxdb-1.5.2.x86_64.rpm
```

### service
```
sudo service influxdb start
sudo chkconfig influxdb on
```

---

## MongoDB

### install

```
rpm -ivh mongodb-org-mongos-3.6.4-1.el6.x86_64
rpm -ivh mongodb-org-server-3.6.4-1.el6.x86_64
rpm -ivh mongodb-org-shell-3.6.4-1.el6.x86_64
rpm -ivh mongodb-org-tools-3.6.4-1.el6.x86_64
rpm -ivh mongodb-org-3.6.4-1.el6.x86_64
```

### service
```
sudo service mongod start
sudo chkconfig mongod on
```
