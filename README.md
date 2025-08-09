# My Tmux Config (Ubuntu)

```bash
sudo apt update && sudo apt install -y tmux git \
&& git clone https://github.com/matklemmen/tmux-conf.git ~/tmux-config \
&& cp ~/tmux-config/.tmux.conf ~/ \
&& git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm \
&& tmux
# Inside tmux: Prefix (Ctrl-space in this config, Ctrl-b normally) then capital I to install plugins
