---
authors:
- admin
- 吳恩達
categories:
- Demo
- 教程
date: "2020-12-13T00:00:00Z"
draft: false
featured: false
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ""
  placement: 2
  preview_only: false
lastmod: "2020-12-13T00:00:00Z"
projects: []
subtitle: "Welcome \U0001F44B We know that first impressions are important, so we've
  populated your new site with some initial content to help you get familiar with
  everything in no time."
summary: "Welcome \U0001F44B We know that first impressions are important, so we've
  populated your new site with some initial content to help you get familiar with
  everything in no time."
tags:
- Academic
- 开源
title: Welcome to Wowchemy, the website builder for Hugo
---

# **Field Notes from CBER Crafting the Cryptoeconomy Conference, Hosted by Columbia University, New York, United-States, 25-26 October 2024[^1].**

Amit Chaudhary \- Labyrinth and Gillmore Centre at Warwick Business School, University of Warwick.

I was invited by the conference organisers to speak on the compliant-privacy research titled *Labyrinth[^2]*. I decided to attend without hesitation because the conference organisers and the research group CBER are among the premier crypto research groups. It was a two-day conference sponsored by the Uniswap Foundation and Avalanche.  
The conference was organised by academics who have published extensively or have significant exposure to crypto-economics research. Since I have been engaging with various academic circles through some of my working papers and professional experience in crypto, I was pleased to find that I could fully engage with both the written and unwritten aspects of the discussions at the conference.  

The organisers did a commendable job by separating the event into workshop days and research days. The first day featured very interesting industry conversations instead of a covering summary of the topics. Second day was focussed on research papers.   
 Although there were occasional outbursts of "crypto maximalism" sentiments, they were quickly overshadowed by discussions focused on the still-evolving understanding of crypto's long-term prospects within the economics and finance professions. Notably, the conference addressed key bottlenecks in the crypto industry, fostering expert discussions and providing valuable opinions.  

 Here is not an exhaustive list, but I found them the main focus of the conference. 

# **Die MEV Die \-** 

The MEV (Miner Extractable Value) problem has been around for a while in public blockchains, but recent developments have accelerated progress. Professor Ciamac Moallemi classification of in-protocol and out-of-protocol MEV solutions provides a valuable framework for understanding the different approaches to addressing this issue. DeFi (Decentralised Finance) is a key area of focus for MEV due to the potential for real economic rent extraction in use cases such as trading, lending, and collateral liquidations.  
The idea of renaming MEV to EV (extractable value) has been proposed by Brad Bachu, at Uniswap Labs, reflecting the broader applicability of the concept beyond miners. Research has progressed significantly since the Flash Boys 2\.0[^3] paper, and the fundamental constraints in MEV mitigation are becoming clearer. The focus has shifted towards MEV tax[^4], application-specific MEV capture, and the realisation that applications can extract economic value from the MEV supply chain.  
The idea that apps are benevolent and can share MEV benefits with end users intrigues me. The entry barriers are high for new protocols such as monopolies and oligopolies, and it would be challenging to convince protocols to scare rents without competition. I worry that this might someday represent the classical web2-like market structure, where few apps dominate the market.   

A remarkable feature of the crypto space is its rapid progression from research to product development. Unlike traditional financial markets, there is no need to wait for exchange permissions, asset listings, or regulated counterparties. The Ethereum Foundation’s presentation on MEV, led by Julian Ma, provided a simple explanation and emphasized Ethereum's commitment to neutrality in MEV profit shares.  

Several project presentations at the conference caught my attention. Sorrela's off-chain sequence commitment bears similarities to other presentations focused on DEXs, including Uniswap and Intents. Uniswap Labs and foundations presented updates on Uniswap v4 hook design and Uniswap x. However, solver-driven architectures like Cowswap, Uniswap, and 1 inch raise concerns regarding payment order flow (PMOF) and adverse selection.  
Professor Joel Hasbrouck's presentation highlighted the subtle fact that CeFi (Centralized Finance) is operating effectively, with end-user prices and welfare not significantly compromised. This raises the question of what value DeFi and DEXs can bring to near efficient markets with 100ms latency. Blockchain scaling bottlenecks remain a challenge, and Layer 2 scaling solutions are making progress, but decentralization constraints prevent the achievement of 100ms latency. A presentation by Professor Mallesh Pai on Intents research[^5] closely resembles the PMOF market structure found in traditional finance being discussed by Professor Hasbrouck's as well. The market structures of UniswapX and Cowswap are akin to those of wholesale markets. This raises an ongoing question for researchers: does this similarity indicate comparable efficiency in decentralised exchange (DEX) trading versus retail flow trading in traditional markets?   

