# 💻 100 Basic Linux Commands  
A complete guide to essential and frequently used commands for entering the world of the Linux terminal  
---

## 🔹 Command 1:
```bash
ls
```

📌 **Description**  
display  file  folder   directory .

🛠 **Important Flags**
- `-l` : display      
- `-a` : display  file   file   
- `-h` : display  file  readable ( KB, MB)

💡 **Example**
```bash
ls -lah
```

📤 **Sample Output**
```bash
drwxr-xr-x  5 user user 4.0K May 12 11:20 .
drwxr-xr-x 18 user user 4.0K May 11 09:00 ..
-rw-r--r--  1 user user 1.2K May 10 14:35 README.md
-rw-r--r--  1 user user  512 May 10 14:35 .env
drwxr-xr-x  2 user user 4.0K May 10 14:35 src
```

## 🔹 Command 2:
```bash
cd
```

📌 **Description**  
change directory   directory  .

🛠 **Important Flags**  
    .

💡 **Example**
```bash
cd /home/user/Documents
```

📤 **Sample Output**  
directory  change     path `/home/user/Documents`  .

## 🔹 Command 3:
```bash
pwd
```

📌 **Description**  
display path  (Full path) directory .

🛠 **Important Flags**  
- `-L` : display path  (symlinks   )  
- `-P` : display path  ( symlinks)

💡 **Example**
```bash
pwd
```

📤 **Sample Output**
```bash
/home/user/Documents
```

## 🔹 Command 4:
```bash
mkdir
```

📌 **Description**  
create    directory .

🛠 **Important Flags**
- `-p` : create directory  open  
- `-v` : display    directory 

💡 **Example**
```bash
mkdir -p /home/user/projects/new_project
```

📤 **Sample Output**
```bash
/home/user/projects/new_project  
```

## 🔹 Command 5:
```bash
rmdir
```

📌 **Description**  
delete directory .

🛠 **Important Flags**
- `-p` : delete directory     

💡 **Example**
```bash
rmdir -p /home/user/projects/new_project
```

📤 **Sample Output**
```bash
/home/user/projects/new_project delete 
```

## 🔹 Command 6:
```bash
rm
```

📌 **Description**  
delete file  directory.

🛠 **Important Flags**
- `-r` : delete open  directory  
- `-f` : delete    
- `-i` : delete    user

💡 **Example**
```bash
rm -rf /home/user/projects/new_project
```

📤 **Sample Output**
directory  contents    delete .

## 🔹 Command 7:
```bash
touch
```

📌 **Description**  
create  file     time   file.

🛠 **Important Flags**
- `-c` :    file،     
- `-t` :  time   file

💡 **Example**
```bash
touch file1.txt
```

📤 **Sample Output**
 file  name `file1.txt`  path   .

## 🔹 Command 8:
```bash
cp
```

📌 **Description**  
  file  folder.

🛠 **Important Flags**
- `-r` :  open folder  
- `-i` :     file  
- `-v` : display file   

💡 **Example**
```bash
cp -r /home/user/docs /home/user/backup
```

📤 **Sample Output**
folder `docs`  contents   `backup`  .

## 🔹 Command 9:
```bash
mv
```

📌 **Description**  
  change name file  folder.

🛠 **Important Flags**
- `-i` :      
- `-v` : display    

💡 **Example**
```bash
mv file.txt new_file.txt
```

📤 **Sample Output**
`file.txt`  `new_file.txt` change name .

## 🔹 Command 10:
```bash
cat
```

📌 **Description**  
display  file  output .

🛠 **Important Flags**
- `-n` :  lines  
- `-E` : display     `$`

💡 **Example**
```bash
cat -n file.txt
```

📤 **Sample Output**
```bash
     1	Hello World
     2	This is a test
```

## 🔹 Command 11:
```bash
echo
```

📌 **Description**  
display    value variable  output  ().

🛠 **Important Flags**
- `-n` :        
- `-e` :  escape sequences  `
`  `	`

