- Revision: How does a network distributed system compare to one running solely on one cpu?
- Define
  - Node
  - Link
  - Router
  - Bandwidth
  - Bursty-ness
  - Latency
  - Jitter
  - Buffer
  - Protocol
  - Multiplexing
  - Federated system
  - Horizontal abstraction 
  - Vertical abstraction
  - Layering in protocol design

- What is multiplexing? Define and give a non-networking (non-lecture) example of: 
  - Time division multiplexing
  - Frequency division multiplexing (hint: use something analogous to frequency)
  - Statistical multiplexing
- Outline how to implement time division multiplexing?

- Why can't we just connect every computer to every other?
  - How do we bypass this problem (big O estimation would be a good idea here :) ) 
- What are the two types of described switching networks and what is the main unit of transfer in each?
  - Give a use case where each is optimal
  - Give a use case where each is highly suboptimal
- Why would a p2p file sharing protocol like bittorrent not work well in a circuit switching network? (Hint think about the costs involved in each network flow and how long each flow exists for)

- Discuss the Internet networking stack
  - What is it
  - Why does this make it simpler to build each part of the system?

- Why when transporting a box of diy electronic parts from China to the UK is it likely that it makes most of the journey inside a ISO container?
  - Does a similar reason apply to why IP is used as a common transport layer in networking?
  - Can you imagine a scenario where IP would not be a good fit?

- Outline the internet :)
  - What kinds of organisations does a packet traverse travelling from Cambridge University to MIT?
  - Discuss the how traffic may differ within these organisations and if it may be possible to exploit that.

- What is the bandwidth delay product and why is it a useful measure for system design?

- Poke around at mininet if you want :)
