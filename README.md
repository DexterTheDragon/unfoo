[![Build Status](https://secure.travis-ci.org/DexterTheDragon/unfoo.png)](http://travis-ci.org/DexterTheDragon/unfoo)

# Unfoo

Unfoo is a little shell script for extracting the contents of compressed files.
It handles multiple formats and even does auto sub-directory detection.

## Supported Formats

    tar
    gzip'd tar
    bzip2'd tar
    lzma'd tar
    xz'd tar
    gzip
    compress
    bzip2
    lzma
    xz
    ace
    rar
    zip
    7zip

## Install

Place unfoo somewhere on your $PATH

## Basic Usage

    $ unfoo linux.tar.gz

## Testing

Run `make test` to execute the test suite. See the README in the `tests/` directory
for more information.

## Contributing

* Fork the project.
* Make your feature addition or bug fix.
* Add tests for it. This is important so I don't break it in a future version unintentionally.
* Commit your changes
* Send me a pull request. Bonus points for topic branches.

## License

(Simplified BSD License)

    Copyright 2002-2011 Graham Forest <vitaminmoo@wza.us> All rights reserved.

    Redistribution and use in source and binary forms, with or without modification, are
    permitted provided that the following conditions are met:

        1. Redistributions of source code must retain the above copyright notice, this list of
            conditions and the following disclaimer.

        2. Redistributions in binary form must reproduce the above copyright notice, this list
            of conditions and the following disclaimer in the documentation and/or other materials
            provided with the distribution.

    THIS SOFTWARE IS PROVIDED BY <COPYRIGHT HOLDER> ''AS IS'' AND ANY EXPRESS OR IMPLIED
    WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND
    FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL <COPYRIGHT HOLDER> OR
    CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
    CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
    SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON
    ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING
    NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF
    ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

    The views and conclusions contained in the software and documentation are those of the
    authors and should not be interpreted as representing official policies, either expressed
    or implied, of Graham Forest
