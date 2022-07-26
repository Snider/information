# Overview

This network design breaks existing networking conventions; required due to inefficient data egress/ingress application paradigms. 

The current internet is building on OSI-7; its limitations and inefficiencies due to the standard's age severely hinder technological development, designed when IP-Transit was not data intensive and network nodes trusted.

The table below outlines phase 1, backwards compatible mode, in future iterations.

As the LetherNet network connectivity deploys, requirements on the OSI-7 network will reduce, allowing E2E operations within the OSI-9 eco-system.

LetherNet is OSI-7 compatible, allowing current IP-Transit providers to participate in the community network by charging fair rates, in line with Social Enterprise philosophies if they so wish as equal members of the network.

# Licence & Permissions

LetherNet is a technology stack licenced under the European Union Public Licence 1.2; the conditions are outlined below for clarity. 

PERMISSIONS: Commercial use, Modification, Distribution, Patent use and Private use.

LIMITATIONS: Liability, Trademark use, Warranty.

CONDITIONS: License and copyright notice, Disclose source, State changes, Network use is distribution, Same license

# Network Layers


| Layer                                                | Layer Code                                                                   | Layer Name                             | Network                                          |
|------------------------------------------------------|------------------------------------------------------------------------------|----------------------------------------|--------------------------------------------------| 
| [0.0.0.0.i0r](https://www.namebase.io/domains/i0r)   | ROOT-ZONE                                                                    | Distributed Root Zone                  | OSI-9                                            |
| [0.0.0.0.i1r](https://www.namebase.io/domains/i1r)   | LTHN-1                                                                       | LetherNet Interface Router             | OSI-9                                            |
| [0.0.0.0.i1b](https://www.namebase.io/domains/i1b)   | [OSI-1](https://en.wikipedia.org/wiki/OSI_model#Layer_1:_Physical_layer)     | Physical Layer                         | [OSI-7](https://en.wikipedia.org/wiki/OSI_model) |
| [0.0.0.0.i2q](https://www.namebase.io/domains/i2q)   | [OSI-2](https://en.wikipedia.org/wiki/OSI_model#Layer_2:_Data_link_layer)    | Data link Layer                        | [OSI-7](https://en.wikipedia.org/wiki/OSI_model) |
| [0.0.0.0.i3q](https://www.namebase.io/domains/i3q)   | [OSI-3](https://en.wikipedia.org/wiki/OSI_model#Layer_3:_Network_layer)      | Network Layer                          | [OSI-7](https://en.wikipedia.org/wiki/OSI_model) |
| [0.0.0.0.ib4](https://www.namebase.io/domains/ib4)   | [OSI-4](https://en.wikipedia.org/wiki/OSI_model#Layer_4:_Transport_layer)    | Transport Layer                        | [OSI-7](https://en.wikipedia.org/wiki/OSI_model) |
| [0.0.0.0.i4v](https://www.namebase.io/domains/i4v)   | LTHN-VPN                                                                     | Virtual Peering Network                | OSI-9                                            |
| [0.0.0.0.i5u](https://www.namebase.io/domains/i5u)   | LTHN-QEUA                                                                    | Quassi Entropy User Access             | OSI-9                                            |
| [0.0.0.0.i5n](https://www.namebase.io/domains/i5n)   | [OSI-5](https://en.wikipedia.org/wiki/OSI_model#Layer_5:_Session_layer)      | Session Layer                          | [OSI-7](https://en.wikipedia.org/wiki/OSI_model) |
| [0.0.0.0.i5d](https://www.namebase.io/domains/i5d)   | LTHN-DQEUA                                                                   | Distributed Quassi Entropy User Access | OSI-9                                            |
| [0.0.0.0.i6p](https://www.namebase.io/domains/i6p)   | [OSI-6](https://en.wikipedia.org/wiki/OSI_model#Layer_6:_Presentation_layer) | Presentation Layer                     | [OSI-7](https://en.wikipedia.org/wiki/OSI_model) |
| [0.0.0.0.i6o](https://www.namebase.io/domains/i6o)   | LTHN-6                                                                       | Interface Router                       | OSI-9                                            |
| [0.0.0.0.i7s](https://www.namebase.io/domains/i7s)   | [OSI-7](https://en.wikipedia.org/wiki/OSI_model#Layer_7:_Application_layer)  | Application Layer                      | [OSI-7](https://en.wikipedia.org/wiki/OSI_model) |
| [0.0.0.0.i7o](https://www.namebase.io/domains/i7o)   | LTHN-POS                                                                     | Layer 7 Privacy Sandbox                | OSI-9                                            |
| [0.0.0.0.iw0](https://www.namebase.io/domains/iw0)   | LTHN-PLB                                                                     | Public Load Balancer                   | OSI-9                                            |
| [0.0.0.0.i9p](https://www.namebase.io/domains/i9p)   | LTHN-POP                                                                     | IPv9 Proof of Peerage                  | OSI-9                                            |
| [0.0.0.0.ifuz](https://www.namebase.io/domains/ifuz) | LTHN-IFUZ                                                                    | Distributed Network Encryption Service | LetherNet                                        |

