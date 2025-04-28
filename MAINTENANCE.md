# Maintenance Policy for UserAuditor

## Supported Operating Systems
- Ubuntu 20.04 LTS
- Ubuntu 22.04 LTS
- Debian 11 ("Bullseye")
- Debian 12 ("Bookworm")
- CentOS 8 Stream
- RHEL 9

## Supported Python Versions
- Python 3.8
- Python 3.9
- Python 3.10
- Python 3.11

## Dependency Update Policy
- Check and update dependencies every 6 months.
- Use Dependabot for automatic alerts if possible.
- Pin critical dependencies to specific versions.

## Release Policy
- Semantic Versioning (SemVer): MAJOR.MINOR.PATCH
- Every release must have:
  - Updated `CHANGELOG.md`
  - GitHub Release with assets (.deb, .rpm, .tar.gz)

## Deprecation Policy
- Support only the last 2 stable Python versions.
- Drop support for OS versions 6 months after their EOL.
- Announce deprecations in the CHANGELOG and README.

---

