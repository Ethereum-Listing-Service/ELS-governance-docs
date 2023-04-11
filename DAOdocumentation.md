# ELS DAO Documentation
  
### Table of Contents
  
**-Introduction**  
**-ELS Architecture**  
**-ELS Token Utility and Distribution**  
**-Governance Process**  
**-Staking Mechanism**  
**-Virtuous Cycle**  
**-Security and Zero-Knowledge Proofs**  
**-Use Cases**  
**-Future Developments**  
**-Conclusion**  

## Introduction <a name="introduction"></a>

ELS (Ethereum Listing Service) is a decentralized on-chain listing service protocol built on Ethereum. 
Its mission is to address current market issues, such as information opacity, low trust, and disorganized classification, 
by creating a more transparent, secure, and efficient information management system. ELS offers a streamlined, permissionless, 
and community-governed platform for organizing and accessing information, tackling information disarray 
and ineffective categorization within the blockchain ecosystem.
  
  
  
## ELS Architecture <a name="architecture"></a>

ELS has created ERC-6150, a hierarchical B+ tree-like structure for NFTs, enabling the dynamic representation of multiple information categories directly through smart contracts. This feature allows users to effortlessly locate the information they need, without worrying about navigating complex directories. Moreover, the Decentralized Autonomous Organization (DAO) is in charge of proposing and approving new categories, as well as managing any invalid information to ensure a transparent and equitable ecosystem. This robust framework promotes user participation and enables the community to play a significant role in the platform's operations.



## ELS Token Utility and Distribution <a name="token-utility"></a>  

The ELS token plays a crucial role in the ELS ecosystem, serving multiple purposes and providing various utilities. Below are the primary functions and use cases of the ELS token:  
  
**Governance:**  
ELS token holders can participate in the platform's decision-making process by voting on proposals and updates. This allows the community to have a direct influence on the platform's development and direction.
  
**Staking:**  
Users are required to stake ELS tokens when creating a post on the platform. The staking mechanism helps ensure content quality and adherence to community guidelines. Users can retrieve their staked tokens if their content is deemed compliant, while tokens from non-compliant content may be confiscated and distributed among users who reported the content.  
  
**Incentives and Rewards:**   
ELS tokens can be distributed as rewards to users who actively participate in community governance, contribute valuable content, or report non-compliant content. This incentivizes users to contribute positively to the platform and maintain a healthy ecosystem.  









## Governance Process <a name="governance-process"></a>
The ELS DAO governance process is as follows:

1. **Create Proposal:**   
Community members create governance proposals and submit them to the ELS DAO.    
2. **Proposal On-Chain:**   
The proposal is recorded on the blockchain to ensure its immutability.    
3. **Community Voting:**   
ELS DAO members vote on the proposal, expressing their support or opposition.    
4. **Zero-Knowledge Proof Generation:**   
The voting results are generated through a zk-verifier, ensuring the results' authenticity and verifiability.    
5. **Verify Voting Results:**   
The zk-verifier validates the zero-knowledge proof on-chain, ensuring the voting results are genuine.    
6. **Update Governance Status:**   
Based on the validated voting results, the ELS DAO's governance status is updated accordingly.    
7. **Execute Proposal:**   
If the proposal receives sufficient support, the proposed changes are executed and take effect.    


## Staking Mechanism <a name="staking-mechanism"></a>
To ensure the compliance of ELS community content and incentivize users to adhere to community guidelines, the ELS DAO implements a staking mechanism based on the ELS token. The staking mechanism is detailed as follows:

1. Users are required to stake a certain amount of ELS tokens in the ELS DAO's pool when posting content. The purpose of staking is to encourage users to post compliant content and follow community guidelines.
2. If five (exact number to be determined) whistleblowers report and successfully prove that a post contains inappropriate content, such as child pornography, organ trafficking, or drug dealing, the user who posted the content will have their staked ELS tokens confiscated.
3. The confiscated ELS tokens will be distributed evenly among the whistleblowers as a reward. This mechanism aims to encourage users to actively monitor and report non-compliant content, maintaining a healthy community environment.

