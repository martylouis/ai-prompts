# Generate API Documentation

## Description

Generate comprehensive API documentation from code comments, function signatures, and existing documentation.

## Usage

```
/generate-api-docs [language] [framework] [output-format]
```

## Parameters

- `language`: Programming language (e.g., python, javascript, typescript, java)
- `framework`: Framework or library (e.g., express, flask, django, react)
- `output-format`: Documentation format (e.g., markdown, openapi, jsdoc, sphinx)

## Examples

### Generate OpenAPI spec for Express.js API

```
/generate-api-docs javascript express openapi
```

### Create Markdown docs for Python Flask app

```
/generate-api-docs python flask markdown
```

### Generate JSDoc for TypeScript React components

```
/generate-api-docs typescript react jsdoc
```

## Output

The command will analyze your codebase and generate:

- API endpoint documentation
- Request/response schemas
- Authentication requirements
- Error handling documentation
- Usage examples
- Code samples

## Requirements

- Codebase with function/class definitions
- Existing comments or docstrings (optional but recommended)
- Clear naming conventions for better analysis

## Tips

- Use descriptive function and parameter names
- Include JSDoc or similar comment blocks
- Organize code with clear separation of concerns
- Provide example usage in comments
