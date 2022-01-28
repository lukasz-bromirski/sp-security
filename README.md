# Service Provider security materials and references
Collected, groomed and maintained by Łukasz Bromirski. Feel free to use and share :)

Copy of the https://null0.pl repository.

## General routing security

* [IOS XR hardening](https://tools.cisco.com/security/center/resources/increase_security_ios_xr_devices.html)
* [IOS XR LTPS on ASR 9000](https://supportforums.cisco.com/document/93456/asr9000xr-local-packet-transport-services-lpts-copp)

## Service Provider security groups, forums, projects and associations

* [MANRS, Mutually Agreed Network Routing Security ISP guides](https://www.manrs.org/isps/guide/)

## Service Provider Network Operating Groups

* [NANOG](https://www.nanog.org/)
* [PLNOG](https://plnog.pl/en/)

## Data plane

### unicast Reverse Path Filtering (uRPF)

* [RFC 2827: Network Ingress Filtering: Defeating Denial of Service Attacks which employ IP Source Address Spoofing](https://datatracker.ietf.org/doc/html/rfc2827)
* [RFC 3704: Ingress Filtering for Multihomed Networks](https://datatracker.ietf.org/doc/html/rfc3704)
* [Unicast Reverse Path Forwarding for the ISPs](https://www.cisco.com/c/dam/en_us/about/security/intelligence/urpf.pdf)
* [Ivan Pepelnjak - Does uRPF Make Sense in Internet Service Provider Networks?](https://blog.ipspace.net/2014/01/does-urpf-make-sense-in-internet.html)

## Management plane

## Services plane

## Control plane

* [RFC 3882: Configuring BGP to Block Denial-of-Service Attacks](https://datatracker.ietf.org/doc/html/rfc3882)
* [RFC 5635: Remote Triggered Black Hole Filtering with Unicast Reverse Path Forwarding](https://datatracker.ietf.org/doc/html/rfc5635) 
* [RFC 6192: Protecting the Router Control Plane](https://datatracker.ietf.org/doc/html/rfc6192)
* [RFC 7454: BGP Operations and Security](https://tools.ietf.org/html/rfc7454)
* [RFC 7999: BGP BLACKHOLE community](https://datatracker.ietf.org/doc/html/rfc7999)
* [Security Control Plane on Cisco devices](https://www.ciscopress.com/articles/article.asp?p=2928193&seqNum=3)
* [Cisco IOS/IOS-XE hardening guide](https://www.cisco.com/c/en/us/support/docs/ip/access-lists/13608-21.html)
* [Cisco IOS XR hardening guide](https://tools.cisco.com/security/center/resources/increase_security_ios_xr_devices.html)
* [Cisco NX-OS hardening guide](https://tools.cisco.com/security/center/resources/securing_nx_os.html)
* [Cisco 6500/6800 Supervisor 2T Control Plane configuration](https://www.cisco.com/c/en/us/support/docs/switches/catalyst-6500-series-switches/118806-config-catalyst-00.html)
* [Juniper protecting Routing Engine Day One](https://kb.juniper.net/library/CUSTOMERSERVICE/Securing_RouteEngine2.pdf)

### BGP blackholing

* [S/RTBH with ASR 9000 and Cisco IOS XR](https://www.cisco.com/c/en/us/support/docs/routers/asr-9000-series-aggregation-services-routers/116386-configure-asr9000-00.html)
* [S/RTBH and D/RTBH on Cisco IOS and IOS-XE](https://www.cisco.com/c/dam/en_us/about/security/intelligence/blackhole.pdf)
* [BGP blackholing, sinkholing and FlowSec usage](https://lukasz.bromirski.net/docs/prezos/certee2017/BGP_Security_101.pdf)

### BGP sinkholing

* [NANOG #28: Sinkholes](https://archive.nanog.org/meetings/nanog28/presentations/sink.pdf)
* [APRICOT 2015: Sinkholes](https://www.senki.org/wp-content/uploads/2015/03/009-Sink-Holes-2012-02-25.pdf)

### BGP QPPB (QoS-Policy Propagation with BGP)

* [Configuring BGP QPPB on Cisco ASR 9000](https://community.cisco.com/t5/service-providers-documents/asr9000-xr-implementing-qos-policy-propagation-for-bgp-qppb/ta-p/3136639)
* [QPPB in Cisco IOS and IOS-XE](http://ptgmedia.pearsoncmg.com/images/9781587201240/appendix/QPPBSection.pdf)

### BGP FlowSpec

* [BGP FlowSpec in IOS XR](https://supportforums.cisco.com/document/12226726/asr9000xr-understanding-bgp-flowspec-bgp-fs)

### BGP RPKI

* [RIPE RPKI tools](https://www.ripe.net/manage-ips-and-asns/resource-management/rpki/tools-and-resources)
* [BGP RPKI with IOS XR](https://www.cisco.com/c/en/us/support/docs/ip/border-gateway-protocol-bgp/217020-bgp-rpki-with-xr7-cisco8000-whitepaper.html)
* [BGP RPKI with JunOS](https://www.juniper.net/documentation/en_US/release-independent/nce/topics/topic-map/nce-187-bgp-rpki-tn-overview.html)
* [BGP RPKI NIST monitor](https://rpki-monitor.antd.nist.gov/)
* [BGP RPKI RIPE per-country stats](https://stat.ripe.net/widget/country-routing-stats)
* [BGP RPKI Internet Society tools](https://www.internetsociety.org/deploy360/securing-bgp/statistics/)
