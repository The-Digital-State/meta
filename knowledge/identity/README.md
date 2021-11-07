Modern technology have given us technology of cryptographic signatures and digital authority. You might have heard about PGP (GPG) keys or SSL certificates. Those are the some fundamental blocks which establish core principles of digital identity management.

We are certain that cryptography must be a foundation of identity in digital state, but it operates differently to publics perception of identity and some serious work is needed to close this gap.

This "Identity" section is specifically focusing on how to connect the concepts of "Cryptopgraphy" and "Zero Knowledge Proof" with "Identity" in the digital state.

## Why digital identity must be adopted?

Use of digital identity has many benifits - enables anonymity, prevents disinformation, propaganda or fake - but the most difficalt challenge is not technical - it's understanding of digital identity principles by your common folks.

This topic is especially important, now that authoritarian regimes invest into research of deep-fake technology and state-hacking.

## How we percieve "identity"?

Human interaction is based around recognition - we identify friends by the way how they look, how they sound, act or behave. Our brain stores some reference clues memories of that person and is used to establish authenticy of a given message.

It's not uncommon for certain regimes to trick those senses, replacing their leaders with doubles and nowdays - fabricate videos and voice. As this technology becomes more accessible, it will be used against oposition of the regime.

## What is Cryptography and Zero Proof Knowledge?

A science field focused on cryptography has given us mechanisms how to create a more reliable ways proove identity.

For example - at one point this document contained a line about a "Quick brown fox", and the history of this was preserved here:

https://github.com/The-Digital-State/meta/commit/a6ac289b391d13a8caa6f1311db7b12f7eb99438#diff-c890d60ca708eb5b8c661712523970608a7e8f64b8b70da1719e865efc6cf6c9R15

But who added that line? The change history of the file indicates that it was signed by a GPG key with ID=0DA7FE21480F206F. You can look this up here: https://keys.openpgp.org/

This key is also listed by a current contributor here: https://github.com/The-Digital-State/meta/blob/main/org/contributors.md

As a consequence - even through the message about "Quick brown fox" is removed now - the history of it is preserved along with the proof which links it up to a current contributor to The Digital State project.

I must also stress that 3 important points:
1. absolutely anyone can verify this information without zero knowledge of real identity of that contributor or having absolutely no personal details. 
2. the proof took seconds to create and would take billions of years to crack.
3. this is much more reliable any other known "proofs" - signatures, statements etc.

This was a very basic introduction to cryptographics signatures, but ZKP is much more than this - would you trust "github.com" or "keys.openpgp.org" servers? Could private key of the contributor become compromised in the future? What if contributor looses his private key which is used for creating signatures, how can he authorize a new key? Should others trust this key?

## What would successful adoption give us?

### Phase 1 - establishing the digital identity

If we are to implement digital identity correctly - that means that each citizen maintains a private identity which they do not share with anyone. Instead they can share "proof" of their identity to others.

To many non-technical people operating identity may be challenging, but the same can be said about "international money transfers" - yet there is a banking industry which makes it simple for any person to send money.

We believe that a similar approach can be implemented with digital identity management. The fundamental underlying technology will be open and highly reliable, but to help prevent human errors - we could facilitate creation of the "Identity banks" - organisations which look after those who want an "easy" solution.

### Phase 2 - uniqueiness and personal data

Suppose person A had to flee the country due to political pressure. Organisation S is offering financial help to political victims and is willing to help person A. 

Organisation S is worried that person A may create multiple digital identities and apply for help multiple times. At the same time person A does not want to share their personal information with organisation S.

To address this we need to introduce a mechanism where we can have a 3rd party verifiers, who can guarantee uniquiness of person A to organisation S without compromising their personal details or location.

Ideally this mechanism would make sure that if person A applies for financial help from organisation S again, they would be able to identify that he has already received help.

### Phase 3 - anonimization

Various countries give citizens a unique numbers which helps them identify a person. The number is given at birth or at a certain age and all citizens must have one.

Because a number like that cannot be changed - it can be used by companies for tracking, can be shared and used for prosecuting individuals.

Anonimization is a mechanism that creates "secondary identity" - maintaining uniquiness but is only usable by a single organisation.

Lets look at example where a phone company is willing to create "client profile" for their customer. If customer wants to leave a phone company and then join them back in a few years, they want them to identify as a same customer. At the same time we don't want this phone compnay to operate with our primary unique person identifiers.

Anonimization process should allow us to create ID2 - secondary IDs for this Phone company which they can use to identify clients, but if their client database gets leaked - other organisations will not be able to cross-match clients without permission from the identity owner.

Another very good example is general voting system. Every citizen is allowed to vote, but their identity must not be associated with their voting result.

### Phase 4 - Guarantoors

Guarantoor is a type of organisation, which stores information or "escrow" funds by an individual and would be pressured to expose information or transfer funds if they are provided with legal request to do so.

Suppose Person A purchases a car. He can now cause an accident on the road and therefore must be insured. Could we design a system that would protect personal information of the driver yet make him liable for the damage he has caused by the accident?

This is where Guarantor organisations come in. Such organisation would be able to recover money from the person and transfer it as the law requires. The precondition could be a court decision.

In a successful implementation, both the court and guarantoor can operate on a zero-knowledge proof basis - not holding personal details and making decision only based on the objective proof.

### Phase 5 - Inter-organisation collaboration

Some further thinking is needed here, but a channels how different organisations exchange information, such as court orders in my previous examples, needs to be reviewed.

Once again - can this be done in a transparent way but without exposing personal details? Can this be implemented between the countries too, with the interpol?







