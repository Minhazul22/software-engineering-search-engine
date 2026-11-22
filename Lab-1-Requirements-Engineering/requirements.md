# Lab 1 – Requirements Engineering

## 1. Project overview

The Software Engineering Search Engine project aims to specify and design a search system that helps users find relevant information from an indexed collection of documents or resources.

> **Working assumption:** The exact data sources, supported file formats, ranking strategy, and user roles are to be confirmed with the project brief and stakeholders. The items below are a starting point, not approved final requirements.

## 2. Goals

- Allow users to submit a search query.
- Return relevant results in a useful and understandable format.
- Provide a maintainable foundation for indexing, searching, and extending the system.
- Document the system's requirements and design decisions.

## 3. Stakeholders and users

| Stakeholder | Interest |
| --- | --- |
| End user | Search for and inspect relevant results |
| Project team | Design, implement, and maintain the system |
| Course instructor / evaluator | Assess completeness and engineering quality |
| System administrator (if applicable) | Configure and operate the system |

## 4. Functional requirements

| ID | Requirement | Priority | Acceptance criteria |
| --- | --- | --- | --- |
| FR-01 | The system shall accept a search query from a user. | Must | A submitted non-empty query is received by the search component. |
| FR-02 | The system shall return a list of results for a valid query. | Must | Results are returned in the documented response format. |
| FR-03 | The system shall order results using a documented relevance strategy. | Must | The ranking strategy is described and applied consistently. |
| FR-04 | The system shall provide a useful response when no results match. | Must | An empty result set is represented without an application error. |
| FR-05 | The system shall validate user input. | Must | Invalid input receives a clear validation response. |
| FR-06 | The system should expose search functionality through a REST API. | Should | The API documentation describes the search endpoint and its parameters. |

## 5. Non-functional requirements

| ID | Requirement | Quality attribute |
| --- | --- | --- |
| NFR-01 | The system should return results within an agreed response-time target under a defined test workload. | Performance |
| NFR-02 | The system should use modular components with clear responsibilities. | Maintainability |
| NFR-03 | API requests and responses should use consistent, documented formats. | Interoperability |
| NFR-04 | Invalid requests should be handled safely and consistently. | Reliability |
| NFR-05 | Any user data collected should be limited to what the application needs and handled securely. | Security / privacy |
| NFR-06 | The project should include setup and usage documentation. | Usability |

## 6. Constraints and assumptions

- The implementation language, framework, database, and deployment environment are not yet specified.
- Search corpus and indexing requirements must be confirmed.
- Performance targets must be agreed and measured against a defined dataset and environment.
- Authentication and authorization requirements depend on the intended users and data.

## 7. Use cases

1. **Search for information:** A user enters a query and receives ranked results.
2. **Review results:** A user inspects result titles, summaries, and available source references.
3. **Handle no matches:** A user receives a clear empty-state response when no results match.
4. **Submit an invalid query:** The system explains the validation problem without failing unexpectedly.

## 8. Open questions

- Which document or content sources should be indexed?
- Which formats must be supported?
- Is indexing performed at startup, on demand, or periodically?
- Which ranking algorithm is required?
- Are filters, pagination, or advanced search needed?
- Is authentication required?
- What response-time and dataset-size targets will be used for evaluation?

## 9. Traceability

Keep requirement IDs stable and reference them from design diagrams, implementation notes, and tests. Update priorities and acceptance criteria when stakeholder decisions are made.
