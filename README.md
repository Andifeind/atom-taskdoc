Taskdoc
=======

Taskdoc is a task documentation language based on Markdown. It uses `.td` as file extension.

```
Todos
=====

My super fancy project ...  

(/) Setup repo
(*) Publish first release
(~) Write documentation
```

A Taskdoc file is simply a Markdown file with a task list. A task can be defined by wrapping a key char with colons. The key char defines the task type.

```
(*) Task item
(#) Mark task as draft
(~) Task is in progress
(/) Task is done
(-) Task failed, was canceled
(!) Task is blocked
(?) Task is incomplete
```
