# todo.sh

POSIX compliant script for (barely) handling your TODO list

### usage

	usage: todo <add|rm>
		add: adds all args after 'add' as a TODO entry
		rm: removes a TODO entry in for of index number, or /pattern/

### example

	$ todo add buy eggs
	$ todo
	1. grab popcorn
	2. buy eggs
	$ todo rm 2
	$ todo add watch back to the future
	$ todo
	1. grab popcorn
	2. watch back to the future
	$ todo rm /future/
	$ todo add watch star wars
	$ todo
	1. grab popcorn
	2. watch star wars
