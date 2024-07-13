# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.0](https://github.com/babichjacob/experimenting-with-binstall/compare/v0.1.1...v0.2.0) - 2024-07-13

### Added
- I expect a minor version bump to occur from my use of the term feat rather than fix (and lack of ! that would trigger a major version bump)

### Fixed
- trying to re-sync version from accidentally overwritten commits
- well not actually a fix but I just want it to be in conventional commit parlance to trigger a patch increment

### Other
- [**breaking**] hoping this exclamation triggers a major version bump
- add a GitHub Actions workflow to compile and publish binaries whenever a new release is cut
- making a change to see what happens
- metadata to be able to publish to crates.io
- add release-plz GitHub Actions workflow
- stop testing nightly in GitHub Actions
- try (cause I don't know if it works) caching in GitHub Actions
- check the powerset of crate features
- add `.history/` to `gitignore` since I have the local history extension in codium
- remove testing beta toolchain (I didn't even know it existed and don't see why nightly + stable doesn't cover it)
- add GitHub Actions workflow to build and test I got from somewhere (I don't remember where)
- initial commit
