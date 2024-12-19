# ComplianceGuard

A comprehensive HR compliance and policy management platform for small businesses.

## Overview

ComplianceGuard is a done-for-you HR policies and compliance documents platform designed specifically for small businesses. It provides automated updates, advisory services, and streamlined document management to ensure ongoing compliance and reduce administrative burden.

## Key Features

- 📄 Automated policy updates and compliance monitoring
- 📁 Document management and template library
- ⚙️ HR policy customization engine
- 📋 Compliance audit trails
- 💬 Advisory services and support
- 📨 Automated distribution and tracking

## Technical Stack

- Frontend: WordPress + Elementor Pro
- Automation: Make (formerly Integromat)
- Database: MySQL
- Document Management: Google Drive API
- Communication: HubSpot (free tier)

## Installation

1. Install WordPress and required plugins:
   - Elementor Pro
   - Custom Post Type UI
   - Advanced Custom Fields Pro
   - WP REST API

2. Configure Google Drive API integration
3. Set up Make workflows
4. Configure HubSpot integration

## Development Setup

```bash
# Clone the repository
git clone https://github.com/YourlocalJay/complianceguard-wp.git

# Navigate to the project directory
cd complianceguard-wp

# Install development dependencies
npm install
```

## Project Structure

```
complianceguard-wp/
├── wp-content/
│   ├── plugins/
│   │   └── complianceguard/
│   │       ├── includes/
│   │       ├── admin/
│   │       └── public/
│   └── themes/
│       └── complianceguard-theme/
├── automation/
│   └── make-workflows/
└── docs/
    ├── setup/
    └── api/
```

## Support

For support inquiries, please contact support@complianceguard.com