+++
title = "Context Discovery and Commitment Attacks: How to Break CCM, EAX, SIV, and More"
authors = [
"Sanketh Menda",
"Julia Len",
"Paul Grubbs",
"Thomas Ristenpart"
]
date = "2023-04-26"
[extra]
venue = "Eurocrypt 2023"
link = "https://eprint.iacr.org/2023/526"
eprintlink = "https://eprint.iacr.org/2023/526"
doi = "10.1007/978-3-031-30634-1_13"
talkvideo = "https://youtu.be/FTxSze5TfIo?t=1280"
+++

A line of recent work has highlighted the importance of context commitment security, which asks that authenticated encryption with associated data (AEAD) schemes will not decrypt the same adversarially-chosen ciphertext under two different, adversarially-chosen contexts (secret key, nonce, and associated data). Despite a spate of recent attacks, many open questions remain around context commitment; most obviously nothing is known about the commitment security of important schemes such as CCM, EAX, and SIV.

We resolve these open questions, and more. Our approach is to, first, introduce a new framework that helps us more granularly define context commitment security in terms of what portions of a context are adversarially controlled. We go on to formulate a new notion, called context discoverability security, which can be viewed as analogous to preimage resistance from the hashing literature. We show that unrestricted context commitment security (the adversary controls all of the two contexts) implies context discoverability security for a class of schemes encompassing most schemes used in practice. Then, we show new context discovery attacks against a wide set of AEAD schemes, including CCM, EAX, SIV, GCM, and OCB3, and, by our general result, this gives new unrestricted context commitment attacks against them.

Finally, we consider restricted context commitment security for the original SIV mode, for which no prior attack techniques work (including our context discovery based ones). We are nevertheless able to give a novel O(2^(n/3)) attack using Wagner's k-tree algorithm for the generalized birthday problem.
