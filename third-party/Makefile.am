# ngtcp2

# Copyright (c) 2017 ngtcp2 contributors
# Copyright (c) 2014 nghttp2 contributors

# Permission is hereby granted, free of charge, to any person obtaining
# a copy of this software and associated documentation files (the
# "Software"), to deal in the Software without restriction, including
# without limitation the rights to use, copy, modify, merge, publish,
# distribute, sublicense, and/or sell copies of the Software, and to
# permit persons to whom the Software is furnished to do so, subject to
# the following conditions:

# The above copyright notice and this permission notice shall be
# included in all copies or substantial portions of the Software.

# THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
# EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
# MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
# NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
# LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
# OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
# WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
EXTRA_DIST = CMakeLists.txt

AM_CPPFLAGS = @DEFS@

noinst_LTLIBRARIES = libhttp-parser.la
libhttp_parser_la_SOURCES = \
	http-parser/http_parser.c \
	http-parser/http_parser.h

noinst_LTLIBRARIES += liburlparse.la
liburlparse_la_SOURCES = \
	urlparse/urlparse.c \
	urlparse/urlparse.h
liburlparse_la_CPPFLAGS = -I${srcdir}/urlparse
