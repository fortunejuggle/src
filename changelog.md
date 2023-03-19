# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog].
and this project adheres to [Semantic Versioning].

## [Unreleased]

- /

## [0.0.2] - 2023-03-18

### Added

- Small description part for sendmail
- samba server user `[homes]` handling if the user connects the first time
- samba printer driver share documentation
- samba hidden and veto files examples
- nfsv4 example even if the requirement on the [Lpi Org] side is merely awareness
- dhcp small additions
- pam_nologin module description
- pam_listfiles example
- sssd description
- ldap description
- doveconf and doveadm
- ip6tables examples
- ipv6 router example
- ssh currently secure algorithm, ciphers and macs added

### Changed
- moves IPv6 to an own Section

### Deprecated
- a note for TCP Wrapper deprecation have been added
  and eBPF is mentioned

### Removed
- postfix obsolete, unsecure DSA Key Option

### Fixed
- Improved Samba example sections
- Trailing white spaces have been deleted
- Improved Figure for IPtables Chains and Tables

### Security

## [0.0.1] - 2021-08-03

- initial release

<!-- Links -->
[keep a changelog]: https://keepachangelog.com/en/1.0.0/
[semantic versioning]: https://semver.org/spec/v2.0.0.html
[lpi org]: https://www.lpi.org/our-certifications/exam-202-objectives

<!-- Versions -->
[unreleased]: ttps://github.com/lpic2book/src/compare/v0.0.2...HEAD
[0.0.2]: https://github.com/lpic2book/src/compare/v0.0.1...v0.0.2
[0.0.1]: https://github.com/lpic2book/src/releases/tag/v0.0.1
