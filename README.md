# Betting Data Processor V2

Enhanced betting data processor with MCP integration, user authentication, and production-ready architecture.

## Project Overview

A modernized version of the betting data processor that adds:
- User authentication and subscriptions
- Database integration via MCP
- Enhanced data visualization
- Production-ready architecture

## Project Structure

```
/server
  /src
    /api         # API routes and controllers
    /services    # Business logic
    /database    # Database models and migrations
    /mcp         # MCP service integrations
    /utils       # Utility functions
  /config       # Configuration files
  /scripts      # Database scripts and utilities

/client
  /src          # Frontend application
  /public       # Static assets

/docs           # Project documentation
```

## MCP Integrations

This project leverages several MCP tools:
1. `@modelcontextprotocol/server-sqlite` - Development database
2. `isaacwasserman/mcp-vegalite-server` - Enhanced visualizations
3. `@modelcontextprotocol/server-memory` - Session management

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/FL232323/betting-data-processor-v2.git
cd betting-data-processor-v2
```

2. Install dependencies:
```bash
# Server dependencies
cd server
npm install

# Client dependencies
cd ../client
npm install
```

3. Setup development database:
```bash
cd server
npm run setup-db
```

4. Start development servers:
```bash
# Start API server
npm run dev

# Start client (in another terminal)
cd ../client
npm run dev
```

## Development Environment

- Server runs on http://localhost:3000
- Client runs on http://localhost:5173

## Requirements

- Node.js 18+
- Python 3.8+
- SQLite 3

## Migration from V1

This version enhances the original betting data processor with:
- User authentication
- Persistent data storage
- Enhanced visualizations
- Production deployment readiness

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
