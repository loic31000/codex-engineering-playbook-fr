# Reference prompt formula

A good working prompt generally contains:

```text
ROLE
OBJECTIVE
CONTEXT
INPUTS
CONSTRAINTS
TASK
EXPECTED OUTPUT
SUCCESS CRITERIA
VERIFICATION
ESCALATION CONDITIONS
```

## Short example

```text
Act as the senior developer responsible for this Story.

Objective:
Implement only the validated acceptance criteria.

Context:
Read the Story, the plan, and only the relevant documentation.

Constraints:
- do not change the scope;
- do not change the architecture without flagging it;
- do not add a dependency without justification;
- do not weaken tests.

Task:
Implement the Story incrementally.

Output:
- modified files;
- acceptance criteria covered;
- tests added/run;
- remaining issues.

Verification:
Run the applicable project checks.

If an important decision is missing, stop only that part and flag it instead of inventing it.
```
