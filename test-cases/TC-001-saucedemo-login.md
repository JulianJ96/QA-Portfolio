| Field | Value |
|-------|-------|
| **Test Case ID** | TC-001 |
| **Title** | Login with Valid Username and Password |
| **Module/Feature** | Login Page |
| **Preconditions** | - User is on SauceDemo login page.<br>- User has valid credentials: username **standard_user**, password **secret_sauce** |
| **Test Steps** | 1. Navigate to https://www.saucedemo.com<br>2. Enter **standard_user** into Username field.<br>3. Enter **secret_sauce** into Password field.<br>4. Click **Login** button. |
| **Expected Result** | User is redirected to the Product Page. URL changes to `https://www.saucedemo.com/inventory.html`. Header displays **Products**. |
| **Actual Result** | User is redirected to the Product Page. URL changed to `https://www.saucedemo.com/inventory.html`. |
| **Status** | ✔️ **Passed** |

**Jira Issue:** [SCRUM-5](https://julianjqa.atlassian.net/browse/SCRUM-5)
