# Lab 3 – Design Patterns

## Objective

Identify and apply appropriate software design patterns to the search engine while keeping the implementation understandable, testable, and maintainable.

## Suggested work

1. Review the system requirements and architecture from Labs 1 and 2.
2. Identify design problems that would benefit from a pattern.
3. Select patterns based on their actual use case rather than adding patterns unnecessarily.
4. Implement each pattern under `src/`.
5. Document the problem, pattern roles, rationale, and trade-offs.
6. Add tests demonstrating expected behavior.

## Candidate patterns (to validate)

| Pattern | Possible application |
| --- | --- |
| Strategy | Allow interchangeable ranking or query-processing algorithms |
| Factory Method | Encapsulate creation of supported document parsers |
| Observer | Notify components when an index is updated, if event-driven updates are needed |

These are suggestions only. Record the patterns actually used by the implementation.

## Source layout

Place implementation code and tests in `src/`. Add subdirectories as needed and document how to build and run the lab.

## Pattern report template

For each pattern, document:

- **Problem:** What design issue is being addressed?
- **Context:** Where does the issue occur in this project?
- **Solution:** How is the pattern structured?
- **Participants:** Which classes or modules play each role?
- **Consequences:** What benefits and trade-offs result?
- **Tests:** How is the behavior verified?

## Status

Initial scaffold. Replace candidate patterns with the final design decisions and implementation details.
