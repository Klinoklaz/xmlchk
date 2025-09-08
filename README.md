# Xmlchk
XML syntax validator written in AWK, suitable for quick check on very large files

## Features
* Error reporting with precise line number and position
* Find incorrect nesting
* Find invalid ASCII characters in tag/attribute/reference names
* Find illegal `--` inside comments
* Find illegal `&` in text or attribute value
* Find malformed tags
* Find malformed attribute lists
* Find illegal CDATA ending `]]>` in text

## Limitations
* PI/DTD/CDATA syntax checking not implemented
* Doesn't report undefined entity/namespace
* Doesn't report duplicated attribute names
* Doesn't report when doc contains multiple root elements
* Doesn't report invalid unicode characters