💡 **Example**
```bash
echo -e "Hello\nWorld"
```

📤 **Sample Output**
```bash
Hello
World
```

---

## 🔹 Command 12:
```bash
man
```

📌 **Description**  
display     .

🛠 **Important Flags**
- `-k` :    manual  
- `-f` : display   

💡 **Example**
```bash
man ls
```

📤 **Sample Output**  
   `ls` open .

---

## 🔹 Command 13:
```bash
whoami
```

📌 **Description**  
display name user .

🛠 **Important Flags**  


💡 **Example**
```bash
whoami
```

📤 **Sample Output**
```bash
user
```

---

## 🔹 Command 14:
```bash
id
```

📌 **Description**  
display UID، GID  group user .

🛠 **Important Flags**
- `-u` :  UID  display   
- `-g` :  GID  display 

💡 **Example**
```bash
id -u
```

📤 **Sample Output**
```bash
1000
```

---

## 🔹 Command 15:
```bash
uname
```

📌 **Description**  
display information system.

🛠 **Important Flags**
- `-a` : display  information  
- `-r` : display  

💡 **Example**
```bash
uname -a
```

📤 **Sample Output**
```bash
Linux mymachine 5.15.0-75-generic x86_64 GNU/Linux
```

---

## 🔹 Command 16:
```bash
top
```

📌 **Description**  
display    execution system  .

🛠 **Important Flags**
- `-n` :      
- `-b` : execution  batch  

💡 **Example**
```bash
top -n 1
```

📤 **Sample Output**  
information   system   display  .

---

## 🔹 Command 17:
```bash
ps
```

📌 **Description**  
display   .

🛠 **Important Flags**
- `aux` : display    
- `-ef` :   display

💡 **Example**
```bash
ps aux
```

📤 **Sample Output**
```bash
USER       PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
root         1  0.0  0.1  22536  1028 ?        Ss   11:20   0:00 /sbin/init
```

---

## 🔹 Command 18:
```bash
kill
```

📌 **Description**  
       (PID).

🛠 **Important Flags**
- `-9` :   kill ()  
- `-l` :   

💡 **Example**
```bash
kill -9 1234
```

📤 **Sample Output**
  PID  1234  .

---

## 🔹 Command 19:
```bash
clear
```

📌 **Description**  
   .

🛠 **Important Flags**  


💡 **Example**
```bash
clear
```

📤 **Sample Output**
   .

---

## 🔹 Command 20:
```bash
history
```

📌 **Description**  
display    .

🛠 **Important Flags**
- `!n` : execution    n  
- `-c` :   

💡 **Example**
```bash
history
```

📤 **Sample Output**
```bash
1  ls
2  cd Documents
3  mkdir test
```

## 🔹 Command 21:
```bash
chmod
```

📌 **Description**  
change    file  folder.

🛠 **Important Flags**
- `+x` :   execution  
- `-r` : delete    
- `u/g/o` :   user، group  

💡 **Example**
```bash
chmod +x script.sh
```

📤 **Sample Output**
file `script.sh`  execution .

---

## 🔹 Command 22:
```bash
chown
```

📌 **Description**  
change   group file  directory.

🛠 **Important Flags**
- `-R` :  change   open  
- `--from=CURRENT` : change       

💡 **Example**
```bash
chown user:group file.txt
```

📤 **Sample Output**
 file `file.txt`  `user`  group  `group` change .

---

## 🔹 Command 23:
```bash
df
```

📌 **Description**  
display     .

🛠 **Important Flags**
- `-h` : display   readable (MB, GB)  
- `-T` : display  file system

💡 **Example**
```bash
df -h
```

📤 **Sample Output**
```bash
Filesystem      Size  Used Avail Use% Mounted on
/dev/sda1        50G   20G   28G  42% /
```

---

## 🔹 Command 24:
```bash
du
```

📌 **Description**  
display    file  folder.

