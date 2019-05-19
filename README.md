# BarcodeRemote
Simple demo project for Girr/Girs concepts. A pretty wacky concept for IR remote control.

This README is just an outline of the concepts. Not yet implemented.

Input: One or more Remotes in the form of a set of [Girr](http://www.harctoolbox.org/Girr.html) files.

A "Host-based" program generates sheet-oriented images of barcodes, together with some human-oriented text,
intended for printing on a page-printer.
Every barcode should encode protocol and parameters, with the command name (and possibly other info) to be printed in human-readable text.

When using, the user scans a bar code with a cheap scanner (USB keyboard compatible),
which sends corresponding command to a [Girs](http://www.harctoolbox.org/Girs.html) server.
(So it is really a Girs client.) Alternatively, the code can be rendered using [IrpTransmogrifier](https://github.com/bengtmartensson/IrpTransmogrifier).
