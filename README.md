# gatus

# cronjob

install this cron on the host if you plan to keep the config up to date.

gatus will automatically reload the configuration files.

```
*/1 * * * * git --git-dir=/<gatus-path>/.git fetch -a
```
