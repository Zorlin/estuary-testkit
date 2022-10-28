# estuary-testkit
Quick 'n dirty Python scripts to benchmark and test Estuary.tech

Planned tests:

* single-threaded upload of ~100 files under 5KiB via API
* time from uploading something to being able to fetch it via local IPFS client
* parallel upload tests of 50, 100, 500 files at a time

Ideas:

* Record data in a format that can easily be piped into GNUplot to make pretty graphs
