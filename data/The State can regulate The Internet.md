---
title: The State can regulate The Internet
type: argument
---

[[uses:The State]], whether it be a [[mention:Socially Constructed State|social illusion]] or [[mention:Weber's State|organization with monopoly on violence]] can, through either its control of people or territory, influence the internet. There are multiple ways states have been known to do this, but no strategy is entirely perfect when it comes to what the internet was made to do: connect everyone in the world with everyone else. Here are the strategies:

 - Corporate Regulation
   - This exploits the fact that when it comes to services run on the Internet, corporations typically are the primary force that runs a service. (And currently, the most popular). Since corporations are typically subject to state influence, this is an avenue by which the state can control the internet.
     - Example: Section 230, Any kind of regulation of corporations that effects usage of the internet.
     - Circumvention: Services that are not run by corporations native to the hostile state, or not run by corporations at all (as is the case for Federated platforms like Mastodon and Matrix, or P2P networks like Bittorrent or IPFS) are not effected by corporate regulation.
 - Domain Name Seizure / Asset Forfiture
   - This exploits the Legal Framework around the Domain Name System, a system that is managed in part by the non-profit ICANN, as well as individual countries that own their own Top-Level Domains (TLD). States have sovereignty over domain names registered in their territory or using TLDs managed by the country in question. Thus, if a state does not like a domain name registered in a country, it has the potential to be taken by the state.
     - Example: https://en.wikipedia.org/wiki/Operation_In_Our_Sites
     - Circumvention: Domains that are not registered in the hostile state, or don't use DNS (such as TOR .onion links, or Ethereum's .eth links) are not affected. Also, this method is not effective for communication protocols that do not require domains. (i.e. P2P networks)
 - Country-Wide Firewall
   - This is more powerful than the other two methods and exploits the fact that Internet infrastructure requires land, and land is controlled by a State, thus the infrastructure can be controlled by the state which allows for blocking of sites. These can range from simple blocks of domains or IP addresses, to advanced deep-packet inspection filters and active probing of suspicious connections.
     - Example: Russia's firewall, Iran's firewall, Great Firewall of China (GFC)
     - Circumvention: This is still an active field of research. For simple firewalls that block just a few IPs, VPNs or Overlay Networks (such as TOR or I2P) can easily circumvent the block. For highly-advanced firewalls such as the GFC, techniques such as domain fronting[1], Peer-to-Peer relaying[2]

[1]: [[cites:Wikipedia - Domain Fronting]]
[2]: [[cites:MassBrowser - Unblocking the censored web for the masses, by the masses]]