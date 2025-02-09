# unTokens

## Error codes

| Code | Name | Description |
| :--- | :--- | :--- |
| 0 | NO\_ERROR | Not a failure. |
| 1 | UNAUTHORIZED | The sender is not authorized to perform this action. |
| 2 | BAD\_INPUT | An invalid argument was supplied by the caller. |
| 3 | COMPTROLLER\_REJECTION | The action would violate the comptroller policy. |
| 4 | COMPTROLLER\_CALCULATION\_ERROR | An internal calculation has failed in the comptroller. |
| 5 | INTEREST\_RATE\_MODEL\_ERROR | The interest rate model returned an invalid value. |
| 6 | INVALID\_ACCOUNT\_PAIR | The specified combination of accounts is invalid. |
| 7 | INVALID\_CLOSE\_AMOUNT\_REQUESTED | The amount to liquidate is invalid. |
| 8 | INVALID\_COLLATERAL\_FACTOR | The collateral factor is invalid. |
| 9 | MATH\_ERROR | A math calculation error occurred. |
| 10 | MARKET\_NOT\_FRESH | Interest has not been properly accrued. |
| 11 | MARKET\_NOT\_LISTED | The market is not currently listed by its comptroller. |
| 12 | TOKEN\_INSUFFICIENT\_ALLOWANCE | ERC-20 contract must allow Money Market contract to call transferFrom. The current allowance is either 0 or less than the requested supply, repayBorrow or liquidate amount. |
| 13 | TOKEN\_INSUFFICIENT\_BALANCE | Caller does not have sufficient balance in the ERC-20 contract to complete the desired action. |
| 14 | TOKEN\_INSUFFICIENT\_CASH | The market does not have a sufficient cash balance to complete the transaction. You may attempt this transaction again later. |
| 15 | TOKEN\_TRANSFER\_IN\_FAILED | Failure in ERC-20 when transfering token into the market. |
| 16 | TOKEN\_TRANSFER\_OUT\_FAILED | Failure in ERC-20 when transfering token out of the market. |

## Failure Info

