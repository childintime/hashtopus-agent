# hashtopus-agent

Agent part of Hashtopus

## added features:

### nodownload

When running hashtopus.exe with nodownload argument (for example mono hashtopus.exe nodownload) than hashtopus agent will not try to download hashcat from server.

### hashtopus.voucher

If hashtopus.voucher file is present in hashtopus agent directory than text in this file will be used as voucher for server registration. After successful registration file is deleted, if registration fails file stays in directory.