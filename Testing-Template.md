```markdown
# Testing Template

## Unit Tests

- **Framework**: Jest for JavaScript/TypeScript, pytest for Python
- **Structure**: `describe` → `it` / `test` → assertions (`expect`)

## Example: JavaScript Unit Test (Jest)

```javascript
// Basic unit test using Jest
describe('add function', () => {
  // Test case 1: normal positive numbers
  it('adds two positive numbers correctly', () => {
    expect(add(2, 3)).toBe(5);
  });

  // Test case 2: negative + positive
  it('adds a negative and a positive number correctly', () => {
    expect(add(-1, 5)).toBe(4);
  });

  // Test case 3: zero handling
  it('handles zero correctly', () => {
    expect(add(0, 7)).toBe(7);
  });

  // Test case 4: invalid input (edge case)
  it('returns NaN when inputs are not numbers', () => {
    expect(add('2', 3)).toBeNaN();
  });
});
## Integration Tests
- Test API endpoints.
- Mock dependencies.

## Coverage Goals
- Aim for 90% branch coverage.
- Run: npm test --coverage

## AI Tips
- Prompt AI: "Generate tests for this function: [code]".
- Review for edge cases.
