# Maxun - No-Code Web Data Extraction Platform

Maxun is an open-source platform that lets you train robots to extract web data automatically. Create custom robots that can emulate user actions and extract data without manual intervention.

## Features

- ✨ Extract Data With No-Code
- ✨ Handle Pagination & Scrolling
- ✨ Run Robots On A Specific Schedule
- ✨ Turn Websites to APIs
- ✨ Turn Websites to Spreadsheets
- ✨ Adapt To Website Layout Changes (coming soon)
- ✨ Extract Behind Login (coming soon)
- ✨ Google Sheets Integration

## Robot Actions

1. **Capture List**: Extract structured and bulk items from websites
2. **Capture Text**: Extract individual text content
3. **Capture Screenshot**: Get fullpage or visible section screenshots

## Configuration

### Required Settings
- **JWT Secret**: Automatically generated secure key
- **Encryption Key**: For securing sensitive data
- **MinIO Credentials**: Access and secret keys for file storage
- **Database Settings**: Name, user, and password

### Storage
The app uses several storage systems:
- PostgreSQL for data storage
- Redis for job scheduling
- MinIO for file storage (screenshots, etc.)

### Additional Features
- BYOP (Bring Your Own Proxy) support
- Scheduled robot runs
- Anti-bot protection bypass options
- Google Sheets integration

## Getting Started

1. Install through RunTipi
2. Configure required settings
3. Access the web interface
4. Create your first robot:
   - Choose extraction type
   - Train robot actions
   - Set schedule (optional)
   - Start extracting data

For more information, visit [Maxun Documentation](https://docs.maxun.dev/).