Get the Forth REPL working end-to-end in the browser:

1. Verify forth-bootstrap.s runs correctly (should print "OK\n*\n" then halt)
2. Test with trunk serve that the page loads and shows output
3. Fix any UART timing issues (byte-at-a-time feeding, poll-before-feed pattern from web-tml24c)
4. Ensure step/step-over/pause/resume controls work correctly in paused mode
5. Verify data stack and return stack displays update correctly during stepping
6. Add auto-scroll to output panel
7. Add disassembly view showing instructions around current PC
8. Test with Playwright MCP to verify the live page renders correctly