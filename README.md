# docker-blesta

Docker container for running Blesta.

It does include `cron` and `apache` & `php`.

You got to run mysql separately.

Blesta is not included, as I version control it in git and deploy by `mikenowak/docker-gitsync`.

This isn't probably for you, but works just fine for my needs.

Run with the ip bind i.e. `--ip 1.2.3.4` or IP changes will invalidate your license.

