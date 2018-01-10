# Development Workflow
## Issue Creation
- Find or create a github issue you want to work on
- Split the issue up if needed. Anything bigger than 2 weeks is way too big
- It will be beneficial to refine the issue with the team before you pull it to *in progress*
## Development
- Create a new branch that has the issue id at the beginning of its name, e.g. `485-gl-resources-leak`
- Create new tests where it applies
- Create or improve existing test maps where it applies
- Create your changes on the branch
- Rebase with master if needed (don't merge master into your branch)
## Testing
- Check if all the tests pass
- Create a PR and ask any or all members of technical-officers-engine to review the PR
- Wait for your team mates to sign off on the PR
## Quality Control
- Make a code review
- Make sure all the tests pass and that the game does not quit with a segfault or error
- Play the game and check for errors
## Finishing
- Merge your branch into master
- Delete your branch
# Things to avoid
- Forgeting to reference the issue in the commit
- Working on more than one github issue in one branch at once or do more than what the issue calls for.
- Merging master back into your branch. Use rebase.
- Working on Epics (anything above 2 weeks). Split them up into smaller tasks instead.
