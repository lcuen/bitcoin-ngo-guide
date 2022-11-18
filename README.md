**The Bitcoin NGO Guide**
============================

## Presented by [The Bitcoin Policy Institute](https://www.btcpolicy.org/) and [Human Rights Foundation](https://hrf.org/)
 
by Leigh Cuen

_How NGOs, activists, foundations, governments, and aid organizations can use bitcoin to improve their operations_

**Preface**
-----------

Over the past decade, many [nonprofit organizations](https://www.tampabay.com/archive/2003/09/15/frozen-accounts-jeopardize-learning-healing-in-gaza/) and [activist groups](https://nonprofitquarterly.org/nonprofits-can-struggle-international-bank-transfers/) from Russia to Nigeria to [India](https://time.com/3816818/greenpeace-india-bank-accounts-frozen/#:~:text=India%20froze%20seven%20bank,country's%20financial%20regulations%2C%20Reuters%20reported.) to Canada have found both their [corporate](https://nonprofitquarterly.org/nonprofits-fall-prey-de-risking-banks/) and [personal bank accounts](https://www.reuters.com/article/nigeria-protests-banking/nigerias-central-bank-freezes-accounts-of-police-brutality-protesters-idUSL4N2HT06D) frozen or confiscated for [political reasons](https://www.latimes.com/world-nation/story/2020-12-16/hong-kong-bank-accounts-frozen), often without any search warrant or due process.

Even for humanitarian and civil society workers that don’t attract legal scrutiny or censorship, banking fees, bureaucracy, and a lack of access to regulated fintech products can impede the movement of funds in a community’s most crucial hour. That’s why a growing variety of NGOs use bitcoin as a tool for [fundraising](https://voltage.cloud/blog/btcpay-server/how-to-start-a-bitcoin-crowdfunding-platform/), grant distribution, and money management.

Bitcoin is a new type of money that is not controlled by any company or government. It gives users the ability to transfer value around the world without relying on any state-issued ID. In a world with surveillance and financial repression on the rise, bitcoin can be a valuable tool for activists and humanitarian organizations.

This guide shows how a variety of nonprofit organizers and donors use bitcoin around the world and illustrates why, and precisely how, they do it. We hope it serves as a useful guide to help grant-makers, civil society groups, independent journalists, and activists understand why they might use Bitcoin, and how to do it as safely and efficiently as possible.

**Executive Summary**
----------------------

Hundreds of nonprofits and civil society groups around the world accept bitcoin donations by using _third party service providers_ for technical support, which may include custody and/or currency conversion. Some of these providers include:

### **Third party service providers**

*   [IBEXPay](https://www.ibexmercado.com/)
*   [OpenNode](https://www.opennode.com/)
*   [BitGive](https://www.bitgivefoundation.org/)
*   [The Giving Block](https://thegivingblock.com/)
*   [BitGo](https://www.bitgo.com/)
*   [Cash App](https://cash.app/help/us/en-us/6502-what-is-cash-for-business)
*   [WooCommerce](https://woocommerce.com/)
*   [Bitrefill](https://www.bitrefill.com/)
*   [Ledn](https://ledn.io/en/faq)
*   [LocalBitcoins](https://localbitcoins.com/)
*   [Buycoins](https://buycoins.africa/)
*   [Sendcash](https://app.sendcash.africa/)
*   [Paxful](https://paxful.com/)
*   [Kuna](https://my.kuna.io/)
*   [Alice-Bob](https://alice-bob.io/)
*   [Money 24](https://money24.kiev.ua/)

However useful these services may be, it’s important to remember that third-party providers carry risks comparable to a bank.

Namely: you may lose access to your funds due to government pressure or management malintent or incompetence.

Third party providers also represent a privacy risk to your organization and your donors since they have full visibility of all transactions that flow through them.

Additionally, many of these providers may simply exclude users in particular jurisdictions for a variety of reasons, such as the country being too small or controversial for global service providers to prioritize the excluded population. Examples may include Syria, Venezuela, Palestine, and remote island nations like Tonga.

To mitigate these risks, humanitarian organizations often utilize the following _self-custody tools_, which do not require a bank account or government-issued identification:

### **Self-custody tools**

*   [BTCPay Server](https://btcpayserver.org/)
*   [Electrum](https://electrum.org/#home)
*   [BlueWallet](https://bluewallet.io/)
*   [Samourai Wallet](https://samouraiwallet.com/)
*   [Nunchuk](https://nunchuk.io/)
*   [Muun](https://muun.com/)

Most people with modest Bitcoin knowledge can use the above-mentioned self-custody tools either straight out of the box or with a modest degree of education from free online resources and videos available on the tool websites. These tools (used in combination with encrypted communication apps such as Signal) can be used to complete a variety of projects that range from [international fundraising](https://www.youtube.com/watch?v=KqsM-n-e4aY) and sales to grant and scholarship distribution.

Our recommended setup for accepting bitcoin donations balances the tradeoff of convenience and third party trust by using a service called [Voltage](https://voltage.cloud/) in combination with [BTCPay Server](https://btcpayserver.org/). Voltage enables you to host a donation page running BTCPay for a small monthly fee. You need to trust Voltage to keep your payment processor up but you retain control over your funds and privacy since the keys to the Bitcoin remain in your control. With this solution, any NGO can add a BTCPay Server interface to their website to allow them to receive bitcoin donations from anywhere in the world in a censorship-resistant and privacy-protecting manner.

A guide for this setup can be found [here](https://voltage.cloud/blog/btcpay-server/btcpay-server-x-voltage-become-a-bitcoin-merchant/). For additional guidance on accepting bitcoin donations in adversarial conditions consider listening to this [Citadel Dispatch conversation](https://www.podpage.com/citadeldispatch/citadel-dispatch-e43-bitcoin-for-beginners-with-bitcoinq_a/).

Since operating one’s own bitcoin wallet requires a modest degree of technical skill, and potentially the challenges of fiat currency conversion or [group management features](https://leighcuen.com/electrum-multisig), some users prefer to combine self-custody tools with _consulting or technical support_ from organizations such as:

**Consultation providers**

*   [Bitcoin for Fairness](https://bffbtc.org/what-we-do/) (NGO)
*   [Casa](https://keys.casa/) (for-profit)
*   [Unchained Capital](https://unchained.com/) (for-profit)
*   [Bitcoin Embassy Tel Aviv](https://www.bitembassy.org/) (NGO)
*   [Human Rights Foundation](https://hrf.org/devfund) (NGO)
*   [Bitcoin Developers Academy](https://bitcoin-developers-academy.teachable.com/) (NGO)

Depending on your needs, these organizations might be able to help you create a collaborative custody solution or help you find the right tools.

All things considered, most of the bitcoin users interviewed for this report cited their primary motivations for using bitcoin as flexibility, speed, relatively low fees, low trust in or access to local banking infrastructure, and an unparalleled combination of personal privacy with transparency related to the deployment of charitable funds. We’ll explore each of these benefits at length.

**Tonga Case Study: Speed and Flexibility**
--------------------------------------------

When a [volcano erupted](https://www.scientificamerican.com/article/the-tongan-volcano-is-a-reminder-of-island-nations-vulnerabilities/) in the South Pacific kingdom of [Tonga](https://www.britannica.com/place/Tonga) on January 15, 2022, it devastated roughly 80,000 people. In addition to destroying homes and infrastructure like hospitals, roads, and airports, the eruption also [severed the local internet cable](https://www.euronews.com/next/2022/02/23/tonga-is-finally-back-online-here-s-why-it-took-5-weeks-to-fix-its-volcano-damaged-interne#:~:text=The%20Pacific%20island%20nation%20lost,that%20provided%20its%20Internet%20connection.), leaving the islanders disconnected from the outside world during the worst humanitarian disaster of their lifetime. Tongan politician [Lord Fusitu'a](https://www.parliament.gov.to/members-of-parliament/nobles/136-lord-fusitu-a), who was in New Zealand receiving medical treatment, quickly called an American friend, the bitcoin-savvy bookkeeper Josh Kimbrow. Together they launched an operation called [Airlift Airwaves](https://github.com/satoshiops/airlift-airwaves), to get aid to the island while international aid organizations stalled.

Kimbrow used [BlueWallet](https://bluewallet.io) to create a bitcoin donation address, [Github](https://github.com) to publicly document the process as they went, and his own bookkeeping business for compliant record-keeping, essentially taking Fusitu’a on as a pro bono client. They used Twitter to raise awareness, raising $50,000 worth of bitcoin in the first 24 hours, enough funds to get started immediately, then up to $125,000 over the following weeks.

They used [Crypto Blockchain Plug](https://cryptoblockchainplug.com/), Bitrefill, and Cash App to liquidate donations as fiat for vendor payments and supplies as needed. Some vendors accepted partial payment in bitcoin or full payments directly in bitcoin, while others preferred fiat. By February 3, 2022, the group was ready to start parachuting supplies to the disconnected islands. The equipment they provided included radios, water desalination equipment, and solar panels.

> “If we had done it with dollar wire transfers from the outside world to Tonga, I wouldn’t have been able to get started with parachuting supplies in such a short timeframe,” Kimbrow said. “Using bitcoin reduced fees for this process. We spent a total of $25.24 in fees across the total project for the bitcoin aspect. We’re still accounting for the banking fees and conversion fees when we needed to cash out from the project.”

Thanks to the **speed and directness** that bitcoin enabled, this grassroots aid campaign was able to get emergency relief equipment to some areas of Tonga faster than established aid organizations. Bitcoin enabled the Airlift Airwaves project to settle tables with vendors the same day. Considering they needed planes and boats to travel from Australia to the islands, where people were dying in the wake of the natural disaster, speed was priceless.

None of this is to suggest that crowdfunding is easy. This grassroots project benefited from the fact its founders already had established reputations in the cryptocurrency industry. Fusitu’a’s political background was also crucial for mobilizing the Tongan diaspora and skilled workers in other countries.

“I’ve been a moderator of [Black Bitcoin Billionaires](https://www.blackbitcoinbillionaire.com/) since early 2020. I had an established relationship with that club. So we used that as a public marketing arm for our campaign, especially because Tongans are people of color and that felt aligned,” Kimbrow said. “Bitrefill was a huge resource. Our ground crew came from all over Brisbane, Australia. We used bitcoin to buy Airbnb gift cards and Amazon Australia gift cards, so we could pay for things directly for that crew. I’d enter the gift card on the website and set it up for people in Australia to be able to pick up the supplies in the Australian store.”

The **flexibility** bitcoin provided enabled the remote team to pay individuals in any country the same day and still buy supplies in Australia, where many businesses didn’t accept organizers’ foreign credit cards, was the key to the operation's success. There is no other form of global money that could have offered this type of fast, borderless operation. One of Bitcoin’s greatest strengths is that there are people willing to accept it in return for the local fiat currency, or for goods and services, almost anywhere on Earth.

**Tax Tips**
---------------

**Always consult your local tax professional about compliant record-keeping.** Airlift Airways was able to operate compliantly by downloading CSV records from both BlueWallet and Cash App, then taking detailed notes about dates affiliated with the operation tasks. For a different example, the Human Rights Foundation (HRF) bitcoin grant recipients must submit IRS tax paperwork in order to receive the grant, as HRF is a US 501(c)3. Check what the tax liabilities and record-keeping laws are in your specific jurisdiction.

**Nigeria Case Study: Privacy and Trust**
-----------------------------------------

In November 2020, the Nigerian government froze [at least 20 bank accounts](https://www.reuters.com/article/nigeria-protests-banking/nigerias-central-bank-freezes-accounts-of-police-brutality-protesters-idUSL4N2HT06D) linked with anti-police brutality protests. Meanwhile Nigerian software developer Ire Aderinokun, one of the organizers behind the activist group [Feminist Coalition](https://feministcoalition2020.com/), said several of the donors to her grassroots movements also found their banking access restricted after charitable wire transfers. These repercussions may have been an example of banks preemptively over-complying to avoid hassle, rather than receiving specific legal orders to restrict activist donors.

Regardless of why the donor bank accounts were compromised, this created fear among protestors and activists. Feminist Coalition continued using the organization’s Nigerian bank account, without any problems, but they needed to find other ways for supporters to donate. That’s where bitcoin came in.

“We started out with a regular bitcoin wallet address, then eventually switched to BTCPay server for better privacy. We could turn that option off \[when a campaign ended\] and more easily manage \[BTCPay server\], rather than having an address that people could send money to at any time,” Aderinokun said. “We moved to BTCPay to protect the privacy of our donors... people who wanted to send it to our bank account were scared to, but they were more willing to donate pseudonymously with bitcoin. The complete control over our funds and the additional privacy that bitcoin gave us felt much safer for us.”

Accepting bitcoin enabled privacy-protecting donations, both locally and internationally, which dramatically [increased the funds](https://feministcoalition2020.com/statement-oct-22/) the activists were able to raise. As long as donors sent bitcoin from self-custody wallets, rather than exchange accounts, they enjoyed more **privacy** than traditional digital donation options. Using BTCPay server helped the activists avoid reusing the same bitcoin addresses, since BTCPay server enabled unique invoices and generates fresh addresses.

Lastly, sending money directly to the activists (instead of through a third-party organization) gave donors a stronger sense of **trust**, because people often trust individuals they can identify more than organizations like banks or institutions like Amnesty International. Feminist Coalition activists often signed their transparency reports and leveraged their professional reputations built by working in the tech industry as well. Both legal names and online pseudonyms can be used for this same purpose as long as the name has an established reputation.

As for the other tools Feminist Coalition needed to complement BTCPay server, Aderinokun said they used a combination of Instagram, Twitter, and WhatsApp for marketing, 1Password for team management of BTCPay server, and the Nigerian exchange app Buycoin for fiat liquidation as needed. She described bitcoin as a “powerful and beneficial tool” that all activists should know about.

**Privacy Tips : Lessons from Ukraine**
---------------------------------------

The bitcoin blockchain is public, meaning all bitcoin transactions are searchable. This means it can be easier to trace a bitcoin transaction than a suitcase full of dollars, so each user must take responsibility for his or her own privacy.

Activists in places like Ukraine must be especially careful about which accounts they use. If they end up living under a Russian occupation, any crypto exchange account affiliated with activities like evacuation efforts could make the bitcoin user vulnerable to the new regime. That’s why Ukrainian bitcoin researcher [Gleb Naumenko](https://thelab31.xyz/team/) recommends the following tools for enhanced privacy:

*   [Tor browser](https://www.torproject.org/download/)
*   Encrypted email services like [Proton](https://proton.me/)
*   [Burner phone](https://theintercept.com/2020/06/15/protest-tech-safety-burner-phone/) or SIM card  
    

Also try to avoid reusing the same bitcoin address. Imagine if you could create a new email address for each person you talked to. That’s possible with bitcoin addresses. This means people who know one address won’t be able to follow your activities, using the same wallet, because to the majority of the public those addresses appear unaffiliated. Our recommended setup of Voltage and BTCPay defaults to new addresses for every participant. For additional tips on bitcoin privacy tools, see:

*   [Payjoin Guide](https://docs.btcpayserver.org/Payjoin/)
*   [JoinMarket](https://github.com/JoinMarket-Org/joinmarket-clientserver)
*   [HRF Bitcoin Privacy Guide](https://medium.com/human-rights-foundation-hrf/privacy-and-cryptocurrency-part-i-how-private-is-bitcoin-e3a4071f8fff)
*   [HRF Guía para Privacidad (Español)](https://medium.com/human-rights-foundation-espa%C3%B1ol/privacidad-y-criptomoneda-parte-i-qu%C3%A9-tan-privada-es-bitcoin-8bfe61c224d1)

**Foundations : Flexibility and Transparency**
-----------------------------------------------

In addition to grassroots activists, many nonprofits and foundations also utilize bitcoin. Steven Lupien, Director of the Center for Blockchain & Digital Innovation at the University of Wyoming, added that nonprofits and [foundations](https://www.uwyo.edu/foundation/crypto/give-crypto.html) (like his own [university](https://slate.com/technology/2021/06/wyoming-cryptocurrency-laws.html)) can liquidate bitcoin by creating business accounts at cryptocurrency exchanges, just like financial firms and other for-profit entities do. His tips for organizations that want to accept bitcoin in a jurisdiction like the U.S. include:

*   Generally speaking, always take the more conservative approach when valuing digital assets and when taking notes for record-keeping. When in doubt, write transaction details down.
*   Routinely consult with your legal counsel and accounting professionals.
*   Research crypto-friendly banks and law firms, such as [Kraken Bank](https://www.kraken.com/bank), [Custodia Ban](https://custodiabank.com/), [Silvergate](https://www.silvergate.com/), [DLXLAW](https://dlxlaw.com/), [Hathaway & Kunz](https://www.hkwyolaw.com/attorney/matthew-d-kaufman/), [Crowley Fleck PLLP](https://crowleyfleck.com/biography/tara-b-nethercott/), and [Olsen Legal Group](https://www.olsenlegalgroup.com/our-team-jared-o.html), just to name a few.

One added perk of using bitcoin as a nonprofit, according to the HRF strategy associate Alex Li, is that nonprofits do not have to pay income tax nor capital gains tax on donated bitcoin. This can be a huge cost-saver, compared to individual activists in the United States who must pay capital gains tax in relation to all their bitcoin transactions.

> “Grant distributions via fiat and Bitcoin all require the recipient to comply with US tax laws by giving HRF identifying tax paperwork,” Li said. “A Bitcoin grant payment just needs a Bitcoin address. Likewise, for receiving Bitcoin, HRF just sends out a Bitcoin address to the donor, which is much faster, cheaper, and easier than a bank wire.”

Even in the United States, wire transfers can cost more than $40, depending on the bank or service provider, so bitcoin almost always offers a cheaper alternative for timely transactions.

Bitcoin can be an especially powerful tool for organizations that make international transactions. Venezuelan ex-pat Alejandro Machado, a member of the [AlumUSB nonprofit](https://alumnusb.org/about-our-work/) that allows donations to the Universidad Simon Bolivar in Venezuela, said that bitcoin was the best way to distribute grants directly to Venezuelan academics and researchers.

The nonprofit has an American bank account and must keep full records of their bitcoin transactions, for tax purposes, so this is not an example of circumnavigating sanctions. It is, however, an example of bitcoin requiring less bureaucracy and lower fees than a fiat transfer. This offers greater **flexibility**, transacting across borders as long as each participant takes responsibility for due diligence and their local tax records, plus **transparency** as to when the money is allocated. Personal relationships are often key to explanations of how the money is allocated, which is no different than fiat. The key differentiator is that it is clear to all parties whenever the money moves.

For broader context, many US-based people routinely transact with Venezuelans without bitcoin, using banking apps like [Zelle](https://www.bloomberg.com/news/features/2020-11-11/zelle-has-turned-dollar-starved-venezuela-into-a-cashless-test-lab). They simply pay higher fees and have less control over the funds than bitcoin users. Venezuelan expats in Spain, Jesus Gonzalez Sevilla and Eduardo Castillo, plus their Caracas-based partner Oswaldo Ramirez Colina, are all working on bitcoin research comparing current tools and risks.

By surveying 1,000 Venezuelans in July 2022, they found 4.9% had recently used [AirTm](https://www.airtm.com/us-en/) for payments, 4.6% had used [Binance](https://www.binance.com/en/support/announcement/360042024232), and 1.5% of respondents had used “cryptocurrencies” for payments in the past month. If 11% of Venezuelans are indeed using Bitcoin and cryptocurrency, that is a significant finding. When it came to remittances, like the type AlumUSB might send, 5.2% of Venezuelan respondents said they had recently received cryptocurrency directly to a self-custody wallet: a small but clearly growing phenomenon.

Finding a bitcoin-savvy accountant in your jurisdiction is often one of the best first steps for organizations that want to use bitcoin. In North America, a few options to consider include [Kate Waltman](https://taxeswithkate.com/), [Metrics Chartered Professional Accounting](https://getmetrics.ca/), and [MDM Financial Services](https://www.mdmfinancialservices.com/).

Do you know of a trustworthy, bitcoin-savvy accountant working in Africa, Latin America, or Asia? How about a nonprofit legal expert? Send suggestions to alex.li@hrf.org so we can update this guide with increasingly diverse recommendations.

Other international compliance experts can be found at [Lawyers without Borders](https://www.lawyerswithoutborders.org/), [Civil Rights Defenders](https://crd.org/), and [Lawyers for Good Government](https://www.lawyersforgoodgovernment.org/), just to name a few.

Furthermore, if you have any questions about bitcoin dispersal and sanctions, be sure to ask a legal professional with expertise in your particular jurisdiction to help search the [Office of Foreign Assets Control](https://home.treasury.gov/policy-issues/office-of-foreign-assets-control-sanctions-programs-and-information)’s online resources to ensure your counterparts are not affiliated with a [restricted or forbidden](https://home.treasury.gov/policy-issues/financial-sanctions/specially-designated-nationals-and-blocked-persons-list-sdn-human-readable-lists) bitcoin address. This is a part of the due diligence process beyond the banking system.

**Volatility Tips: Stablecoins 101**
-------------------------------------

The bitcoin market is volatile, so some users prefer to hold value in “stablecoins” like USDC, DAI, or USDT, which are all pegged to the American dollar. Ledn loan startup co-founder Mauricio Di Bartolomeo said that stablecoins are particularly popular among Latin American bitcoin users. However, these stablecoins rely on trust with a centralized issuer that can block, freeze, or seize funds at will. It is also important to keep in mind that these coins are only as stable as their underlying blockchains. USDC and DAI rely on the Ethereum blockchain, for example, which requires transaction fees even if the coin itself retains the $1 value. Note that you cannot send stablecoins to a bitcoin wallet address. The user will need a unique wallet address for that specific stablecoin.

“The ability to open your phone and offer a \[crypto\] address that you can receive dollar-denominated value into is giving people the power of a US bank account anywhere in the world,” di Bartolomeo said. “But stablecoins that use blockchains like Ethereum may be prohibitively expensive because of transaction fees.”

Some people might prefer to convert bitcoin into stablecoins when the bitcoin price is high, to hold that reliable dollar value, then convert just a fraction of it back into bitcoin when they need to spend it outside of an exchange. Stablecoins can be held in self-custody wallets like [Ledger](https://www.ledger.com/) or [Trezor](https://trezor.io/). Some people crowdfund with Ethereum-based stablecoins using platforms like [Endaoment](https://www.endaoment.org/orgs) or [Gitcoin](https://gitcoin.co/)

Stablecoins can be very helpful for the billions of people who live under weak or collapsing currencies. As Bartolomeo reminds us, “With knowledge of stablecoins and Bitcoin, NGOs worldwide can finally use dollars without bank accounts or opt out of the US dollar system. They now have a choice.”

**Hardware Wallet Tips: Custody 101**
-------------------------------------

One of the safest ways to store bitcoin is with a [hardware wallet](https://bitcoinmagazine.com/guides/how-to-use-a-bitcoin-hardware-wallet). It’s considered a best practice to use such a device with a microUSB cord and a power bank, so that you never need to plug it into the computer. This is called an “air-gapped” wallet.

Our recommended hardware wallet is called a [Coldcard](https://coldcard.com/). Be sure to backup your wallet using your secret backup words, often called a seed phrase, on paper or steel, then store it somewhere that it won’t get lost or stolen. These backup words can be used to recover your bitcoin among most bitcoin wallets since there is a unified backup standard. For example, as long as you keep your 12 or 24 word seed phrase, even if you lose your phone or Coldcard, you can download a new Bitcoin wallet app on a fresh phone or acquire a new Coldcard, enter the words, and still have access to your funds.

Unlike a password, a private key cannot be changed. So, warning: if you lose your seed phrase, you can permanently lose access to your funds. Consider keeping redundant backups: one option is to share the same key with multiple trusted members of an organization, but remember that anyone with access to the backup words can spend the bitcoin and transactions cannot be reversed. If someone uses the key to send bitcoin, it is permanent. Keys should not be shared with anyone who is not accountable for fiduciary duties, and generally they should be shared with as few people as possible.

**Conclusions**
---------------

In conclusion, it makes sense to use bitcoin as a donation tool when you’re **working across borders**; when you’re in a situation that **requires urgent speed**; when you would benefit from **low transaction fees**; when you are dealing with an **underbanked population** that doesn’t trust or doesn’t have access to financial service providers; or when you are an **activist concerned that the government will freeze or censor** your funds.

There are of course challenges to using Bitcoin, including the fact that it is a nascent technology with a relatively small user base, and that it is not as private as cash. That being said, educational materials are proliferating in different languages every day, and traveling with a suitcase full of dollars or with cash sewn into one’s clothes is not very practical. It can be much easier and safer to travel with the keys to one’s bitcoin on a mobile wallet, on a hardware wallet, or even memorized in a “[brain wallet](https://en.bitcoin.it/wiki/Brainwallet#:~:text=To%20create%20a%20brainwallet%2C%20use,because%20of%20fallible%20human%20memory.).”

As of today, bitcoin is the most widely-used cryptocurrency in the world. This means it is easiest to find people willing to trade it for other assets or accept it for goods and services, at least according to activists like Naumenko and Aderinokun, who have both used bitcoin to buy emergency supplies in periods of unrest. However, these days it is relatively rare to find counterparties who already know how to use the Lightning Network or bitcoin privacy tools, and there are few organizations that offer consulting or education. A notable challenge with regard to accepting bitcoin today may be getting legal and tax clarity for your work with this new currency, but the resources in this guide can be of major help.

If you are a grant-maker or NGO and would like to start incorporating bitcoin into your grant-making or fundraising process, we would recommend starting with the resources in this guide. Self-custody is an excellent goal for NGOs, especially activist ones in adversarial environments. If receiving donations through Voltage and BTCPay and storing them on the wallets mentioned in this guide proves too much of a challenge, we recommend reaching out to companies like Unchained Capital or Casa, organizations like Bitcoin for Fairness, the Bitcoin Developers Academy, or the Human Rights Foundation, or any of the consultants listed in the appendix for help.

In the end, the beauty of bitcoin is that free, open source tools offer any NGO with an internet connection the opportunity to be its own bank, today.

**Privacy Tips : Lessons from Eritrea**
---------------------------------------

Bitcoin has a scaling tool called the Lightning Network, which can make payments even faster and cheaper. A transaction that might have cost around $0.30 and taken 10 minutes can happen in seconds for a fraction of a penny, using the Lighting Network, which can be important for low-income users that live on just a few dollars a day.

Eritrean journalist and human rights activist Meron Estefanos said that many refugees in East Africa prefer BlueWallet, because this mobile wallet app is easy to use and offers Lightning invoices that work for more than an hour. Other Lightning-friendly wallets, like Muun, offer invoices (requests for payment) that must be filled in the same hour. It’s important to note that Lightning is a new technology and that standards and tools continue to change and improve every few months.

“The Lightning Network is fast and cheap, and more private than most other tools,” Estefanos said. “For us, especially refugees that rely on remittances and don’t have IDs, bitcoin can be life saving. Otherwise they are reliant on people with IDs, who generally charge an extra fee.”

Lightning transactions are not searchable in the same way that regular bitcoin transactions are, so using the Lightning Network can be an affordable way to improve privacy. Estefanos added that once the Lightning Network transaction settles to the underlying bitcoin blockchain, multi-signature custody (which BlueWallet also has) can boost security.

“With bitcoin, if you have three keys in different places, if one keyholder is tortured then the funds still are protected. Especially for LGBTQ commmunities in Africa, bitcoin will also be a great tool because those people are often persecuted,” she said.

In conclusion, she added refugees and activists are most likely to convert bitcoin into fiat currencies using local Telegram groups. If you don’t know of any such local groups, the [Lnp2pBot](https://lnp2pbot.com/) tool might help connect local Lightning Network users, depending on the region. [BTCPay server](https://docs.btcpayserver.org/LightningNetwork/) is also an excellent tool for managing Lightning transactions and connecting on [Telegram](https://t.me/btcpayserver) with other bitcoin users.

**FAQ**
-------

**Q: Isn’t using bitcoin bad for the environment?**

**A:** Any computer network that uses electricity has some environmental impact, including online banking systems. Luckily, using the Lightning Network is one of the most energy-efficient ways to send money anywhere in the world. The only electricity used in a Lightning Network transaction is the power required for the phone or laptop, there’s no additional bitcoin mining required (until the transaction finally settles to the underlying blockchain). Users can make as many Lightning transactions as they want before they finally settle it (all at once) to the bitcoin blockchain. Reference the [University of Cambridge Bitcoin Electricity Consumption Index](https://ccaf.io/cbeci/index) for more information on bitcoin electricity usage and [Amboss](https://amboss.space/) or [1ML](https://1ml.com/) for more information on the Lightning Network.

**Q: Aren’t there regulations that prohibit using bitcoin?**

**A:** There are very few jurisdictions where it is legally prohibited to send or receive bitcoin. These jurisdictions may include [Bolivia](https://www.euronews.com/next/2022/04/27/bitcoin-ban-these-are-the-countries-where-crypto-is-restricted-or-illegal2#:~:text=There%20is%20a%20complete%20ban,a%20country%20or%20economic%20zone.), [Qatar](https://freemanlaw.com/cryptocurrency/qatar-2/), [Nepal](https://www.nepalitimes.com/opinion/decrypting-nepals-ban-on-crypto/), [Ghana](https://www.bog.gov.gh/notice/digital-and-virtual-currencies-operations-in-ghana/), [Algeria](https://freemanlaw.com/cryptocurrency/algeria/), and [Bangladesh](https://tile.loc.gov/storage-services/service/ll/llglrd/2021687419/2021687419.pdf). Countries like [China](https://www.bloomberg.com/news/articles/2022-05-17/china-makes-a-comeback-in-bitcoin-mining-despite-government-ban) have restricted bitcoin usage, without banning it entirely, and [many African countries are still unclear](https://www.thomsonreuters.com/en-us/posts/wp-content/uploads/sites/20/2022/04/Cryptos-Report-Compendium-2022.pdf) on the extent of their bitcoin regulations. However, in most circumstances it is lawful to use bitcoin in the same ways that someone can use fiat, as long as users take responsibility for their own tax records and due diligence. Consult local law experts for requirements in your jurisdiction.

**Q: Isn’t bitcoin prohibitively volatile?**

**A:** According to Estefanos, Naumenko, and Aderinokun, bitcoin was actually at times less volatile and less cumbersome to convert than other currencies available in their population’s particular circumstances. The dollar price of bitcoin fluctuates, just like any asset. This usually isn’t a problem for people who want to spend modest amounts of bitcoin quickly. For institutions that want to hold bitcoin for several months or years, treating it like gold is a helpful analogy. Some institutions may prefer to use a custodial service or convert bitcoin into stablecoins, in order to more accurately predict what the dollar value will be. On the other hand, always remember that the asset is only as stable as the underlying blockchain. If the Ethereum blockchain fails, the Ethereum-based stablecoin may not offer value or liquidity when it comes time to spend that money.

**Q: Is it easy to fundraise with bitcoin?**

**A:** All fundraising requires public relations and outreach, as well as account management. It’s not as simple as making a bitcoin address, or writing an open source proposal, then expecting to receive funds. Anyone who wants to earn or gather bitcoin should know that it will require marketing and operations labor, just like any other grant program or fundraising campaign. Tap into bitcoin communities and crypto-focused publications for exposure to relevant audiences and prospective donors.

**Further Resources**
----------------------

### **Hardware retailers:**

*   [**Coinkite**](https://coinkite.com/)
*   [**DIYnodes.com**](https://diynodes.com/)
*   [**Start9**](https://start9.com/latest/)
*   [**SeedSigner**](https://seedsigner.com/)
*   [**Trezor**](https://trezor.io/)

**Bitcoin/Lightning consultants:**
-----------------------------------

*   **Contact:** k3tan@btcpay.ministryofnodes.com + https://www.ministryofnodes.com.au/ 
*   **Tutorials:** https://www.youtube.com/ministryofnodes
*   **Contact:** mario.havel@protonmail.com
*   **IRL workshop space:** https://bordel.paralelnipolis.cz
*   **Contact:** odell@bitcointv.com
*   **Tutorials:** [Bitcoin for Beginners](https://www.podpage.com/citadeldispatch/citadel-dispatch-e43-bitcoin-for-beginners-with-bitcoinq_a/) & [Accepting Bitcoin Donations](https://www.podpage.com/citadeldispatch/cd57-bitcoin-crowdfunding-and-donations-with-coinjoiner-pavlenex-and-tony/)
*   **Contact:** daxsosa@gmail.com
*   **Tutorials:** http://www.youtube.com/user/daxsosa/
*   **Contact:** btcsessions@gmail.com 
*   **Tutorials:** https://www.youtube.com/c/BTCSessions