If, after investigation, the content is deemed compliant, the staked ELS tokens will be returned to the user who posted the content.
By implementing this staking mechanism, the ELS DAO aims to encourage users to follow community guidelines, reduce the spread of illegal and immoral content, and foster a healthy, orderly environment.
  
## Virtuous Cycle <a name="virtuous-cycle"></a>
By implementing the ELS (Ethereum Listing Service) staking mechanism, we aim to promote a virtuous cycle within the community. The following are ways to achieve a virtuous cycle through the staking mechanism:

1. **Incentivize Compliant Content:**  
By requiring users to stake ELS tokens when posting content, they are encouraged to post high-quality, compliant content. Users can only reclaim their staked tokens if the content is deemed compliant.
  
2. **Reduce Harmful Information:**  
The staking mechanism increases the cost of posting harmful content, reducing the likelihood of spreading illegal and immoral content.  

3. **Community Self-Monitoring:**  
By rewarding whistleblowers, the system encourages community members to actively participate in monitoring and reporting non-compliant content. This self-monitoring helps maintain community order and safety.  

4. **Protect Vulnerable Groups:**  
By combating harmful content, such as child pornography, organ trafficking, and drug dealing, the ELS DAO helps protect the rights of vulnerable groups and uphold social justice and fairness.  
  
5. **Establish Trust and Reputation:**  
A virtuous cycle within the ELS community improves its reputation, attracting more users and encouraging existing users to value and trust the community.  
  
In summary, by implementing the staking mechanism, ELS aims to create a healthy, orderly communication environment that encourages the posting of high-quality content and promotes a virtuous cycle within the community.

  
## Security and Zero-Knowledge Proofs <a name="security-zkp"></a>  
ELS DAO management includes two essential components to ensure its decentralization and security:  

1. **Governance voting validation using zk-verifier:**   
ELS's governance contract integrates a zero-knowledge proof (zk) verifier to validate the community voting results provided by the oracle. By leveraging zero-knowledge proofs to obtain proposal voting results, we ensure a more decentralized voting process without centralized methods such as snapshot. 
  
2. **Distinguishing official and unofficial retailers with zero-knowledge proofs:**    
ELS employs zero-knowledge proof technology to create a prover on the front-end, differentiating between official and unofficial retailers. By utilizing zero-knowledge proofs, ELS allows users to identify trustworthy official retailers while maintaining content integrity and authenticity.  
  
The combination of these two components results in a more secure, transparent, and decentralized ELS DAO management, offering users a higher level of trust and an improved overall experience.
  
    
## Use Cases <a name="use-cases"></a>  
With its versatile nature, ELS can be applied in diverse fields, including but not limited to:  
  
1.**Decentralized Social Networks:**  
ELS can be used to power decentralized social networks, where users can publish and share content without fear of censorship or restrictions from a centralized authority.  

2.**Product Listing Platforms:**  
ELS can facilitate the listing and sale of products without relying on a centralized marketplace, promoting fair competition and access to a diverse range of goods.  
  
3.**NFT Marketplaces:**  
ELS can be utilized to create a transparent and fair system for organizing and categorizing different types of artwork, enabling artists and collectors to engage in decentralized transactions.  
  
4.**Publishing Platforms：**  
ELS can serve as a decentralized platform for sharing and accessing various types of information, such as news, opinion articles, and educational content, without the interference of central authorities.  
  
5.**Job Listing Platforms:**  
ELS can be used to post job listings in a decentralized manner, ensuring that employers and job seekers can connect without the need for a centralized authority or platform.    
  
## Future Developments <a name="future-developments"></a>  
As the volume of listing data grows, ELS plans to move its storage from the L1 smart contract to more scalable storage solutions, such as Ethereum native storage layer, EthStorage, or IPFS. The category structure and DAO governance will remain on Ethereum L1 to ensure the platform's decentralization.  
  
In conclusion, ELS (Ethereum Listing Service) is a decentralized on-chain listing protocol that addresses the challenges of information organization and access on the blockchain. By leveraging ERC-6150, its custom hierarchical B+ tree-like structure, community-driven governance, and a wide range of applications, ELS aspires to make a lasting impact on the Ethereum ecosystem and drive the future of decentralization.  
