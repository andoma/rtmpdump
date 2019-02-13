RTMP Dump

A toolkit for RTMP streams, now part of the advanced media center movian https://movian.tv, must be adapted to use OpenSSL-1.1

The original files from http://rtmpdump.mplayerhq.hu/ could be compiled using the description in the README file. For a detailed description look into the README file.

As part of the movian project the files were recharged and after that cannot be used stand-alone. By default they are configured for use with the OpenSSL library. Updating OpenSSL to versions higher than 1.0 broke the compatibility to earlier versions thus preventing successfully generating the final application. Analogously to <https://github.com/JudgeZarbi/RTMPDump-OpenSSL-1.1> three files in subdirectory librtmp had to be modified.

Disclaimer: Use the program for what purpose you like, but hold in mind, that I will not be responsible for any harm it will cause to your hard- or software. It was your decision to use this piece of software. The original copyright notices will remain fully intact.

