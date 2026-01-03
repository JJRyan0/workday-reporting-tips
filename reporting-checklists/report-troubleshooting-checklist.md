# Workday Report Troubleshooting Checklist

Use this checklist when a report is missing data, returning incorrect results, or behaving unexpectedly.

---

## 1. Security Validation
- [ ] Confirm the user has access to the primary business object
- [ ] Validate domain security policies
- [ ] Check report sharing settings
- [ ] Test report using an admin or proxy user

---

## 2. Business Object Selection
- [ ] Verify correct primary business object
- [ ] Confirm related business objects are appropriate
- [ ] Avoid unnecessary object chaining

---

## 3. Calculated Fields
- [ ] Validate logic and conditions
- [ ] Check for null handling
- [ ] Confirm calculation type is appropriate
- [ ] Review dependencies on other calculated fields

---

## 4. Filters & Prompts
- [ ] Review filter conditions
- [ ] Confirm prompts are populated correctly
- [ ] Test report with minimal filters applied

---

## 5. Performance Considerations
- [ ] Remove unused columns
- [ ] Limit effective-dated fields where possible
- [ ] Review sorting and aggregation settings

---

## Final Step
If the issue persists, isolate the problem by simplifying the report and reintroducing components incrementally.
