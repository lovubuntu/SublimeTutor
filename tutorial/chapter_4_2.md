Goto definition
================

Starting version 3 only, Sublime Text also supports `Goto definition` command.
This depends upon the indexing strategy and recognized symbols.

* Shortcut - `Cmd + Option + down`

Exercise
---------

1. This will work If you project has been indexed (which should be the case, 
   if you have been following along)
2. Put your cursor on `Foo` and press `Goto definition` shortcut. (If you have
   changed the Foo class to Bar as part of chapter_1 exercise make sure you 
   undo those changes in chapter_1.rb)
3. The same thing for `bar1` and `bar2` below.


```

foo = Foo.new
foo.bar1

foo.bar2

```