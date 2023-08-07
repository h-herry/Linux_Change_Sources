# Linux_Change_Sources

1.修改sources.list

vi /etc/apt/sources.list

2.增加源后 直接更新命令执行就行

apt-get update

# Debian

deb https://mirrors.ustc.edu.cn/debian/ bullseye main contrib non-free

deb-src https://mirrors.ustc.edu.cn/debian/ bullseye main contrib non-free

deb https://mirrors.ustc.edu.cn/debian/ bullseye-updates main contrib non-free

deb-src https://mirrors.ustc.edu.cn/debian/ bullseye-updates main contrib non-free

deb https://mirrors.ustc.edu.cn/debian/ bullseye-backports main contrib non-free

deb-src https://mirrors.ustc.edu.cn/debian/ bullseye-backports main contrib non-free

deb https://mirrors.ustc.edu.cn/debian-security/ bullseye-security main contrib non-free

deb-src https://mirrors.ustc.edu.cn/debian-security/ bullseye-security main contrib non-free

# Ubuntu

deb https://mirrors.ustc.edu.cn/ubuntu/ kinetic main restricted universe multiverse

deb-src https://mirrors.ustc.edu.cn/ubuntu/ kinetic main restricted universe multiverse

deb https://mirrors.ustc.edu.cn/ubuntu/ kinetic-security main restricted universe multiverse

deb-src https://mirrors.ustc.edu.cn/ubuntu/ kinetic-security main restricted universe multiverse

deb https://mirrors.ustc.edu.cn/ubuntu/ kinetic-updates main restricted universe multiverse

deb-src https://mirrors.ustc.edu.cn/ubuntu/ kinetic-updates main restricted universe multiverse

deb https://mirrors.ustc.edu.cn/ubuntu/ kinetic-backports main restricted universe multiverse

deb-src https://mirrors.ustc.edu.cn/ubuntu/ kinetic-backports main restricted universe multiverse

# Not recommended

# deb https://mirrors.ustc.edu.cn/ubuntu/ kinetic-proposed main restricted universe multiverse

# deb-src https://mirrors.ustc.edu.cn/ubuntu/ kinetic-proposed main restricted universe multiverse
