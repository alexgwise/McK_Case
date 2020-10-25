
# The Case for McKesson Adopting Blockchain Technology

## Overview and Origin
McKesson Corporation [MCK](https://www.cnbc.com/quotes/?symbol=MCK&qsearchterm=mck) is a publicly traded, Fortune 8 company founded in 1833 by Charles Olcott and John McKesson.<sup>1,2</sup> McKesson's business holdings have ebbed and flowed over the decades, but currently operates as the largest healthcare products distributor in North America. While many may see McKesson's size and 187 years of operations as a sign of strength, history has shown that such companies are also **ripe for disruption**.

This case study will focus on one specific aspect of the healthcare distribution operating model for McKesson and its competitors: Pharmaceutical Contract Pricing. 

## The Competitive and Operational Landscape:

McKesson is one of three major pharmaceutical wholesalers, including AmerisourceBergen, and Cardinal Health, which distribute ~92% of all the medications in the U.S.<sup>3</sup> AmerisourceBergen has a similar business model to that of McKesson, with a slightly increased focus on Specialty drugs. They have also diversified into veterinary health.<sup>4</sup> Cardinal Health also competes for the same customer base as McKesson, with the exception of its Medical Surgical practice being geared to the acute care/hospital space, while McKesson focuses on non-acute points of care. 

McKesson's business units are organized into four reporting segments:<sup>5</sup>

- U.S. Pharmaceutical and Specialty Solutions

  - Comprising over 80% of McKesson's revenue, Pharmaceutical and Specialty solutions consists of distribution sales to Health Systems, Retail Pharmacies, Specialty Clinics, and Long-Term Care facilities. As of its last earnings release, McKesson expects this segment to experience 3% to 6% growth this fiscal year.<sup>6</sup>

- Prescription Technology Solutions (RxTS)

  - McKesson's Rx Technology Solutions division hosts a suite of complimentary software systems and services for its customers. Major products include Relay Health, a 50,000 pharmacy prescription payment network, CoverMyMeds which assists pharmacies and doctors with prior authorization confirmations for prescriptions, and RxCrossroads, offering patient assistance programs and adherence solutions.<sup>7,8,9</sup>

- International 

  - A recently established reporting segment comprised of McKesson's Canadian and European operations. McKesson's Canadian business consists of both distribution operations, Well.CA, and the Rexall Pharmacy chain. McKesson Europe operations also perform distribution operations across thirteen countries, including the operation of over 2,300 Lloyds pharmacy locations.<sup>10</sup>

- Medical Surgical Solutions

  - McKesson's business unit supplying non-Rx medical equipment and supplies to non-acute customers, or put simply, all points of care with the exception of hospitals. According to its most recent earnings statement, Medical Surgical sales are expected to grow between 8% - 12% this fiscal year.<sup>6</sup>  

## The Customer Pricing Experience 

One major reason for a Pharmaceutical wholesaler's role in the healthcare supply chain is the sheer volume of pharmaceutical, medical supply, and biotech companies in the market today. With well over 1,300 companies manufacturing medications and over 180,000 dispensing locations<sup>3</sup> across the Unite States, a centralized point of ordering, billing, and delivery removes the need for each manufacturer to build out this capability. Similarly, customers don't have to log into each individual supplier's ordering system to purchase a medication.

However, manufacturers often have multiple price points for the same medication across various customer groups who have noteable purchasing power or due to regulatory requirements. So while a given medicine may have a certain list price, there are potentially an infinite combination of customer and item price points across the U.S. This creates a need for distributors to be informed of these negotiated price points in order to facilitate the terms of the contract between the two parties. Below is an illutrative example:

Let's say McKesson purchases three bottles of blood pressure medication from Teva Pharmaceuticals for $100 per bottle. Customer A has no negotiated contract price with Teva directly, and pays $100 for the drug. In contrast, Customer B has a contract with Teva, providing them with a $20 discount.

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

Because Customer B ultimately buys the product from McKesson, not Teva, McKesson must have a copy of the contract in order to ensure the customer is accurately billed. In this example, McKesson has just been forced to sell a medication below its initial cost. As a result, this delta value is ***charged back*** to Teva. When the customer sale is made, McKesson must provide various data elements to Teva including the date of sale, invoice number, national drug code, customer DEA registration information, and contract reference ID, to be reimbursed.

### The Current Technology

Distributors and manufacturers have traditionally relied on Electronic Data Interchange (EDI) files for sharing contract pricing information and for performing chargeback reconciliation.<sup>9</sup> A few of its advantages are its high degree of standardization, wide industry adoption, and relatively low cost. That said, EDI files also have several drawbacks:

- Typically processed in batches rather than real time
- Information only, not smart contract enforceable
- Not visible to the end customer
- Subject to manipulation

### The Negative Ripple Effects

Let's go back to our customer example with Customer B buying blood pressure medication. If the customer's contract price was increased $80 to $85 effective October 1st, but that information was not shared by Teva Pharmaceuticals until October 3rd, the customer will have incorrect invoice pricing for the three day period. The customer will be under-charged on their invoice, and the chargeback to Teva will be overstated. Worse, because this contract could impact potentially thousands of customers, the $5 per unit of product can add up very quickly. Teva may also take several days to inform McKesson of their unwillingness to pay the full chargeback amount. This ultimately leaves McKesson with a few choices:

- Try and get Teva to honor the old price due to the late notification
- Bill the customer for the additional $5 per unit after the original sale, resulting in a poor customer experience and possible collections issue, or
- Write off the $5 lost due to the outdated pricing information used at the time of sale

On top of the financial risk, the reconciliation of these timing differences add considerable administrative costs for both the manufacturer and distributor.

### The Opportunity and Potential Benefits


customer could also gain visibility to the contract, rather that the manufacturer exclusively communicating contract terms to the wholesaler.


* What specific financial problem is the company or project trying to solve?

* Who is the company's intended customer?  Is there any information about the market size of this set of customers?
What solution does this company offer that their competitors do not or cannot offer? (What is the unfair advantage they utilize?)

* Which technologies are they currently using, and how are they implementing them? (This may take a little bit of sleuthing–– you may want to search the company’s engineering blog or use sites like Stackshare to find this information.)

[![Blockchain](http://img.youtube.com/vi/5MArmZpzU68/0.jpg)](https://youtu.be/5MArmZpzU68 "Contracts and Chargebacks")

## Recommendations

Thankfully, as an employee of McKesson in our Contract Administration department, I'm in a good position to recommend these changes. In fact, we are in the early stages of testing our blockchain node with 
* If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!)

* Why do you think that offering this product or service would benefit the company?

* What technologies would this additional product or service utilize?

* Why are these technologies appropriate for your solution?

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
- 11: [Proprietary Data]
- Chronicled
Capital IQ
- Adam Fein Wholesaler Report
- Drug Channels
- DSCSA legislation
- 340B Act
