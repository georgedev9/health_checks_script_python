# health_checks_script_python

This Python script checks the system CPU, Memory, and Disk Usage.

It will send an email if there are problems, such as:

* Report an error if CPU usage is over 80%
* Report an error if available disk space is lower than 20%
* Report an error if available memory is less than 500MB
* Report an error if the hostname "localhost" cannot be resolved to "127.0.0.1"
