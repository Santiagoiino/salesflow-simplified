# SalesFlow - Automated Sales Management System

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![n8n](https://img.shields.io/badge/n8n-1.0.0-orange)
![License](https://img.shields.io/badge/license-MIT-green)

## Overview
SalesFlow is an intelligent automation system that monitors email inboxes for sales notifications from multiple channels (Marketplace, Web, Direct) and processes them automatically.

## Demo Version Features
- Email monitoring and processing
- Basic AI-powered sale detection
- Channel classification (Marketplace/Web/Other)
- Airtable integration for data storage
- Real-time Telegram notifications

## Enterprise Version Features
- Advanced AI processing
- Multi-channel pattern recognition
- Custom business rules engine
- Detailed data extraction
- Advanced error handling
- Historical data analysis
- Custom integrations
- Advanced reporting

## Technical Stack
- **n8n**: Workflow automation platform
- **Gmail API**: Email monitoring
- **Groq AI**: Sale classification
- **Airtable**: Database storage
- **Telegram**: Notifications

## Setup Requirements
1. n8n instance
2. Gmail account
3. Groq API key
4. Airtable account
5. Telegram bot

## Quick Start
1. Clone this repository
2. Import workflow to n8n
3. Configure credentials:
   - Gmail OAuth2
   - Groq API
   - Airtable API
   - Telegram Bot Token
4. Set up Airtable base with required fields:
   - Date
   - Channel
   - Product
   - Customer
5. Activate workflow

## Demo Limitations
The demo version includes basic functionality to showcase the system's potential. For advanced features and custom implementations, please contact us for the Enterprise version.

## License
MIT License - see [LICENSE.md](LICENSE.md)

## Author
Santiago Iino Cotado 