# Syncronization

------------------------------------------------------------------------

## NTP

```shell
cat >> /etc/rc.conf <<eof
ntpd_enable="YES"
ntpdate_enable="YES"
ntpd_sync_on_start="YES"
ntpdate_hosts="at.pool.ntp.org"
eof

```
