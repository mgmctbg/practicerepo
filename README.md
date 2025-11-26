# 2. 리눅스
## 2.1. 명령어 종류
1. 파일 관리 :
2. 쉘 :
3. 파일 액세스 관리 :
4. 패키지 관리 :
5. 아카이빙/압축 :
6. 프로세스 :
7. 시스템 사용자 관리
- 사용자 : - (①)
- 그룹 : - (①)
8. 파일 시스템 관리 :
9. 네트워크 관리 :
## 2.1. 명령어 종류
1. 파일 관리 : `ls`, `cd`, `mkdir`, `rmdir`, `touch`, `vi`, `cat`, `mv`, `rm`, `find`
2. 쉘 : `chsh`, `echo`, `export`, `alias`, `unalias`, `history`
3. 파일 액세스 관리 : `chmod`, `umask`, `chown`
4. 패키지 관리 :
5. 아카이빙/압축 : `tar`, `gzip`, `gunzip`, `bzip2`, `bunzip2`
6. 프로세스 : `ps`, `pgrep`, `kill`, `sleep`, `jobs`, `fg`, `bg`
7. 시스템 사용자 관리
- 사용자 : `useradd`, `usermod`, `userdel`, `passwd`, `su`
- 그룹 : `groupadd`, `groupmod`, `groupdel`, `gpasswd`, `newgrp`
8. 파일 시스템 관리 : `fdisk`, `mkfs`, `dd`, `df`, `du`, `mount`, `umount`
9. 네트워크 관리 : `nmcli`, `ip`, `route`, `ping`, `traceroute`, `netstat`, `nmap`, `ufw`
```
git clone <remote-repo>
```
```
git add .|<files>
```
```
git commit -m "<msg>"
```
```
git push <remote> <branch>
```
### 3.2.2. 원격 레포지토리의 변경사항 가져오기
```
git fetch <remote>
```
```
git merge <remote> <branch>
```
### 3.2.3. 브랜치 및 로그 확인
```
opensw@tux:~/gitlab/openswproject$ git branch
develop
* main
opensw@tux:~/gitlab/openswproject$ git log --oneline --dec
orate --graph --all
* c3dc21d (HEAD -> release) Resolve conflict
|\
| * 4cfe584 (develop) New line about log
| * 332c95b New feature's code
* | b88648d Create introduction file about new version
|/
* b2f6043 (main) Need to a new function
```
