```
usage: podspecutil <command> [<args>]

Commands to manage a cocopod podspec.

commands
push    	 Pushes a podspec to remote.
update  	 Updates the podspec version and commits the changes
tag     	 Tags a git repo with the current podspec version and pushes 
                 to remote
validate	 Validates the podspec.


arguments:

--spec-repo=<name>		 The name of the spec repo

--sources=<source1,source2,etc>	 Private cocoapod source urls, comma separated.

--path=<path>			 Working path. defaults to the current working directory

--usage				 Prints this usage information
```