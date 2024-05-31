# CLIPZIP

Create encrypted zip files with the clipboard content for sharing.

This scripts are thought to be used for being executed from the terminal
in order to send files throw a chat client.

## Dependencies

- Ms Windows: 7z, nircmd, Busybox for Windows.
- GNU/Linux: 7z, xclip, POSIX shell.

## Help

clipzip

    Usage: clipzip {-V | -o |  [-n NAME][-p PASSWORD] }
    
    Create an encrypted zip in "~/.secret/clipzip" with the contents
    of the clipboard. A text editor will be openned before to check
    the contents. If neither -n, -p are specified they are asked for
    interactively. Finaly the directory containing the zip is openned
    with a browser for easy drag.

dirzip

    Usage: dirzip {-V | [-n NAME][-p PASSWORD] DIRECTORY }
    
    Create a (optionally encrypted) zip of a directory, then
    the directory containing the zip is opened with a browser
    for easy drag.

filezip

    Usage: filezip {-V | [-n NAME][-p PASSWORD] FILE }
    
    Create a (optionally encrypted) zip of a file. Then
    the directory containing the zip is opened with a browser
    for easy drag.

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)
