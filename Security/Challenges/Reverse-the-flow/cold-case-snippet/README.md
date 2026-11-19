# Cold Case Snippet

- **Category:** OSINT
- **Difficulty:** Easy

## Story
During an archival review of an old cold case, investigators recovered a partially redacted newspaper clipping describing a tragic incident involving a discharged soldier (`clipping_redacted.jpg`). Key names and lines have been blacked out, leaving only fragments of text and historical context.

Your task is to trace the clipping back to its original publication in a national library archive, find its catalog record, and extract the Library of Congress Control Number (LCCN) along with the primary newspaper title.

## Explanation
This challenge covers **Historical OSINT and Archival Pivoting**. Even when key details in an image are redacted, unredacted text fragments—such as unique names, military units, dates, and surrounding column context—can serve as exact search queries in digitized historical newspaper databases (such as the Library of Congress's *Chronicling America* collection). Once the original issue is located, players must inspect the publication's catalog metadata to retrieve the LCCN and format the flag properly.

## Files
- `clipping_redacted.jpg`: Redacted newspaper clipping image to investigate.

## Flag Format
`MC{lccn_newspaper_title}` (e.g., `MC{sn12345678_the_daily_gazette}`)
