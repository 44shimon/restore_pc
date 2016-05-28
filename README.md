Restore My Ubuntu PC
-------------

This is for Xenial Ubuntu

To run on my Ubuntu Server do the following
Define the default_user otherwise playbook will fail

```

ansible-playbook --skip-tags desktop site.yml -e "default_user=stanley"
```
