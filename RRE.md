# RRE

> A system has not learned a correction merely because it can repeat it. It has learned the correction when the correction changes what the system does next.

**Contradiction → Locate → Revise → Replay → Persist → Attest → Carry Forward**

1. **Contradiction** — Record the expected behavior, what the system actually did, and the evidence that shows the mismatch.
2. **Locate** — Identify the rule, assumption, record, or implementation that governed the behavior. Mark uncertainty when the evidence leaves the cause open.
3. **Revise** — Correct the part that governed the behavior and state what should happen at the next relevant opportunity. Preserve the original record for comparison.
4. **Replay** — Run the triggering case again. Use an equivalent case when the original cannot be repeated. Record the resulting action and compare it with the original behavior and the expected correction.
5. **Persist** — Save the verified correction where it will govern the next relevant action. Record where it lives and verify that the system reads it through its normal execution path.
6. **Attest** — Record the contradiction, change, replay evidence, persistence, and scope of the verified correction. When a material question remains open, such as a failed replay or unverified persistence, record it and leave the correction open.
7. **Carry Forward** — Carry the supported finding into later relevant decisions. Record what changes in prediction, standing, trust, role assignment, credit, or treatment within the finding's scope.

## Revision Status

- **Stated Correction** — The corrected rule can be repeated in speech or writing.
- **Replayed Correction** — The corrected rule produces the expected result when tested against the triggering case or its equivalent.
- **Installed Revision** — The corrected rule changes behavior when an analogous condition recurs.
- **Carried Revision** — The installed correction persists into later relevant decisions without requiring the original subject to repurchase the same correction.

These distinctions are defined in [Attestation Integrity](ATTESTATION-INTEGRITY.md#10-rre-integration).

For a formal Closed Loop Attestation, follow the ordinary review and append-only evidence requirements in [The Closing Condition](README.md#the-closing-condition).