🛠 **Important Flags**
- `-h` : display  readable  
- `-s` : display   
- `-a` : display  file

💡 **Example**
```bash
du -sh *
```

📤 **Sample Output**
```bash
1.1M    folder1
512K    file.txt
```

---

## 🔹 Command 25:
```bash
head
```

📌 **Description**  
display  lines  file .

🛠 **Important Flags**
- `-n` :  lines    display

💡 **Example**
```bash
head -n 5 file.txt
```

📤 **Sample Output**
display ۵   file `file.txt`.

---

## 🔹 Command 26:
```bash
tail
```

📌 **Description**  
display  lines  file .

🛠 **Important Flags**
- `-n` :  lines  display  
- `-f` :    file (  log)

💡 **Example**
```bash
tail -f /var/log/syslog
```

📤 **Sample Output**
display  lines file      change.

---

## 🔹 Command 27:
```bash
grep
```

📌 **Description**  
  (Pattern)  file  output .

🛠 **Important Flags**
- `-i` :        
- `-r` :  open  
- `--color` :  

💡 **Example**
```bash
grep -i "error" logfile.txt
```

📤 **Sample Output**
 lines   "error"   ، display  .

---

## 🔹 Command 28:
```bash
find
```

📌 **Description**  
  file  directory   .

🛠 **Important Flags**
- `-name` :   name  
- `-type` :    file  
- `-size` :    file

💡 **Example**
```bash
find . -name "*.py"
```

📤 **Sample Output**
display  file `.py`  directory   .

---

## 🔹 Command 29:
```bash
locate
```

📌 **Description**  
   file      path.

🛠 **Important Flags**
- `-i` :        
- `-c` : display   

💡 **Example**
```bash
locate config.json
```

📤 **Sample Output**
display path  file `config.json`    .

---

## 🔹 Command 30:
```bash
which
```

📌 **Description**  
display path execution name     .

🛠 **Important Flags**  


💡 **Example**
```bash
which python
```

📤 **Sample Output**
```bash
/usr/bin/python
```

## 🔹 Command 31:
```bash
alias
```

📌 **Description**  
 name      user.

🛠 **Important Flags**  


💡 **Example**
```bash
alias ll='ls -lah'
```

📤 **Sample Output**
       `ll`  output `ls -lah`  .

---

## 🔹 Command 32:
```bash
unalias
```

📌 **Description**  
delete  alias .

🛠 **Important Flags**
- `-a` : delete  alias

💡 **Example**
```bash
unalias ll
```

📤 **Sample Output**
Alias   `ll` delete .

---

## 🔹 Command 33:
```bash
env
```

📌 **Description**  
display   variable .

🛠 **Important Flags**
- `-u` : delete  variable   
- `-i` : execution    

💡 **Example**
```bash
env
```

📤 **Sample Output**
display  variable  system.

---

## 🔹 Command 34:
```bash
export
```

📌 **Description**  
  change variable      .

🛠 **Important Flags**  


💡 **Example**
```bash
export PATH=$PATH:/custom/path
```

📤 **Sample Output**
variable PATH  path   .

---

## 🔹 Command 35:
```bash
unset
```

📌 **Description**  
delete variable      .

🛠 **Important Flags**  


💡 **Example**
```bash
unset MY_VAR
```

📤 **Sample Output**
variable `MY_VAR` delete .

---

## 🔹 Command 36:
```bash
sleep
```

📌 **Description**  
 execution    time .

🛠 **Important Flags**
- `s` :  (default)  
- `m` :   
- `h` : 

💡 **Example**
```bash
sleep 5
```

📤 **Sample Output**
execution     ۵   .

---

## 🔹 Command 37:
```bash
date
```

📌 **Description**  
display     time system.

🛠 **Important Flags**
- `+FORMAT` :   output  
- `-u` : display time UTC

💡 **Example**
```bash
date "+%Y-%m-%d %H:%M:%S"
```

