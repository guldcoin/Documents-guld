# Guld Membership Agreement

Effective Date 01/06/2016

## Article 1: Members

This is a multi-party agreement entered into by the Members upon name registration.

### Section 1: Member Names

No name registration will be considered valid until the corresponding registration fee specified in Appendices A and B has been paid, and at least one Member has witnessed the transaction.

Claims to existing but unregistered names require a simple majority of `guld:Equity` approval.

Names may only include lowercase letters, numbers, and dashes (-).

Names may be anywhere from 1-40 characters in length.

Names less than 4 characters are subject to Premium Name Prices, specified in Appendix B.

If a member does not sign anything for 3 years, their name will be considered defunct. In this event, all prior contracts will be canceled and the name will be made available for claim in a new registration.

### Section 2: Individual Names

Each Individual Member must register a name and public key in the designated blocktree locations, and pay the one-time individual name registration fee specified in Appendix A and B.

Individuals may sign and witness contracts with their registered name and key. Such records must be kept in the member's blocktree branch.

### Section 3: Group Names

Members may form groups by registering a group membership agreement signed by the founding members, and paying the one-time group name registration fee specified in Appendix A and B.

Each group membership agreement must define a vote weighting table, and must maintain a public record of all names and keys of voters.

Groups may sign and witness contracts by obtaining signatures by a majority of weighted votes. Such records must be kept in the group's blocktree branch.

### Section 4: Device Names

Individuals and groups may register additional names with unique signing keys as "Devices".

Device names must end with `-ai` or `-device`.

Devices are the legal responsibility of their owner.

Devices receive their own namespaces, and ledger accounts, which may be controlled with either that device's signing key or the owner's key.

Devices may sign and witness contracts with their registered name and key. Such records must be kept in the device's blocktree branch.

## Article 2: Core Groups

This Agreement defines the following groups, which all Members must witness.

### Section 1: Guld group

This Agreement defines the group with name "guld", a Group member subject to Article 1 Section 3.

The guld group uses ledger-cli files to keep it's vote weighting table, with voting members defined as those having balance in a `guld:Equity` sub-account in their name.

All paths in this Agreement and all others filed in the blocktree are assumed to be relative to the path `.blocktree/guld`, which is governed by the guld group.

The guld group stores their vote weighting table and other ledger files in `ledger/GULD`.

The guld group is a meritocracy, in which only those Members who contribute open source intellectual property will receive `guld:Equity`, always in the form of a grant. All types of contributions will be considered, including but not limited to technology, art, law, and administration. Budget panels will be elected by area of expertise to manage contributions and grants.

All `guld:Equity` balances are non-transferable.

### Section 2: Peer to Peer Bar group

This Agreement defines the group with name "p2p-bar", a Group member subject to Article 1 Section 3.

The p2p-bar group uses ledger-cli files to keep it's vote weighting table, with voting members defined as those having balance in a `p2p-bar:Equity` sub-account in their name.

The p2p-bar group stores their vote weighting table and other ledger files in `ledger/p2p-bar/p2p-bar/equity.dat`.

The p2p-bar group is an international association of legal professionals also known as a bar association. All members of the p2p-bar group must agree to uphold both their local laws, as well as the contracts they witness on the blocktree.

The p2p-bar group will review and manage the grant budget for all contributions to the field of law.

All arbitrators named in witnessed contracts must be registered members of the p2p-bar group.

All `p2p-bar:Equity` balances are non-transferable.

## Article 3: The Blocktree

The purpose of this Agreement is to govern the contents of the blocktree, a distributed filesystem.

### Section 1: Root Hash

Members agree to accept all files and history of the blocktree as is, from the first prototype ledger in June 2016 up to the root hash, which is `23c03194e1b951e5dd4d2d0889de7a551ea83a74`.

### Section 2: Namespaces

Each registered name entitles the member to a corresponding namespace on the blocktree. The member has the right to publish files to their official sub-trees and branches, as enumerated in Appendix D.

Each member takes legal responsibility for the contents of their blocktree branch, and must be able to provide a signed history for each file and witnessed link in their branch upon demand by Arbitrator or other authority agreed to by contract.

Each member may maintain a perspective branch in their name for any other record in the blocktree.

### Section 3: Rights and Restrictions

Members may encrypt any files that are not otherwise contractually restricted. Any open source encryption tools which are linked in the blocktree `tech` sub-tree may be used.

Members may publish original content to their own namespace, provided it does not violate the terms of this Agreement or another registered contract.

Members cannot publish to another Member’s branch without contractually defined right.

Members may create and govern additional sub-trees within their own, linking such as git sub-modules.

No Member shall publish or cause to be published to the blocktree a file which is larger than 10 MB. Such files should be shared using torrents, and the torrents should be published to the blocktree.

No Member shall publish or cause to be published any malicious executables or instructions.

No Member shall publish or cause to be published anything which would be considered a crime for someone in their local jurisdiction to publish.

### Section 4: Data Retention

Each member must retain all contracts to which Member is a party, as well as all data referenced in the contracts.

Each member must retain source for any files linked in their branch of the blocktree.

Members agree to keep a copy of the guld ledger, especially any transactions involving the `guld:Equity` account or one of their own accounts.

## Article 4: Contracts

Members are free to contract with each other, subject to the terms of this Agreement.

### Section 1: Format

Parties may be known by their public key and name registered to a group common to all parties, i.e. the guld group.

Parties must be able to sign contracts with detached signature blocks.

