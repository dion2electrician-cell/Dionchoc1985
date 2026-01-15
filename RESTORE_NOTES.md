# Upstream Restoration Notes

## Source
- **Upstream Repository:** https://github.com/gateio/proof-of-reserves
- **Commit Hash:** 76f8e6291a24abc799883d2338999918e7829003
- **Restoration Date:** 2026-01-15

## Directories Restored
The following directories were verified to be identical to upstream:
- `client/` - Client utilities for proof generation and verification
- `utils/` - Utility functions and helpers
- `config/` - Configuration files and handlers
- `example_data/` - Example CSV data for testing

## Files Copied
All files in the above directories match the upstream repository at commit 76f8e6291a24abc799883d2338999918e7829003:

### client/
- keygen.go
- prover.go
- tools.go
- user_proof.go
- verify.go
- witness.go

### utils/
- account_tree.go
- constants.go
- error_codes.go
- redis_lock.go
- secret_manager.go
- tools.go
- types.go
- utils.go

### config/
- .DS_Store
- cex_config.json
- config.go
- config.json
- proof.csv
- user_config.json

### example_data/
- PoR0612.csv

## Build and Test Status
- ✅ `go mod tidy` - No changes needed, dependencies already up to date
- ✅ `go build ./...` - Build successful
- ✅ `go test ./...` - All tests passed (2/2 tests in root package)

## Edits Applied
No edits were necessary. All files were already present and identical to the upstream repository.

## Remaining Issues
None. The project builds and tests successfully without any modifications.

## License
All copied files maintain the Apache License 2.0 from the upstream repository.
