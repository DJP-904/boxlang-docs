[comment]: # (Note: This documentation is generated dynamically in the build process.  To modify the contents, change the javadoc on the _invoke method of the BIF class)

# Function: `TransactionRollback`

Rollback the current transaction and discard all unpersisted queries.

## Method Signature
```
TransactionRollback(savepoint=[string])
```
### Arguments

| Argument | Type | Required | Description | Default |
|----------|------|----------|-------------|---------|
| `savepoint` | `string` | `false` | String name of the savepoint to rollback to. If not provided, the entire transaction will be rolled back. |  |

## Examples

```
TransactionRollback(savepoint=[string])
```

## Related
  * [IsInTransaction](IsInTransaction.md)
  * [IsWithinTransaction](IsWithinTransaction.md)
  * [QueryExecute](QueryExecute.md)
  * [TransactionCommit](TransactionCommit.md)
  * [TransactionSetSavepoint](TransactionSetSavepoint.md)