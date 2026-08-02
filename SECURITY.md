# Security policy

This list performs bounded review, not certification. Pin exact versions, inspect diffs before upgrades, use `--ignore-scripts` during dependency intake when possible, and run third-party apps with least privilege and loopback-only bindings.

Never commit API keys or feed them to imported Skills. Treat model files deserialized by Pickle/PyTorch as executable code unless they use a safe tensor format and trusted provenance.

Report a security issue privately to the repository owner before opening a public issue that would expose credentials or a working exploit.
