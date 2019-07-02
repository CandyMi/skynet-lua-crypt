# skynet-lua-crypt

  fork from [here](https://github.com/CandyMi/core_framework).

## Add supported algorithms

  Like skynet `lua-crypt`, But add `crc32`、`crc64`、`sha256`、`hmac_sha256` supported.

## Replace file

   Copy all `.c` files in `skynet-lua-crypt/src` to the `luaclib-src` folder and replace the relevant files.

## Build && Install with skynet. (Only test In Skynet v1.2)

  You can achieve fast compilation by simply replacing the `skynet/lua-crypt / Makefile` file with the `skynet / Makefile` file.

  Finally, You need use `make platform(linux/macosx/freebsd)` to build it.

## LICENSE

  [MIT LICENSE](https://github.com/CandyMi/skynet-lua-crypt/blob/master/LICENSE)
