```bash
[  OK  ] Started User Profile Loading.
[  OK  ] Mounted Personal Information.
[  OK  ] Reached target: Social Links.
[ INFO ] Loading professional skills...
[ FATAL] KERNEL PANIC: NOT SYNCING: A fatal exception occurred in module "gh_profile.ko"
         
         CPU: 1 PID: 101 Comm: Profile README Tainted: G             6.9.4-arch1-1
         Hardware name: Github Profile
         
         Call Trace:
          <TASK>
          ? find_contact_info+0x1a/0x420
          ? connect_on_linkedin(https://linkedin.com/in/mattia-righetti)
          ? review_my_review(https://mattrighetti.com/)
          <TASK_END>

         RIP: 0010:panic+0x2a7/0x2a7 RSP: ffff88800c603e18 EFLAGS: 00000246
         RAX: 0x0000000000000000 RBX: 0x00000000DEADBEEF RCX: 0x0000000000000001
         RDX: 0x00000000CAFEBABE RSI: 0x00000000BADF00D1 RDI: 0xffffffff81e8b340

[ ALERT] ---[ end Kernel panic - not syncing: VFS: Unable to mount root fs on unknown-block(0,0) ]---
[ POWER] System halted.
```
