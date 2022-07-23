# Network Cryptographic Functionalities 

## Standards Used

## Data Sovereignty Functionalities

### OpenPGP Identities using quasi entropy usernames.

- [Authentication Test Cases](https://github.com/dAppServer/server/blob/main/test/auth/user.test.ts)
- [Authentication Over Insecure Channels Test Case](https://github.com/dAppServer/server/blob/main/test/auth/rest.test.ts)
- [Quasi Entropy Salt Test Cases](https://github.com/dAppServer/server/blob/main/test/crypt/quasi-salt.test.ts)

#### Overview

Foundationally the OSI-9 stack is made possible with a quasi entropy [[1]](#1) based username system; in short, it allows network operations without exposing the original input.

The network uses the resulting hash as the seed for the UUIDv5-based DNS system. At the same time, the exact identity is not guessable to the network, and the ability to comply with law enforcement via local judiciaries as required remains for every network user.

The purpose of this is to assist in protecting citizen's rights online; as the current network expands, it is getting harder and harder to help protect real lives. It is restoring power to local governments and relevant courts in a global network.

In other use cases, the network segments use hash map overrides, allowing peering between nodes and cryptographic ownership of their network segment.

#### Hash Creation Elements

- [Hash Function](https://github.com/dAppServer/server/blob/aa8b0168e9778417b55c28ddd39ff75f553054e6/src/services/crypt/quasi-salt.ts#L38)
- [Salt Function](https://github.com/dAppServer/server/blob/aa8b0168e9778417b55c28ddd39ff75f553054e6/src/services/crypt/quasi-salt.ts#L48)
- [Default Map](https://github.com/dAppServer/server/blob/aa8b0168e9778417b55c28ddd39ff75f553054e6/src/services/crypt/quasi-salt.ts#L11)

## References
<a id="1">[1]</a> 
Dénes Petz,
Quasi-entropies for finite quantum systems,
Reports on Mathematical Physics,
Volume 23, Issue 1,
1986,
Pages 57-65,
ISSN 0034-4877,
https://doi.org/10.1016/0034-4877(86)90067-4.
(https://www.sciencedirect.com/science/article/pii/0034487786900674)
Abstract: Convexity properties of entropy-like functionals on states of a finite dimensional algebra are discussed. The treatment covers both the quantum mechanical and the classical cases. The purpose is to generalize Lieb's convexity theorem and the monotonicity of the relative entropy using the Jensen inequality of operator convex functions. From the quasi-entropies defined here the quantum version of Rényi's α- entropies can be deduced.
