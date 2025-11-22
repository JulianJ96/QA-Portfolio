**Field** | **Details** |
| :--- | :--- |
| **Test Case ID** | TC-SF6-01 |
| **Title** | Training Mode Input Display Accuracy – Quarter-Circle Forward Motion (QCF) Registration |
| **Feature Area** | Training Mode / Input Recognition / Gameplay Systems |
| **Preconditions** | - PS5 is powered on  
- User is logged in  
- Controller is connected and working  
- Street Fighter 6 is launched  
- Player has reached the main menu  
- Character Selected: **Jamie**  
- Mode entered: Training Mode → Default settings |
| **Test Steps** | 1. From Main Menu, navigate to **Fighting Ground → Training**  
2. Select **Jamie** vs any dummy character  
3. In Training Settings, set **Input Display → ON**  
4. Perform the motion ⬇️⬇️ + Punch (Down Down + P), repeat once  
5. Perform the motion ⬇️→↘️ + Kick (Quarter Circle Forward + K), repeat 10 times at normal pace  
6. Observe the input history on-screen for each attempt |
| **Expected Result** | - Each time ⬇️⬇️ + P is performed correctly, **Input Display shows “The Devil Inside” twice**  
- After this, verify a number or gourd appears showing **2**  
- Each time ⬇️→↘️ + K is performed correctly, **Input Display shows “The Devil Inside” twice** and **Bakkai**  
- No extra or missing inputs should appear |
| **Actual Result** | After performing “The Devil Inside” move, a number and guard appeared representing drink level. Once level 2 was reached, the Bakkai move was input and executed successfully |
| **Status** | ✔️ **Passed** |
| **Evidence** | Will be linked with Jira page |
| **Notes** | Inputs may not have been the cleanest on a controller, but the moves executed correctly |
| **Jira Issue** | [SCRUM-8](https://julianjqa.atlassian.net/browse/SCRUM-8) |
