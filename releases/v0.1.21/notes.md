# UmaPilot v0.1.21

- Refresh the active dashboard project when its saved contents change, even if its update timestamp is unchanged. This fixes the seed checkbox reporting Saved while staying unchecked and leaving the displayed loop order stale.
- Keep the checkbox and optional seed step synchronized after save, polling and reload. Disabling the option removes the optional step. Current careers retain their original setup; seed insertion still happens at a safe career boundary.

Validated through the actual project subscription and dashboard control with a concurrent-save conflict, checked-state and loop-order assertions, polling/reload and disabling. The regression fails with the previous timestamp-only refresh and passes with this fix. Merge tests and the production build pass. No personal data or credentials are included.
