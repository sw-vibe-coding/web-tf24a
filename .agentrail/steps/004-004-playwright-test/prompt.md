Test the Forth debugger UI end-to-end with Playwright MCP:

1. Build and serve the app with trunk
2. Navigate to the app and verify initial load state
3. Test the REPL: type Forth input, verify output appears
4. Test stepping: click Step, verify register values change and disassembly highlights
5. Test breakpoints: click a disassembly line, verify breakpoint marker appears, run and verify it stops
6. Test dictionary browser: click Dictionary tab, click a word, verify inspector shows definition
7. Test reset: click Reset, verify state returns to initial
8. Fix any issues discovered during testing