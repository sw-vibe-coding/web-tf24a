Enhance debugger panels with richer inspection:

1. Add memory map visualization bar showing kernel/dict/free/rstack/dstack regions
2. Add dictionary browser — walk the Forth dictionary linked list, show word names and CFAs
3. Add word inspector — when clicking a dictionary entry, show its definition (thread contents)
4. Add caller chain view — walk the return stack to show nested word calls
5. Add breakpoint support — click disassembly lines to toggle breakpoints
6. Add compile log panel showing assembler output (labels, addresses)
7. Test all new panels with Playwright MCP