# HelpBuoy

Self-hosted remote support for Windows and Linux, a small alternative to
TeamViewer QuickSupport.

[HelpBuoy](https://www.helpbuoy.com) lets a support techie take over the screen
of someone who asks for help. You run your own server, a single Go binary that
speaks SSH on one port. It authenticates keys and connects techies to computers,
and nothing else: no shell, no file transfer, no forwarding. A session only
carries the screen and the mouse and keyboard input, and the person receiving
help approves every connection.

## Repositories

| Repository | What it is |
| --- | --- |
| [HelpBuoy](https://github.com/HelpBuoy/HelpBuoy) | The server, the desk app for techies and the Windows and Linux clients |
| [helpbuoy-site](https://github.com/HelpBuoy/helpbuoy-site) | The Hugo website at helpbuoy.com, with the guides and downloads |
| [helpbuoy-admin](https://github.com/HelpBuoy/helpbuoy-admin) | Admin and customer portal for the support business: plans, invoices, requests and verified servers |

To try it, download the server, the desk app and a client from the
[latest release](https://github.com/HelpBuoy/HelpBuoy/releases/latest), or
clone the HelpBuoy repository and run `./run.sh` to start all three on one
machine.
