# Install tocking

## macOS

Use the macOS disk image attached to the release. Open it and drag tocking to Applications. Launch it from Applications. Match the app's published version and signing identity with the release notes.

Do not remove quarantine attributes or disable Gatekeeper. If macOS refuses a package, report the exact message and the release version.

## Windows x64

Download the Windows release ZIP and extract the entire folder to a location you control. Keep all DLLs and the data folder next to tocking.exe, then run tocking.exe. A shortcut can point to that executable.

The release includes the app-local Microsoft C++ runtime. The embedded browser also requires Microsoft Edge WebView2 Runtime; if Windows reports it missing, install it from Microsoft's official WebView2 download page. No Visual Studio installation is needed.

Code-signing and reputation status are stated in the release notes. Do not disable antivirus or Windows security protections to install an untrusted package.

## Verify a download

Compare the downloaded archive's SHA-256 with SHA256SUMS attached to the same release. A checksum checks file consistency; it is not a substitute for the publisher signature.

## Keep team data during updates

Quit the old app and replace only the application files. Do not delete the app's user data, credential storage, recovery keys, or Cloudflare resources. Use the same package identity for updates.
