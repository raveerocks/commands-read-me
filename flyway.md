| Command                | Description                                                      |
|------------------------|--------------------------------------------------------------|
| 🏁 `migrate`               | Migrate the database to the latest version.                   |
| ⏫ `clean`                 | Clean (drop) all database objects.                            |
| 🔄 `undo`                  | Undo the most recent applied migration.                       |
| 🔄 `validate`              | Validate the applied migrations against the available ones.   |
| 📝 `info`                  | Show the details of all applied and pending migrations.       |
| 📝 `repair`                | Repair the metadata table after a failed migration.           |
| 🔄 `baseline`              | Baseline an existing database to a specific version.          |
| ➕ `migrateToBaseline`      | Migrate to a specific baseline version.                       |
| ⬆️ `undoAll`               | Undo all applied migrations.                                  |
| ⏪ `baselineRepair`         | Repair the metadata table after a failed baseline.            |
| 🔒 `lock`                   | Lock the metadata table to prevent concurrent migrations.     |
| 🔓 `unlock`                 | Unlock the metadata table.                                    |
| 🔄 `pending`               | Show the details of pending migrations.                       |
| 📝 `repairChecksums`       | Repair the checksums of the applied migrations.               |
| 📝 `undoLastN`             | Undo the N most recent applied migrations.                    |
| 🔄 `validateWithFlyway`    | Validate the applied migrations using a different Flyway instance. |
| 🔍 `history`               | Show the details of all applied migrations.                   |
| 📋 `baselineVersion`       | Retrieve the baseline version.                                |
| 📋 `pendingCount`          | Count the number of pending migrations.                       |
| 📋 `pendingBaseline`       | Check if there is at least one pending migration without a baseline. |
| 📋 `currentStatus`         | Show the current status of all migrations.                    |
| 🌐 `repairOnValidationError` | Repair the metadata table when a validation error occurs.    |
| 🌐 `outOfOrder`            | Allow out-of-order migrations.                                |
| 🔍 `resolvedMigration`      | Retrieve the resolved migration for a version.                |
| 🔄 `validateOnMigrate`      | Validate applied migrations during migration.                 |
