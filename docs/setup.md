# Development Setup

## Local Development Setup

[To be completed - Step-by-step local development environment setup]

### Prerequisites

- **Node.js**: Version 18+ for frontend development
- **.NET SDK**: Version 8.0+ for backend development
- **Python**: Version 3.11+ for AI engine
- **Docker**: For containerized development
- **Git**: Version control

### Environment Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/alex-enterprisenation/Multi-Tenant-SaaS-AI.git
   cd Multi-Tenant-SaaS-AI
   ```

2. **Backend Setup**
   - Navigate to `src/backend/`
   - Install .NET dependencies
   - Configure connection strings
   - Run database migrations

3. **Frontend Setup**
   - Navigate to `src/frontend/`
   - Install Node.js dependencies
   - Configure environment variables
   - Start development server

4. **AI Engine Setup**
   - Navigate to `src/ai/`
   - Create Python virtual environment
   - Install Python dependencies
   - Configure AI model settings

### Environment Variables

Create `.env` files for each component:

**Backend (.env)**
```
ConnectionStrings__DefaultConnection=your_connection_string
JwtSettings__SecretKey=your_secret_key
JwtSettings__Issuer=your_issuer
JwtSettings__Audience=your_audience
```

**Frontend (.env.local)**
```
NEXT_PUBLIC_API_URL=http://localhost:5000
NEXT_PUBLIC_APP_NAME=Multi-Tenant SaaS AI
NEXTAUTH_SECRET=your_nextauth_secret
NEXTAUTH_URL=http://localhost:3000
```

**AI Engine (.env)**
```
DATABASE_URL=your_database_url
MODEL_STORAGE_PATH=/path/to/models
API_KEY=your_api_key
LOG_LEVEL=INFO
```

### Database Setup

1. **Install PostgreSQL**
2. **Create Database**
3. **Run Migrations**
4. **Seed Initial Data**

### Development Workflow

1. **Start Services**
   - Backend API: `dotnet run`
   - Frontend: `npm run dev`
   - AI Engine: `uvicorn main:app --reload`

2. **Testing**
   - Unit tests for each component
   - Integration tests
   - End-to-end testing

3. **Code Quality**
   - Linting and formatting
   - Type checking
   - Security scanning

### Troubleshooting

Common issues and solutions:

- **Port Conflicts**: Check for existing services on required ports
- **Database Connection**: Verify connection strings and database status
- **Dependencies**: Ensure all required software is installed
- **Environment Variables**: Validate all required variables are set

### IDE Configuration

Recommended IDE setup:

- **VS Code**: Extensions for C#, TypeScript, Python
- **JetBrains**: Rider for .NET, WebStorm for frontend
- **PyCharm**: For AI engine development

### Docker Development

Alternative setup using Docker:

```bash
# Build and run all services
docker-compose up --build

# Individual services
docker-compose up backend
docker-compose up frontend
docker-compose up ai-engine
``` 