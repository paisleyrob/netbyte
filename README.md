netbyte
=======
Converts command line arguments through
[ntohl()](http://linux.die.net/man/3/ntohl) and 
[htonl()](http://linux.die.net/man/3/htonl).

To build issue
```sh autoreconf -i && ./configure && make```

Sample output on an intel (little-endian) architecture:

    $ ./netbyte 3000
             unsigned      signed
     orig:       3000        3000
    ntohl: 3087728640 -1207238656
    htonl: 3087728640 -1207238656
