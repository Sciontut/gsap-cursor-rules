# gsap-cursor-rules

A Cursor rule for GSAP animation. Drop the `.cursor/` directory into any project and the rule becomes available to Cursor's agent.

## What's here

```
.cursor/rules/
  gsap.mdc
```

## Activation

The rule uses `alwaysApply: false` with a `description`, so Cursor's agent loads it when your prompt signals **GSAP animation** work — and stays out of unrelated tasks. To force it always-on, set `alwaysApply: true`; to scope by file type, add a `globs:` list.

## Source

**Authored from documentation, not converted from a third-party skill.** The URL provided (greensock/gsap) is the GSAP library source, which has no SKILL.md. This rule distills GSAP's official documented patterns (gsap.com/docs) into Cursor guidance. Verify version-specific APIs against the live docs.
