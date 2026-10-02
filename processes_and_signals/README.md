# Shell, processes and signals

This directory contains Bash scripts covering processes, PIDs, signals and init scripts.

- 0-what-is-my-pid: displays its own PID
- 1-list_your_processes: displays a list of the currently running processes, for all users, in a user-oriented format with the process hierarchy
- 2-show_your_bash_pid: displays the lines containing the bash word, to easily get the PID of the Bash process
- 3-show_your_bash_pid_made_easy: displays the PID and the name of the processes whose name contains the word bash, without using ps
- 4-to_infinity_and_beyond: displays "To infinity and beyond" indefinitely, with a sleep of 2 seconds between each iteration
- 5-dont_stop_me_now: stops the 4-to_infinity_and_beyond process using kill
- 6-stop_me_if_you_can: stops the 4-to_infinity_and_beyond process without using kill or killall
- 7-highlander: displays "To infinity and beyond" indefinitely and "I am invincible!!!" when receiving a SIGTERM signal
- 67-stop_me_if_you_can: stops the 7-highlander process without using kill or killall
- 8-beheaded_process: kills the 7-highlander process
- 10-process_and_pid_file: creates the file /var/run/myscript.pid containing its PID, displays "To infinity and beyond" indefinitely and reacts to the SIGTERM, SIGINT and SIGQUIT signals
- manage_my_process: writes "I am alive!" to the file /tmp/my_process indefinitely, with a pause of 2 seconds between each message
- 11-manage_my_process: init script managing manage_my_process with the start, stop and restart arguments
