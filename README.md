1) install tmux
2) tmux -V to see if it is installed (3.3a in july 2023)
3) create a file by (tmux ~/.tmux.conf)
4) #git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
5) to install plugins
6) Ctrl +A , I -> reload config
7) # Ctrl + I to install plugins





## creating sessions

| command | function|
|:----:|:----:|
| tmux |create new session|
| tmux new -s *session_name* |create new session with a name|
| tmux ls | see sessions created|
| tmux attach -t *session_name* | go back to session created|
| tmux detach | detach from current session|
| tmux kill-ses | kill the current session|
| tmux kill-session -t *session_name*| kill session with a session name |
| tmux kill-session -t *-a* | kill all sessions but current one |


## in a session

| command | function|
|:-----------:|:----:|
| Ctrl+z |tmux mode -> (tm)|
|  (tm) **&#124;** |  split window vertically |
|(tm) - | split window horizontally|
|(tm) r | refreash tmux configuration|
| exit | cloase window created|
| (tm) j | resize split window (down)|
| (tm) k | resize split window (up)|
| (tm) l | resize split window (right)|
| (tm) h | resize split window (left)|
| (tm) m | maximize and minimize window|
| (tm) I | install plugins|
| Ctrl + j | jump to different split window (down)|
| Ctrl + k | jump to different split window (up)|
| Ctrl + l | jump to different split window (right)|
| Ctrl + m | jump to different split window (left)|
| (tm) c | create mew wondow (like a tab)|
| (tm) # of window  | open window with # (like changing tabs|
| (tm) , | rename opened window|
| (tm) n | open next window|
| (tm) p | open previous window|
| (tm) w | see all the session and window (tabs)|
| (tm) &#x5B; | copy mode (cm)|

