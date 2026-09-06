# MW AFK — releases

Built APKs for the Modern Warships AFK farming macro.

The source lives in a **private** repo. This one is public and contains only:

- `latest.json` — what the app reads to decide whether it is out of date
- the APKs, attached to [Releases](../../releases)

The app checks `latest.json` on this repo's `main` branch. It is fetched from
`raw.githubusercontent.com` rather than the GitHub API because the API
rate-limits unauthenticated callers to 60 requests an hour per IP and raw
does not.

Nothing here is secret, and the app carries no token — that is the whole reason
this repo exists separately.

## Installing an update by hand

If the in-app button ever fails, download the newest APK from Releases and open
it. Android will ask you to confirm. It installs over the top and keeps your
settings.
