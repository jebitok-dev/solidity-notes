<div align="center">
  <h1 align="center">Solidity Notes</h1>
</div>

### What

- This repository consists of three documents that deal with explaining their topics.
  - **General Notes :** This is the longest one. It explains the syntax part and then whys and whats of the syntax where applicable. Sometimes also involves code examples that bring a few gotchas to the table. 
  - **Internals** : This document deals with explaining the data locations and how they can affect any gas costs. Organisation of data is also explained.
  - **Security** : This document deals with a few security vulnerabilities involved when writing smart contracts. In the end, it also has a few points on developing smart contracts. 
  - **Gas Optimisations :** This document mentions some things a smart contract developer can do to save gas costs. Security and Gas Optimsations by no means cover all exisiting topics, but they cover a few that are important.
- This resource is written for **Solidity v0.8.11**.

### Where

- I prepared these docs while learning too. Almost 80% of the information here is from the docs, but attached together with extra bit of information that makes sense and makes you remember the concept.
- Rest is from answering/asking and countless hours of browsing through Ethereum StackExchange.

### Who

- This repository can be used by people who are new to solidity but not to programming altogether. You're okay if you know what variables are and how functions are written to understand this doc.
-  **This is written with an absolute solidity beginner in mind**. But I wouldn't recommend learning programming starting with solidity.

### How

- This repository should not be used as a complete source of learning. I followed the approach below and recommend it to anyone willing to learn solidity.
  - Start at [Solidity by example](https://solidity-by-example.org/). I looked at 6/7 code examples per day and highlighted/wrote down concepts that were new.
  - Next, head to [Solidity Docs](https://docs.soliditylang.org/en/latest/). I read 1/2 topics per day that are on the sidebar. And try to look out for and learn the concepts that you noted down.
  - Now for the important part, **this doc is exactly written parallel to both the resources.** All the topics you'll encounter can be found in **general notes** in the same order.
  - I recommend using this repo, especially **general notes** **AFTER** getting an introduction to a topic with any of above resources.
- Read the **general notes** when some syntax doesn't make sense and if you want to know the whys of something you saw in the docs. Ideally, you should complete some topics in solidity by example and get familiar with that topic in docs. Then head over to **general notes** for reinforcing your concepts.
- The **Internals, Gas Optimsations** are to be read when you are tackling concepts like reference types. At some places, general notes tells you to go and check for some concepts.
- The **Security** doc assumes you've **completed the syntax part** and are now searching for good practices. It also includes some suggestions for newcomers when developing smart contracts.

### What Next : 

- This is just learning about solidity. Ethereum and EVM is a lot bigger and more complicated concept. Having an idea of blockchains in general helps a lot in understanding transactions and the adversarial environment of miners.
- Try reading [Mastering Ethereum](https://github.com/ethereumbook/ethereumbook). The Solidity part is outdated but the ideas are not.
- Now, doing is far more involving and demanding than learning but also most enjoyable. The golden rule is to **Ship code no matter how bad**. Having working products make you stand out. Deploy on testnets and get people to use it. 
- Head over to [Buildspace](https://buildspace.so/) to start developing Dapps. It helped me a lot to learn the `ethers.js` library. Also take a look at [Ethernaut](https://ethernaut.openzeppelin.com/) which is really cool and offers challenges.
- Next, head over to the [Learning section at Openzeppelin](https://docs.openzeppelin.com/learn/) to learn and use frameworks like **Hardhat** and get an introduction to writing tests.
- And finally, head over to [Openzeppelin Contracts](https://docs.openzeppelin.com/contracts/4.x/) to learn all the token standards and utilities they offer. 
- Build as many dapps as you can while also maintaining the quality part. Write more and more tests for your contracts and try to achieve good coverage. Host your working dapps and let people know they can use it. 
- And most importantly, keep up with the industry by following all the new updates and learning them. Subscribe to [Week In Ethereum News](https://weekinethereumnews.com/) and alike. Also follow @samczsun and take a look at his [blog](https://samczsun.com/) where he delves into deeper concepts.

##### Want to contribute?

- While I can say with confidence that I checked all resources while writing the docs, I'm also sure that there will be errors. 
- Please make a PR if you found any error whether conceptually wrong or a simple grammatical error.

##### Want to make me happy?

- Please leave a star 🌟 on the repo if you've found this resource helpful so that many others can discover it.

- And if you ever want to donate, here's my Ethereum Address : 

  **0x4e9606FEA76112BF275fA5764614b5847066694E**

  **ENS-1** : 0xpranay.eth

  **ENS-2** : pranayreddy.eth

## License :

<p xmlns:dct="http://purl.org/dc/terms/">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="https://github.com/0xpranay">
    <span property="dct:title">Pranay Reddy</span></a>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">Solidity Notes</span>.
</p>

