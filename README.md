# TCP Dump Analyses with Wireshark

This repo aims to store all notes from TCP Dump analyses using Wireshark tool. The repo contains tips, tricks, teory overview and good practices.



## References

[Wireshark Ultime Hands On](https://www.udemy.com/course/wireshark-ultimate-hands-on-course/)

[Wireshark Docs](https://www.wireshark.org/docs)

## Requirements

Wireshark

[GeoLite2 Free Geolocation Data](https://dev.maxmind.com/geoip/geolite2-free-geolocation-data?lang=en)



## Interface

![](imgs/wireshark-interface.png)

### Filters

```bash
eq not or and
==  !   |  &&
```

```bash
contains (exact string) # frame contains google
match (regex) # http.host matches "\.(org|com|br)"
```

#### Statistics

![Statistics](imgs/statistics.png)



### Tips & Tricks

#### TCP Options to take a look

* TTL (Time to Live) - Router passed throw;

* Window Size

* Delta Time (Time between last packages sent/received)

* TCP Options

  * Acknowledment
  * Push
  * Reset
  * Syn

  

