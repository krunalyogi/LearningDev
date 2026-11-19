# DBMS Progress Log — 19 November 2026

**Database:** PostgreSQL  
**Practical:** College Practical 1

### Topics Covered

1. **UPDATE**
   - Updating existing records.
   - Using `SET` to modify column values.
   - Using `WHERE` to target specific records.
   - Updating multiple columns in one query.
   - Performing arithmetic updates (`balance = balance + 5000`).
   - Understanding the consequences of omitting `WHERE`.

2. **Transactions**
   - `BEGIN` — starting a transaction.
   - `COMMIT` — permanently saving transaction changes.
   - `ROLLBACK` — discarding uncommitted changes.
   - Understanding transaction lifecycle.
   - Understanding why transactions are important in banking operations.

### Practical Implementation

- Corrected A005's city from `Vadodra` to `Vadodara`.
- Executed UPDATE queries on the ACCOUNT table.
- Tested transactions using `BEGIN`, `UPDATE`, and `ROLLBACK`.
- Verified that rollback restores the previous committed balance.
- Understood that rollback cannot undo an already committed transaction.

### Important Concepts Learned

- Repeated UPDATE statements apply their changes repeatedly.
- Arithmetic updates use the existing database value.
- Missing WHERE clauses can unintentionally update every row.
- PostgreSQL marks a transaction as aborted after certain statement errors until it is rolled back.
- COMMIT and ROLLBACK are alternative transaction-ending decisions.

### Current Progress

| Topic | Status |
|---|---|
| CREATE TABLE | Studied + Implemented |
| Data Types | Studied |
| INSERT INTO | Studied + Implemented |
| UPDATE | Studied + Practiced |
| BEGIN | Studied + Tested |
| COMMIT | Studied |
| ROLLBACK | Studied + Tested |

### Next Session

- DELETE statement
- DELETE with WHERE
- Difference between DELETE, TRUNCATE and DROP

**Today's focus:** Understanding how to modify database records safely and manage transactions in PostgreSQL.