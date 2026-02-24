# Resend API Refactor
## Files to Delete
- [ ] `unsubscribe.ts`
- [ ] `WelcomeTemplate` and all files in `emails/` folder
- [ ] Uninstall `@react-email/render` and `react dependencies`

## Resend Dashboard
- [ ] Create welcome email template with `{{email}}` variable
- [ ] Create contact notification template with `{{name}}, {{email}}, {{subject}}, {{message}}` variables
- [ ] Create contact auto-reply template with `{{name}}, {{email}}, {{subject}}, {{message}}` variables

## Code Changes
- [ ] Add `export const prerender = false` to `subscribe.ts`
- [ ] Refactor `subscribe.ts` to use both contact template IDs
- [ ] Refactor `contact.ts` to use both contact template IDs
- [ ] Add template IDs to `.env` file as environment variables
