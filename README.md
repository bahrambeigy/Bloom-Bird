Bloom-Bird
==========

A Scalable Open Source Router Based on Bloom filter


Bloom-Bird is a fork of standard BIRD software routing daemon (http://bird.network.cz). The Bird project aims to develop a fully functional dynamic IP routing daemon primarily targeted on (but not limited to) Linux, FreeBSD and other UNIX-like systems and distributed under the GNU General Public License. 
The Bloom-Bird has an extra Bloom Filter feature which helps its Forwarding Information Base (FIB)s to search nodes faster when number of inserted IP prefixes into them becomes huge.


Installation:

./configure [--enable-ipv6]

make && make install

