# TMUX config

Place the file in the `${HOME}/` directory and add a `.` in the beginning (NOTE: These instructions will overwrite your config file)
```
git clone https://github.com/abhijitmajumdar/tmux_config.git
cd tmux_config
cp tmux.conf ~/.tmux.conf
```

OR

Launch a session using the config
```
git clone https://github.com/abhijitmajumdar/tmux_config.git ~/tmux_config
tmux -L user_server -f ~/tmux_config/tmux.conf new-session -s sess_name
```
