Explain what the pushd and popd commands do in your own words:

the 'pushd' command saves the current working directory in memory so it can
be returned to at any time, optionally changing to a new directory. 
The 'popd' command returns to the path at the top of the directory stack.
"popd" pops the stack, removing the top item (i/like/icecream) and letting 
the next item (~/temp) pop to the top of the stack, becoming the new working directory.
popd, like pushd, shows the stack on its side, with the top of the stack on the left 
and the bottom of the stack on the right.



 




