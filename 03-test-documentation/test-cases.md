# Test Cases — Simulated E-commerce Application

> These are illustrative test cases. They have not been executed against a live application.

| ID | Feature | Scenario | Expected result | Priority |
|---|---|---|---|---|
| TC-LOGIN-001 | Login | Sign in with valid credentials | User is authenticated | High |
| TC-LOGIN-002 | Login | Sign in with an incorrect password | Access is denied and a clear message appears | High |
| TC-LOGIN-003 | Login | Submit empty required fields | Required-field validation is displayed | Medium |
| TC-CART-001 | Cart | Add an available product | Product appears in cart with correct details | High |
| TC-CART-002 | Cart | Increase product quantity | Quantity and subtotal are updated correctly | High |
| TC-CART-003 | Cart | Remove a product | Product is removed and totals are recalculated | Medium |
| TC-CHECKOUT-001 | Checkout | Continue with required fields completed | User can proceed to order review | High |
| TC-CHECKOUT-002 | Checkout | Submit checkout with a required field missing | Submission is blocked and field is identified | High |
| TC-SEARCH-001 | Search | Search for an existing product | Relevant matching products are displayed | Medium |
| TC-SEARCH-002 | Search | Search for a product with no matches | Empty state is displayed clearly | Low |

## Detailed test case example

### TC-CART-001 — Add an available product to the cart

- **Priority:** High
- **Type:** Functional
- **Preconditions:** Product is available for purchase.
- **Test data:** Any product marked as available.

**Steps**
1. Open the product catalog.
2. Select an available product.
3. Open its details page.
4. Select the add-to-cart action.
5. Open the shopping cart.

**Expected result**
The selected product appears in the cart with the correct name, unit price, and initial quantity.

**Execution status:** Not executed.
