# HPSR-2016-workshop-paper
This paper proposes a scheme to reduce a size of
a packet header for a segment routing (SR) architecture in a
software-defined network. In the segment routing architecture,
a segment identification (SID) list inserted in packet header is
used to indicate a path between source and destination. An SID
corresponds to a segment. In some networks, the path may consist
of a long SID-list. As a result, a large packet overhead may
be occurred and SR may not guarantee the multiprotocol label
switching (MPLS) backward compatibility due to that currently
deployed MPLS equipments typically support a limited number
of stacked labels. In the proposed scheme, the SID-list is replaced
by a single tag to indicate the route. A destination IP address
of the packet is modified at necessary network elements along
the route. To achieve the objective of the proposed scheme, an
algorithm to calculate flow entries is introduced. An analytical
result shows that the size of the packet header becomes 47%
smaller, compared to a scheme that uses the SID-list, when the
length of SID-list is 16.
