# Quick-start
Create an alias for long commands. I made it to shorten long commands with a series of arguments or access directory-dependent scripts anywhere. 

### Installation
- clone or make a copy of the quick script
- Pick one of these:
```
#Run it from its directory
/path/to/quick <command>

#or include it to your PATH
/path/to/quick install <PATH>

#or install it to /usr/local/bin - you may need to use sudo
/path/to/quick install

#the last two will allow you to call the quick script from anywhere
```
### Use
```
quick add shortname 'docker-compose -f /path/to/somewhere up --build --no-cache'
quick shortname

quick help

Quick Start v0.1.0
Command list:
------------------
add option_name bash_command - create an alias
rm option_name - delete an alias
disable option_name - disable an alias
enable option_name - enable an alias
install install_path - cp quick script to a directory (default: /usr/local/bin)
explain option_name - show command for an alias
ls - list all aliases
```

### Meta
Author: hrkyoung [iam@hkryoung.com](iam@hrkyoung.com)
