# asa-procedures
A collection of scripts to generate cisco asa configs and rebuild procedures.

If you're like me then your ASA VPN configs are a set-it and forget-it affair.
Years may go by between times when major config changes are required.

If a reconfig becomes necessary or a device dies and needs to be rebuilt it's nice to have a step-by-step procedure handy that includes the credentials+details associated w/ each VPN conection so you don't have to "think" about things too much during a crucial downtime.
Because sometimes just "backing up the config" doesn't give you everything you need.
and you want to avoid getting stuck troubleshooting your box when a production device is down.

Also: If/when the ASA config syntax changes, it's nice to be able to update a script w/ the new syntax and be able to re-generate setup/rebuild procedures for multiple devices instead of re-creating/editing a set of documents for each device.

These scripts do not include flags that would let them generate configs for a particular ASA firmware revision.
It would be nice to include that feature in the future.

