# Regression Testing Checklist

Use this checklist after a change to verify that important existing workflows remain stable.

> Adapt the checklist to the actual change impact. Items are not considered passed until they are executed and evidence is recorded.

## Authentication
- [ ] Login with valid credentials
- [ ] Login with invalid credentials
- [ ] Required-field validation
- [ ] Logout ends the user session

## Product catalog
- [ ] Product list loads correctly
- [ ] Product details show expected information
- [ ] Search returns relevant results
- [ ] Empty search results show a helpful message

## Shopping cart
- [ ] Add product to cart
- [ ] Update product quantity
- [ ] Remove product from cart
- [ ] Subtotal and total are recalculated
- [ ] Cart state remains consistent while navigating

## Checkout
- [ ] Required fields are validated
- [ ] Invalid data is rejected with clear feedback
- [ ] Order summary matches cart contents
- [ ] User cannot proceed when mandatory information is missing

## Execution summary

| Field | Value |
|---|---|
| Build / version | To be filled |
| Environment | To be filled |
| Execution date | To be filled |
| Executed by | To be filled |
| Passed | To be filled |
| Failed | To be filled |
| Blocked | To be filled |
| Related defects | To be filled |

**Important:** Do not mark unchecked items as passed. Record blockers and defects separately.
