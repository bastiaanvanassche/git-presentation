##### Rewriting history: git reset (2)


* 3 modi:
  * `--soft`
    * does NOT touch *Index (staging area)* or *Working Directory*
    * moves the *HEAD* pointer
  * `--mixed` (default)
    * does NOT touch *Working Directory*
    * moves the *HEAD* pointer
    * updates *Index (staging area)*
  * `--hard`
    * updates everything: HEAD, *Working directory* and *Index*
    * *be careful!*
