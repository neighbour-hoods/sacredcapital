---
description: Built by the Economikit Alliance
---

# Technical Architecture

The Reputation Vault infrastructure is being built by the Economikit Alliance on Holochain's recently released RSM version. One of the key reasons for building on Holochain is it's emphasis on contextual validation, which is critical for the relativistic view of reputation that we foster.

In Holochain terminology, the Vault is a hApp bundle, with a collection of DNAs as zomes - which are articulated in the modules below. More details will be published soon. 

**Modules involved in the Reputation Vault**

![](../.gitbook/assets/image%20%283%29.png)

Assigning 'Trusted' Nodes: Allows listing of specific agent-ids as 'trusted' through which bridge calls will be established for porting of reputation data.

Consent Mechanism: Enables porting of reputation data across apps and communities through consent of the agent involved. 

RPC to read/pull reputation data: RPC from agent to relevant 'trusted node' which then bridges into the specific DNA to read reputation data

Read/Write Reputation Score Adaptors: coordination of data to and from the DSL for Cultural Articulation

\*\*\*\*

