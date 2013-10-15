### About deHasher

PHP class and web script for decode hash sums.

### Demo

See demo here: http://hash.ziggi.org/

### Using API

    Encode: http://hash.ziggi.org/api.php?type=TYPE&text=TEXT
            type - type of hash, currently available: md5, md5_md5, sha1, base64
            text - any text

    Decode: http://hash.ziggi.org/api.php?type=TYPE&hash=HASH&uot=0/1
            type - type of hash, currently available: md5, md5_md5, sha1, base64
            hash - hash string
            uot (optional) - Use an external database. 1 - true, 0 - false.

    Count:  http://hash.ziggi.org/api.php?type=TYPE&count
            type - type of hash table, currently available: all, md5, md5_md5, sha1
            Returns the number of elements