# Manual Testing

This section demonstrates a structured approach to manual software testing using an independent, simulated e-commerce application.

## Testing approach

- Review requirements and acceptance criteria before execution.
- Cover positive, negative, boundary, and alternative flows.
- Prioritize critical user journeys and high-impact risks.
- Record preconditions, test data, steps, and expected results.
- Capture clear evidence and report reproducible defects.

## Example coverage areas

| Feature | Example validations |
|---|---|
| Login | Valid credentials, invalid password, empty fields |
| Product catalog | Product visibility, search, filters, details |
| Shopping cart | Add, remove, quantity update, total calculation |
| Checkout | Required fields, address validation, order summary |
| Session | Navigation, logout, session expiration behavior |

## Sample scenario

**ID:** TC-LOGIN-001  
**Title:** Sign in with valid credentials  
**Priority:** High  
**Preconditions:** A test account exists and is active.  
**Steps:**
1. Open the login page.
2. Enter a valid email address.
3. Enter the corresponding valid password.
4. Select the sign-in action.

**Expected result:** The user is authenticated and redirected to the expected post-login page.

**Status:** Not executed — illustrative test case.
