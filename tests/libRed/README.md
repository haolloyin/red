### LibRed tests and demo files.

The `libRed.dll` precompiled library (using `stdcall` ABI) provided in this folder is required for the `text.xlsm` demo. That file contains three Excel/libRed integration demos:

* **Pong**: shows how to integrate a VBA form with a Red window and handle all events in a common event loop.

* **Extractor**: shows how to invoke Parse DSL from VBA in order to process a cell text content.

* **Console**: simple Red console made from Excel cells, shows how to create VBA callbacks in Red.
