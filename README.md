
# (நம்Chain Improvement Proposal) ![](https://img.shields.io/badge/Project-Nam-ff69b4.svg) ![](https://img.shields.io/badge/Namchain-WIP-Blue.svg) 

<p align="center">
<img src="https://1.bp.blogspot.com/-0SArWfduw68/XkxV8EmBBcI/AAAAAAAAABw/h9aWSWbm0J4kilgn3xddzQ3PdoP-e3RZgCLcBGAsYHQ/s1600/SAVE_20200127_132431.jpg" width="200" align="center">
</p>  

<pre>
 NIP: NIP-1
 Title:  NIP Purpose and Guidelines
 Author(s): Ramaguru Radhakrishnan (ramaguru.90@gmail.com)
 Created: 18-Oct-2020
 Type:  Process
 Status: Draft
</pre>

# NIP - NamChain Improvement Proposal 

NamChain Improvement Proposal (NIP) describes the proposed standards for the நம்Chain platform, a design document providing information to the community, or describing a new feature or its processes or environment.

Like Bitcoin and Ethereum Community, we also intend NIP to be the primary mechanisms for proposing new features, for collecting community input on an issue, and for documenting the design decisions that have gone into Bitcoin.

# NIP Types
  - Standard NIP
    - Core
    - Library
    - Tools
    - DLTs
    - BIS
  - Informational
  - Process 

Each NIP should have the following parts:

  - **Preamble** - RFC 822 style headers containing metadata about the NIP, including the NIP number, a short descriptive title (limited to a maximum of 44 characters), and the author details. See below for details.
  - **Abstract** - A short (~200 word) description of the technical issue being addressed.
  - **Motivation (*optional)** - The motivation is critical for NIPs that want to change the நம்Chain protocol. It should clearly explain why the existing protocol specification is inadequate to address the problem that the NIP solves. NIP submissions without sufficient motivation may be rejected outright.
  - **Specification** - The technical specification should describe the syntax and semantics of any new feature. The specification should be detailed enough to allow competing, interoperable implementations for any of the current நம்Chain platforms.
  - **Rationale** - The rationale fleshes out the specification by describing what motivated the design and why particular design decisions were made. It should describe alternate designs that were considered and related work, e.g. how the feature is supported in other languages. The rationale may also provide evidence of consensus within the community, and should discuss important objections or concerns raised during discussion.
  - **Backwards Compatibility** - All NIPs that introduce backwards incompatibilities must include a section describing these incompatibilities and their severity. The NIP must explain how the author proposes to deal with these incompatibilities. NIP submissions without a sufficient backwards compatibility treatise may be rejected outright.
  - **Test Cases** - Test cases for an implementation are mandatory for NIPs that are affecting consensus changes. Other NIPs can choose to include links to test cases if applicable.
  - **Implementations** - The implementations must be completed before any NIP is given status “Final”, but it need not be completed before the NIP is merged as draft. While there is merit to the approach of reaching consensus on the specification and rationale before writing code, the principle of “rough consensus and running code” is still useful when it comes to resolving many discussions of API details.
  - **Security Considerations** - All NIPs must contain a section that discusses the security implications/considerations relevant to the proposed change. Include information that might be important for security discussions, surfaces risks and can be used throughout the life cycle of the proposal. E.g. include security-relevant design decisions, concerns, important discussions, implementation-specific guidance and pitfalls, an outline of threats and risks and how they are being addressed. NIP submissions missing the “Security Considerations” section will be rejected. An NIP cannot proceed to status “Final” without a Security Considerations discussion deemed sufficient by the reviewers.
  - **Copyright Waiver** - All NIPs must be in the public domain. See the bottom of this EIP for an example copyright waiver.
  
 # NIP Formats and Templates
 NIPs should be written in [markdown format](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). There is a template to follow.

<pre>
 NIP: <NIP number>
 Title: <NIP title>
 Author(s): <list of authors' real names and optionally, email address>
 Created: <date created on, in ISO 8601 (yyyy-mm-dd) format>
 Type: <Informational | Library | Tools | DLTs | Process>
 Status: <Draft | Active | Accepted | Deferred | Rejected | Withdrawn | Final | Superseded>
* Requires: <NIP number>
* Replaces: <NIP number>
* Superseded-By: <NIP number>
* Resolution: <url>
</pre>
   
# NIP Auxiliary Files
NIPs normally may include auxiliary files such as Images and diagrams. Auxiliary files should be included in a subdirectory for that NIP as follows: assets/nip-N-C-ext, where "N" is the NIP number, "C" is a serial number (starting at 1), and "ext" is replaced by the actual file extension. Such that when linking to an image in the NIP, use relative links such as ../assets/eip-1-1-png
   
# NIP Editors
 - Ramaguru Radhakrishnan (@ramagururadhakrishnan) 
 
# Style Guide
Whenever referring to an NIP by number, it should be written in the hyphenated form NIP-N where N is the NIP’s assigned number.
 
# History
This document was derived heavily from Bitcoin Improvement Proposal (BIP) written by written by Amir Taaki & Ethereum Improvement Proposal (EIP) written by Martin Becze, Hudson Jameson, et al. both of these inturn was derived from Python's PEP-0001. In many places text was simply copied and modified. Although the PEP-0001 text was written by Barry Warsaw, Jeremy Hylton, and David Goodger, they are not responsible for its use in the NamChain Improvement Proposal (நம்Chain Improvement Process), and should not be bothered with technical questions specific to நம்Chain or the NIP process.
 
# Copyright
Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
 
# Citation
Please cite this document as:

Ramaguru Radhakrishnan, **"NIP-1: NIP Purpose and Guidelines,"** NamChain Improvement Proposal(நம்Chain Improvement Proposal), October 2020. [Online serial]. 
