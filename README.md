# OEPTF (Open European Public Transit Format)
This repo shows **the OpenAPI specification** to work with the Open European Public Transit Format. 

[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) ![Open Source? Yes!](https://badgen.net/badge/Open%20Source%20%3F/Yes%21/blue?icon=github)

## What's OEPTF?
OEPTF is the first standard who is trying to standardize european transit. 

Some semantics are made for european purposes only (like INTERCITY_EXPRESS_TRAIN or ICE) which is related to Deutsche Bahn ICE trains, so it's recommended to use it only for the european area.


## What do we want to achieve?

We try to keep things european and future-proof:
 - European Semantics (like ICE, IC, EC, etc.)
 - Future Proof (fields for Autonomous driving, Transrapid, etc.)

and flexible: 
 - Fits everywhere: only basic fields are required, everything else is optional
 - No limits: Works perfectly with gRPC, REST, etc. due to the OpenAPI nature

but standardized:
 - Easy data source switching: OEPTF endpoints are easy to switch due to the standardized search query and endpoints

It's reusable:
  - Simple objects: We keep our objects simple to be able to reuse objects
  - Sharing: Some objects are shared with eachother, making interoperabillity much easier


## What's missing?
  - Support for more european semantics
  - More documentation of the objects
  - Optional search by coordinates and name and not being limited by IDs


## Responsible freedom

This API specification is licensed under **BSD-3-Clause**, which enables you the freedom to create your own standard, or just expand OEPTF.


<br />
<br />
_Made by Zwei & PDesire_
