@"
# 🏗 Project Architecture

## Folder Structure
- src/
  - controllers/
  - models/
  - routes/
  - services/
- tests/
- config/

## Data Flow
- User -> Routes -> Controller -> Service -> Model -> DB
- Response flows back the same way

## Guidelines
- Keep files <300 lines
- Separate business logic from controllers
- Follow Feature-Based structure
"@ | Set-Content architecture.md
