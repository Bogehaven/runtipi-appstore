# Part-DB

Part-DB is an Open-Source inventory management system for electronic components. It is designed to be installed on a web server, allowing access via any browser without the need to install additional software.

## Features

- **Inventory Management:** Track electronic parts, assign categories, footprints, manufacturers, and store locations. Parts can also be grouped using tags and associated with various files like datasheets and pictures.
- **Multi-language Support:** Supports multiple languages including German, English, Russian, Japanese, French, Czech, Danish, and Chinese.
- **Barcode/Label Generation:** Generate barcodes and labels for parts and storage locations. The built-in barcode scanner allows barcode scanning via webcam.
- **User Management:** Includes a user system with groups and detailed permissions. Supports two-factor authentication (Google Authenticator and Webauthn/U2F keys) and password reset via email.
- **Single Sign-On (SSO):** Supports SSO via SAML, which can be integrated with LDAP or Active Directory.
- **Import/Export System:** Allows importing and exporting of parts and data structures, and supports BOM import for projects from KiCAD.
- **Project Management:** Create projects, assign parts to the BOM, track inventory usage, and withdraw components directly from the database.
- **Event Log:** Track inventory changes and user actions, and revert parts to older versions.
- **Responsive Design:** Compatible with PCs, tablets, and smartphones.
- **Database Support:** Supports MySQL, SQLite, and PostgreSQL.
- **Rich Text Support:** Allows rich text descriptions and comments in parts.
- **Currency Support:** Supports multiple currencies and automatic exchange rate updates.
- **Search and Filter:** Includes powerful search and filter functions, including parametric search.
- **Automatic Thumbnail Generation:** Automatically generates thumbnails for pictures.
- **Cloud Integration:** Integrates with cloud providers like Octopart, Digikey, Farnell, LCSC, and TME to get part information, datasheets, and prices.
- **API Access:** Provides an API to access Part-DB from other applications or scripts.
- **KiCad Integration:** Use Part-DB as a central datasource for KiCad, showing available parts directly inside KiCad.
