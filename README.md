# Laboratory Work 1: Git Basics
Author: [Serhii Kruzer 79833]
Reviewer: [Nazar Koldun 79833]

## 1. User Stories
1. **As a** customer, **I want** to register in the system, **so that** I can place orders.
2. **As an** administrator, **I want** to add new products, **so that** I can update the store's inventory.
3. **As a** customer, **I want** to view my purchase history, **so that** I can track my expenses.

## 2. Use Cases
Total of 3 use cases described:

*   **UC-1: User Registration**
    *   **Actor:** Customer
    *   **Action:** The user enters their email and password. The system saves the data and creates an account.
*   **UC-2: Product Management**
    *   **Actor:** Administrator
    *   **Action:** The administrator enters the product name and price, then clicks "Save". The system updates the catalog.
*   **UC-3: Order Placement**
    *   **Actor:** Customer
    *   **Action:** The user adds items to the cart, enters the delivery address, and confirms payment.

## 3. Use Case Diagram
*(Diagram generated using Mermaid)*

```mermaid
pie title Number of Use Cases by Role
    "Customer" : 2
    "Administrator" : 1
flowchart LR
    A([Customer]) --> B(Register)
    A --> C(Place an order)
    A --> D(View history)

    E([Administrator]) --> F(Manage products)
