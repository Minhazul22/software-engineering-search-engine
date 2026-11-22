# Lab 4 – REST API

## Objective

Expose the search engine's functionality through a documented REST API.

## Suggested endpoint

The following is a starting proposal; confirm the route and behavior against the implementation and course specification.

| Method | Path | Purpose |
| --- | --- | --- |
| GET | `/api/search?q={query}` | Search the indexed collection |

## API design checklist

- Define request parameters, validation, and defaults.
- Define a consistent JSON response schema.
- Define behavior for empty queries and no matches.
- Choose and document appropriate HTTP status codes.
- Add pagination and filters only if required.
- Document error response formats.
- Add automated tests for successful and invalid requests.
- State how to run the service locally.

## Example response (illustrative)

```json
{
  "query": "example search",
  "results": [],
  "total": 0
}
```

Adjust this schema to match the actual API implementation.

## Directory guide

- `src/` – API and application source code.
- `api-documentation/` – OpenAPI specification, endpoint descriptions, and usage examples.

## Status

Initial scaffold. Add implementation, tests, and accurate API documentation as they are developed.
