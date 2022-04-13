# Pull Request Template

Filling this template is mandatory. PRs will be immediately closed by maintainers if this template is not filled.

## Description

Please include a summary of the change and provide links to any relevant ClickUp tickets. Also list any dependencies that are required for this change.

## List any Related Issues or Changes (if applicable)

Related Issues

## List relevant Stakeholders (if applicable)

Stakeholders

## Deployment Timeline

Enter proposed deployment timeline here

## Type of change

- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] This change requires a Documentation and/or Wiki update

## How Has This Been Tested?
 
- [ ] Manual Testing
- [ ] Automated Testing
- [ ] Both Manual and Automated Testing Performed

Please describe the tests that you ran to verify your changes. Provide instructions so we can reproduce.

## Risk Assessment

Consider the following factors when evaluating the Risk associated with this change

* Complexity of the change - a couple of lines of code etc would be considered LOW, 1000 lines of code across multiple repos would be considered HIGH
* Probability of something going wrong - A well tested change with high confidence or a routine change would be LOW, a change that lacks more concise testing would be considered a higher risk
* Impact to Luma Health and our  customers if something goes wrong - Something internal only, or something that only covers a subsection of our product would be considered LOW, something that affects application functionality or the user experience would be considered a higher risk

- [ ] LOW risk
- [ ] MEDIUM risk
- [ ] HIGH risk

## Backout Plan

Use this space to detail how to roll-back this change should it be required. Be specific. 

## Final Checklist:

- [ ] I have performed a self-review of my own code
- [ ] I have tested my code to prove my fix is effective or that my feature works
- [ ] I have commented my code in areas where it's hard to make the code speak for itself
- [ ] My changes breaks no tests
- [ ] I have reviewed and understand te Root Cause Analysis (RCA) of recent incidents
- [ ] POST DEPLOY - I have verified that this change was successful or initiated a backout 
