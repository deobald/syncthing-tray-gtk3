
let's call this thing "heap". here's a bullet point list of the things i want in Heap:

- the app is stupidly, __stupidly__ easy to install on any device / platform
    - think Tailscale vs. Wireguard
- there is probably a SaaS for convenience that's also totally optional and hopefully open source. it's local-first, first.
- zero organization. no folders, no method of control whatsoever.
- at least at first, there is no way to delete a file, no way to modify a file, no way to "move" a file (and no meaning to a "move" operation anyway, since no folders)
- phone: click "share" = share a file to the Heap. that's the only significant write operation.
- desktop: drop a file on the system tray icon / app to add it to the heap. that's the only significant write operation.
- all apps: type text to search for files. that's the only significant read operation.
- all apps: the main view is a timeline you can scrub back and forth, preferably with platform-specific previews of files. hopefully not very fancy.
- all apps: index into files to help with search
- all apps: type a little searchable message(s) to attach to a file so it's easier to find later. tags... but long-form if you want.

some maybes / future features:
- web: drop a file on the (SaaS, probs) app to add it to the heap
- browser: click "bookmark" (in a browser extension, probs) = share a url (which is a file) to the Heap.
- email: email yourself (to SaaS, probs) = maybe to steven@heap.com or whatever (the Gmail behaviour, verbatim)
- OCR: "indexing into files" should also OCR images (a la Evernote)
- maybe there is some way to chain files into a "thread", like you would in Gmail (aka "these files are related, somehow, across time") ... this feels like a very risky complication to add, though.

some maybes / future NFRs:
- maybe there is some way to force delete a file (at least for legal reasons, if there's a SaaS)
- maybe there is some way to set a retention period on disk-limited devices, if you really have to
- maybe there is a way to flag files as "large" so they don't go to disk-limited devices... but god i hope not
- maybe there are all sorts of other ways to configure this thing under Advanced Settings. but i really, really hope not. technical features bad. go install syncthing if you want syncthing.
