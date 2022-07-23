# Simplified Network Architecture

This network design breaks existing networking conventions; required due to inefficient data egress/ingress application paradigms. 

The current internet is building on OSI-7; its limitations and inefficiencies due to the standard's age severely hinder technological development, designed when IP-Transit was not data intensive and network nodes trusted.

# Network Layers

| Layer | Layer Code | Layer Name                             | Network   |
|-------|------------|----------------------------------------|-----------| 
| i0r   | ROOT-ZONE  | Distributed Root Zone                  | LetherNet |
| i1r   | LTHN-1     | LetherNet Interface Router             | LetherNet |
| i1b   | OSI-1      | Physical Layer                         | ClearNet  |
| i2q   | OSI-2      | Data link Layer                        | ClearNet  |
| i3q   | OSI-3      | Network Layer                          | ClearNet  |
| ib4   | OSI-4      | Transport Layer                        | ClearNet  |
| i4v   | LTHN-VPN   | Virtual Peering Network                | LetherNet |
| i5u   | LTHN-QEUA  | Quassi Entropy User Access             | LetherNet |
| i5n   | OSI-5      | Session Layer                          | ClearNet  |
| i5d   | LTHN-DQEUA | Distributed Quassi Entropy User Access | LetherNet |
| i6p   | OSI-6      | Presentation Layer                     | ClearNet  |
| i6o   | LTHN-6     | Interface Router                       | LetherNet |
| i7s   | OSI-7      | Application Layer                      | ClearNet  |
| i7o   | LTHN-POS   | Application Layer                      | LetherNet |
| iw0   | LTHN-PLB   | Public Load Balancer                   | LetherNet |
| i9p   | LTHN-POP   | IPv9 Proof of Peerage                  | LetherNet |
| ifuz  | LTHN-IFUZ  | Distributed Network Encryption         | LetherNet |
