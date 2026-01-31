---
description: Generate a professional excuse for why code isn't done
---

# Excuse Generator

Generate a professional, believable excuse for why the code/feature/task isn't complete.

The user will provide context: `$ARGUMENTS`

## Excuse Categories

Pick one randomly and craft a detailed excuse:

### Technical Excuses
- "The requirements changed mid-sprint"
- "Discovered a critical architectural issue that needs addressing first"
- "Blocked by a dependency that hasn't been released yet"
- "The API documentation was incorrect"
- "Found a security vulnerability that took priority"

### Environmental Excuses
- "CI/CD pipeline was down for 6 hours"
- "Package registry had an outage"
- "My local environment got corrupted"
- "Needed to upgrade [tool] which broke everything"
- "VPN issues prevented access to internal resources"

### Process Excuses
- "Still waiting on code review feedback"
- "The acceptance criteria weren't clear"
- "Had to attend unexpected meetings all day"
- "Was pulled into a production incident"
- "Onboarding the new team member took priority"

### Philosophical Excuses
- "The more I worked on it, the more edge cases I discovered"
- "I realized we were solving the wrong problem"
- "Premature optimization concerns arose"
- "Technical debt from previous sprint caught up with us"
- "The scope was larger than initially estimated"

## Output Format

Generate an excuse that is:
1. **Professional** - Suitable for a standup or status update
2. **Specific** - Include technical details to sound credible
3. **Blameless** - Don't blame specific people
4. **Forward-looking** - Include an estimated completion time
5. **Partially true** - The best excuses contain a grain of truth

## Example Output

> The feature is 80% complete, but during implementation I discovered that the upstream API doesn't support pagination as documented. I've reached out to the platform team and am awaiting their response. In the meantime, I've implemented a temporary workaround that I'll need to refactor once we get clarification. Expected completion: end of day tomorrow, assuming we hear back.

## Disclaimer

*This excuse is for entertainment purposes only. Please don't actually use these. Do your work. Ship your code. Be honest in standups.*

*(But if you must... this one's pretty good.)*
