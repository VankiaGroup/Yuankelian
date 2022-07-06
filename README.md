## What is Yuankelian

CITA is a fast and scalable blockchain kernel for enterprises. CITA supports both native contract and EVM contract, by which enterprise users can build their own blockchain applications. CITA has a unique architecture which enables enterprise users to release all their computing resources.

- **Horizontal scalability**: With the microservice architecture, a logical node can be easily scaled to a cluster of servers. Node administrators can increase system capacity simply by adding more PC servers on high load. The administrator can even use dedicated servers to provide services for hot-spot accounts. Outside one node's boundary, nodes communicate with each other using P2P network; inside each node, microservices communicate with each other by messaging queue.

![](https://github.com/citahub/citahub-docs/blob/master/docs/assets/cita-assets/architecture.jpg?raw=true)

- **Customizable and Pluggable Components**: CITA's microservices are loosely coupled and their communications are only via the message queue. Hence, it‘s flexible to improve current components with better algorithms (such as new consensus algorithms) or more appropriate technical solutions (such as new DBs or new privacy solutions). Moreover, business logic is extremely complicated in enterprise applications. With CITA, you can easily customize your blockchain with the certain feature to fit your own business requirements.

- **High Performance**: In CITA, consensus and transaction execution are decoupled as separate microservices. The consensus service is only responsible for transaction ordering, which can finish independently before transaction execution, thus increase transaction processing performance. In additional, CITA also includes lots of other optimizations to fully utilize multi-cores and multi-servers' computing power. To this end, it utilizes the Rust language, a hybrid imperative/OO/functional language with an emphasis on efficiency.

- **Resiliency and Reliability**: CITA provides tools to backup blockchain data by taking snapshot, which can help you to resync the blockchain data in a short time. And through Rust’s language-level memory and thread guarantees and a disciplined approach to exception-handling, we can state with a high degree of certainty that our code cannot crash, hang or bomb-out unexpectedly.

- **Compatibility**: CITA supports the use of Solidity, Go, and Rust to develop smart contracts. It also supports all Ethereum development tools (Truffle, Zeppelin, Remix, etc.).

- **Chain Interoperability**: We perceive that independent blockchains are constantly emerging nowadays and even more in the future. How do these chains interoperate with each other to form blockchain network? CITA Support cross-chain communication by providing a simple cross-chain protocol currently. More explorations are undertaking in CITA, aiming to amplify the value of applications running on the various chains.

- **Engineering Experience**: There're many CITA networks running in banks, payment and insurance production environment, with Rivtower or CITA Integration Provider's technical support.  CITA has accumulated a lot of engineering experience.

## Contact us

Email: <liuyong@vankia.cn>

