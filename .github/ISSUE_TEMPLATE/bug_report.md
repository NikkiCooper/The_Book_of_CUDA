---
name: Bug Report
about: Report a bug or unexpected behavior
title: "[Bug] "
labels: bug
assignees: ''
---

body:
  - type: markdown
    attributes:
      value: |
        Thanks for reporting a bug! Please fill out the details below.

  - type: input
    id: environment
    attributes:
      label: Environment
      description: OS, CUDA version, GPU model, etc.
      placeholder: "Windows 11, CUDA 12.2, RTX 3080"

  - type: textarea
    id: steps
    attributes:
      label: Steps to Reproduce
      description: What did you do to trigger the bug?
      placeholder: "1. Run script X\n2. Observe error Y"

  - type: textarea
    id: expected
    attributes:
      label: Expected Behavior
      placeholder: "It should have done Z"

  - type: textarea
    id: actual
    attributes:
      label: Actual Behavior
      placeholder: "Instead, it did A"
