+++
title = "Private Hierarchical Governance for Encrypted Messaging"
authors = [
"Armin Namavari", "Barry Wang", "Sanketh Menda", "Ben Nassi", "Nirvan Tyagi", "James Grimmelmann", "Amy Zhang", "Thomas Ristenpart"
]
date = "2024-05-21"
[extra]
venue = "IEEE S&P 2024"
link = "https://arxiv.org/abs/2406.19433"
arxivlink = "https://arxiv.org/abs/2406.19433"
publishedlink = "https://doi.ieeecomputersociety.org/10.1109/SP54263.2024.00235"
auxtalktext = "rwc2024"
auxtalkvideo = "https://youtu.be/JNF3t73F-bs"
+++

The increasing harms caused by hate, harassment, and other forms of abuse online have motivated major platforms to explore hierarchical governance. The idea is to allow communities to have designated members take on moderation and leadership duties; meanwhile, members can still escalate issues to the platform. But these promising approaches have only been explored in plaintext settings where community content is public to the platform. It is unclear how one can realize hierarchical governance in the huge and increasing number of online communities that utilize end-to-end encrypted (E2EE) messaging for privacy.

We propose private hierarchical governance systems. These should enable similar levels of community governance as in plaintext settings, while maintaining cryptographic privacy of content and governance actions not reported to the platform. We design the first such system, taking a layered approach that adds governance logic on top of an encrypted messaging protocol; we show how an extension to the message layer security (MLS) protocol suffices for achieving a rich set of governance policies. Our approach allows developers to rapidly prototype new governance features, taking inspiration from a plaintext system called PolicyKit. We build a prototype E2EE messaging system called MlsGov that supports content-based community and platform moderation, elections of community moderators, votes to remove abusive users, and more.
