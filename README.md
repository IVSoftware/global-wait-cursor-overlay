## Global Wait Cursor

Your question raises a unique problem. You'd like to have a wait cursor, e.g. on your main form when you show the modal dialog, but which disables the main form (of course) preventing it from _ever_ showing a wait cursor. One workaround is to create a temporary clear overlay (a top-level form) positioned over the main form that is _not_ disabled and _can_ show a wait cursor. I'd post an example if this question were open but it's not. And I can't post it to the other question's thread because this answer is not a fit for that question. So I guess if you need a link to an example let me know.

![show wait cursor over disabled form](https://github.com/IVSoftware/global-wait-cursor-overlay/blob/master/global-wait-cursor/Screenshots/faux-global-wait-cursor.png?raw=true)