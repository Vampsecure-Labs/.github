---
name: "Feature request (EN)"
about: Suggest a new capability or improvement for a VSL tool
title: '[FEAT] <tool-name>: <brief description>'
labels: enhancement
assignees: ''
---

## Tool

<!-- Which tool should be improved? If it's a new standalone tool, write "new tool". -->

## Current behavior / limitation

<!-- What can't you do today, or what works poorly? -->

## Proposed behavior

<!-- What should the tool do instead? Be as specific as possible. -->

## Use case

<!-- Describe a real engagement scenario where this would be useful. -->

```bash
# Example of the command or workflow you'd want to run
python3 vamp_<tool>.py --new-flag ...
```

## Expected output / report section

<!-- What should the JSON output or HTML report look like? Paste an example if you can. -->

## VSL schema impact

<!-- Does this add new fields to the findings JSON? Does it affect vamp-penreport output? -->
- [ ] New fields in `findings[]`
- [ ] New top-level output key
- [ ] Changes to vamp-penreport / vamp-orchestrator integration
- [ ] No schema changes

## Willing to contribute?

- [ ] I can submit a pull request for this feature
- [ ] I can help test an implementation
- [ ] I'm just making a suggestion

---

> All VSL tools must produce standard JSON output (`findings[]` array) compatible with `vamp-orchestrator` and `vamp-penreport`. Keep that in mind when proposing new tools or output fields.
