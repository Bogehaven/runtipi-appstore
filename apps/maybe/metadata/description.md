# Maybe Finance - Personal Finance Management

Maybe is a comprehensive personal finance and wealth management platform that helps you track your net worth, investments, and financial goals. This open-source solution provides powerful tools to manage your finances effectively.

## Features

- Net worth tracking
- Investment portfolio management
- Financial goal setting and tracking
- Multi-currency support (with additional setup)
- Secure, self-hosted solution

## Configuration Options

### Required Settings
- **Secret Key Base**: Automatically generated secure key for Rails
- **Database Password**: Password for PostgreSQL database

### Database Configuration
You can choose between using the built-in PostgreSQL database or connecting to an external one:

1. **Built-in Database**
   - Simply set the database password
   - Data is stored in the app's data directory

2. **External Database**
   - Enable "Use External Database"
   - Provide your PostgreSQL server details:
     - Host
     - Port
     - Database name
     - Username
     - Password

## Getting Started

1. Install the app through RunTipi
2. Configure the required settings
3. If using an external database, ensure it's accessible and credentials are correct
4. Access Maybe through your browser at the configured domain
5. Create your account and start managing your finances

## Important Notes

- The app requires PostgreSQL 16 or later
- When using an external database, ensure it's properly backed up
- SSL is handled by RunTipi's reverse proxy

For more information, visit the [Maybe GitHub repository](https://github.com/maybe-finance/maybe).