Contract variables must be indicated with underscores followed by a single space and an UPPERCASE_NAME i.e. _______ ARBITRATOR

### Section 2: Registration With Witnesses

A contract is considered valid once witnessed by a third party Member.

### Section 3: Arbitration

All disputes of or related to the formation, performance, or execution of this Agreement, if not resolved by the parties, shall be submitted to the sole jurisdiction of the p2p-bar group (the ARBITRATOR) and agree to abide by the terms of the award, under the New York Convention on Enforceability.

Contracts must define an arbitrator, who must be a registered member of the p2p-bar group, in good standing.

Contracts must agree to the terms of the New York Convention on Enforceability on arbitration.

In the case of a dispute, all data related to the disputed contract must be shared with the contractually defined arbitrator, with proof of their authenticity by witnessed links in the blocktree.

## Article 5: Amendments

Any amendments to this Agreement or documents referenced herein shall be made in writing and signed cryptographically by a majority of `guld:Equity` holders, and published to guld blocktree branches, including the amendments to the writing requirement stated in this provision.

## Appendices

### Appendix A. Name Registration Fees

| Category          | Unit Price | Limit | Description                                            |
|-------------------|------------|-------|--------------------------------------------------------|
| Individual Member | 0.1 GULD   | 1     | Only one Individual name may be registered per person. |
| Group Member      | 0.1 GULD   | none  | Groups must pay the unit price per each voting member. |
| Device Member     | 0.1 GULD   | none  | Individuals and groups may register multiple devices.  |

### Appendix B. Premium Name Registration Fees

| Name Length | Unit Price   | Total Number | Total Premium  |
|-------------|--------------|--------------|----------------|
| 1 char      | 100,000 GULD | 37           | 3,700,000 GULD |
| 2 chars     | 1,000 GULD   | 1,369        | 1,369,000 GULD |
| 3 chars     | 10 GULD      | 50,653       | 506,530 GULD |

### Appendix C. Ledger Name Registration Fees

| Category          | Unit Price | Limit | Description                                            |
|-------------------|------------|-------|--------------------------------------------------------|
| Blockchain        | 1,000 GULD | none  | Entire blockchains may be registered, but only registered addresses and contracts will be witnessed. |
| Ledger Contract   | 100 GULD   | none  | Individual ledger commodities can be defined either as native to the blocktree or a registered Blockchain. |
| Individual Ledger | 10 GULD    | 1     | Each individual may register a personal, time-based ledger. |
| Group Address     | 1 GULD     | 10    | Groups may register up to 10 official addresses for each Blockchain. |
| Individual Address | 0.1 GULD  | 1     | Individuals may register one address for each Blockchain. |

### Appendix D. Blocktree File Paths

All paths given are relative to `.blocktree/guld`.

| Path                           | Owner       | Required | Description of Contents       |
|--------------------------------|-------------|----------|-------------------------------|
| /dotfiles                      | guld        | Yes      | Member sub-modules containing configuration files. |
| /dotfiles/{member-name}        | member-name | Yes      | Member configuration files, including required `.gitconfig`. |
| /keys                          | guld        | Yes      | Sub-modules of different types of keys. |
| /keys/pgp                      | guld        | Yes      | Member sub-modules containing ASCII armored PGP public keys. |
| /keys/ssh                      | guld        | Yes      | Member sub-modules containing SSH public keys. |
| /keys/pgp/{member-name}        | member-name | Yes      | Member ASCII armored PGP public key(s) named by lower-case fingerprint. |
| /ledger                        | guld        | Yes      | Sub-modules of different token ledgers. |
| /ledger/GULD                   | guld        | Yes      | Member sub-directories containing GULD transactions. |
| /ledger/GULD/guld              | guld        | Yes      | Transactions debiting GULD from the guld group, as well as all `guld:Equity` transactions. |
| /ledger/GULD/{member-name}     | member-name | Yes      | Transactions debiting GULD from member-name. |
| /tech                          | guld        | Yes      | Technology, organized by language, registered and available for use in guld tools and apps. |
| /Documents                     | guld        | Yes      | Member sub-modules containing text files. |
| /Documents/guld                | guld        | Yes      | Guld shared text files, including this Agreement. |
| /Documents/{member-name}       | member-name | No       | Member text files. |
| /Audio                         | guld        | No       | Member sub-modules containing audio files. |
| /Audio/{member-name}           | member-name | No       | Member audio files and/or torrents for them. |
| /Pictures                      | guld        | No       | Member sub-modules containing image files. |
| /Pictures/{member-name}        | member-name | No       | Member image files and/or torrents for them. |
| /Video                         | guld        | No       | Member sub-modules containing video files. |
| /Video/{member-name}           | member-name | No       | Member video files and/or torrents for them. |
| /.password-store               | guld        | No       | Member sub-modules containing encrypted passwords. |
| /.password-store/{member-name} | member-name | No       | Member encrypted passwords. |

### Appendix E. Glossary

| Word        | Definition                                                                   |
|-------------|------------------------------------------------------------------------------|
| Member      | A party to this Agreement.                                                   |
| Blocktree   | The file system defined in this Agreement, a distributed git tree maintained by the Members. |
| Witness     | A third party Member who merges a hash reference to a file, thereby confirming it's existence, path and uniqueness. |
| guld group  | The group which develops and maintains the blocktree and supporting systems. |
| branch      | A member's version of a file or set of files.                                |
| sub-tree    | A portion of the blocktree, owner determined by the linked branch i.e. everything under /tech is owned by guld unless otherwise specified by branch name and/or LICENSE file. |
