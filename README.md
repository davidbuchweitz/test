# Tobbins registry test fixture

Run `tob install` followed by `tob examples/demo.tob` (prints 12).

Published immutable fixtures: DavidBuchweitz.Foundation 1.0.0; DavidBuchweitz.Test 1.0.0, 2.0.0 and 2.0.1. Foundation remains hidden from discovery but installable by version and as a dependency. The first two Test snapshots intentionally reference a missing dev-only package to verify that dev dependencies do not propagate transitively. Version 2.0.1 has an installable root development graph.
