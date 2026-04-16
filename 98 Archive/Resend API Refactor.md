# Resend API Refactor
## Files to Delete
- [x] `unsubscribe.ts`
- [x] `WelcomeTemplate` and all files in `emails/` folder
- [x] Uninstall `@react-email/render`

## Resend Dashboard
- [x] Create welcome email template with `{{email}}` variable
- [x] Create contact notification template with `{{name}}`, `{{email}}`, `{{subject}}`, `{{message}}` variables
- [x] Create contact auto-reply template with `{{name}}`, `{{subject}}`, `{{message}}` variables
- [x] Copy all three template IDs

## Code Changes
- [x] Add `export const prerender = false` to `subscribe.ts`
- [x] Refactor `subscribe.ts` to use welcome template ID
- [x] Refactor `contact.ts` to use both contact template IDs
- [x] Add template IDs to `.env` file as environment variables
