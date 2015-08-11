clean
=====

Clean™, the next generation terminal UI toolkit.

```c
Surface* s = Surface_New(80, 24);
Label* label = Label_New("Are you ready kids?", 10, 30);
Surface_AddElement(label);
Surface_DrawToWindow(s, stdscr);
```

## Dependencies

Dependencies are as follows:
  - types (http://github.com/TeamLe-Shop/types)
