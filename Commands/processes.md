# Process Management in Linux

## 🔍 View Processes

```bash
ps aux
top
htop
#Search for Specific Processes
ps aux | grep nginx
pgrep ssh
#Kill Processes
kill <PID>
kill -9 <PID>
pkill firefox
#View Process Tree
pstree

# Background Execution
gedit &
💡 Notes
kill -9 sends SIGKILL to force termination

pgrep is cleaner than ps aux | grep

htop allows interactive killing and sorting

