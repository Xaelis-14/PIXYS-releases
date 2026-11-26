# PIXYS Android releases

This repository distributes signed PIXYS Android packages and release manifests.
The application source repository remains private. No user memory, messages,
credentials or private signing keys belong in this distribution repository.

Each release statement is signed locally with the application's existing signing
key. PIXYS checks it against the signer of the installed application, then checks
the complete downloaded package, its version and its Android signature before
requesting installation. Android may require user confirmation.

Public update metadata is independent of the address and availability of the
personal PIXYS server. Access to that server is a separate connection.
