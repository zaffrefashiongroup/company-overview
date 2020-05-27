# Mabel
ZFG's flagship brand, a high-end clothier specializing in fine outerwear and handcrafted leather goods. Mabel BU manages a hybrid-cloud environment.

Mabel’s web presence was developed in 2002 to capture an increasing trend for online shopping. The flagship application stack, Mabel eCommerce, is a modular, three-tier architecture constructed using web, application, and database solutions from popular vendors in those spaces. In 2008, company-wide efforts were made to virtualize resources to consolidate server sprawl and introduce the agility that virtualization brought to the table.

The web tier that accepts and tracks user sessions is largely stateless and distributed using a Content Delivery Network (CDN). Regional points of presence (PoP) provide a local experience for online shoppers based on their geographic location.
The application tier hosts internally developed binaries that provide: control signaling; nightly extract, transform, load (ETL) workers; a lookup service for user data; and payment processing. Most of the binaries were developed in-house and have been upgraded in-place over the life of Mabel eCommerce.

The database tier stores customer records, including purchase information, and is used to complete purchase orders and surface buying trends to the Mabel Marketing department.

## Cloud-First Initiative
In 2017, the CIO of Zaffre Fashion Group mandated a cloud-first mentality for net-new applications in an effort to reduce spend on managing data center operations, leverage increased focus on core business initiatives, and shrink the lag between great ideas and feature releases. Aligned to this effort, Mabel’s IT Director tasked the Center of Excellence and technical operators to construct a new architecture for Mabel eCommerce using AWS.

The ultimate goal is to enrich the customer experience to further cement ZFG as the leading brand for buyers who demand a custom-tailored shopping experience for bespoke, one-of-a-kind products. From eCommerce to brick and mortar stores, a focus on consistency, elasticity, and high availability will further the product and engineering teams to deliver on this vision and unify the buying experience. Both the development and operations teams are excited to pay down technical debt, eliminate legacy headaches from building and managing Mabel eCommerce, and eventually re-architect the storefront to use cloud native services.
