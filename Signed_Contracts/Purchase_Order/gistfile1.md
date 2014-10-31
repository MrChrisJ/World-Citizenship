# Rough Outline of Purchase to Payment using Blockchain ID

This is an idea I am developing for a possible use case for the [Blockchain ID system](https://github.com/MrChrisJ/World-Citizenship).  

A buyer logs in to a merchant’s website and wants a record of a purchase in order to prove the transfer of ownership. The user may wish to associate the ownership of the Product with their PGP Key, the one they have had witnessed and signed in to the Bitcoin Blockchain, rather than a Bitcoin address.  

They may also wish to have protection from a Man in the Middle Attack and will want confirmation from the seller that the Payment address sent to them on the Sales Order is in fact theirs and not one that has been altered by someone who has attacked the site.  

## To achieve this using available tools we will need:   
A buyer & seller with Blockchain IDs  
Bitcoin Armory or Bitcoin QT
PGP Software    
A product to exchange that is easy to uniquely identify e.g. it has a serial number

## The Steps
1. Buyer logs in to website with an ID that has been verified with their PGP signature
2. Buyer’s software checks the Seller’s terms to see if it matches their preferences that have been predetermined before the purchase. If any exceptions are found it will notify the buyer and ask if they agree and wish to continue or renegotiate.
3.  Buyer puts in an offer in the form of a Purchase Order (PO) for a product using the product information on the site including”  
a. Any extra terms to the agreement  
b. A refund address  
4. Buyer Signs and transmits PO
5. Seller receives Purchase Order and verifies the signature
6. If Seller agrees then transmit Sales Order with:  
a. Confirmation of all information  
b. Bitcoin send address with Bitcoin Bare Signature with shared secret message  
c. Expiration of contract if payment is not made  
5. Buyer receives message and performs the following checks:  
a. Checks Bitcoin Bare Signature with shared secret message on hosted server  
b. If the address on the Sales Order matches the shared secret and the PGP Key of the message on the host then continue…  
6. Buyer sends the coins
7. Seller sends the product  

We might also be able to include proof of delivery from the courier personnel dropping off the product. Not to mention escrow service too using multisig wallet.

