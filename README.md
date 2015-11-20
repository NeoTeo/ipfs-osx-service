# IPFS OS X Service

A simple (no, really) service to add files and directories to IPFS using the Finder and your mouse.

## Requirements

Due to a quirk in Automator only the most basic environment variables are imported so you need to make sure the ipfs executable's path is correct:

Double click the script and choose `Open with Automator` and, if necessary, edit the GOPATH (to match your own) in the top script.  Save and close.

## Install

Double click script and choose `Install`.

## Usage

From there select the files you want to add to IPFS from Finder and select  `AddToIPFS`.
If you want to copy a hash to the clipboard, select the hash and choose ok.

![](ShowOSXIPFS.gif?raw=true "IPFS OSX Service in action.")
## Todo

Add ability to choose multiple hashes -> clipboard.

## License

MIT
