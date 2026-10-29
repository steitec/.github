# Security Policy

## Supported versions

Unless a project says otherwise, only its latest release receives fixes.

## Reporting a vulnerability

Please **do not open a public issue**. Report it privately through the
repository's **Security** tab → **Report a vulnerability** (GitHub private
vulnerability reporting), or by e-mail to hello@steitec.net.

Include the project and version, how to reproduce the problem and what impact
you expect. You will get an answer within a week. Once a fix is released, the
report is published as a GitHub security advisory, crediting you if you wish.

Several projects are test tools (simulators, test kits) that are meant for
development machines and CI, not for untrusted networks. A missing
authentication on a simulated instrument is by design; crashes, code
execution or file access through crafted input are not.
