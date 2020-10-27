
# The Case for McKesson Adopting Blockchain Technology

## McKesson's Origin
McKesson Corporation [MCK](https://www.cnbc.com/quotes/?symbol=MCK&qsearchterm=mck) is a publicly traded, Fortune 8 company founded in 1833 by Charles Olcott and John McKesson.<sup>1,2</sup> McKesson's business holdings have ebbed and flowed over the decades, but currently operates as the largest healthcare products distributor in North America. While many may see McKesson's size and 187 years of operations as a sign of strength, history has shown that such companies are also **ripe for disruption**.

This case study will focus on one specific aspect of the healthcare distribution operating model for McKesson and its competitors: Pharmaceutical Contract Pricing. 

## The Competitive and Operational Landscape:

McKesson is one of three major pharmaceutical wholesalers, including AmerisourceBergen, and Cardinal Health, which distribute ~92% of all the medications in the U.S.<sup>3</sup> AmerisourceBergen has a similar business model to that of McKesson, with a slightly increased focus on Specialty drugs. They have also diversified into veterinary health.<sup>4</sup> Cardinal Health also competes for the same customer base as McKesson, with the exception of its Medical Surgical practice being geared to the acute care/hospital space, while McKesson focuses on non-acute points of care. 

McKesson's business units are organized into four reporting segments:<sup>5</sup>

- U.S. Pharmaceutical and Specialty Solutions

  - Comprising over 80% of McKesson's revenue, Pharmaceutical and Specialty Solutions consists of distribution sales to health systems, retail pharmacies, specialty clinics, and long-term care facilities. As of its last earnings release, McKesson expects this segment to experience 3% to 6% growth this fiscal year.<sup>6</sup>

- Prescription Technology Solutions (RxTS)

  - McKesson's Rx Technology Solutions division hosts a suite of complimentary software systems and services for its customers. Major products include Relay Health, a 50,000 pharmacy prescription payment network, CoverMyMeds, which assists pharmacies and doctors with prior authorization confirmations for prescriptions, and RxCrossroads, offering patient assistance programs and adherence solutions.<sup>7,8,9</sup>

- International 

  - A recently established reporting segment comprised of McKesson's Canadian and European operations. McKesson's Canadian business consists of distribution operations, Well.CA, and the Rexall Pharmacy chain. McKesson Europe operations also perform distribution operations across thirteen countries, including the operation of over 2,300 Lloyds pharmacy locations.<sup>10</sup>

- Medical Surgical Solutions

  - McKesson's business unit supplying non-Rx medical equipment and supplies to non-acute customers, or put simply, all points of care with the exception of hospitals. According to its most recent earnings statement, Medical Surgical sales are expected to grow between 8% - 12% this fiscal year.<sup>6</sup>  

## The Domain of Pharmaceutical Pricing and the Customer Experience 

One major reason for a pharmaceutical wholesaler's role in the healthcare supply chain is the sheer volume of pharmaceutical, medical supply, and biotech companies in the market today. With well over 1,300 companies manufacturing medications and over 180,000 dispensing locations<sup>3</sup> across the United States, a centralized point of ordering, billing, and delivery removes the need for each manufacturer to build out this capability separately. Similarly, customers don't have to log into each individual supplier's ordering system to purchase a medication.

However, manufacturers often have multiple price points for the same medication across various customer groups, due to their negotiating strength or regulatory requirements. Therefore, while a given medicine may have a certain list price, there are potentially an infinite combination of customer and item price points across the U.S. This creates a need for distributors to be informed of these negotiated price points in order to facilitate the terms of the contract between the two parties. Below is an illustrative example:

Let's say McKesson purchases two bottles of blood pressure medication from Teva Pharmaceuticals for $100 per bottle. Customer A has no negotiated contract price with Teva directly, and pays $100 for the drug. In contrast, Customer B has a contract with Teva, where they have negotiated a $20 discount.

| Party       | Drug Cost   | 
| :---------: | :---------: |
| McKesson    | $100        |
| Customer A  | $100        |
| Delta       | $0          |

| Party       | Drug Cost   |
| :---------: | :---------: |
| McKesson    | $100        |
| Customer B  | $80         |
| Delta       | $20         |

Because Customer B ultimately buys the product from McKesson, not Teva, McKesson must have a copy of the contract in order to ensure the customer is accurately billed. In this example, McKesson has just been forced to sell a medication below its initial cost. As a result, this delta value is ***charged back*** to Teva. When the customer sale is made, McKesson must provide various data elements to Teva including the date of sale, invoice number, national drug code, customer DEA registration information, and contract reference ID, in order to be reimbursed.

### The Current Technology

Distributors and manufacturers have traditionally relied on Electronic Data Interchange (EDI) files for sharing contract pricing information and for performing chargeback reconciliation.<sup>9</sup> A few of its advantages are its high degree of standardization, wide industry adoption, and relatively low cost. That said, EDI files also have drawbacks:

- Information is typically processed in batches rather than real time
- Information only, not smart contract enforceable
- Not visible to the end customer and no customer validation of data
- Subject to manipulation

### The Negative Ripple Effects

Let's go back to our customer example where Customer B is buying discounted blood pressure medication. If the customer's contract price was increased from $80 to $85 effective October 1st, but that information was not shared with McKesson by Teva until October 3rd, the customer will have incorrect invoice pricing for the three-day period. The customer will be charged too low of a price, and the "chargeback" to Teva will be overstated. Worse, because this contract could impact potentially thousands of other customers, the $5 discrepancy per unit of product can add up very quickly. This ultimately leaves McKesson with a few choices:

1. Try and get Teva to honor the old contract price due to the late notification
1. Bill the customer for the additional $5 per unit after the original sale, resulting in a poor customer experience and possible collections issue
1. Write off the $5 lost due to the outdated pricing information used at the time of sale

As the distributor, McKesson is in the awkward position of trying to enforce a contract that it is not a signing member of. The customer would argue they should not be liable for the manufacturer's delayed communication to the distributor. The manufacturer would argue the customer has a signed copy of the contract, and was already aware of the price increase. 

On top of the financial risk, the reconciliation of these timing differences adds considerable administrative costs for both the manufacturer and distributor. You may have also noticed that the customer is not involved in communicating or validating the contract pricing the manufacturer sends to McKesson. This creates the need for additional audits and controls for the customer as well. Ultimately, everyone spends considerable time and money validating that the price they pay is correct.

## Recommendations and Potential Benefits

The challenges described above are industry wide and not unique to McKesson. However, McKesson has the opportunity to gain a competitive advantage by reducing its operating costs and improving the customer experience through the use of a blockchain network.

Blockchain technology, in its simplest terms, is a peer to peer network that utilizes a distributed ledger. Meaning, each of the participants on a blockchain network share the same set of books. Everyone has a copy, making it difficult for any one participant to forge records. Each blockchain participant has access to see the transactions entered into the distributed ledger. The term blockchain refers to how transactions are recorded and stored. Activity on a blockchain network is unchangeable with each record having a unique identifier and timestamp (block), and is linked to the previous set of transactions (chain).<sup>11</sup> 

For McKesson's purposes, a blockchain network would provide the real-time sharing of information that pharmaceutical pricing contracts lack today. Rather than transmitting EDIs unilaterally and then hoping the receiver ingests them into their respective system of record (SAP, JD Edwards, etc.), all participants would share a distributed ledger on the blockchain network. In our earlier example, if Teva raises the price of a drug for a particular customer, that contract update would be shared with the customer and distributor in near real time. This addresses some shortcomings in the current EDI process:

- Eliminates communication delays
- Ensures everyone's version and timing of contract changes are in sync
- Increases customer's confidence in the pricing shown in the distributor's ordering system

**But wait! It gets better!**

Blockchain networks are also able to use smart contract protocols. These smart contracts can help verify and enforce the terms of a contract in a digital manner.<sup>12</sup> Going back to our original example again, a smart contract rule could be established where pricing changes are made effective on or after the timestamp of the blockchain transaction. This would prevent manufacturers from communicating information that would attempt to impact previous customer invoices. Similar rules could be put in place requiring confirmation of contract terms from both the customer and manufacturer before changes take effect. 

![](https://github.com/alexgwise/McK_Case/blob/main/customer%2C%20distributor%2C%20manufacturer.jpeg)

*Image courtesy of Chronicled.com*

With the addition of smart contract capabilities, a few more advantages have been added to the list:

- Provides the customer a voice in ensuring accurate contract pricing
- Greatly reduces administrative costs in reviewing and enforcing contract terms
- Increases chargeback payment speed from the manufacturer to the distributor

## Next Steps

Thankfully, as a leader in McKesson's Contract Administration department, I'm in a good position to help act on these recommended changes. In fact, my team and I are in the early stages of testing a blockchain network with the Onmark customer purchasing group, and pharmaceutical manufacturer, Genentech.<sup>13</sup> The Mediledger Network, supported by Chronicled<sup>14</sup>, represents our baby steps into this exciting technology. Based on the reasons outlined in the recommendations section, it is our hope that this results in a cleaner, more efficient, and cost effective approach that ultimately benefits our patients and communities. 


## Cool, a video recap!

Finally, if this was TLDR, please check out Chronicled's YouTube video, which gives a very nice description of the current opportunity and benefits. I'm excited to be part of this journey.

[![Blockchain](http://img.youtube.com/vi/5MArmZpzU68/0.jpg)](https://youtu.be/5MArmZpzU68 "Contracts and Chargebacks")

## Works Cited

Sources: 
- 1: [Fortune.com](https://fortune.com/company/mckesson/fortune500/)
- 2: [McKesson History](https://www.mckesson.com/About-McKesson/Our-History/)
- 3: [Healthcare Distribution Alliance](https://hda.org) 
- 4: [AmerisourceBergen](https://www.amerisourcebergen.com/about-who-we-are)
- 5: [McKesson Investor Relations](https://investor.mckesson.com/news/financial-news/2020/McKesson-Realigns-Organizational-Structure-to-Better-Serve-Customers-and-Patients-While-Optimizing-Growth/default.aspx)
- 6: [Fiscal Q1 Earnings Release](https://s24.q4cdn.com/128197368/files/doc_financials/2021/q1/MCK-Q1FY21-Earnings-Call-Slides-Final.pdf)
- 7: [Relay Health](https://www.mckesson.com/About-McKesson/Businesses/RelayHealth/)
- 8: [CoverMyMeds](https://www.covermymeds.com/main/)
- 9: [RxCrossroads](https://www.mckesson.com/About-McKesson/Businesses/RxCrossroads/) 
- 10: [McK Europe](https://www.mckesson.eu/mck-en) 
- 11: [EDI](https://www.edibasics.com/what-is-edi/)
- 11: [Blockchain 101](https://www.computerworld.com/article/3191077/what-is-blockchain-the-complete-guide.html)
- 12: [Block Geeks](https://blockgeeks.com/guides/smart-contracts/)
- 13: [Forbes](https://www.forbes.com/sites/rachelwolfson/2019/05/02/pfizer-and-other-healthcare-companies-aim-to-bring-blockchain-based-chargeback-protocol-to-market/#50ceea31f5b3)
- 14: [Chronicled](https://www.chronicled.com/chargebacks)
