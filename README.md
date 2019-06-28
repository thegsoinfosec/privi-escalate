# privi-escalate
Privilege escalation commands and scripts

#After getting a shell execute the commend to add system stability.  
#And,because the dirty_writeback_centisecs is set to 0, all periodic writeback is disabled.

echo 0 > /proc/sys/vm/dirty_writeback_centisecs 
