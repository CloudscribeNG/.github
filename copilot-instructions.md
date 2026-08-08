# Copilot Instructions for BaseDev

When editing scripts or code in this repository:

- Do not run full end-to-end runtime script executions after each code change by default.
- Prefer fast validation only (syntax checks, diagnostics, targeted static checks).
- Run long-running integration or full script execution only when explicitly requested by the user, or at a clear milestone the user asks to validate end-to-end.
- If full execution is needed, summarize expected runtime cost before running.
