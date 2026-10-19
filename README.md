# OKCUT Quick Depth 3 local runtime v0.20

Installation-only runtime/model download for OKCUT Plugin Suite.
The installer downloads both parts, checks each SHA256, concatenates them in
numeric order and verifies the final ZIP SHA256 before installation. Parts are
raw binary splits, not independently extractable archives. Each is below2GiB.
No BSKL/Red Giant vendor plugin, account or license system is included.
Runtime: embedded Python and pinned public dependencies; public pretrained
Distill-Any-Depth Base model. Not an OKCUT-trained AI model. Per-component license
and notice files are included inside the runtime package. After installation,
rendering is local and does not require this download server or an Internet
connection. Host-specific native AE adapter is embedded in the installer.