📤 **Sample Output**
```bash
2025-05-12 12:00:00
```

---

## 🔹 Command 38:
```bash
cal
```

📌 **Description**  
display        .

🛠 **Important Flags**
- `-y` : display     
- `-3` : display  ، ،  

💡 **Example**
```bash
cal -3
```

📤 **Sample Output**
    display  .

---

## 🔹 Command 39:
```bash
uptime
```

📌 **Description**  
display time   system  information  .

🛠 **Important Flags**  


💡 **Example**
```bash
uptime
```

📤 **Sample Output**
```bash
12:00:00 up 3 days,  5:42,  2 users,  load average: 0.10, 0.15, 0.20
```

---

## 🔹 Command 40:
```bash
who
```

📌 **Description**  
display user    system .

🛠 **Important Flags**
- `-a` : display  information  
- `-q` : display  name user  

💡 **Example**
```bash
who
```

📤 **Sample Output**
```bash
user1   tty7         2025-05-12 10:00
user2   pts/0        2025-05-12 10:10
```

## 🔹 Command 41:
```bash
users
```

📌 **Description**  
display user    system   .

🛠 **Important Flags**  


💡 **Example**
```bash
users
```

📤 **Sample Output**
```bash
user1 user2
```

---

## 🔹 Command 42:
```bash
groups
```

📌 **Description**  
display group  user  .

🛠 **Important Flags**  


💡 **Example**
```bash
groups user1
```

📤 **Sample Output**
```bash
user1 : user1 sudo docker
```

---

## 🔹 Command 43:
```bash
hostname
```

📌 **Description**  
display  change name host (hostname) system.

🛠 **Important Flags**
- `-f` : display name  host (FQDN)

💡 **Example**
```bash
hostname
```

📤 **Sample Output**
```bash
my-computer
```

---

## 🔹 Command 44:
```bash
ping
```

📌 **Description**  
     host (hostname  IP).

🛠 **Important Flags**
- `-c` :   ping  
- `-i` :   time  

💡 **Example**
```bash
ping -c 4 google.com
```

📤 **Sample Output**
```bash
64 bytes from google.com: icmp_seq=1 ttl=117 time=12.3 ms
...
```

---

## 🔹 Command 45:
```bash
traceroute
```

📌 **Description**  
display path  closed   destination.

🛠 **Important Flags**
- `-n` : display     
- `-m` :     (hops)

💡 **Example**
```bash
traceroute google.com
```

📤 **Sample Output**
display path        destination.

---

## 🔹 Command 46:
```bash
netstat
```

📌 **Description**  
display  ،  path    .

🛠 **Important Flags**
- `-tuln` : display  open       
- `-p` : display PID name 

💡 **Example**
```bash
netstat -tuln
```

📤 **Sample Output**
```bash
Proto Recv-Q Send-Q Local Address           Foreign Address         State      
tcp        0      0 0.0.0.0:22              0.0.0.0:*               LISTEN     
```

---

## 🔹 Command 47:
```bash
ss
```

📌 **Description**  
    `netstat`  display information  .

🛠 **Important Flags**
- `-tuln` : display  TCP/UDP  
- `-p` : display PID 

💡 **Example**
```bash
ss -tuln
```

📤 **Sample Output**
   open     display  .

---

## 🔹 Command 48:
```bash
ifconfig
```

📌 **Description**  
display     (    `ip`).

🛠 **Important Flags**
- `interface` : display information       
- `up/down` :     

💡 **Example**
```bash
ifconfig
```

📤 **Sample Output**
information    IP، MAC  closed /.

---

## 🔹 Command 49:
```bash
ip
```

📌 **Description**  
   `ifconfig`   .

🛠 **Important Flags**
- `ip a` : display   
- `ip r` : display  path

💡 **Example**
```bash
ip a
```

📤 **Sample Output**
display  IP  MAC    .

---

## 🔹 Command 50:
```bash
curl
```

📌 **Description**  
   URL   response.

