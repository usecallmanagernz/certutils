# Certificate Utilities

Utilities to manage .tlv and .sgn files.

* `tlvfile` - Parse or create .tlv files (eg: ITLFile.tlv).
* `sgnfile` - Parse or create .sgn files.
* `stripsgn` - Remove .sgn header from a firmware file.
* `certhash` - Hash an x509 certificate and output as base64.
* `mkcert` - Make self-signed X509 certificates.

See [Device Security](http://usecallmanager.nz/itl-file-tlv.html) for
example usage.

## Requirements

The following non-standard Python modules are required: `crytography` and
`asn1crypto`.

You can use the packages provided by your OS distribution or run
`sudo pip3 install -r requirements.txt` to satisfy those dependancies.
