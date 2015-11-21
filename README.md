# IPFS OS X Service

A simple (no, really) service to add files and directories to IPFS using the Finder and your mouse.

## Requirements

Due to a quirk in Automator only the most basic environment variables are imported so you need to make sure the ipfs executable's path is correct:

Double click the script and choose `Open with Automator` and, if necessary, edit the GOPATH (to match your own) in the top script.  Save and close.

## Install

Double click script and choose `Install`.

## Usage

From Finder select the files you want to add to IPFS, right click and select `AddToIPFS`. 
A dialog will show a list of the added files' hashes and names.
If you want to copy any of the hashes (and only the hash) to the clipboard, select them and choose ok.
For multiple selection the system defaults apply: Shift, command or dragging the selection.

![](ShowOSXIPFS.gif?raw=true "IPFS OSX Service in action.")
## Todo

## License

MIT
