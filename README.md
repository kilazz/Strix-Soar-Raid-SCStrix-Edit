## Strix Soar/Raid Edit Default/OEM
#### Compatibility >
- Windows 10 x64 19041+
#### Removal >
- Remove all packages, check via [Rapr][DriverStoreExplorer]
- Restart PC
#### Installation Default/OEM >
- Install ASMedia_USB3x_1.16.61.1
- Install Strix_Soar_Setup_1.1.23.exe
- Remove package `nhAsusSC150.inf/nhAsusSC200.inf`, check via [Rapr][DriverStoreExplorer]
- Restart PC ~
- Unzip the archive .7z(Zstandard)
- Run _CertTest/`CertTest.bat` ~
- Install `Only one` >
- Default >
`Install_Default.cmd`
- OEM >
`Install_DolbyAtmos.cmd`
`Install_DTSXUltra.cmd`
`Install_Nahimic.cmd`
- Restart PC
#### Problems >
- After running nhAsusStrixSonicStudioSC.exe a microfreeze for a couple of seconds is possible ~

[DriverStoreExplorer]: https://github.com/lostindark/DriverStoreExplorer
