# World Citizenship - Creating Affordable Decentralised Passport Services Using Available Cryptographic Tools

**Also published here:** [https://docs.google.com/a/chrisellis.me/document/d/1hq52GT0sQ8mJBZ3_qr-LIpZTBFqIDA2WV8vb_1m8i4U/edit#bookmark=id.tukd0op21duu](https://docs.google.com/a/chrisellis.me/document/d/1hq52GT0sQ8mJBZ3_qr-LIpZTBFqIDA2WV8vb_1m8i4U/edit#bookmark=id.tukd0op21duu)  
**Proof of Publication:** [http://www.cryptograffiti.info/?txnr=1247](http://www.cryptograffiti.info/?txnr=1247)  

**See also [the Journal](https://github.com/MrChrisJ/World-Citizenship/blob/master/Journal.md)** 

## Goal

The goal of this project is to learn and layout a simple process for anyone in the world to create their own Private Passport Service that can be used to validate and prove the existence of other persons using nothing but available tools.

We will prefer open source where available and we will draw on the cryptographic tools like Public Private Key Cryptography (PGP) and blockchain technology in the form of Bitcoin.

By doing this we aim to give people across the world the ability to grant one another Global Citizenship by virtue of their being witnessed in space and in time. This witnessing can be documented with photography and video, that content can be signed with PGP signatures, hashed and timestamped. It can then be joined with Social Network Validation services like Keybase.io before being plugged in to more dynamic reputation systems.

First and foremost this is a learning exercise to discover whether the currently available open source cryptographic tools are up to the task of a global social network.

## Apparatus

1. Laptop x2 (one belongs to organisers and the other to our new citizen)
2. Webcam
3. PGP Software
4. Printer
5. Laminator
6. Cool looking World Citizen Passport design

## Method

### Step 1
A determined group of forward thinking cypherpunks setup a meet up in their local town using a service like meetup.com 

### Step 2
A group of soon-to-be World Citizens arrive at a commercial venue as advertised bringing with them their laptop and an eagerness to learn.

### Step 3
They are given a brief tutorial in operational security, best practice like how to do good key management with demonstrations of things like Password Managers etc. 

Their laptop can be given a security audit also if they wish. 

Videos will have been made available to them before the meet up but it’s important for the organisers to get a sense of how well they understand the concepts so that they go in with their eyes open.

### Step 4
The citizens participate in a group photo that can be cropped down to make each individual passport photo.
The exact location and direction in which the group photo is taken could display the moste uniquely identifiable element(s) of the environment the in which the meetup takes place (landmarks, buildings, etc.) to provide a further reference to the georaphical location.

### Step 5
They then go to a private room with their laptop and generate a new PGP Key that is preferably air gapped. They could also be sold a [crypto-stick](https://www.crypto-stick.com/) or similar product.

### Step 6
The image and the PGP Key’s ID and Biometric Fingerprint are laid out in to an HTML document thus:

![Blockchain Passport](https://github.com/MrChrisJ/World-Citizenship/blob/master/Media/Passport-Layout-01.png)

The PGP key is then used to publicly sign the completed document and image.

### Step 7
The new global citizen then has their PGP Key signed by others in attendance. A SHA256 digest of the key is then placed along with the key’s ID in to the Bitcoin blockchain using an address that is preferably owned by the commercial venue hosting the event.

By including the Merkle Root of the latest block we prove we have knowledge of an event that cannot have taken place any time prior the latest block being published.

By signing the Passport with a PGP key we bind  the state of the document to it’s cryptographic signature preventing us from changing its contents without detection.

By stamping the digest of the resulting passport and its signature in to the blockchain following these steps we prove that it existed in this state at no time later than the block in which it was published.

By using the venue’s Bitcoin address (preferably one used by their customers) with a public IP address we prove that it exists in this space.

This is because Bitcoin nodes collect IP data in the debug.log file. Additionally since the venue is commercial they have an interest in maintaining their reputation and advertising their location. (Note: GPS data on phones can easily be spoofed).

### Step 8
The document is printed out and presented in a cool Passport Design. It can be branded as BitNation, World Crypto Network or something of the organiser’s choice. 

The person is recognised as a World Citizen by the adherence to the protocol not by the branding of the passport which will be a stylistic choice like where you get your coffee.

### Finishing Up
You have now proved that this new global citizen existed at this point in time and space and was witnessed by others.

They are now free to sign other people’s PGP Keys like at a regular [key signing party](http://en.wikipedia.org/wiki/Key_signing_party).

They can also create an account with a website like Keybase:
https://keybase.io/chrisellis which they can use to validate their other social media identities and plug in their new key in to more dynamic reputation systems

## Notes

As a proof of concept, we need to look at both the appropriateness of the current tools and also the ethics of this. First thought are as follows:

1. The brave new world citizens must fully understand what they are involving themselves in and must be educated such that they can make a voluntary decision about such an open and public gesture. This may not be right for many people who risk personal safety by being so exposed. The benefit of Public Private Key Cryptography of course is that we do have granularity when it comes to the revealing of the cryptographic digests and their corresponding contents but more needs to be done.
2. The “Global Passport” only contains the name which can be a pseudonym and a photo of the individual for future offline verification and not their Date of Birth or Gender as I am trying to keep this as simple and elegant as possible. Any ‘rich data’ which is more social in its nature should be placed in to the social networking sphere and the reputation systems which should be tailored to voluntary agreements between community members. In fact the person’s legal identity may not even be necessary and they could be given a name based on the randomness of the Merkle Root for example or the Fingerprint.
3. An Expiry Date is included as a feature and should be thought carefully about. It is possible that someone could have their PGP key stolen and it’s important that the right intervals of time are chosen so that they can “check-in” to such meet ups on a regular enough basis that they can publicly revoke old keys. The hope is that by bringing down the cost of providing such a service all over the world registering yourself will become effortless.
4. We should think carefully before thinking about how biometrics can be used. It would not be wise to leave biometric data out in the open in plain text as it could be used by another. However if it could be salted or hashed with another string and if it can only be implemented at certain times and places according to protocol then it could be used as a kind of Seed which could generate other identities.
5. The citizens could also use the meet up as an opportunity to prove other identities like BitMessage addresses in case they are a journalist for example and want to prove that this secure drop for whistle blowers is going to send content to where they say it will.
6. One person multiple identities may also be an issue but not if we accept this as a feature of the system and do not misattribute what we are using these passports for. It is already possible to have multiple passports even from the same country if you know what to do.









