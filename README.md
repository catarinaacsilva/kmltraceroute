# KML Traceroute

Tool to create geo-referenced TCP traceroutes in KML format for visualization on a map/globe.  It can only handle IPv4 routes.

KML files can be viewed using this [link](http://ivanrublev.me/kml/) or this [link](http://kmlviewer.nsspot.net/)

The code use this [api](https://freegeoip.live/) to search the geolocation of IP addresses

## Requirements

- Ubuntu 20.04 (optional)
- traceroute
- jq
- curl
- net-tools

# Run

1. `sudo ./kmltraceroute <IP OR NAME>  >trace.kml`

2. Open, e.g this [link](http://kmlviewer.nsspot.net/) and choose file `trace.kml`


# Symbol description

| Tables                                        | Description   |
| ----------------------------------------------|:-------------:|
| ![destination](icons/destination.png =20x)         | right-aligned |
| ![lost](icons/lost.png =250x)                       | centered      |    
| ![hostingservers](icons/hosting-servers.png =250x)  | are neat      |
| ![backup](icons/backup.png =250x)                   | are neat      | 
| ![flag](icons/flag.png =250x)                       | are neat      |   


## Authors

* **Catarina Silva** - [catarinaacsilva](https://github.com/catarinaacsilva)

Based (forked) [petterreinholdtsen](https://github.com/petterreinholdtsen/kmltraceroute) repository

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details