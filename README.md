# Xmlchk
XML syntax validator written in AWK, suitable for quick check on very large files

## Features
* Error reporting with precise line number and position
* Find incorrect nesting
* Find invalid ASCII characters in tag/attribute/reference names and PI targets
* Find illegal `--` inside comments
* Find malformed references or invalid `&` in text or attribute value
* Find malformed PIs and tags
* Find malformed attribute lists
* Find illegal CDATA ending `]]>` in text

## Limitations
* DTD/CDATA/Schema validation not implemented
* Doesn't report undefined namespaces
* Doesn't report when doc contains multiple root elements
* Doesn't report invalid unicode characters

## Links
* https://www.w3.org/TR/xml/