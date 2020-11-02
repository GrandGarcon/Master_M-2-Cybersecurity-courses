# researching the paper : [Griefling Penalty and countermeasures](https://arxiv.org/pdf/2005.09327.pdf).
Complete Credits to the above paper and a lot of the sentences are taken "as it is". 

## 1. Context : 

How to avoid the attacks done due to the malicious behaviour by the intermediate , third party verifiers on the payment channel network .it does not comprise the transaction but cretes denial of service by the adversary node command the particular channel , or can even decrease the  lockdosn time . 

given that in an PCN ,each of the corresponding nodes being utilised as an channel , they have possiblity of implementing the  parameters payment channel  like  lockout time , sending / forwarding payment requests etc. here it will cover the sybil behaviour of following two categories 

1. trying to stalling network : Adversary controlling sender and receiver of payment requests , not allowing intermediaries to accept the transactions 

this can be done by ensemble of nodes being in connection of the main sender , the will either make it more complex by diverting the transactions into multiple 


2. removing the competitior with higher channel capacity.





3. stalling networking using the intermediary choking point : 




thus the possible solution being thoght of is to make sure that the attacker has to pay an unbearable  penalty everytime  it tries to do an attack , or to implement an wave   based consensus  algorithm that tries to restrict the forwarding of the maliciou payment request more than once 



thus paper tries to create upgraded version of the HTLC with penalty for griefing . for this , we  will try to understand the notations of the Payment channel attacks and  what HTLC pays the role in the lightening network .


first version of counterting  attack implementation of GP:

here we will be doing the tweaks , the penalty is the time delay that has to be generated  in case the intermediate node is massively forwarding the transactions between the nodes. 

but still we have the problem of "Reverse griefing" this is caused due when the contract tries to malign the terms of the offchain contract and getting it intentionally rejected on the receiever end , and after maximum number of attemps , the sender will have to pay ht etransaciton penalty .


### Parameters being used :

-  Rate of Griefing penalty : this will be deducted as compensation from the balance of the node responsible for the griefing.

- Routing attempt Cost : this will try to probe to possible paths that will be able to route the transactions. 



### Some salient characterstics 

#

- here the protocol tries to blind the value 