🛠 **Important Flags**
- `-O` :  file  name   
- `-L` :     
- `-I` :   header

💡 **Example**
```bash
curl -O https://example.com/file.txt
```

📤 **Sample Output**
file `file.txt`  path   .

## 🔹 Command 51:
```bash
wget
```

📌 **Description**  
 file      .

🛠 **Important Flags**
- `-O` :  name output  
- `-c` :     
- `--limit-rate` :    

💡 **Example**
```bash
wget -O myfile.zip https://example.com/file.zip
```

📤 **Sample Output**
file `file.zip`  name `myfile.zip`  .

---

## 🔹 Command 52:
```bash
scp
```

📌 **Description**  
 file   system   SSH.

🛠 **Important Flags**
- `-r` :  open folder  
- `-P` :   SSH

💡 **Example**
```bash
scp file.txt user@192.168.1.10:/home/user/
```

📤 **Sample Output**
file `file.txt`  system destination  .

---

## 🔹 Command 53:
```bash
rsync
```

📌 **Description**  
      file.

🛠 **Important Flags**
- `-a` :   ( ، time  ...  )  
- `-v` :  verbose  
- `--delete` : delete file    delete 

💡 **Example**
```bash
rsync -av folder/ /backup/folder/
```

📤 **Sample Output**
folder `folder`  destination  .

---

## 🔹 Command 54:
```bash
diff
```

📌 **Description**  
  file  display .

🛠 **Important Flags**
- `-u` : display output   unified  
- `-q` :     display 

💡 **Example**
```bash
diff -u file1.txt file2.txt
```

📤 **Sample Output**
lines   file display  .

---

## 🔹 Command 55:
```bash
cmp
```

📌 **Description**  
  file        .

🛠 **Important Flags**
- `-l` : display      
- `-s` :     output

💡 **Example**
```bash
cmp file1.bin file2.bin
```

📤 **Sample Output**
      file.

---

## 🔹 Command 56:
```bash
stat
```

📌 **Description**  
display information   file  directory.

🛠 **Important Flags**
- `-c` :   output

💡 **Example**
```bash
stat file.txt
```

📤 **Sample Output**
```bash
  File: file.txt
  Size: 1234       Blocks: 8          IO Block: 4096   regular file
...
```

---

## 🔹 Command 57:
```bash
file
```

📌 **Description**  
  file.

🛠 **Important Flags**
- `-i` : display MIME type  
- `-b` : delete name file  output

💡 **Example**
```bash
file file.txt
```

📤 **Sample Output**
```bash
file.txt: ASCII text
```

---

## 🔹 Command 58:
```bash
basename
```

📌 **Description**  
 name file   path .

🛠 **Important Flags**
- `-s` : delete  

💡 **Example**
```bash
basename /home/user/file.txt
```

📤 **Sample Output**
```bash
file.txt
```

---

## 🔹 Command 59:
```bash
dirname
```

📌 **Description**  
 path directory   path  file.

🛠 **Important Flags**  


💡 **Example**
```bash
dirname /home/user/file.txt
```

📤 **Sample Output**
```bash
/home/user
```

---

## 🔹 Command 60:
```bash
cut
```

📌 **Description**  
        input.

🛠 **Important Flags**
- `-d` :    
- `-f` :   ()

💡 **Example**
```bash
cut -d ',' -f 1 names.csv
```

📤 **Sample Output**
  file CSV display  .

## 🔹 Command 61:
```bash
sort
```

📌 **Description**  
 lines  file   input.

🛠 **Important Flags**
- `-r` :    
- `-n` :    
- `-k` :     

💡 **Example**
```bash
sort -n numbers.txt
```

📤 **Sample Output**
lines file `numbers.txt`     .

---

## 🔹 Command 62:
```bash
uniq
```

📌 **Description**  
delete lines   input ( lines    ).

🛠 **Important Flags**
- `-c` : display    
- `-d` :  display lines   
- `-u` :  display lines 

