# Erwan's handy tools

### Ubuntu changelogs french mirror

> Although `fr.archive.ubuntu.com` exists, `fr.changelogs.ubuntu.com` doesn't.
> It's useful for when you need to run `sudo do-release-upgrade` if you can't access `changelogs.ubuntu.com` (from company network policies and such)
> The meta-release files are modified so that all `archive.ubuntu.com` are now `fr.archive.ubuntu.com`.
>
> This _should_ be enough for you to run `do-release-upgrade`.
>
> __PLEASE NOTE:__ In order to use this mirror, you will need to modify the `/etc/update-manager/meta-release` file,
> and replace `https://changelogs.ubuntu.com/meta-release` with `https://www.erwanegasse.com/tools/fr.changelogs.ubuntu.com/meta-release`.

- [./fr.changelogs.ubuntu.com/meta-release](https://www.erwanegasse.com/tools/fr.changelogs.ubuntu.com/meta-release)
- [./fr.changelogs.ubuntu.com/meta-release-lts](https://www.erwanegasse.com/tools/fr.changelogs.ubuntu.com/meta-release-lts)
