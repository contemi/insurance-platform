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

| Functional Area | Comment |
| ----------- | ----------- |
| User Management | Ability to create and manage users. Users can be assigned multiple roles. As the other Contemi systems are added to the Open Source community, the functionality already exists to manage access to them and facilitate Single Sign On (SSO) with 2FA if required. |
| Back Office UI | The PMS is designed for back office use. Whilst APIs will exist for integration with other UIs (e.g. customer facing websites and apps). |
| Customer Management | This is not the full CRM component which Contemi has and may form part of the long-term roadmap. It serves the needs of a PMS to manage a customer in the appropriate way for a given country. |
| Customer Search | Ability to search by customer, quote or policy ID, as well as a more general but insurance specific search (e.g. risk object name). |
| Basic product examples | Some sample products will be included, e.g. Travel Insurance. Additionally, support will be provided to take a product definition (currently in JSON) and generate the visualization and premium calculations. |
| Sales (Quotes) | The user will be able select a partner/channel, then a product, run through a workflow of questions to create a quote with a premium. The quote can be later retrieved and accepted (purchased). |
| Policy Management | Allows the management of a policy through its lifetime.  |
| Payments | Handling of the payment schedule, with yearly to monthly schedules and different rounding and residuals options. |
| Document Storage and Generation | Ability to generate documents such as quote and policy documents. And storing these in a central repository. The generation is based around composable document templates generating XHTML and conversation to PDF. Note: In release 1, the user will need to build or code in their own converter (else use commercially available software). Release 2 this issue will be resolved. |
| Data Listener | Component to act as the conduit through which events, non-SQL data, etc. can be used for Data Warehousing activities |
| Multi-lingual | Language can be dynamically changed on the website (assuming the translations have been uploaded into the system). |
| Event History | The history of events – typically for auditing purposes. Any change to the data should cause and event to be created and stored. This is Insurance Platform wide. |
| Configuration | For a given instalment (or longer-term tenant) – which features of the system are turned on off, branding for the different channels, products and specific rules of those products. |

![alt text](https://github.com/contemi/insurance-platform/blob/master/Archictecture.png "insurance platofrm arcitecure diagram")

## License
The exact license under which this software will be available is not yet finalized.

## Contributions
We will be looking for contributions. Anything from bug report (and bug fixes), to suggestions for new functionality.

## Project Status
In internal development – code is being re-shaped and packaged so it is ready for the Open Source community.

## How to get more information
Please email <OpenSource@contemi.com>