💡 **Example**
```bash
uniq -c names.txt
```

📤 **Sample Output**
     file display  .

---

## 🔹 Command 63:
```bash
tee
```

📌 **Description**  
 output   file  display time   .

🛠 **Important Flags**
- `-a` :    file (append)

💡 **Example**
```bash
echo "Test" | tee log.txt
```

📤 **Sample Output**
```bash
Test
```
  file `log.txt`   .

---

## 🔹 Command 64:
```bash
xargs
```

📌 **Description**  
execution   input      .

🛠 **Important Flags**
- `-n` :       execution  
- `-d` :   

💡 **Example**
```bash
echo "file1 file2" | xargs rm
```

📤 **Sample Output**
file `file1`  `file2` delete .

---

## 🔹 Command 65:
```bash
yes
```

📌 **Description**  
    (    )  .

🛠 **Important Flags**  


💡 **Example**
```bash
yes | rm -i *.txt
```

📤 **Sample Output**
 file    delete   yes  "y" .

---

## 🔹 Command 66:
```bash
echo -e
```

📌 **Description**  
display     escape sequences  `\n`  `\t`.

🛠 **Important Flags**
- `-e` :   escape   
- `-n` :      

💡 **Example**
```bash
echo -e "line1\nline2"
```

📤 **Sample Output**
```bash
line1
line2
```

---

## 🔹 Command 67:
```bash
read
```

📌 **Description**  
 input  user  .

🛠 **Important Flags**
- `-p` : display message    input  
- `-s` :   input (  )

💡 **Example**
```bash
read -p "Enter your name: " name
```

📤 **Sample Output**
user name       variable `name`  .

---

## 🔹 Command 68:
```bash
printf
```

📌 **Description**  
display      C.

🛠 **Important Flags**
-     `%s`, `%d`, `%f`  .

💡 **Example**
```bash
printf "Name: %s\nAge: %d\n" "Ali" 25
```

📤 **Sample Output**
```bash
Name: Ali
Age: 25
```

---

## 🔹 Command 69:
```bash
bc
```

📌 **Description**  
     .

🛠 **Important Flags**
- `-l` :       

💡 **Example**
```bash
echo "scale=2; 10/3" | bc -l
```

📤 **Sample Output**
```bash
3.33
```

---

## 🔹 Command 70:
```bash
expr
```

📌 **Description**  
execution     .

🛠 **Important Flags**  


💡 **Example**
```bash
expr 5 + 3
```

📤 **Sample Output**
```bash
8
```

## 🔹 Command 71:
```bash
crontab
```

📌 **Description**  
 time execution    time .

🛠 **Important Flags**
- `-e` :    time  
- `-l` : display   
- `-r` : delete  

💡 **Example**
```bash
crontab -e
```

📤 **Sample Output**
file   time open .

---

## 🔹 Command 72:
```bash
at
```

📌 **Description**  
execution    time  ( ).

🛠 **Important Flags**
- `-l`  `atq` : display   time  
- `-d`  `atrm` : delete   time

💡 **Example**
```bash
echo "echo Hello" | at now + 1 minute
```

📤 **Sample Output**
 `echo Hello`    execution .

---

## 🔹 Command 73:
```bash
uptime
```

📌 **Description**  
display  time   system.

🛠 **Important Flags**  


💡 **Example**
```bash
uptime
```

📤 **Sample Output**
```bash
12:10:00 up 3 days,  2:03,  1 user,  load average: 0.01, 0.05, 0.10
```

---

## 🔹 Command 74:
```bash
watch
```

📌 **Description**  
execution   output       open time.

🛠 **Important Flags**
- `-n` :   time execution (  )  
- `-d` :  change

💡 **Example**
```bash
watch -n 2 df -h
```

📤 **Sample Output**
 ۲   output `df -h`  .

---

## 🔹 Command 75:
```bash
alias
```

📌 **Description**  
 name   .

🛠 **Important Flags**  


