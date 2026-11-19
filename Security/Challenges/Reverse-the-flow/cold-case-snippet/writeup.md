# Writeup: Cold Case Snippet

## Flag
`MC{sn84020504_evening_star_newark}`

## Step 1: Analyze Unredacted Clues
Inspecting `clipping_redacted.jpg` reveals several redacted bars alongside clear text clues:
- Dateline fragment: `O., Dec. 26.-`
- Name & details: `Anton` ... `of Andrew` ... `honorably discharged from the Fifty-fifth` ... `United States Artillery Fort Hancock, a month ago, committed suicide here late last night by drinking carbolic acid. He was out of work and despondent. A year ago, near` ... `captured an Italian murderer of a policeman, receiving a stab in the side, which laid him up a month. For this action he received a reward.`
- Surrounding context: `"professor's"` plea above, `DEAD.` / `RATION` / `50 Oxford` on the left, and `Dutch army` / `The Clerical` / `suffrage` on the right.

## Step 2: Search Historical Newspaper Archives
1. Open the Library of Congress digitized newspaper archive (**Chronicling America**).
2. Search using distinctive phrases from the clipping, such as `"Fifty-fifth United States Artillery"` `"Fort Hancock"` `"carbolic acid"`.
3. Locate the matching issue: ***The evening star and Newark advertiser*** (Newark, N.J.), **December 26, 1907** (Last Edition, Image 3 of 12).

## Step 3: Retrieve LCCN & Build the Flag
1. Open the newspaper's catalog record / title information page in the archive.
2. Note the LCCN: `sn 84020504` (normalized as `sn84020504`).
3. Combine the LCCN with the newspaper title according to the format:
   `MC{sn84020504_evening_star_newark}`
