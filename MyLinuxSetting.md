Linux 相关配置

Ubuntu 配置PS1：修改root下的.bashrc文件
修改如下
if [ "$color_prompt" = yes ]; then
    PS1='[\[\e[34;1m\]\u@\[\e[0m\]\[\e[32;1m\]\H\[\e[0m\]\[\e[31;1m\] \w\[\e[0m\]]\$ '
else
    # PS1='${debian_chroot:+($debian_chroot)}\u@\h:\w\$ '

CentOS7 配置PS1：修改/etc/profile文件，末尾加上下面的代码
export PS1='[\[\e[34;1m\]\u@\[\e[0m\]\[\e[32;1m\]\H\[\e[0m\]\[\e[31;1m\] \w\[\e[0m\]]\$ '
