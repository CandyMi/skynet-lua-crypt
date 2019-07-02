# skynet-lua-crypt

  fork from [here](https://github.com/CandyMi/core_framework).

## Lua crypto algorithms supported extend

  Like skynet `lua-crypt`, But add `md5`、`crc32`、`crc64`、`sha256`、`sha512`、`hmac_md5`、`hmac_sha256`、`hmac_sha512` supported.

  Note that this is a Lua C API implementation, And tested by `exmaple/testsha.lua` file.

## Replace file

   Copy all files in `skynet-lua-crypt/src` to the `luaclib-src` folder and replace the relevant files.

## Build && Install with skynet. (Only tested In Skynet v1.2)

  You can achieve fast compilation by simply replacing the `skynet-lua-crypt/Makefile` file with the `skynet/Makefile` file.

  Finally, You need use `make platform(linux/macosx/freebsd)` to build it.

## LICENSE

  [MIT LICENSE](https://github.com/CandyMi/skynet-lua-crypt/blob/master/LICENSE)
