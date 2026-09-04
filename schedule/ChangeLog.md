# CHANGELOG 2INVOICESPLIT FOR <a href="https://www.dolibarr.org">DOLIBARR ERP CRM</a>

## 22.1.0
- New: Fixed payment days per thirdparty (TK2607-0754). A thirdparty can now have one or more fixed days of month configured; when set, they take priority over the global fixed day of the payment condition and the calculated due date is pushed forward to the next matching day.

## 22.0.0
- New: Compatibility with Dolibarr 22.0.0

## 21.0.0
- New: Compatibility with Dolibarr 21.0.1
- New: Custom invoice splits

## 20.0.0
- New: Compatibility with Dolibarr 20.0.0
- Fix: Bug on schedule list.

## 19.0.1
- Fix: Bug on schedule list

## 19.0.0
- New: Compatibility with Dolibarr 19.0.0

## 17.1.0
- New: Compatibility with PHP 8
- Fix: Expirations of 1 date does not make them good

## 17.0.0
- New: Compatibility with Dolibarr 17.0.0
- Fix: Minor bugs

## 16.0.0
- New: Compatibility with Dolibarr 16.0.0

## 15.0.1
- Fix: Boxes don't show correctly

## 15.0.0
- New: Compatibility with Dolibarr 15.0.0

## 14.0.1
- Fix: Add decalogs correctly

## 14.0.0
- New: Compatibility with Dolibarr 14.0.0

## 12.0.0
- New: Compatibility with Dolibarr 12.0.0<br/>
- New: Paymode column in list of next schedules<br/>
- New: Change bill's limit pay date field to the date of bill's next schedule<br/>
- Fix: Invoice split's rights and references

## 11.0.1
- Fix: Error in bill's reference on the schedule's list

## 11.0.0
- New: Compatibility with Dolibarr 11.0.0
- New: Calcule first schedule with the Dolibarr Standard (end of month, decalogue...)

## 10.0.2
- Fix: Paying bills from a third party creates schedules on other bills

## 10.0.1
- Fix: It doesn't filter by commercials in case the user didn't have permission to see all schedules

## 10.0.0
- New: Compatibility with Dolibarr 10.0.0<br/>
- Fix: MYSQL strict mode

## 9.0.0
- New: Compatibility with Dolibarr 9.0.0

## 8.0.2
- Fix: Fill cond_reglement_code when is empty

## 8.0.1
- Fix: Wrong Paid in schedule tab on facture

## 8.0.0
- New: Compatibility with Dolibarr 8.0.0<br/>
- New: Add schedule for suppliers<br/>
- Fix: Total_TTC wrong calculate

## 7.0.0
- New: Compatibility with Dolibarr 7.0.0

## 5.0.2
- Fix: Bug on maturities that have already received payments

## 5.0.1
- Fix:Error in the application of payments in some schedules

## 5.0.0
- Fix: Compatibility with Dolibarr 5.0

## 4.0.3
- Fix: Bug when modify invoice amount

## 4.0.2
- Fix: Bug loading client info

## 4.0.1
- Fix: Corrected display of some decimal

## 4.0.0
- New: Fix Dolibarr 4.0<br/>
- Fix: User rights<br/>
- Fix: Compatibility with Dolibarr 4

## 3.9.0
- New: Fix Dolibarr 3.9

## 3.8.0
- New: Module creation.
