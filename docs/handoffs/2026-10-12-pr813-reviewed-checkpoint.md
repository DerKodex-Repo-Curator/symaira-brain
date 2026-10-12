# Reviewed Skills checkpoint and historical evidence handoff

## Goal and boundaries

Preserve the previously reviewed Skills/startup work and its original separate source and review revisions on GitHub. This is an archival source checkpoint, not the current PR implementation, accepted native parity, integration or a release.

The base code commit is `149c39e75d4282f0e7252dff58d44aabd4b95317`. Its thirteen commits beyond `2f6880815a4aa65c4a2d7810240ef0cfd1effe4d` include profile-bound memory/audit/history startup, scoped YAML value/document encoding, Windows render-lock ownership, number serialization under CLI feature unification, comparison-cache hashes, retained render transactions and restore/executable modes. The earlier startup and YAML source tips below are independent originals, not ancestors to be silently treated as identical to this integrated checkpoint.

The later `handoff/20261012-rust-wip` source is separate and already preserves newer Skills reference work and 24 Memory/Browse WIP files. Neither it nor the current draft PR813 head is overwritten or merged by this publication. Do not select a historical variant as the new implementation base without reconciling the actual current PR and source differences.

**Next bounded task:** prepare and independently inspect a privacy-safe export of the historical evidence described below, preserving each original digest, source binding, complete failure/result counts and the exact distinction between original and redacted bytes. Until a safe reachable export or an independently approved replacement evidence route exists, historical acceptance reuse and the complete cloud handoff remain blocked. Do not call the source migration complete.

## Exact source identity

Repository: https://github.com/danieljustus/symaira-brain, public, non-fork.

| Remote branch | Base code / original commit | Role |
|---|---|---|
| `handoff/20261012-pr813-reviewed` | `149c39e75d4282f0e7252dff58d44aabd4b95317` | This documentation-only archival checkpoint; final immutable HEAD is supplied by the external verification receipt |
| `symaira-brain/t_11cd8f23-pr-813-independently-verify-repairs-clea` | `149c39e75d4282f0e7252dff58d44aabd4b95317` | Exact original integrated source tip, retained separately |
| `symaira-brain/t_b56385b0-correct-834-startup-spec-findings-withou` | `b728a631c1795314295597d1ec7d7bc0612e7583` | Exact original startup repair |
| `symaira-brain/t_5b5e2061-finish-835-scoped-yaml-repair-typed-corp` | `c440fa060740922c63b37136773d69e382fb6ed4` | Exact original YAML repair |
| `hermes-subagent/subagent-sa-0-70dcd616` | `b043fb195ea88315229a0c050641602cd4a019c5` | Original independent specification review, `independent-spec-review-3276.md` |
| `hermes-subagent/subagent-sa-1-903d07f1` | `1c1e2a391713654ce28e755f31d316ad167268d5` | Original independent quality review, `migration/independent-quality-review-3276.md` |
| `handoff/20261012-rust-wip` | `12fbeb610800f62f861bb61cc0430cc8c8e91924` | Separate later source checkpoint and Draft PR865 |
| `oracle/skills-control-nofollow-v1` | `ce909711d6e7125d281840d14744e7aa987f626f` | Separately versioned corrected Go reference for the later checkpoint, not substituted into this historical result |

The current candidate PR is https://github.com/danieljustus/symaira-brain/pull/813. At closeout it was OPEN/DRAFT, auto-merge disabled, head `578d201f579c45d13af3c076277e87ef8dcf6f74` on `issue/764-json-eof-state-correction`. This differs from both preserved checkpoints. Re-read before continuing; never silently substitute a later HEAD for a tested revision.

The later source handoff is `docs/handoffs/2026-10-12-rust-continuation.md` at `12fbeb610800f62f861bb61cc0430cc8c8e91924`, with independent verification at https://github.com/danieljustus/symaira-brain/pull/865#issuecomment-6119857759. The final commit containing this document is identified outside the document, avoiding a self-referential SHA.

## Required inputs and disposition

