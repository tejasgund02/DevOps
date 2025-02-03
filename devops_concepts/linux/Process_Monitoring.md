# Process Monitoring

* observation and analysis of processes

* to ensure optimal performance, efficiency, and compliance 


### List command use in the process monitoring:


1. `ps -e` : Lsit all running processes.

2. `ps aux`: show process for alluser , Display process owner and resource usage,Includes processes that don't have a controlling terminal (such as daemon processes).

3. `top`: it give all infromation of running live work in processer.(Rel-time view with dynamically).



4. Viewing running processes: `ps`, `top`, `htop` , `pstree`



5. Checking CPU usage: `top`, `htop`, `mpstat`, `sar`


6. Checking memory usage: `free`, `vmstat`, `top`, `htop`


7. Monitoring disk I/O usage: `iotop`, `iostat`, `dstat`


8. Viewing process hierarchy: `ps -ef --forest`, `pstree`


9. Checking open files by processes: `lsof`


10.  Monitoring network connections: `netstat`, `ss`, `iptraf-ng`


11. Viewing process states: `ps aux`, `top`, `htop`


12. Tracking process start and end times: `ps -eo pid`,`lstart`,`etime`


13. Monitoring threads within processes: `ps -T`, `htop`


14. Checking process owner and group: `ps -eo user`,`group`,`pid`,`cmd`


15. Viewing signals sent to processes: `kill -l`, `ps -eo pid`,`sig`


16. Tracking zombie or orphan processes: `ps aux | grep 'Z'`, `top`

