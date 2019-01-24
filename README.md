# expect_script__make_and_scp
**script them all (routine tasks)**
- working on a blade systems. everytime, in order to verify a bug fix. the target needs to be built again and transfer to all blades. it is tedious, and waste time if done manually => script them all!

**sample output:**
```
$ ./expect_script_scp
----- log truncated -----
----- Checking libz.a
----- log truncated -----
spawn scp dnsc root@10.11.12.13:/tmp
root@10.11.12.13's password:
dnsc                                    100% 4821KB   4.7MB/s   00:00
spawn scp dnsc root@10.11.12.14:/tmp
root@10.11.12.14's password:
dnsc                                    100% 4821KB   4.7MB/s   00:00
```
