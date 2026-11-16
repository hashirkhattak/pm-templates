# User Story Template

A user story is one short sentence that says who needs what, and why. If you cannot finish the sentence, the feature is not ready to build.

## The sentence

> As a **[type of user]**, I want to **[do something]**, so that **[I get this result]**.

## Full template

**Story ID:** [e.g. APP-12]
**Title:** [short name]
**Priority:** Must have / Should have / Nice to have
**Estimate:** [story points or hours]

**Story**
As a [user], I want to [action], so that [result].

**Acceptance criteria** (the story is done when all of these are true)
- [ ] Given [starting point], when [user does something], then [what should happen].
- [ ] Given [starting point], when [user does something], then [what should happen].
- [ ] Error case: when [something goes wrong], the user sees [clear message].

**Notes for developers**
- [links to designs, APIs or documents]
- [anything tricky they should know]

**Out of scope**
- [what this story does NOT include]

## Example

**Title:** Reset password

As a **returning customer**, I want to **reset my password by email**, so that **I can get back into my account without calling support**.

Acceptance criteria
- [ ] Given I am on the login page, when I tap "Forgot password", then I can enter my email.
- [ ] Given I entered a registered email, when I submit, then I get a reset link within 2 minutes.
- [ ] The link stops working after 24 hours.
- [ ] Error case: when the email is not registered, the user sees "We could not find that email."

## Quick check before you hand a story to the team
- [ ] One user, one action, one result
- [ ] Small enough to finish in one sprint
- [ ] Acceptance criteria are testable by QA
- [ ] Designs or examples are attached
