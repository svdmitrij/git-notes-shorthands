git-notes-shorthands
====================

scripts for easy deal with git notes

В файле .git/config секцию origin можно привести к виду 
<pre>[remote "origin"]
        url =   .....
        fetch = +refs/heads/*:refs/remotes/origin/*
        fetch = +refs/notes/*:refs/notes/*
        fetch = +refs/tags/*:refs/tags/*</pre>
        
тогда при фетче будут подтягиваться notes и tags        
