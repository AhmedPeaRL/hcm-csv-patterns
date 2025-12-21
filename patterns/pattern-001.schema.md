# Pattern 001 Schema

The CSV structure is fixed and must not be altered.

Columns (in order):

1. timestamp (UTC)
2. source
3. state
4. fluctuation_level
5. pressure_status
6. note

Rules:

- Column order is mandatory.
- No additional columns are allowed.
- Free text is permitted only in the final column.
- Empty values are allowed if truthful.

Schema violations invalidate the artifact.

---

RX-HCM
