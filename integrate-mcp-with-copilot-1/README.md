# Integrate MCP with Copilot

This project sets up a server using the Model Context Protocol (MCP) and connects to a PostgreSQL database. It provides functionalities to interact with the database, including listing table schemas, executing read-only SQL queries, and summarizing table information.

## Project Structure

```
integrate-mcp-with-copilot
├── src
│   └── mcp-server.js       # Server setup and database interaction logic
├── package.json             # NPM configuration file
└── README.md                # Project documentation
```

## Features

- **List Table Schemas**: Retrieve and display the schemas of all tables in the connected PostgreSQL database.
- **Run Read-Only SQL Queries**: Execute SQL SELECT queries against the database.
- **Summarize Table Information**: Get the row count, column types, and sample rows from a specified table.

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd integrate-mcp-with-copilot
   ```
3. Install the dependencies:
   ```
   npm install
   ```

## Usage

To start the server, run the following command:
```
node src/mcp-server.js
```

Make sure to configure your PostgreSQL connection settings in the `src/mcp-server.js` file or set the appropriate environment variables.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.