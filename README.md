```
usage: podspecutil <command> [<args>]

Commands to manage a cocopod podspec.

commands
push    	 Validates and pushes a spec repo to remote.
update  	 Updates the .podspec version and commits the changes.
tag     	 Tags the repo with the current .podspec version and pushes 
                 the change to remote.
validate	 Validates the .podspec using pod spec lint.


arguments:

--spec-repo=<name>		 The name of the spec repo

--sources=<source1,source2,etc>	 Private cocoapod source urls, comma separated.

--path=<path>			 The path of the repo. defaults to the current working directory

--usage				 Prints this usage information
```
