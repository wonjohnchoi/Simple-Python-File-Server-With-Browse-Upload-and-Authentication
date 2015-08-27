#Simple Python File Server With Browse, Upload, and Authentication
This is a simple file server that
* supports file directory browse of the server
* supports file upload to the server
* supports authentication

It is tested with Ubuntu 14.04, python 2.7.6

Find the latest version at https://github.com/wonjohnchoi/Simple-Python-File-Server-With-Browse-Upload-and-Authentication

###How To Install
Read and edit settings.py.

`sudo ./install`

Once the script is completed, this file server should be registered as an upstart service.

Check the file server at http://host:port/base_url

###How To Uninstall
`sudo ./uninstall`

###Credit
This is a fork of http://li2z.cn/?s=SimpleHTTPServerWithUpload written by bones7456 (who also forked from http://www.opensource.apple.com/source/python/python-3/python/Lib/SimpleHTTPServer.py)

This fork adds install scripts and authentication.
