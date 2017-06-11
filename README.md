# Natively compiled libraries for libmagic on 32bit Windows<br>
libmagic identifies file types by checking their headers according to a predefined list of file types.<br>
This functionality is exposed to the command line by the Unix command _file_.

This libraries are created by copying magic1.dll, regex2.dll, zlib1.dll, and magic.mgc from the Binaries & Dependencies zip files provided by the <a href="http://gnuwin32.sourceforge.net/packages/file.htm">File for Windows</a> project. If you are using a 64-bit build of python, you'll need 64-bit libmagic binaries which can be found here: <a href ="https://github.com/pidydx/libmagicwin64">libmagicwin64</a>.

