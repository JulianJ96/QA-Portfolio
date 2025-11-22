# Test Case: SCRUM-8 – SF6 Training Mode Input Display (Jamie)

| **Field** | **Details** |
| :--- | :--- |
| **Test Case ID** | TC-SF6-01 |
| **Title** | Training Mode Input Display Accuracy – Quarter-Circle Forward Motion (QCF) Registration (Jamie) |
| **Feature Area** | Training Mode / Input Recognition / Gameplay Systems |
| **Preconditions** | - PS5 is powered on<br>- User is logged in<br>- Controller is connected and working<br>- Street Fighter 6 is launched<br>- Player has reached the main menu<br>- Character Selected: **Jamie**<br>- Mode entered: Training Mode → Default settings |
| **Test Steps** | 1. From Main Menu, navigate to **Fighting Ground → Training**<br>2. Select **Jamie** vs any dummy character<br>3. In Training Settings, set **Input Display → ON**<br>4. Perform the motion ⬇️⬇️ + Punch (Down Down + P), repeat once<br>5. Perform the motion ⬇️→↘️ + Kick (Quarter Circle Forward + K), repeat 10 times at normal pace<br>6. Observe the input history on-screen for each attempt |
| **Expected Result** | - Each time ⬇️⬇️ + P is performed correctly, **Input Display shows “The Devil Inside” twice**<br>- After this, verify a number or gourd appears showing **2**<br>- Each time ⬇️→↘️ + K is performed correctly, **Input Display shows “The Devil Inside” twice** and **Bakkai**<br>- No extra or missing inputs should appear |
| **Actual Result** | After performing “The Devil Inside” move, a number and guard appeared representing drink level.<br>Once level 2 was reached, the Bakkai move was input and executed successfully |
| **Status** | ✔️ **Passed** |
| **Evidence** | Will be linked with Jira page |
| **Notes** | Inputs may not have been the cleanest on a controller, but the moves executed correctly |
| **Jira Issue** | [SCRUM-8](https://julianjqa.atlassian.net/browse/SCRUM-8) |
