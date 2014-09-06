fabric-usergroups
=================

Fabric script to perform user group modifications

(add/remove operations require sudo privilages)

#### Dependencies:

- python-pip

```
$ pip install -r requirements.txt
```


### Usage:
##### Add user to a group

```
$ fab addgrp:user=<username>,grp=<groupname>
```

##### Group membership checks

```
$ fab chkgrp:user=<username>
```

##### Remove user from groups

```
$ fab remgrp:user=<username>,exceptgrp=<groupname>
```

*Note* - exceptgrp is optional (user maintains membership)