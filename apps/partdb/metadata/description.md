Part-DB

## Installation

On first time setup, run `docker exec --user=www-data partdb php bin/console doctrine:migrations:migrate` after the container has started

## Features

* Inventory management of your electronic parts. Each part can be assigned to a category, footprint, manufacturer,
  and multiple store locations and price information. Parts can be grouped using tags. You can associate various files
  like datasheets or pictures with the parts.
* Multi-language support (currently German, English, Russian, Japanese, French, Czech, Danish, and Chinese)
* Barcodes/Labels generator for parts and storage locations, scan barcodes via webcam using the builtin barcode scanner
* User system with groups and detailed (fine granular) permissions.
  Two-factor authentication is supported (Google Authenticator and Webauthn/U2F keys) and can be enforced for groups.
  Password reset via email can be set up.
* Optional support for single sign-on (SSO) via SAML (using an intermediate service
  like [Keycloak](https://www.keycloak.org/) you can connect Part-DB to an existing LDAP or Active Directory server)
* Import/Export system for parts and data structure. BOM import for projects from KiCAD is supported.
* Project management: Create projects and assign parts to the bill of material (BOM), to show how often you could build
  this project and directly withdraw all components needed from DB
* Event log: Track what changes happen to your inventory, track which user does what. Revert your parts to older
  versions.
* Responsive design: You can use Part-DB on your PC, your tablet, and your smartphone using the same interface.
* MySQL, SQLite and PostgreSQL are supported as database backends
* Support for rich text descriptions and comments in parts
* Support for multiple currencies and automatic update of exchange rates supported
* Powerful search and filter function, including parametric search (search for parts according to some specifications)
* Automatic thumbnail generation for pictures
* Use cloud providers (like Octopart, Digikey, Farnell, LCSC or TME) to automatically get part information, datasheets, and
  prices for parts
* API to access Part-DB from other applications/scripts
* [Integration with KiCad](https://docs.part-db.de/usage/eda_integration.html): Use Part-DB as the central datasource for your
  KiCad and see available parts from Part-DB directly inside KiCad.

With these features, Part-DB is useful to hobbyists, who want to keep track of their private electronic parts inventory,
or maker spaces, where many users should have (controlled) access to the shared inventory.

Part-DB is also used by small companies and universities for managing their inventory.