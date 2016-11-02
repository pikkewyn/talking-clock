![deb dir tree](./dir-tree-deb.png  "deb dir tree")

build deb package:
```bash
$ dpkg-deb --build deb
```
check contents of deb package
```bash
$ dpkg -c talking-clock.deb 
```