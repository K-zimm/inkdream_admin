# Inkdream Admin

This application demonstrates consuming the shared `inkdream` Go module.

## Running locally

```bash
go run .
```

📝 The `go.mod` file includes a local `replace` directive so that the project can
use unreleased changes while iterating. After you publish a git tag for the
module, remove the `replace` line and run `go get github.com/K-zimm/inkdream@<tag>`.
