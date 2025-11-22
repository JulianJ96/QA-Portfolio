| Field | Value |
|-------|-------|
| **Test Case ID** | TC-002 |
| **Title** | Add Item to Cart |
| **Module/Feature** | Product Page / Cart |
| **Preconditions** | - User is logged into SauceDemo (standard_user / secret_sauce).<br>- User is on the Products page.<br>- Product(s) to add are in stock. |
| **Test Steps** | 1. Navigate to the Products page (if not already there).<br>2. Locate the first product in the list.<br>3. Click the product to open its detail page.<br>4. Click the **Add to Cart** button.<br>5. Verify the button changes to **Remove**.<br>6. Verify the shopping cart icon updates (item count increases).<br>7. Click the shopping cart icon.<br>8. Verify the selected product appears in the cart with correct name and quantity. |
| **Expected Result** | Product is added to the cart successfully.<br>Add to Cart button changes to **Remove**.<br>Shopping cart icon updates item count.<br>Product appears in cart with correct name and quantity. |
| **Actual Result** | Product was added to the cart successfully.<br>Add to Cart button changed to **Remove**.<br>Shopping cart icon updated item count.<br>Product appears in cart with correct name and quantity. |
| **Status** | ✔️ **Passed** |

**Notes:**  
- The backpack item HTML is missing a title.  
- The last product on the list is missing a header/title element.

**Jira Issue:** [SCRUM-7](https://julianjqa.atlassian.net/browse/SCRUM-7)
