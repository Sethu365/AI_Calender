**AI Calendar**

AI-powered calendar that lets users create, update, cancel, and list events using natural language commands. Works offline with a local LLM and uses an MCP server for database operations.

**Features**

**Create and manage events** via natural language

**Local LLM** for intent and entity extraction

**MCP server** ensures database operations and validation

**Simple REST API**

**Setup**
# Clone the repository
git clone https://github.com/your-username/ai-calendar.git
cd ai-calendar

# Restore dependencies and build
dotnet restore
dotnet build

dotnet run --project src/Api


**Test API** with Postman or Swagger

Notes

**JWT/OAuth2 authentication** included

**Input validation** and **rate limiting** implemented

Fully **offline support** via local LLM