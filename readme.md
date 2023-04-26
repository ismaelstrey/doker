# inicio

TPL2

in: {?last(/TPL-02/net.if.in[ifInOctets.99353])}
Out: {?last(/TPL-02/net.if.out[ifOutOctets.99353])}
____________________________
SFP 25 BGP

Label Value
in: {?last(/TPL-02/net.if.in[ifInOctets.99354])}
Out: {?last(/TPL-02/net.if.out[ifOutOctets.99354])}
____________
SFP 26

SFP 27
____________
in: {?last(/TPL-02/net.if.in[ifInOctets.99355])}
Out: {?last(/TPL-02/net.if.out[ifOutOctets.99355])}
____________
SFP 28


TPL1
in: {?last(/TPL-02/net.if.in[ifInOctets.99329])}
Out: {?last(/TPL-02/net.if.out[ifOutOctets.99329])}
____________
ETH 01

{?last(/{HOST.HOST}/agent.ping)}
{?last(/{HOST.HOST}/icmppingsec.last(0))}


SSID:{?last(/{HOST.HOST}/ssid-ubnt)}
SINAL:{?last(/{HOST.HOST}/ubntWlStatSignal)}
UPTIME:{?last(/{HOST.HOST}/uptime)}
POP:{?last(/{HOST.HOST}/system.location[sysLocation.0])}



