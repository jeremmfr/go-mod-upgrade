<!-- markdownlint-disable-file MD013 MD041 -->
# changelog

## v0.4.0 (2024-09-06)

ENHANCEMENTS:

* release now with Go v1.23

PATCH:

* update golang dependencies

## v0.3.0 (2024-02-09)

ENHANCEMENTS:

* release now with Go v1.22

PATCH:

* update golang dependencies

## v0.2.0 (2023-10-12)

ENHANCEMENTS:

* change color for package name to red when update minor version but with major version `v0`
* release now with Go v1.21

PATCH:

* update golang dependencies

## v0.1.4 (2023-06-08)

PATCH:

* update golang dependencies

## v0.1.3 (2023-06-08)

BUG FIXES:

* rollback changes in v0.1.1 (no fix needed)

## v0.1.2 (2023-06-07)

BUG FIXES:

* fix message when force update but all modules are up to date

## v0.1.1 (2023-06-07)

BUG FIXES:

* fix missing version when release

## v0.1.0 (2023-06-07)

> First release since create fork

ENHANCEMENTS:

* add new `tidy` argument to execute `go mod tidy` after modules update
* fix color for package name and version with major, minor, patch update

BUG FIXES:

* changes the handling of erroneous packages, those that cannot be found or are malformed (add `-e` argument when launch `go list`)
