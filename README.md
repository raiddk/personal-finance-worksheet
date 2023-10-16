# personal-finance-worksheet

A personal finance worksheet that I've created to help with budgeting and financial insight.

To Do:
~~- [ ] Combine the expense and bills in one column.~~ Copying and pasting values with merged columns would reset the columns back to unmerged.
- [x] Port ods worksheet to xlsx format.
- [ ] Move all data input for each section to an input section.
    - [ ] Move equities and bonds input fields to the input section.
    - [ ] Move cash, liquid, cash equivalents input fields to the input section.
- [ ] Improve UI.
    - [x] Create area for income, bills, expenses, savings input fields.
        - Main input area. Saving is auto calculated now. 10/15
    - [ ] Create area for equities and bonds input fields.
    - [ ] Create area for more cash, liquid, cash equivalents input fields.
- [x] Fix Emergency Savings Calculations tab
- [x] Implement compound interest calculations with the savings over time.
    - ~~This has to be done compunding the annual interest rate monthly to be more precise.~~
    - Decided on doing a simplier compounding formula that does the following:
        - *(Savings Amount for 1 Year + Previous Year Principal with Interest)(1+Input Savings Rate)^1 Year*
        - Stretched it out over 1-10 years
- [ ] Add a way to track retirement related withdrawals and calculations over time.
    - [ ] Figure out where to add that in the income, bills, expenses, savings section.
    - [ ] Copy the compound interest calculation and apply it to the retirement calculations over time.
- [ ] Add automated testing section.
    - [ ] Test that the compound interest calculations are correct.
    - [x] Test that the scenario 1 and 2 bills and monthly total expenses are correct.
    - [ ] Test whether the asset allocations are accurate.
    - [x] Test whether the emergency savings calculation is correct.
- [ ] Utilize stocks functionality within Excel to give real time updates.