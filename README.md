# FTPeasy
A lightweight, concurrent FTP server written in pure Go for [this tutorial](https://medium.com/better-programming/how-to-write-a-concurrent-ftp-server-in-go-part-1-3904f2e3a9e5).

Compile the binary and run it to launch the server on port `8080` (default), or configure it with the `-port` flag. Congratulations! Your server is ready to receive requests through your FTP client of choice.

**Note**: This is not an SFTP server. Connections to it are not secure. Don't try to use it for anything important.

## To do
* Username and password authentication
* Sandbox users, preventing them from escaping the filesystem.
* Test suite.
* Write outstanding FTP functions described by the specification.
