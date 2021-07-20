[![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/usecallmanagernz/certutils/python%20lint/master?label=python%20lint)](https://github.com/usecallmanagernz/certutils/actions/workflows/pylint.yml) [![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/usecallmanagernz/certutils/shell%20lint/master?label=shell%20lint)](https://github.com/usecallmanagernz/certutils/actions/workflows/shellcheck.yml) [![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/usecallmanagernz/certutils?color=blue&label=version&sort=semver)](https://github.com/usecallmanagernz/certutils/releases)

# Certificate Utilities

Utilities to manage .tlv and .sgn files.

* `tlvfile` - Parse or build .tlv files (eg: ITLFile.tlv).
* `sgnfile` - Parse or build .sgn files.
* `stripsgn` - Remove .sgn header from a firmware file.
* `certhash` - Hash an x509 certificate and output as base64.
* `enccnf` - Encrypt or decrypt SEPMAC.cnf.xml files.
* `mkcert` - Make self-signed X509 certificates.

See [Device Security](http://usecallmanager.nz/itl-file-tlv.html) for
example usage.

## Requirements

The following non-standard Python modules are required: `crytography`
and `lxml`.

You can use the packages provided by your OS distribution or run
`sudo pip3 install -r requirements.txt` to satisfy those dependancies.
