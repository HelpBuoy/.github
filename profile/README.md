# HelpBuoy

Self-hosted remote support for Windows and Linux, a small alternative to
TeamViewer QuickSupport.

[HelpBuoy](https://www.helpbuoy.com) lets a support techie take over the screen
of someone who asks for help. You run your own server, a single Go binary that
speaks SSH on one port. It authenticates keys and connects techies to computers,
and nothing else: no shell, no file transfer, no forwarding. A session only
carries the screen and the mouse and keyboard input, and the person receiving
help approves every connection.
