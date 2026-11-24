# Day Trader skill pack (vendored)

The `trader-*` skills in this folder are copied from
https://github.com/Jakeschincariol/day-trader-skill at commit `3d0f4ef`
(MIT, see `DAY-TRADER-SKILL-LICENSE`). Tests and fixtures were not copied.

Before the SEC tools work, set `SEC_USER_AGENT` or add `"sec_user_agent"` to
`trader/config.json`. Paper trading is the default, and `trader-broker` never
places an order without your explicit yes.
