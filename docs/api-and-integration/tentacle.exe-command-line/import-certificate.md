---
title: Import certificate
---

Replace the certificate that Tentacle uses to authenticate itself

**Import certificate options**

```text
Usage: Tentacle import-certificate [<options>]

Where [<options>] is any of:
      --instance=VALUE       Name of the instance to use
  -r, --from-registry        Import the Octopus Tentacle 1.x certificate from
                               the Windows registry
  -f, --from-file=VALUE      Import a certificate from the specified file
                               generated by the new-certificate command or a
                               Personal Information Exchange (PFX) file
      --pw, --pfx-password=VALUE
                             Personal Information Exchange (PFX) private key
                               password

Or one of the common options:
      --console              Don't attempt to run as a service, even if the
                               user is non-interactive
      --nologo               Don't print title or version information
      --noconsolelogging     Don't log to the console
```
