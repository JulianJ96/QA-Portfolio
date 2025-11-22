# Test Case: TC-Inv-BETA-TR-01 – Training Mode Input Display Accuracy (Bulletproof)

| **Field** | **Details** |
| :--- | :--- |
| **Test Case ID** | TC-Inv-BETA-TR-01 |
| **Title** | Training Mode Input Display Accuracy – Invincible VS Beta (Bulletproof) |
| **Feature Area** | Training Mode / Input Display / Controls / Gameplay Systems |
| **Preconditions** | - Game launched and on main menu<br>- Controller(s) connected and working<br>- Training Mode selected<br>- Character selected: **Bulletproof**<br>- Input Display turned on (if available)<br>- Training Dummy set to Stand or Block |
| **Test Steps** | 1. Enter Training Mode<br>2. Select Practice Mode<br>3. Select **Bulletproof** as Player 1<br>4. Select Random for Dummy<br>5. Perform basic attacks (light, medium, heavy) and record input registration<br>6. Perform special moves / combo motions (e.g., quarter circle, directional + attack) and observe input display<br>7. Repeat each move 5–10 times for consistency<br>8. Record any incorrect input registration, skipped frames, or misfires<br>9. Observe visual feedback on input display and character response |
| **Expected Result** | - All inputs register correctly in the input display<br>- No misfires or skipped actions<br>- Visual cues (hit animation, sound effects) correspond to inputs<br>- Character responds correctly to all directions and attacks<br>- Input history updates accurately for repeated attempts |
| **Actual Result** | - All basic attacks and special moves registered correctly in the input display<br>- Input display and visual feedback matched expected behavior for every move<br>- No misfires, skipped frames, or glitches observed<br>- Actual results aligned fully with expected results |
| **Status** | ✔️ Passed |
| **Evidence** | Will be in Jira linked below |
| **Notes** | - The standard controls for special moves are directional buttons. Quarter circle forward/back moves are also an option.<br>- Medium attacks do not have an auto-combo like Light attacks<br>- Heavy attacks either launch the opponent or spike to the ground for a ground bounce<br>- Combo break is implemented in the game<br>- My inputs were not perfectly clean, but moves still executed correctly |
| **Jira Issue** | [SCRUM-09](https://julianjqa.atlassian.net/browse/SCRUM-9) |
