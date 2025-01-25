+++
title = "Robust AE With Committing Security"
authors = [
"Viet Tung Hoang",
"Sanketh Menda",
]
date = "2024-10-02"
[extra]
venue = "Asiacrypt 2024"
link = "https://eprint.iacr.org/2024/1542"
eprintlink = "https://eprint.iacr.org/2024/1542"
doi = "10.1007/978-981-96-0947-5_11"
talkvideo = "https://youtu.be/LpJtHRxgFBw?t=1421"
+++

There has been a recent interest to develop and standardize Robust Authenticated Encryption (Robust AE) schemes. NIST, for example, is considering an Accordion mode (a wideblock tweakable blockcipher), with Robust AE as a primary application. On the other hand, recent attacks and applications suggest that encryption needs to be committing. Indeed, committing security isalso a design consideration in the Accordion mode. Yet it is unclear how to build a Robust AE with committing security.

In this work, we give a modular solution for this problem. We first show how to transform any wideblock tweakable blockcipher TE to a Robust AE scheme SE that commits just the key. The overhead is cheap, just a few finite-field multiplications and blockcipher calls. If one wants to commit the entire encryption context, one can simply hash the context to derive a 256-bit subkey, and uses SE on that subkey. The use of 256-bit key on SE only means that it has to rely on AES-256 but doesn't require TE to have 256-bit key.

Our approach frees the Accordion designs from consideration of committing security. Moreover, it gives a big saving for several key-committing applications that don't want to pay the inherent hashing cost of full committing.
