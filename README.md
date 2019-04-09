# insurance-platform

## Business Case
Modern insurers are adopting Open Source into their IT architecture at an increasing pace. What is not yet available is an insurance platform for a new insurer to get “off the shelf”, can adopt, configure and run their business. Nor, is there an insurance platform that a well-established insurer can pick up and run and manage new lines of business in short time scale.

Contemi intends to help create such an insurance platform that can be developed in such a way to allow insurers (new and old) to do the things an insurer just has to do, but with sufficient flexibility to do it in their way, to encompass new trends and to stay competitive.

Contemi is going to leverage its own modern, core policy management system as the start point for the platform. Whilst the system needs to be re-shaped for the Open Source community – it is a system already being used by insurers. Previous versions of the system are being used by companies today to transact their business. Contemi has many years of experience developing insurance applications and systems for big and small insurers.

## Grand Vision
The business case eludes to a grand vision. Contemi’s vision is to push as much of its insurance and related systems into the Open Source community as practical and beneficial as possible.

And, for the Contemi’s Open Source Insurance platform to be the insurance platform globally that insurers, of any size, want to use.

This defines a high-level roadmap which may include items such as claims, re-insurance, customer engagement, DWH, dashboards, portals, etc. However, InsureTech trends, other disrupting technologies and ideas/requests from the community (which we hope directly includes insurers) needed to be accounted for and refine the order and priority of code introduced by Contemi.

## Short Term Roadmap
Phase one, is to deliver a core policy management system. Custom products can be defined, quote(s) created and purchased to form a policy (or policies). Where a policy can be adjusted midterm, terminated, or renewed. And, for all these typical insurance actions, payment schedules are created or amended.

The system is written in C# using .net core. And packaged as a set of micro-services. We follow a polyglot persistence pattern giving a flexible choice of database technologies. 

## Phase One Functionality
The first phase will split into two main deliveries. The first delivers a completed yet simplified policy management system (PMS) – suitable for a small start-up.  The second delivery builds on the first enriching many of the components with functionality and options that a more established insurer would look for in a PMS.

Here’s the functionality in a little more detail:



![alt text](https://github.com/contemi/insurance-platform/blob/master/Archictecture.png "insurance platofrm arcitecure diagram")

