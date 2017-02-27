# <%= process.name %> <%= event %>

Process: <%= process.name %> 

Error Time: <%= date %>

Up Time: <%- (new Date(process.pm_uptime)).toString() %>

Restart Count <%= process.restart_time %>

Executable: <%= process.pm_exec_path %>

Standard Log Path <%= process.pm_out_log_path %>

Error Log Path: <%= process.pm_err_log_path %>

