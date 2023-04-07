# Bio

## whoami

My name is John Conwell and I'm a data scientist focused on utilizing data analysis and machine learning to identify phish and malware activity in North-South network traffic and their associated internet infrastructure. I've been exploring this intersection of machine learning and cyber security since 2017 and feel like I've found my calling. I believe that data science isn’t just about data and algorithms, but requires you to understand and empathize with your users; their needs, goals, values, and fears. This is especially true in cyber security where the cost of bad threat predictions could be devastating.

I have a diverse set of experiences, including software engineering, performance tuning, data visualization, entrepreneurship, and business. This has given me a well-rounded perspective that I bring to every aspect of my job. I try to balance the needs of the project, the customer, and the business equally to ensure my projects are successful.

When not honing my InfoSec and Machine Learning chops I also grow around 20 varieties of habaneros each year, make my own hot sauces, and fly First Person View (FPV) drones.

## Links

* [Mastadon](https://infosec.exchange/@turbo)
* [Twitter](https://twitter.com/turboCodr)
* [GitHub](https://github.com/jconwell)
* [LinkedIn](https://www.linkedin.com/in/jconwell/)
* [Keybase](https://keybase.io/turbojc/)

## Open Source Projects

### [Secret Handshake](https://github.com/jconwell/secret_handshake) 

A prototype malware C2 channel using x509 certificates to hold the data payloads over mTLS

### [FQDN Parser](https://github.com/jconwell/fqdn_parser)

FQDN Parser (Fully Qualified Domain Name Parser) is a library used to parse FQDNs into their component parts,
including subdomains, domain names, and their [Public Suffix](https://publicsuffix.org/list/public_suffix_list.dat).

It also provides additional contextual metadata about the domain's TLD including:

- International TLDs in both unicode and puny code format
- The TLD type: generic, generic-restricted, country-code, sponsored, test, infrastructure, and host_suffix (.onion)
- The date the TLD was registered with ICANN
- In the case of multi-label effective TLDs, is it public like `.co.uk` which is owned by a Registrar or private like `.duckdns.org` which is owned by a private company
- If the TLD (or any label in the FQDN) is puny code encoded, the ascii'ification of the unicode. This can be useful for identifying registrable domains that use unicode characters that are very similar to ascii characters used by legitimate domains, a common phishing technique.

TLD metadata can be used as contextual features for machine learning models that generate predictions about domain names and FQDNs.

### [DomainCAT](https://github.com/DomainTools/DomainCAT)

A InfoSec analysis tool used to explore the strength of domain to domain connectivity within a set of domains. It's useful for identifying clusters of related domains that share some common set of registration, naming, or infrastructure patterns during a security investigation such as threat hunting.