💡 **Example**
```bash
alias gs='git status'
```

📤 **Sample Output**
by typing `gs`،  `git status` execution .

---

## 🔹 Command 76:
```bash
time
```

📌 **Description**  
  time execution  .

🛠 **Important Flags**  


💡 **Example**
```bash
time ls
```

📤 **Sample Output**
display  time ، CPU user  system  execution .

---

## 🔹 Command 77:
```bash
timeout
```

📌 **Description**  
execution     time .

🛠 **Important Flags**
- `--preserve-status` :   open   
- `--foreground` : execution  

💡 **Example**
```bash
timeout 5s ping google.com
```

📤 **Sample Output**
ping   ۵     .

---

## 🔹 Command 78:
```bash
basename
```

📌 **Description**  
display  name file   path .

🛠 **Important Flags**
- `-s` : delete    output

💡 **Example**
```bash
basename /etc/nginx/nginx.conf
```

📤 **Sample Output**
```bash
nginx.conf
```

---

## 🔹 Command 79:
```bash
dirname
```

📌 **Description**  
display  directory   path  file.

🛠 **Important Flags**  


💡 **Example**
```bash
dirname /etc/nginx/nginx.conf
```

📤 **Sample Output**
```bash
/etc/nginx
```

---

## 🔹 Command 80:
```bash
logger
```

📌 **Description**  
 message  log system (syslog).

🛠 **Important Flags**
- `-p` :    facility  
- `-t` :  

💡 **Example**
```bash
logger -t MyApp "Backup completed"
```

📤 **Sample Output**
message  `/var/log/syslog`  `/var/log/messages`  .

## 🔹 Command 81:
```bash
df -h
```

📌 **Description**  
display        readable.

🛠 **Important Flags**
- `-h` : display output   readable  MB  GB  
- `-T` : display  filesystem

💡 **Example**
```bash
df -h
```

📤 **Sample Output**
```bash
Filesystem      Size  Used Avail Use% Mounted on
/dev/sda1        50G   20G   28G  42% /
```

---

## 🔹 Command 82:
```bash
du -sh
```

📌 **Description**  
display    file  directory.

🛠 **Important Flags**
- `-s` : display  (total)  
- `-h` : output    

💡 **Example**
```bash
du -sh /home/user
```

📤 **Sample Output**
```bash
4.1G    /home/user
```

---

## 🔹 Command 83:
```bash
uptime -p
```

📌 **Description**  
display  time   system    .

🛠 **Important Flags**
- `-p` :  display  time    

💡 **Example**
```bash
uptime -p
```

📤 **Sample Output**
```bash
up 3 days, 2 hours, 5 minutes
```

---

## 🔹 Command 84:
```bash
hostnamectl
```

📌 **Description**  
    hostname system.

🛠 **Important Flags**
- `set-hostname` : change name host  
- `status` :  information 

💡 **Example**
```bash
hostnamectl set-hostname my-new-host
```

📤 **Sample Output**
name host system  `my-new-host` change .

---

## 🔹 Command 85:
```bash
journalctl
```

📌 **Description**  
 log systemd   system.

🛠 **Important Flags**
- `-xe` :  log   
- `-f` :   log  
- `--since` :  time

💡 **Example**
```bash
journalctl -xe
```

📤 **Sample Output**
display log      .

---

## 🔹 Command 86:
```bash
systemctl
```

📌 **Description**  
    systemd   .

🛠 **Important Flags**
- `start` :    
- `stop` :    
- `status` :    
- `enable` :   

💡 **Example**
```bash
systemctl status ssh
```

📤 **Sample Output**
display   `ssh`.

---

## 🔹 Command 87:
```bash
service
```

📌 **Description**  
      SysVinit.

🛠 **Important Flags**
- `start` :   
- `stop` :   
- `restart` :    
- `status` :  

💡 **Example**
```bash
service ssh restart
```

📤 **Sample Output**
 `ssh`   .

