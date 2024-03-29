## Fedimints as a local business-to-business medium of exchange

#### Local community business-to-business use case: Black Mountain, NC

##### Vibrant local economy
In the book One Second After, William Forstchen describes Black Mountain, NC in the quote, *"John paused and looked back down the street for a moment. I’m living in a damn Norman Rockwell painting, he thought yet again, for the thousandth time."*. William Forstchen lives in Black Mountain and describes it well. Everyone knows everyone, yet it is a town of almost 10,000 residents. The town is situated off Interstate 40 about 15 miles east of Asheville. Local businesses dominate the area including: hardware store, art galleries, restaurants and pubs, breweries, bakeries, and music venues. It is a healthy and thriving community where business from locals is supplemented with cash from tourists.

An important characteristic of Black Mountain businesses is the large amount of business-to-business transactions. Restaurants buy local baked goods; music venues, restaurants and pubs buy beer from local breweries; stores sell art and other wares from local artists and craftsmen. A high percentage of the goods sold in Black Mountain are produced locally; especially beer, coffee, and art. Currently, Black Mountain is a circular economy running over traditional payment rails and occasional bartering. 

These traditional payment rails extract value and financially monitor this vibrant local economy. This is where a fedimint can be leveraged to remove unjust surveillance and friction from the financial life blood of the local community.

```mermaid
graph TD;
   A[Brewing Supplier]-->Brewery
   Brewery-->B[Brewery Pub];
   Brewery-->Restaurant;
   Bakery-->Restaurant;
   Farmer-->Bakery;
   Farmer-->Restaurant;
   Artist-->Gallery;
```
#### Enter Fedimints - Bitcoin demoninated payment facilitators  
Fedimints are a relatively new technology that use Federated Chaumian eCash as a medium of exchange within the federated mint (fedimint). Each fedimint is its own ecosystem, however the Fedimint implementation does allow for sending funds between fedimints using the Lightning network.

Let's take a step back to a higher level to see how fedimints align with the needs of a local community's business-to-business relationships. 

##### Governance 
We need to understand how fedimints are structurally governed. Fedimints operate with Bitcoin as their reserve asset. A 'member' of the fedimint deposits bitcoin and in return receives the equivalent amount of eCash. With this eCash the member can transact with other members on the fedimint. It is a circular economy. Members can withdrawl their bitcoin by turning in their eCash. In this way it functions similar to a traditional bank and this is where the structure of the 'guardians' is critical to the success and longevity of every fedimint. 'Guardians' control the bitcoin held in reserve. Each one holds a key to a multisig wallet containing the bitcoin reserves of the fedimint. The specifics of the multisig can be configured when the fedimint is established. The Fedimint implementation has standards for the minimum number of signatures on the multisig to encourage responsible governance, but this is just a first step. This is where local community business-to-business is a great fit. We will dive deeper shortly after we cover privacy next.
   
##### Privacy 
Chaumian eCash behaves just like paper cash in your physical wallet, but over a digital medium. It is private. Your bank cannot see how you spend paper cash once you withdrawl it from an ATM. Similarly, guardians in the fedimint do not know who is sending or receiving eCash, or member balances. This differs from Bitcoin. Transactions on the Bitcoin network are public and if your address is known to belong to you, everyone can see how you are transacting with bitcoin. For some, such as the Bitwise Bitcoin ETF this makes it easy for them to attest their holdings. For individuals this is a risk, potentially to physical security in case of a $5 wrench attack.

Fedimints give us better privacy than native bitcoin in exchange for loss of control over our bitcoin. The fedimint is the custodian of our bitcoin and this requires our trust that the guardians will act responsibly and not issue more eCash than the amount of bitcoin they hold in reserve. In traditional banking, a small portion of our deposited money is held at the bank. This is known as fractional reserve banking. This is why bank runs are so detrimental to the banking system. The governance structure of the fedimint must align guardian incentives with the members to minimize the risk of fractional reserve insolvency.

##### Aligning incentives
A discussed, fedimints are not without risk. We determined the governance structure of a fedimint must align guardian incentives with the members to minimize the risk. Take for example a credit union. Board members in a credit union are elected by the members of the credit union. A similar approach can be used in a fedimint that provides services to a tight-knit local community. In the local business-to-business example, the guardians can be elected by the members. If our members are all business owners, the most trusted business owners in the community will be elected as guardians. These guardians rely on business partnerships from the members in the fedimint. It would be detrimental for them to undermine the well being of the fedimint. The incentives are aligned.

##### Monetary Attributes
Traditionally when we think of money, we think in terms of fiat currency issued by centralized institutions like the Federal Reserve or European Central Bank. Essentially we think in dollars ($). Just as in the past when we thought of money in terms of commodities like silver and gold, in the future we will think of money in terms of the digital commodity, bitcoin (&#8383;). 

For a commodity, piece of paper, or entry on a bank's general ledger to be considered 'money' it must have three attributes: store of value, medium of exchange, unit of account. A form of money typically acquires these attributes in the respective order, but we are going to start with medium of exchange because it is most relevant for our business-to-business use case, though all apply.

###### Medium of exchange
In its most simple terms, medium of exchange is the ‘medium’ in which we exchange goods and services. The most efficient means of transacting near limitless types of goods and services is for the community to agree on a common medium of exchange. This was the major public justification of Europe’s switch from individual nation-state currencies to the Euro (&euro;). In the US, we have benefited from the petrodollar, pricing of OPEC oil transactions in dollars ($). Recently both the Euro and Dollar are threatened, respectively, with Brexit and OPEC pricing oil in BRICS currencies, specifically the Chinese Yuan. The lesson to be learned from recent events is modes of medium of exchange are fluid. They change over time.

###### Unit of account
Pricing. Continuing from the OPEC example in the previous section. Unit of account is the measurement used to identify the value of a good or service. It is most efficient to have a universal unit of account. We all know the inefficiency of imperial vs metric measuring systems. How many centimeters is one foot? We can estimate, but most likely we will resort to a conversion formula. Similarly, but worse, currencies float and exchange rates constantly change, making it near impossible to do the math in your head. When OPEC priced all oil transactions in dollars, it made the dollar a world-wide unit of account. This secured the dollar’s status as world reserve currency after the 1970s collapse of the Bretton Woods System. No Dorthy, we aren’t on the gold standard anymore. Oh and more news, we are also no longer on the petrodollar system. The world-wide unit of account is up for grabs. Because civilization favors efficiency, and world war is not an option this time, bitcoin (&#8383;) is best positioned to take the title.

###### Store of value
How well does the dollar hold its value over time? How well does gold hold its value over time? This is the key measure of a money's store of value. There are two aspects that contribute to store of value: scarcity and durability. Gold does not tarnish, that is its durability. Gold is scarce and expensive to mine, that is its scarcity. Fiat currencies do not measure well in store of value. The dollar does better than most, but still it does not measure up to gold. When Satoshi conceived Bitcoin he based it on the characteristics of gold at the very foundation. We even call bitcoin creation mining. It has a fixed scarce supply of 21 million bitcoin. Bitcoin satisfied the store of value attribute at its inception. Unit of account and medium of exchange require the displacement of incumbent forms of money, and theirfore is much more difficult to accomplish.

