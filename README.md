# AES
AES encrypt and decrypt. Implement the Java server and client communication c

There are four kinds of the implementation of AES algorithm, such as CBC/ECB/OFB/CFB,
the four kinds of Java and C implementation. AES algorithm and at the end of the filling (padding), 
there are three kinds of Java support way of padding NoPadding/PKCS5Padding,
and C does not explicitly set the padding mode, the default is padding at the end add '\ 0'.
This is a big pit, how many people in this pit. 
In addition, many JAVA AES algorithm online, many of them use SecureRandom, 
if your code appeared SecureRandom this stuff, then you can no longer in C solve it.