| Input | Location / identity | Disposition |
|---|---|---|
| Complete source, vendors, generated scalar/document fixtures and their provenance | Exact commits above; `Cargo.toml`, `Cargo.lock`, `go.mod`, `go.sum`, `rust/symbrain-skills/vendor/`, `rust/symbrain-skills/tests/fixtures/` | Published source; do not copy uncommitted operator files into a checkout |
| Immutable historical Go source | Same repository, `dcddcef0df5789123c7c9a7ebe6e01f10e941f2c`; Go1.26.7 | Reconstruct through the existing `scripts/skills-argv-oracle/build_go.py` producer and its declared receipt contract; do not edit the oracle or bless arbitrary binaries |
| Rust LLM Git dependency | Public https://github.com/danieljustus/symaira-corekit at `04d1411adb57aa602b992509121011aa7666ff1a` | Pinned in the manifest/lock; obtain through the normal locked Cargo resolver |
| Historical native/review evidence archive | `t_11cd8f23-verified-blocker-evidence.zip`, SHA-256 `e03876a52e4892c535f8c6fb8f52ef8c48a15e85eca1099d294506989faa07d8`, 4,603,681 bytes, 41 CRC-valid members | **Blocked for cloud access.** Original retained by the operator; no approved remote URL exists. Nine receipt members contain personal absolute home paths. No unmodified public upload or pretend-access claim |
| Later Memory/Browse WIP | `docs/handoffs/2026-10-12-rust-inputs.json` at `12fbeb610800f62f861bb61cc0430cc8c8e91924` | All 24 file digests match the retained original, published snapshot and independent GitHub checkout; not merged here |

The historical archive contains the complete `native-local-final-149.json`, review reports, source/compiler closure receipts, Git-index binary observations and raw command logs. An operator-local attachment is not a GitHub artifact. A redacted derivative must have its own inventory and digests and must never masquerade as the original hash-pinned receipt. Rebuilding a binary does not recover a historical raw observation. No release, expiring Actions artifact or paid storage is used as a durable substitute.

Required original evidence is not classified as an exclusion. All local originals remain unchanged. Reproducible build caches, generated product binaries, Python bytecode, Finder metadata, unrelated private planning/control databases and personal data are excluded because they are not source inputs to these scoped checks. The earlier rejected hand-written YAML prototype is superseded and is not an input to this reviewed revision; its public rejection remains recorded at https://github.com/danieljustus/symaira-brain/issues/835#issuecomment-6087882514. No old source or failed capture is deleted.

No Git submodule or Git LFS input is required by the inspected root source. Separate Browse/Operate/Scope workspaces and Apple platform locks retain their own gates; passing a root check does not cover them. Production credentials, signing material, Vault data, personal memory and live stores are not included. No provider credential is needed for the focused checks below. Future authorized secret-dependent operations must use the operator-approved secret manager, never repository files or chat messages.

## Actual evidence and known failure

The original native report was parsed again from the retained archive during closeout: status `failed`, `native_surface_gate_passed=false`, 1,112 required cases, 403 collected, 402 matched, one mismatch (`mcp-018-skills_restore`), zero collected controls. The 709 missing cases are not passes. The raw index difference remains recorded. The narrow owner-approved next comparator correction may address only proven volatile Git-index stat-cache fields; preserve full raw bytes/SHA, all nonvolatile index fields, all other protocol/filesystem state, negative controls and independent review. That approval is not an executed repair or native acceptance.

The archival code has an independently reviewed bounded source scope, not complete native/platform approval. Read the exact public review revisions and these code-local contracts:

- `docs/adr/startup-state-opt-in-834.md`
- `docs/adr/skills-yaml-value-preservation-835.md`
- `docs/adr/skills-yaml-repair-local-835.md`
- `scripts/skills-native-oracle/README.md`

| Command / check | Tested source | Environment | Actual closeout result |
|---|---|---|---|
| `python3 -B -m unittest discover -s scripts/skills-native-oracle -p test_startup_controls.py -v` | Clean `149c39e75d4282f0e7252dff58d44aabd4b95317` | macOS27.0.1 arm64, Python3.14.2 | Exit0, 11 synthetic structural controls passed; not native Windows/Go/Rust evidence |
| `python3 -B scripts/skills-native-oracle/test_git_fixture.py -v` | Same clean original code | macOS27.0.1 arm64, Python3.14.2, Git2.54.0 | Exit0, one real-Git fixture test passed; not complete product/native parity |
| `python3 -B -m unittest discover -s scripts/skills-native-oracle -p test_reference_admission.py -v` | Independent GitHub checkout of the separate `12fbeb610800f62f861bb61cc0430cc8c8e91924` | Same host | Exit1, 9 tests, one reproducible pinned-SDK-environment error at `scripts/skills-argv-oracle/compiler_inputs.py:57`; production provenance must not be relaxed |
| Exact-head remote CI for the later `12fbeb610800f62f861bb61cc0430cc8c8e91924` | Same later checkpoint | GitHub Actions, paginated read | 13 complete workflow runs: 11 failed, two succeeded. This is not green CI |
| Fresh direct-GitHub checkout at the final HEAD containing this handoff | Final HEAD supplied by external receipt | Pending | Do not infer success before the external receipt |

