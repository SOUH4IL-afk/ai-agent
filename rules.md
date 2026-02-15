@"
# 🧠 Project Coding Rules

## Naming Conventions
- Variables: camelCase
- Functions: camelCase
- Classes: PascalCase
- Files: kebab-case

## Security
- Validate all external inputs
- Sanitize database queries
- Use environment variables for secrets
- No hardcoded credentials

## Performance
- Avoid N+1 queries
- Use lazy loading
- Prefer streaming over full memory loading

## Clean Code
- Single responsibility per function
- Avoid deeply nested logic (>3 levels)
- Use meaningful variable names
- Add comments only when necessary

## Testing
- Suggest unit tests for new logic
- Check edge cases
"@ | Set-Content rules.md
