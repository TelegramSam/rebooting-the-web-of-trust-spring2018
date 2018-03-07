
# TLS Flex

*Previous Title: Open TLS*

Contributors: Sam Curren, David Crocker

## Abstract
TLS usage  is currently burneded by problematic certificate mechanisms. The goal for this work is to eliminate the certificate burden and thereby enable a broader range of applications for TLS use.

First, enable alternative certificate mechanisms, and second, explore TLS use for additional applications, including client validation.

The work will explore current efforts to enhance TLS use with DANE, and provide for support of DID as an additional certificate validation mechanism.

Promoting client certificate use will enable mutual authentication as part of the existing TLS handshake.

This work is intended to benefit those seeking authentcaton without reliance on an established certificate authority. Early adopters are expected to consist of those validating certificates registered on a blockchain.

As an example, this work will lower the administrative burden and provide greater flexibility in networks of servers or iot devices. The advantages include validation that extends beyond the existing certificate checks for custom applications.
 
This work is expected to require no changes to the TLS protocol.
