+++
title = "Flexible Authenticated Encryption"
authors = [
    "Sanketh Menda", "Julia Len", "Viet Tung Hoang", "Mihir Bellare", "Thomas Ristenpart"
]
date = "2023-10-04"
[extra]
link = "https://www.nist.gov/video/third-nist-workshop-block-cipher-modes-operation-day-2"
venue = "The Third NIST Workshop on Block Cipher Modes of Operation 2023"
venuelink = "https://csrc.nist.gov/Events/2023/third-workshop-on-block-cipher-modes-of-operation"
talkvideo = "https://www.nist.gov/video/third-nist-workshop-block-cipher-modes-operation-day-2"
talkslides = "/talks/nist2023/slides.pdf"
extendedabstract = "https://csrc.nist.gov/csrc/media/Events/2023/third-workshop-on-block-cipher-modes-of-operation/documents/accepted-papers/Flexible%20Authenticated%20Encryption.pdf"
+++

We define and build a new type of AEAD scheme that we call flexible. Flexibility is intended as an answer to the growing list of desired security and performance features for future AEAD standards. Rather than a scheme per requirement, we offer a single scheme that flexibly incorporates multiple requirements, yet in a unified, systematic, and performance-optimal way. Mandatory for our definition are to provide classic unique-nonce AE security and, importantly and more novel, context commitment; then additionally to allow keys and nonces of arbitrary length. Beyond this, the scheme is configurable through an application-chosen input called a configuration. Via this input, one says what further or advanced security or performance attributes one wants; for example, misuse resistance, nonce-hiding, preservation of length, or parallelizability. The choice can be made dynamically and the scheme will provide the chosen set of attributes without changing the key. In providing a flexible scheme, we take a clean-slate approach. Our Flex scheme is built from a single permutation. Our implementations show that, for each configuration, the performance of Flex is competitive with that of current, dedicated schemes that directly and only provide the features named in that particular configuration.
