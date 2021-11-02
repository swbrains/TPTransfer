# TPTransfer
Tool to transfer (export/import) configuration files for the TextPad editor (Windows).

This is a Windows application I wrote for transferring the configuration files for the TextPad editor from one PC to another.

It will parse the TextPad config file to get the folder assignments for macros, clips, key bindings, and syntax files, and copy those folders to a specified location (like a network folder or a flash drive).

During import, it parses the target computer's TextPad config file to get the folder assignments for the various file types and copies the files from the source location (network folder or flash drive) and copies them to those folders on the target computer.
