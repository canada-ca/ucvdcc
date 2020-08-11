# User-Centric Verifiable Digital Credentials Challenge
![UCVDCC Logo](images/ucvdcc.png)

## Links to Handy References

* [Official Notice of Challenge](https://www.ic.gc.ca/eic/site/101.nsf/eng/00068.html)
* [Use Cases](use-cases.md)
* [Common Workplan](common-workplan.md]
* [Digital Ecosystem Requirements](Digital-Ecosystem.md)
* [VC Examples Repository on Canada-ca](https://github.com/canada-ca/vc-examples-ca)

# Problem Statement
This challenge is seeking a portable secure digital credentials (self-sovereign identity) solution held by individuals that can be independently, cryptographically and rapidly verified using emerging distributed ledger standards and an approach that may give rise to a global digital verification platform. For many contexts, ranging from applying for a job to transiting checkpoints for aviation security, paper documents remain the predominant way to prove key attributes about an individual, such as their name, date of birth, academic/professional qualifications, or security clearance. While these attributes might be presented in digital form, there are no widely adopted or standardized methods to issue and rapidly verify digital credentials across many different contexts. There exists no current capability to digitally verify without dependencies on centralized or low-latency network platforms (or both).

**Note**: The operational solution will be required to store all personal information within Canada

# Desired outcomes and Considerations
## Essential (Mandatory) Outcomes
Proposed solutions must:

1. Create User-centric Verifiable Digital Credentials able to operate on a national or global interoperable verification platform;
2. Protect the privacy and identity of the user at all times<sup id="fnr-a">[a](#fn-a)</sup>;
3. Incorporate the following emerging and/or mature specifications for interoperability that have been funded, tested and/or championed by the United States of America Department of Homeland Security:
    * Decentralized Identifiers (Standards Development Organizations: World Wide Web Consortium (W3C) or Decentralized Identity Foundation),
    * Verifiable Credentials (Standards Development Organization - W3C); and
    * JavaScript Object Notation for Linked Data / JSON-LD (Standards Development Organization - W3C);
4. Demonstrate the feasibility of the specifications described above in support of creating, transmitting and storing verifiable digital credentials using wallet or agent reference implementations. These reference implementations may include but not are limited to: Blockcerts, Hyperledger Indy Aries
5. Adhere to applicable policy instruments, guidelines and frameworks, including but not limited to:
    * Requirements specified in the Treasury Board Directive on Identity Management; and
    * Conformance Criteria specified in the Public Sector Profile of the Pan-Canadian Trust Framework.

<sup><a name="fn-a">[a](#fnr-a)</a></sup>
In relation to protecting privacy and identity of the user, the bidder is expected to demonstrate, in the proposal, knowledge and application of relevant controls as outlined in applicable guidance, including but not limited to CSE ITSP.30.31 published at https://www.cse-cst.gc.ca/en/system/files/pdf_documents/itsp.30.031v3-eng_0.pdf

It is also expected that the bidder demonstrate, in the proposal, sufficient knowledge to enumerate relevant threat agents and mitigation approaches

## Additional Outcomes
Proposed solutions should:

1. Give issuers and recipients ownership of their official records that can be cryptographically signed and presented anywhere to verify credential provenance and ownership.
2. Give issuers and recipients autonomy over how they use their records and verify digital credentials. For example, if issuers decide to switch vendors later on, they retain full access and use of their digital certificates.
3. Give relying trusted third parties the ability to verify any record independently, in independent fashion, for free and independent of any software vendor or issuing institution. Relying parties can easily verify any digital credential through widely available technology such as a web browser or a mobile phone. Verification is based on open and interoperable approaches.
4. Provide leading-edge digital credential security to enable the global trust economy that are cryptographically signed thus enabling third parties to verify their provenance and ownership.
5. Demonstrate the components of self-sovereign identity:
    * decentralized and portable;
    * demonstrated control of attributes; and independence from a centralized registry, identity provider, or certificate authority.
6. Demonstrate multiple partnerships and interoperability with other companies within verifiable credential ecosystem.

# Background and Context
This challenge intends to determine the feasibility and characteristics of developing a national or global interoperable verification platform that can be used to independently verify digital credentials issued by a dynamic set of trusted issuers, and used by a broad and diverse population of users. This can be tested in a context, such as aviation security where there are many actors and authorities operating across many organizational and geographical boundaries. 

Building on these standards, the goal is to prove that a decentralized, interoperable digital verification ecosystem can be built that can be used by many independent issuers, operators, and most importantly users, by means of open-source libraries and standards-based capabilities. In order for a new technology to gain adoption, it must be made accessible through easy-to-use and widely available software and ubiquitous infrastructure such as Blockchain, Distributed Ledger Technology (DLTs) and Self-Sovereign Identity (SSI). A government could potentially leverage these and develop a ubiquitous infrastructure with enhanced transparency and auditing of public service operations, greater visibility into multi-party business operations, and automation of paper-based processes to improve delivery of services to organizations and citizens. 

There exists a common need to issue entitlements, attestations and certifications for a variety of purposes including travel, training, education, affiliation, organizational identity and delegated authority and more. Current issuance processes are often paper based, non-interoperable and are susceptible to loss, destruction, forgery, and counterfeiting. While there is a diversity of contexts, there are many common needs across different departmental and agency contexts with a potential use of interoperable implementations of Blockchain, DLTs and SSI that also support the growth and availability of a competitive marketplace of diverse technology implementations for government and industry to draw upon to deliver cost effective and innovative solutions. 

For many contexts, ranging from applying for a job to transiting checkpoints for aviation security, paper documents remain the predominant way to prove key attributes about an individual, such as their name, date of birth, academic/professional qualifications, or security clearance. While these attributes might be presented in digital form, there are no widely adopted or standardized methods to issue and rapidly verify digital credentials across many different contexts. There exists no current capability to digitally verify without dependencies on centralized or low-latency network platforms (or both). In addition, there is a potential need for self-sovereign identity, which is the concept that people and businesses can store their own identity data on their own devices, and provide it efficiently to those who need to validate it, without relying on a central repository of identity data.
