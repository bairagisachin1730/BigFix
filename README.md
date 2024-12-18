# BigFix
BigFix relevance and Action scripts


lrwxrwxrwx. 1 root root       68 Dec 18 08:08 java-8 -> /root/jdks/java-1.8.0-openjdk-1.8.0.252.b09-0.portable.jre.el.x86_64
[root@rhel8 jdks]# cd java-8
[root@rhel8 java-8]# ls -lrt
total 184
-r--r--r--. 1 248 135 153250 Apr 13  2020 THIRD_PARTY_README
-rw-r--r--. 1 248 135     84 Apr 13  2020 release
drwxr-xr-x. 4 248 135     47 Apr 13  2020 man
-r--r--r--. 1 248 135  19274 Apr 13  2020 LICENSE
drwxr-xr-x. 2 248 135    172 Apr 13  2020 bin
-r--r--r--. 1 248 135   1522 Apr 13  2020 ASSEMBLY_EXCEPTION
drwxr-xr-x. 9 248 135   4096 Apr 13  2020 lib
[root@rhel8 java-8]# cat release
JAVA_VERSION="1.8.0_252"
OS_NAME="Linux"
OS_VERSION="2.6"
OS_ARCH="amd64"
SOURCE=""
[root@rhel8 java-8]# echo $java_home

[root@rhel8 java-8]# echo $JAVA_HOME
/root/jdks/java-8



BESClientActionMastheadPath not set and no masthead found
Q: variables of environment of process "chronyd"
A: INVOCATION_ID = 1aab606aecf04385893f0704ae580602
A: JOURNAL_STREAM = 9:21644
A: LANG = en_US.UTF-8
A: OPTIONS =
A: PATH = /usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin
T: 7254
19:21
Q: variables of environment of process "rsyslogd"
A: INVOCATION_ID = 636fb959db5c41389a4720f58e8eecb9
A: LANG = en_US.UTF-8
A: NOTIFY_SOCKET = /run/systemd/notify
A: PATH = /usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin
A: SYSLOGD_OPTIONS =
T: 7747


Q: values  of variables of environment
A: () {  ( alias;%0a eval ${which_declare} ) | /usr/bin/which --tty-only --read-alias --read-functions --show-tilde --show-dot $@%0a}
A: 100000
A: /root
A: rhel8.localdomain
A: /root/jdks/java-8
A: en_US.UTF-8
A: ||/usr/bin/lesspipe.sh %25s
A: root
A: rs=0:di=01;34:ln=01;36:mh=00:pi=40;33:so=01;35:do=01;35:bd=40;33;01:cd=40;33;01:or=40;31;01:mi=01;05;37;41:su=37;41:sg=30;43:ca=30;41:tw=30;42:ow=34;42:st=37;44:ex=01;32:*.tar=01;31:*.tgz=01;31:*.arc=01;31:*.arj=01;31:*.taz=01;31:*.lha=01;31:*.lz4=01;31:*.lzh=01;31:*.lzma=01;31:*.tlz=01;31:*.txz=01;31:*.tzo=01;31:*.t7z=01;31:*.zip=01;31:*.z=01;31:*.dz=01;31:*.gz=01;31:*.lrz=01;31:*.lz=01;31:*.lzo=01;31:*.xz=01;31:*.zst=01;31:*.tzst=01;31:*.bz2=01;31:*.bz=01;31:*.tbz=01;31:*.tbz2=01;31:*.tz=01;31:*.deb=01;31:*.rpm=01;31:*.jar=01;31:*.war=01;31:*.ear=01;31:*.sar=01;31:*.rar=01;31:*.alz=01;31:*.ace=01;31:*.zoo=01;31:*.cpio=01;31:*.7z=01;31:*.rz=01;31:*.cab=01;31:*.wim=01;31:*.swm=01;31:*.dwm=01;31:*.esd=01;31:*.jpg=01;35:*.jpeg=01;35:*.mjpg=01;35:*.mjpeg=01;35:*.gif=01;35:*.bmp=01;35:*.pbm=01;35:*.pgm=01;35:*.ppm=01;35:*.tga=01;35:*.xbm=01;35:*.xpm=01;35:*.tif=01;35:*.tiff=01;35:*.png=01;35:*.svg=01;35:*.svgz=01;35:*.mng=01;35:*.pcx=01;35:*.mov=01;35:*.mpg=01;35:*.mpeg=01;35:*.m2v=01;35:*.mkv=01;35:*.webm=01;35:*.ogm=01;35:*.mp4=01;35:*.m4v=01;35:*.mp4v=01;35:*.vob=01;35:*.qt=01;35:*.nuv=01;35:*.wmv=01;35:*.asf=01;35:*.rm=01;35:*.rmvb=01;35:*.flc=01;35:*.avi=01;35:*.fli=01;35:*.flv=01;35:*.gl=01;35:*.dl=01;35:*.xcf=01;35:*.xwd=01;35:*.yuv=01;35:*.cgm=01;35:*.emf=01;35:*.ogv=01;35:*.ogx=01;35:*.aac=01;36:*.au=01;36:*.flac=01;36:*.m4a=01;36:*.mid=01;36:*.midi=01;36:*.mka=01;36:*.mp3=01;36:*.mpc=01;36:*.ogg=01;36:*.ra=01;36:*.wav=01;36:*.oga=01;36:*.opus=01;36:*.spx=01;36:*.xspf=01;36:
A: /var/spool/mail/vagrant
A: /opt/BESClient
A: /root/jdks/java-8/bin:/bin:/sbin:/bin:/usr/sbin:/usr/bin
A: /opt/BESClient/bin
A: /bin/bash
A: 1
A: /bin/su
A: 1000
A: 1000
A: vagrant
A: auto
A: xterm
A: root
A: ./qna
A: declare -f
T: 228

