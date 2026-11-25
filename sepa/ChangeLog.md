# CHANGELOG SEPA FOR <a href="https://www.dolibarr.org">DOLIBARR ERP CRM</a>

## 24.0.0 [2026-07-30]
- New: Compatibility with Dolibarr 24.
- Fix: Compatibility with Dolibarr 23 (bank account of the request found by invoice + withdrawal receipt, since llx_prelevement_lignes.fk_prelevement_demande only exists from v24).
- Fix: Dolibarr 14-16: the validation before creating a direct debit order queried llx_prelevement_demande (llx_prelevement_facture_demande before v17) and fk_societe_rib (v21+); the SQL error was ignored and the order was created without checking IBAN/BIC/mandate/holder. A read error now blocks the order.
- Fix: Dolibarr 14: default customer bank account was not found (different CompanyBankAccount::fetch() signature), so the file could not be generated.
- Fix: Dolibarr 14-17: pending direct debit list uses the right request table and only filters by type from v18.
- New: Create direct debits for members
- New: Possibility to delete direct debit requests from the list
- New: Possibility of entering SEPA data directly at the time of generating the direct debit
- New: Use the RUM number as a reference for the mandate

## 22.0.0 [2025-11-17]
- New: Compatibility with Dolibarr 21.
- New: Compatibility with Dolibarr 22.

## 20.0.0 [2024-08-12]
- New: Compatibility with Dolibarr 20
 
## 19.0.0 [2024-07-17]
- New: Compatibility with Dolibarr 19

## 17.0.1 [2023-06-09]
- Fix: It does not show a list of direct debits on Dolibarr 17

## 17.0.0 [2023-02-24]
- New: Compatibility with Dolibarr 17

## 16.0.0 [2022-06-20]
- New: Compatibility with Dolibarr 16

## 15.0.0 [2022-05-04]
- New: Compatibility with Dolibarr 15

## 14.1.0 [2021-10-18]
- New: Inclusion of standard 58

## 14.0.0 [2021-09-17]
- New: Compatibility with Dolibarr 14

## 12.0.0 [2020-07-13]
- New: Compatibility with Dolibarr 12

## 11.0.0 [2020-02-12]
- New: Compatibility with Dolibarr 11

## 10.0.0 [2019-08-08]
- New: Compatibility with Dolibarr 10

## 9.0.0 [2019-02-18]
- New: Compatibility with Dolibarr 9

## 8.0.1 [2019-01-25]
- Fix: Group invoices by third in MYSQL, only php versions > 7

## 8.0.0 [2018-08-17]
- New: Compatibility with Dolibarr 8

## 7.0.0 [2018-08-01]
- New: Compatibility with Dolibarr 7

## 5.0.2 [2017-09-08]
- Fix: Regresion

## 5.0.1 [2017-06-16]
- Fix: Admin correction

## 5.0.0 [2017-06-09]
- Fix: Compatibility Dolibarr 5.0

## 4.0.1 [2017-01-20]
- Fix: Bug deleting company with mandate

## 4.0.0 [2016-10-17]
- New: Withdrawal list<br/>
- Fix: Compatibility Dolibarr 4.0 & PHP 7

## 3.9.0 [2016-04-01]
- New: Group invoices of same customer<br/>
- New: Custom concepts

## 3.8.0 [2015-10-22]
- New: Compatibility Dolibarr 3.8

## 3.7.0
- New: Spanish Norm 58

## 3.6.0
- New: Improve error messages<br/>
- New: Compatibility with B2B<br/>
- New: Suffix change by withdrawal type

## 3.5.2
- Fix: Bug when special characters

## 3.5.1
- Fix: Bug when no file is generated<br/>
- Fix: Bug in date of charge

## 3.5.0
- New: Module develop
