#### HEAD pointer
##### General info

* HEAD is a pointer to the current branch
  * .git/HEAD file in your git repository
* Is useful to indicate parent commits
  * 2 notations: '~' or '^'
    * Remember: a git commit can have *more than one parent*
    * HEAD~1: goes up to through the tree
    * HEAD^2: to specify *second* parent of a commit