Q: names of  variables of environment
A: BASH_FUNC_which%25%25
A: HISTSIZE
A: HOME
A: HOSTNAME
A: JAVA_HOME
A: LANG
A: LESSOPEN
A: LOGNAME
A: LS_COLORS
A: MAIL
A: OLDPWD
A: PATH
A: PWD
A: SHELL
A: SHLVL
A: SUDO_COMMAND
A: SUDO_GID
A: SUDO_UID
A: SUDO_USER
A: S_COLORS
A: TERM
A: USER
A: _
A: which_declare
T: 194


Q: variable "JAVA_HOME" of environment
A: JAVA_HOME = /root/jdks/java-8
T: 94

Q: value of  variable "JAVA_HOME" of environment
A: /root/jdks/java-8

Reference: https://developer.bigfix.com/relevance/search/?query=variable&platform=session%2Credhat%2Clinux


developer.bigfix.comdeveloper.bigfix.com
Inspector Search | BigFix Developer
Learn how to customize your BigFix deployment.



Q: lines whose (it contains "JAVA_VERSION") of file "/root/jdks/java-8/release"
A: JAVA_VERSION="1.8.0_252"
T: 206
20:03
value of  variable "JAVA_HOME" of environment



Q: exist value of  variable "JAVA_HOME" of environment
A: True
T: 84

Relevance:
exist value of  variable "JAVA_HOME" of environment

Q: file "release" of folder "/root/jdks/java-8"
A: /root/jdks/java-8/release


Q:  file "release" of folder ( value of  variable "JAVA_HOME" of environment)
A: /root/jdks/java-8/release

Final:
Q: lines whose (it contains "JAVA_VERSION") of  file "release" of folder ( value of  variable "JAVA_HOME" of environment)

############## substring operations and references ###########################
Q: substrings separated by "=" of lines whose (it contains "JAVA_VERSION") of  file "release" of folder ( value of  variable "JAVA_HOME" of environment)
A: JAVA_VERSION
A: "1.8.0_252"
T: 225
20:56

Q: substring after "="  of lines whose (it contains "JAVA_VERSION") of  file "release" of folder ( value of  variable "JAVA_HOME" of environment)
A: "1.8.0_252"
T: 217

Reference : substring: https://developer.bigfix.com/relevance/search/?query=substring

developer.bigfix.comdeveloper.bigfix.com
Inspector Search | BigFix Developer

