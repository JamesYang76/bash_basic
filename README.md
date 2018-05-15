# bash_basic

#### printenv
List Environmental Variables
```bash
$ printenv
```
#### export
marks an environment variable to be exported with any newly forked child processes and thus\
it allows a child process to inherit all marked variables.
```bash
$ export JAVA_HOME=/usr/local/jdk
$ export | grep JAVA_HOME
```
