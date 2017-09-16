# pexpo
pexpo is ping sending tui tool with cool clomun & logging loss-count in the Multi platform(Windows, Mac, Linux...).  
pexpo has tui engine is [termbox-go](https://github.com/nsf/termbox-go), sending ICMP engine is [go-fastping](https://github.com/tatsushid/go-fastping).  
So, pexpo's code is NATIVE [The Go Programming Language](http://golang.org) application.  
This is inspired the [pinger](https://github.com/hirose31/pinger), [Exping](http://www.woodybells.com/exping.html).
  
## Demo (Linux)
![result](https://github.com/nao4arale/pexpo/blob/master/pexpo_linux.gif)

## Demo (windows10)
![result](https://github.com/nao4arale/pexpo/blob/master/pexpo_windows.gif)

## Implemention
- very light, and quick application(for Pinging to the too many hosts).
- Run on multi platforms(Windows7, Windows10, Mac, Linux...) with ONLY one app!!
- ipv4, and ipv6!!
- Display Counting Ping loss per host.
- Display Current Dead host(if host is revive, and dead mark is vanish).
### more...
- logging ping result($HOME/.pexpo/result_$DATE_.txt).
- Check the syntax on the ping-list(# is comment out, ignoring blank line, no description is ok...).

## Writer & License
pexpo's was writed by nao4arale (Twitter:@A_Resas, MAIL:n4sekai5y@gmail.com).  
This software is released under the MIT License, see LICENSE.
