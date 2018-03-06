Graph
=====

Graph view contains the control flow graph. When you use :doc:`../../commands/gui/graph` command or context menu in the disassembly view, it will show the control flow graph here.

There are two modes to show the control flow graph: Normal mode and overview mode.

In overview mode, the program will draw all the control flow graph within the window area, but not output the disassembly. When the first instruction is traced when trace record is enabled on this memory page, the whole basic block will be shown in a different color (Default is green).
