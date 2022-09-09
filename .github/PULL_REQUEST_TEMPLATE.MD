#### Resolves [Jira ticket]

## Context 

A brief description of the context and the purpose behind these changes (i.e. what problem elicited the request for this feature/requirement, a description of the bug being fixed)

## Summary of Changes
A brief description of the changes included in the PR. (i.e. rationale behind solution for implementation of a new feature, etc.) Screenshots if applicable.

## Progress Checklist
A break down of the steps. Useful when the PR is in the draft stage
- [ ] step 1 
- [ ] step n

## Additional Considerations
Any additional consequences, side effects, uncertainties stemming from the changes in this PR.

## Instructions for the Reviewers
What do you expect from the reviewers? E.g. What code should be run to reproduce the results? Is there anything that needs attention? 
 
## Housekeeping Checklist
- [ ] Linked the PR to a Jira ticket?
- [ ] Linked the Jira ticket to the PR?
- [ ] Checked Draft/vs Ready to Review?
- [ ] Tagged the reviewers if Ready for Review?

## Code Review Checklist

The following items shall be verified prior to merging any new code into the production environment.

### Correctness
| Item                                                                                                                                  | Yes                    | No                     | N/A                     |
|---------------------------------------------------------------------------------------------------------------------------------------|------------------------|------------------------|------------------------|
| Does the pull request description completely and accurately describe the changes made?                                                | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> |
| Is there appropriate exception and error handling for all edge cases that may break the existing code or cause undesirable behaviour? | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> |
| Unit tests were added or modified for all new features and changes?                                                                   | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> |
| Documentation was updated for all new features and changes?                                                                           | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> |
| Has the test coverage been assessed?                                                                                                  | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> |
| Are the tests within the pull request passed?                                                                                         | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> |                                                                                       | <ul><li>[ ]</li></ul> | <ul><li>[ ]</li></ul> | <ul><li>[ ]</li></ul> |                                                                                      | <ul><li>[ ]</li></ul> | <ul><li>[ ]</li></ul> | <ul><li>[ ]</li></ul> |                                                                                      | <ul><li>[ ] Yes</li><li>[ ] No</li><li>[ ] NA</li></ul> |

### Style and Clarity
| Item                                                                   | Yes                    | No                     | N/A                     |
|------------------------------------------------------------------------|------------------------|------------------------|------------------------|
| Were the formatting, styling, and linting assessed?                    | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> |
| Is the code leveraging existing libraries and checked for repetitions? | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> |
| Are all debugging and testing code removed (ex. print statements)?     | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> |

### Performance
| Item                                                                   | Yes                    | No                     | N/A                     |
|------------------------------------------------------------------------|------------------------|------------------------|------------------------|
| Is the code performance checked to minimize time and space complexity? | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> |

### Security
| Item                                                         | Yes                    | No                     | N/A                     |
|--------------------------------------------------------------|------------------------|------------------------|------------------------|
| Is critical information leaking out of the app?              | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> |
| Are passwords or other sensitive information handled safely? | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> |
| Are there any obvious logic flaws or security holes?         | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> |
| Is audit logging properly implemented?                       | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> | <ul><li>[ ] </li></ul> |
