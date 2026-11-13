# Security policy

## Reporting a vulnerability

Report privately: open the **Security** tab of the affected repository and
choose **Report a vulnerability**. Don't open a public issue, pull request
or discussion for it.

Include:

- device model and build number (Settings → About phone), or the app
  version;
- steps to reproduce or a proof of concept;
- what an attacker gains.

We confirm the report, agree a disclosure date with you and credit you in
the release notes if you want. There is no bug bounty.

## Scope

In scope is what we ship on top of GrapheneOS: our platform patches, our
apps, the update pipeline, the site and the web installer.

A bug that also reproduces on stock GrapheneOS, AOSP, the kernel, Vanadium
or hardened_malloc belongs upstream: report it to
[GrapheneOS](https://grapheneos.org/contact) or the Android security team.
Tell us as well if it affects our releases.

Weaker protection from an option the user explicitly enabled after a
warning screen is documented behaviour, not a vulnerability. A way around
that screen or around the option's limits is one.