Professor Campbell Harvey's presentation on DeFi was particularly insightful. His lectures on DeFi are highly regarded for their accessibility to a wide range of audiences, and his book on DeFi[^6] is recommended reading. Despite the rapid pace of innovation in DeFi, Harvey's book retains its value as a foundational resource.

#  **Privacy can't be done without compliance \- **

One of the noteworthy features of the conference was its emphasis on privacy. The majority of attendees, including conference organizers, recognized privacy as a significant obstacle to crypto adoption. However, a challenge arose: how to strike a balance between regulatory compliance and providing privacy? The Tornado Cash and Ethereum censorship resistance paper[^7] sparked numerous questions from the audience.  
While the negative impact of the Tornado sanctions was evident, there was a lone builder who continued to develop blocks containing Tornado transactions. Remarkably, this builder was one of the largest in the Ethereum ecosystem, highlighting the fragile state of Ethereum censorship, as it relied heavily on a single individual. A key takeaway was that without regulatory compliance, we may face a future where builders reject transactions from privacy-focused applications.  

Vitalik's co-authored paper presentation on privacy pools[^8] by Prof. Fabian Schar, which utilised association sets based on zero-knowledge proofs, offered a compelling framework for regulatory compliance in privacy pools. While the audience was initially impressed, subsequent questions revealed that this was not the ultimate solution for compliance.  
A positive aspect of the conference was a beginner-level class on zero-knowledge, led by NYU professor Benedikt Bünz, which used clear examples to illustrate the privacy paradigm. Additionally, I presented the Labyrinth protocol, advocating for privacy without liquidity fragmentation while maintaining regulatory compliance. I introduced the concept of Decom (Decentralized Compliance), which allows for selective disclosure of secrets[^9] at the user's discretion.

# **Restaking is not well understood.** 

During the Eigen Layer[^10] team's 30-minute presentation on restaking, there were significant interruptions, indicating a disconnect between theoretical discussions in crypto-economics and the practical implementations by practitioners. However, this should not be a cause for concern, as restaking remains a controversial topic with numerous unanswered questions regarding its risks and potential vulnerabilities within its economic system. I must commend Brett from Eigen Layer for providing clear schematics of the new Eigen Layer security model. At this early stage, we have yet to fully grasp the true impact and risks associated with restaking.

# **Notable Mentions:** 

There was a Circle Insight Best Paper Award given for an excellent tokenomics paper[^11] by Cong, Li, and Wang. The presentation by Professor Ye was truly captivating, akin to the level of a master orator. I believe it was the best presentation, tied with Professor Bruno Biais's talk on why cryptocurrencies matter. Whether it's as a hedge against government spending or as a fundamental means of sustaining network effects, both presentations provided essential insights into what drives the fundamental value of cryptocurrencies. 

Tim Roughgarden's panel on the economic limits of consensus[^12] effectively summarised their complex paper into just three slides. Ed Felten presented an overview of rollups and graciously commented on some new upgrades to Arbitrum's designs, particularly regarding the decentralisation of sequencers and the transaction ordering mechanism. I had a fascinating conversation with a professor about rollups and centralization risks. I think L2Beat's rollup stages will be beneficial. However, most rollups are currently at an early stage of decentralisation.

Special thanks to Fahad and Andreas for their dedication, not only in organising but also in presenting fundamental concepts and key design principles of DEXs. I was especially pleased I didn’t miss Agostino Coppini’s, as I had the chance to hear his keynote on DeFi challenges just a few weeks ago at Warwick. The conference concluded with the announcement of research grants of up to $50,000 for research proposals. I must say this is the best indication of research integration with the crypto ecosystem because, as people say, that crypto zeitgeist starts with grants and community\! 

[^1]