| Code | Name |
| :--- | :--- |
| 0 | ACCEPT\_ADMIN\_PENDING\_ADMIN\_CHECK |
| 1 | ACCRUE\_INTEREST\_ACCUMULATED\_INTEREST\_CALCULATION\_FAILED |
| 2 | ACCRUE\_INTEREST\_BORROW\_RATE\_CALCULATION\_FAILED |
| 3 | ACCRUE\_INTEREST\_NEW\_BORROW\_INDEX\_CALCULATION\_FAILED |
| 4 | ACCRUE\_INTEREST\_NEW\_TOTAL\_BORROWS\_CALCULATION\_FAILED |
| 5 | ACCRUE\_INTEREST\_NEW\_TOTAL\_RESERVES\_CALCULATION\_FAILED |
| 6 | ACCRUE\_INTEREST\_SIMPLE\_INTEREST\_FACTOR\_CALCULATION\_FAILED |
| 7 | BORROW\_ACCUMULATED\_BALANCE\_CALCULATION\_FAILED |
| 8 | BORROW\_ACCRUE\_INTEREST\_FAILED |
| 9 | BORROW\_CASH\_NOT\_AVAILABLE |
| 10 | BORROW\_FRESHNESS\_CHECK |
| 11 | BORROW\_NEW\_TOTAL\_BALANCE\_CALCULATION\_FAILED |
| 12 | BORROW\_NEW\_ACCOUNT\_BORROW\_BALANCE\_CALCULATION\_FAILED |
| 13 | BORROW\_MARKET\_NOT\_LISTED |
| 14 | BORROW\_COMPTROLLER\_REJECTION |
| 15 | LIQUIDATE\_ACCRUE\_BORROW\_INTEREST\_FAILED |
| 16 | LIQUIDATE\_ACCRUE\_COLLATERAL\_INTEREST\_FAILED |
| 17 | LIQUIDATE\_COLLATERAL\_FRESHNESS\_CHECK |
| 18 | LIQUIDATE\_COMPTROLLER\_REJECTION |
| 19 | LIQUIDATE\_COMPTROLLER\_CALCULATE\_AMOUNT\_SEIZE\_FAILED |
| 20 | LIQUIDATE\_CLOSE\_AMOUNT\_IS\_UINT\_MAX |
| 21 | LIQUIDATE\_CLOSE\_AMOUNT\_IS\_ZERO |
| 22 | LIQUIDATE\_FRESHNESS\_CHECK |
| 23 | LIQUIDATE\_LIQUIDATOR\_IS\_BORROWER |
| 24 | LIQUIDATE\_REPAY\_BORROW\_FRESH\_FAILED |
| 25 | LIQUIDATE\_SEIZE\_BALANCE\_INCREMENT\_FAILED |
| 26 | LIQUIDATE\_SEIZE\_BALANCE\_DECREMENT\_FAILED |
| 27 | LIQUIDATE\_SEIZE\_COMPTROLLER\_REJECTION |
| 28 | LIQUIDATE\_SEIZE\_LIQUIDATOR\_IS\_BORROWER |
| 29 | LIQUIDATE\_SEIZE\_TOO\_MUCH |
| 30 | MINT\_ACCRUE\_INTEREST\_FAILED |
| 31 | MINT\_COMPTROLLER\_REJECTION |
| 32 | MINT\_EXCHANGE\_CALCULATION\_FAILED |
| 33 | MINT\_EXCHANGE\_RATE\_READ\_FAILED |
| 34 | MINT\_FRESHNESS\_CHECK |
| 35 | MINT\_NEW\_ACCOUNT\_BALANCE\_CALCULATION\_FAILED |
| 36 | MINT\_NEW\_TOTAL\_SUPPLY\_CALCULATION\_FAILED |
| 37 | MINT\_TRANSFER\_IN\_FAILED |
| 38 | MINT\_TRANSFER\_IN\_NOT\_POSSIBLE |
| 39 | REDEEM\_ACCRUE\_INTEREST\_FAILED |
| 40 | REDEEM\_COMPTROLLER\_REJECTION |
| 41 | REDEEM\_EXCHANGE\_TOKENS\_CALCULATION\_FAILED |
| 42 | REDEEM\_EXCHANGE\_AMOUNT\_CALCULATION\_FAILED |
| 43 | REDEEM\_EXCHANGE\_RATE\_READ\_FAILED |
| 44 | REDEEM\_FRESHNESS\_CHECK |
| 45 | REDEEM\_NEW\_ACCOUNT\_BALANCE\_CALCULATION\_FAILED |
| 46 | REDEEM\_NEW\_TOTAL\_SUPPLY\_CALCULATION\_FAILED |
| 47 | REDEEM\_TRANSFER\_OUT\_NOT\_POSSIBLE |
| 48 | REDUCE\_RESERVES\_ACCRUE\_INTEREST\_FAILED |
| 49 | REDUCE\_RESERVES\_ADMIN\_CHECK |
| 50 | REDUCE\_RESERVES\_CASH\_NOT\_AVAILABLE |
| 51 | REDUCE\_RESERVES\_FRESH\_CHECK |
| 52 | REDUCE\_RESERVES\_VALIDATION |
| 53 | REPAY\_BEHALF\_ACCRUE\_INTEREST\_FAILED |
| 54 | REPAY\_BORROW\_ACCRUE\_INTEREST\_FAILED |
| 55 | REPAY\_BORROW\_ACCUMULATED\_BALANCE\_CALCULATION\_FAILED |
| 56 | REPAY\_BORROW\_COMPTROLLER\_REJECTION |
| 57 | REPAY\_BORROW\_FRESHNESS\_CHECK |
| 58 | REPAY\_BORROW\_NEW\_ACCOUNT\_BORROW\_BALANCE\_CALCULATION\_FAILED |
| 59 | REPAY\_BORROW\_NEW\_TOTAL\_BALANCE\_CALCULATION\_FAILED |
| 60 | REPAY\_BORROW\_TRANSFER\_IN\_NOT\_POSSIBLE |
| 61 | SET\_COLLATERAL\_FACTOR\_OWNER\_CHECK |
| 62 | SET\_COLLATERAL\_FACTOR\_VALIDATION |
| 63 | SET\_COMPTROLLER\_OWNER\_CHECK |
| 64 | SET\_INTEREST\_RATE\_MODEL\_ACCRUE\_INTEREST\_FAILED |
| 65 | SET\_INTEREST\_RATE\_MODEL\_FRESH\_CHECK |
| 66 | SET\_INTEREST\_RATE\_MODEL\_OWNER\_CHECK |
| 67 | SET\_MAX\_ASSETS\_OWNER\_CHECK |
| 68 | SET\_ORACLE\_MARKET\_NOT\_LISTED |
| 69 | SET\_PENDING\_ADMIN\_OWNER\_CHECK |
| 70 | SET\_RESERVE\_FACTOR\_ACCRUE\_INTEREST\_FAILED |
| 71 | SET\_RESERVE\_FACTOR\_ADMIN\_CHECK |
| 72 | SET\_RESERVE\_FACTOR\_FRESH\_CHECK |
| 73 | SET\_RESERVE\_FACTOR\_BOUNDS\_CHECK |
| 74 | TRANSFER\_COMPTROLLER\_REJECTION |
| 75 | TRANSFER\_NOT\_ALLOWED |
| 76 | TRANSFER\_NOT\_ENOUGH |
| 77 | TRANSFER\_TOO\_MUCH |



