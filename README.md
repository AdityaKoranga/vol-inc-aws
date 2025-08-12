# vol-inc-aws

first check the storage strucutre using `lsblk`

```shell
sudo growpart /dev/xvda 1
sudo resize2fs /dev/xvda1
df -h
```
