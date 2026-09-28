# Phase 6 – Project Testing

## Test Categories
### Functional Testing
Verify registration, login, logout, planner forms, recommendation generation, and history.

### Validation Testing
Test empty fields, invalid budgets, zero/negative values, very large budgets, and missing optional data.

### AI Testing
Use multiple budgets and preferences and verify that responses remain relevant to the selected category.

### Multimodal Testing
Test Jewelry Planner with no image, valid outfit image, and unsupported/invalid image input.

### UI Testing
Check navigation, forms, recommendation cards, and responsiveness.

## Sample Test Cases
| ID | Test | Expected Result |
|---|---|---|
| T01 | Valid home budget | Home recommendations displayed |
| T02 | Missing budget | Validation message |
| T03 | Valid party request | Event recommendations displayed |
| T04 | Jewelry + outfit image | Style-aware recommendations |
| T05 | Invalid login | Authentication error |
| T06 | History request | Previous recommendations displayed |
