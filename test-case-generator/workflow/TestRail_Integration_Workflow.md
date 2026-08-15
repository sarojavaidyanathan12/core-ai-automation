# TestRail Integration Workflow

## Trigger
User approves test cases

## Inputs
- hiddenJsonSchema
- Approved test case IDs

## Processing
1. Filter approved test cases
2. Build TestRail payload
3. Call TestRail API
4. Capture response

## Output
- Success message
- Created TestRail IDs
