# Price Hunter releases

Official public release files and signed update manifests for Price Hunter.

The stable client endpoint is:

`https://updates.pricehunter.tasstack.kz/stable/latest.json`

Release packages are uploaded and independently downloaded/verified before the
signed stable manifest is changed. Immutable versioned manifests are preserved
under `manifests/`; `stable/latest.json` is published last.

Version 1.0.3 is a technical pilot of the existing client's update channel. It
adds per-computer ZIP export folder settings, executed version and successful
update-date information, unclipped column selectors, and an updater that closes
after success. The preceding 1.0.1 and 1.0.2 releases and their signed manifests
remain available unchanged. The
GitHub Release is marked as a prerelease. Local update, data preservation and
forced rollback checks passed; clean-Windows, two-computer LAN and agreed real
Outlook delivery checks remain before a general commercial rollout.
