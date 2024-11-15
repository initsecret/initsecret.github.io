+++
title = "Ask Your Cryptographer if Context-Committing AEAD Is Right for You"
authors = [
"Mihir Bellare",
"John Chan",
"Paul Grubbs",
"Viet Tung Hoang",
"Julia Len",
"Sanketh Menda",
"Thomas Ristenpart",
"Phillip Rogaway"
]
date = "2023-03-28"
[extra]
venue = "Real World Crypto 2023"
venuelink = "https://rwc.iacr.org/2023/program.php"
link = "https://youtu.be/Xh849Ij3lhU?t=2767"
talkvideo = "https://youtu.be/Xh849Ij3lhU?t=2767"
talkslides = "/talks/rwc2023/slides.pdf"
+++

This talk will make the case, on behalf of a group of authors of many of the recent results on commitment in AEAD, that the community should prioritize and standardize AEAD designs that achieve commitment to the key, associated data, and nonce. We call this context commitment. The main benefit of such schemes is that they preclude practitioners from having to make choices about what parts of the context should be committing. While context commitment has not yet seen the same kind of attacks in practice as key commitment, we expect them to be discovered and, to get ahead of attackers, standardization efforts should therefore target context commitment. We will start our presentation by defining context commitment [BH22], highlighting in particular how it is not formally implied by key commitment. We next discuss new attacks that exploit this gap, including showing context-commitment attacks on recently proposed key commitment-secure schemes [Kra19, §3.1.1], [ADG+22, §5.3], and [D+22]. These hint at a rich landscape of possible attacks, and we briefly discuss frameworks that explore this landscape [BH22,CR22,MLGR22]. Finally, we provide an overview of recent proposals for new AEAD schemes that achieve context commitment, and discuss avenues for future work.
