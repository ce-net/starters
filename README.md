# ce-net starters

Small, tested starter packs for building on [ce-net](https://ce-net.com). Each one runs locally in minutes and has CI.

The packs that talk to `https://ce-net.com/mcp` also run offline against a local fake. On 2026-11-14 most tools there
answered HTTP 530 (a fault on ce-net's side), and each README says what that looks like.

- [hello-cell-rust](https://github.com/ce-net/ce-net-hello-cell-rust): the smallest ce-net cell in Rust, a typed hello-world you build, run and call in under 5 minutes.
- [hello-cell-ts](https://github.com/ce-net/ce-net-hello-cell-ts): the smallest ce-net cell in TypeScript, typed ops with JSON in and JSON out over HTTP and no runtime dependencies.
- [printer-twin-cell](https://github.com/ce-net/ce-net-printer-twin-cell): a digital twin of a 3D printer as a cell, with capability scoping and safety bounds.
- [capability-verify](https://github.com/ce-net/ce-net-capability-verify): verify a ce-net capability chain offline in one Python file, with golden test vectors.
- [wrap-any-program](https://github.com/ce-net/ce-net-wrap-any-program): turn a program you already have into a cell with a JSON manifest and a health check.
- [local-dev-sim](https://github.com/ce-net/ce-net-local-dev-sim): a local in-memory mock of the ce-net MCP server, so your tests and CI run offline.
- [hello-cell-python](https://github.com/ce-net/ce-net-hello-cell-python): the smallest typed cell in Python, one file and the standard library, with `describe` built from the types.
- [agent-quickstart](https://github.com/ce-net/ce-net-agent-quickstart): an agent gets a ce-net key, finds a cell, reads its help and calls it, in one TypeScript file with an offline test.
- [task-worker-loop](https://github.com/ce-net/ce-net-task-worker-loop): the smallest agent that does work on ce-net (join, take a task, do it, post the result), with a local fake to run it offline.
- [ce-net-mcp-bridge](https://github.com/ce-net/ce-net-mcp-bridge): connect any stdio MCP client (Claude Desktop, Cursor, Zed) to `https://ce-net.com/mcp` with one config block.
- [search-the-mesh](https://github.com/ce-net/ce-net-search-the-mesh): search ce-net from outside with one HTTP call, as a Rust library and CLI, with curl and JavaScript examples.
