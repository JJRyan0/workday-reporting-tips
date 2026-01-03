# Missing Data Troubleshooting Flow

Use this flow when a Workday report returns fewer rows than expected.

---

## Step 1: Is the Data Missing for All Users?
- Yes → Go to Step 2
- No → Likely a security issue

---

## Step 2: Security Check
- Validate domain permissions
- Test with elevated access
- Review report sharing

If data appears with higher access → Security is the root cause.

---

## Step 3: Filter Review
- Remove all filters
- Re-run the report
- Reintroduce filters one at a time

If data disappears after adding a filter → Filter logic issue.

---

## Step 4: Calculated Fields
- Disable calculated fields temporarily
- Validate field logic
- Check for null conditions

---

## Step 5: Business Object Review
- Confirm correct primary business object
- Validate related object paths

---

## Outcome
Most missing data issues are caused by **security or filter logic**, not the report itself.
