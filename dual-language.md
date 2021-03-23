## Multiple file YAML example
Path: manifests / m / Microsoft / WindowsTerminal / 1.6.10571.0 / Microsoft.WindowsTerminal.yaml

```YAML
PackageIdentifier: "Microsoft.WindowsTerminal"
PackageVersion: "1.6.10571.0"
DefaultLocale: "en-US"
ManifestType: "version"
ManifestVersion: "1.0.0"
```

Path: manifests / m / Microsoft / WindowsTerminal / 1.6.10571.0 / Microsoft.WindowsTerminal.locale.en-US.yaml

```YAML
PackageIdentifier: "Microsoft.WindowsTerminal"
PackageVersion: "1.6.10571.0"
PackageLocale: "en-US"
Publisher: "Microsoft"
PublisherURL: "https://www.microsoft.com/"
PrivacyURL: "https://privacy.microsoft.com/"
PackageName: "Windows Terminal"
PackageURL: "https://docs.microsoft.com/windows/terminal/"
License: "MIT"
LicenseURL: "https://github.com/microsoft/terminal/blob/master/LICENSE"
ShortDescription: "The new Windows Terminal, a tabbed command line experience for Windows."
Tags: 
- "Console"
- "Command-Line"
- "Shell"
- "Command-Prompt"
- "PowerShell"
- "WSL"
- "Developer-Tools"
- "Utilities"
- "cli"
- "cmd"
- "ps"
- "terminal"
ManifestType: "defaultLocale"
ManifestVersion: "1.0.0"
```

Path: manifests / m / Microsoft / WindowsTerminal / 1.6.10571.0 / Microsoft.WindowsTerminal.locale.fr-FR.yaml

```YAML
PackageIdentifier: "Microsoft.WindowsTerminal"
PackageVersion: "1.6.10571.0"
PackageLocale: "fr-FR"
Publisher: "Microsoft"
ShortDescription: "Le nouveau terminal Windows, une expérience de ligne de commande à onglets pour Windows."
ManifestType: "locale"
ManifestVersion: "1.0.0"
```

Path: manifests / m / Microsoft / WindowsTerminal / 1.6.10571.0 / Microsoft.WindowsTerminal.installer.yaml

```YAML
PackageIdentifier: "Microsoft.WindowsTerminal"
PackageVersion: "1.6.10571.0"
Platform: 
 - "Windows.Desktop"
MinimumOSVersion: "10.0.18362.0"
InstallerType: "msix"
InstallModes: 
 - "silent"
PackageFamilyName: "Microsoft.WindowsTerminal_8wekyb3d8bbwe"
Installers: 
 - Architecture: "x64"
   InstallerUrl: "https://github.com/microsoft/terminal/releases/download/v1.6.10571.0/Microsoft.WindowsTerminal_1.6.10571.0_8wekyb3d8bbwe.msixbundle"
   InstallerSha256: 092aa89b1881e058d31b1a8d88f31bb298b5810afbba25c5cb341cfa4904d843
   SignatureSha256: e53f48473621390c8243ada6345826af7c713cf1f4bbbf0d030599d1e4c175ee
 - Architecture: "arm64"
   InstallerUrl: "https://github.com/microsoft/terminal/releases/download/v1.6.10571.0/Microsoft.WindowsTerminal_1.6.10571.0_8wekyb3d8bbwe.msixbundle"
   InstallerSha256: 092aa89b1881e058d31b1a8d88f31bb298b5810afbba25c5cb341cfa4904d843
   SignatureSha256: e53f48473621390c8243ada6345826af7c713cf1f4bbbf0d030599d1e4c175ee
 - Architecture: "x86"
   InstallerUrl: "https://github.com/microsoft/terminal/releases/download/v1.6.10571.0/Microsoft.WindowsTerminal_1.6.10571.0_8wekyb3d8bbwe.msixbundle"
   InstallerSha256: 092aa89b1881e058d31b1a8d88f31bb298b5810afbba25c5cb341cfa4904d843
   SignatureSha256: e53f48473621390c8243ada6345826af7c713cf1f4bbbf0d030599d1e4c175ee
ManifestType: "installer"
ManifestVersion: "1.0.0"
```