---

## 🔹 Command 88:
```bash
lsblk
```

📌 **Description**  
display        .

🛠 **Important Flags**
- `-f` : display information filesystem  
- `-o` :   output

💡 **Example**
```bash
lsblk -f
```

📤 **Sample Output**
```bash
NAME   FSTYPE LABEL UUID                                 MOUNTPOINT
sda                                                         
├─sda1 ext4         e9f1b3ae-1234-4567-aaaa-bbbbbbbbbbbb /
```

---

## 🔹 Command 89:
```bash
blkid
```

📌 **Description**  
display UUID   filesystem .

🛠 **Important Flags**  


💡 **Example**
```bash
blkid
```

📤 **Sample Output**
```bash
/dev/sda1: UUID="e9f1b3ae-1234-4567-aaaa-bbbbbbbbbbbb" TYPE="ext4"
```

---

## 🔹 Command 90:
```bash
mount
```

📌 **Description**  
      path   filesystem.

🛠 **Important Flags**
- `-t` :   filesystem  
- `-o` :    read-only

💡 **Example**
```bash
mount /dev/sdb1 /mnt
```

📤 **Sample Output**
 `/dev/sdb1`  `/mnt`  .

## 🔹 Command 91:
```bash
umount
```

📌 **Description**  
       filesystem.

🛠 **Important Flags**
- `-l` :   lazy (    ،  )  
- `-f` :   unmount

💡 **Example**
```bash
umount /mnt
```

📤 **Sample Output**
path `/mnt`     .

---

## 🔹 Command 92:
```bash
fdisk
```

📌 **Description**  
  .

🛠 **Important Flags**
- `-l` :       
- `-u` : display   sector

💡 **Example**
```bash
fdisk -l
```

📤 **Sample Output**
       system display  .

---

## 🔹 Command 93:
```bash
mkfs
```

📌 **Description**  
 filesystem     .

🛠 **Important Flags**
- `-t` :  filesystem

💡 **Example**
```bash
mkfs -t ext4 /dev/sdb1
```

📤 **Sample Output**
 `/dev/sdb1`      .

---

## 🔹 Command 94:
```bash
passwd
```

📌 **Description**  
change   user    user.

🛠 **Important Flags**
- `-l` :     
- `-u` : open   

💡 **Example**
```bash
passwd
```

📤 **Sample Output**
        .

---

## 🔹 Command 95:
```bash
adduser
```

📌 **Description**  
  user   system.

🛠 **Important Flags**
- `--home` :  path home  
- `--shell` :   default

💡 **Example**
```bash
adduser ali
```

📤 **Sample Output**
user `ali` create .

---

## 🔹 Command 96:
```bash
deluser
```

📌 **Description**  
delete  user  system.

🛠 **Important Flags**
- `--remove-home` : delete directory home user

💡 **Example**
```bash
deluser ali --remove-home
```

📤 **Sample Output**
user `ali`  home  delete .

---

## 🔹 Command 97:
```bash
addgroup
```

📌 **Description**  
create  group user .

🛠 **Important Flags**  


💡 **Example**
```bash
addgroup devs
```

📤 **Sample Output**
group `devs` create .

---

## 🔹 Command 98:
```bash
delgroup
```

📌 **Description**  
delete  group user.

🛠 **Important Flags**  


💡 **Example**
```bash
delgroup devs
```

📤 **Sample Output**
group `devs` delete .

---

## 🔹 Command 99:
```bash
su
```

📌 **Description**  
       user  (default root).

🛠 **Important Flags**
- `-` :   user destination

💡 **Example**
```bash
su -
```

📤 **Sample Output**
  root    .

---

## 🔹 Command 100:
```bash
sudo
```

📌 **Description**  
execution      (root)  change user.

🛠 **Important Flags**
- `-i` :    root  
- `-u` : execution   user 

💡 **Example**
```bash
sudo apt update
```

📤 **Sample Output**
closed system   root  .
