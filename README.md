# vim

apt install vim tmux tree mc

Для установки конфига выполнить команду от root:

rm -rf /etc/vim && mkdir /etc/vim && git clone https://github.com/omelchuk95/omelchuk_vim_tmux.git /etc/vim && mv /etc/vim/tmux.conf /etc/

Для прописи ключей выполнить команду от sysex:

sudo mv authorized_keys /home/sysex/.ssh/ && sudo mv sshd_config /etc/ssh/