Historical compiler, strict lint and native receipts are not rerun or promoted by this documentation-only publication. Exact-head CI for this new archival HEAD will be inspected once in the external receipt; absent, queued or failed runs are not success. No CI repair/watch loop is started. This is a paused source/evidence handoff, not acceptance of all open issues.

## Reproduce the scoped checks

Working directory for all commands: the repository root of a clone fetched directly from GitHub. The repository pins Rust1.98.0 plus rustfmt/Clippy in `rust-toolchain.toml`; Go is pinned to1.26.7 in `go.mod`, not the host's unrelated default Go. Use a supported Python3 (observed3.14.2), Git (observed2.54.0), Bash and, for later compiler work, Rustup and a C toolchain for bundled native dependencies.

```sh
git clone --branch handoff/20261012-pr813-reviewed https://github.com/danieljustus/symaira-brain.git
cd symaira-brain
# Use the immutable final SHA supplied by the external verification receipt.
git checkout --detach <verified-final-head>
git rev-parse HEAD
git status --porcelain=v1 -uall
python3 --version
git --version
python3 -B -m unittest discover -s scripts/skills-native-oracle -p test_startup_controls.py -v
python3 -B scripts/skills-native-oracle/test_git_fixture.py -v
```

No package installation, product binary, private configuration or secret is needed for that standard-library/Git scope. Tests use owned temporary fixture state. For source comparison, fetch each exact additional branch above and require its SHA to match before reading it. `git fetch origin <exact-branch>` and `git rev-parse FETCH_HEAD` are sufficient; do not infer recoverability merely from similar code or a PR title.

Future compiler/native acceptance is separate. Inspect the current source and approved target first. The existing locked workspace commands are `cargo fetch --locked`, `cargo test --locked -p symbrain-skills -p symbrain-cli -p symbrain-gateway`, `cargo clippy --locked -p symbrain-skills -p symbrain-cli -p symbrain-gateway --all-targets -- -D warnings`, and `cargo build --locked -p symbrain-cli`. These commands have **not** been executed by this closeout. `make lint`, the full Go/race gates and platform-specific workflows remain additional obligations, not replaced by these commands or metadata extraction. Use fresh owned HOME/USERPROFILE/XDG and temp/output paths for actual product tests, never real operator stores; applicable variables include `TMPDIR`, `CARGO_HOME`, `CARGO_TARGET_DIR`, `GOTOOLCHAIN` and `CGO_ENABLED`, with no secret values supplied here.

GitHub and public package registries must be reachable for a later locked build. A local Mac must retain its existing storage/reserve guard; a generic cloud runtime should use its own approved filesystem/cache paths, not copy a private launcher or fabricate the mounted local drive. Native Linux and Windows execution must occur on those systems. macOS GUI, filesystem, Keychain/TouchID and signing checks require native hardware, rights and separate authorization. Target-cloud runtime, network permissions, production rights and native GUI/hardware: **not checked** by a local GitHub clone.

## Continue safely

Read repository instructions and verify the requested immutable SHA and remote source identity. First resolve the privacy-safe historical evidence-access task. Then reconcile the newer PR813/#865 source before any implementation. Do not restart obsolete executors, release parked work, merge, enable auto-merge, tag, sign, release, retire Go, delete preserved work or use a paid provider from this handoff alone.

All scoped local execution is paused, with no current run, worker PID or claim on the seven original parked work items; the related current acceptance/integration items are parked too. The shared scheduler is disabled without an active fire claim. Existing remote CI is allowed to finish, but no new cloud job or workflow dispatch is authorized by this document. Implementation acceptance and complete cloud readiness remain open, even after all source refs and scoped fresh-checkout checks are verified.
