# `puma64.ayufan.dev`

This is a test running on http://puma64.ayufan.dev:

1. It uses CloudFlare to cache the page closest to user
2. It actively checks the `CF-Cache-Status` to be `HIT`
3. It requires CloudFlare (on proxying side) to be configured to `Ignore Query String`

This is an extended copy of a script found on
http://www.dslreports.com/tools/puma6.
