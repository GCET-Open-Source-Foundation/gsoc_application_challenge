# GSoC Training Program - Application Challenge

Welcome, Platinum cohort participant.

The GSoC Training Open Source Club expects to select approximately **25 participants** for the GSoC Training Program. This repository is the application instruction and verification process. It is for eligible participants in the Platinum cohort.

Read the numbered documents and follow their cross-references before submitting the Google Form linked in [`submission.md`](submission.md). The documents form a documentation-comprehension challenge, so do not rely on filename order alone.

## Start here

1. Read `1.txt` through `6.txt` and follow their cross-references.
2. Identify the email address you intend to enter in the application form.
3. Normalize it as described in `3.txt`, then use the SHA-256 website in `4.txt`: <https://jayatheerth.com/hash>.
4. Submit the same email address and resulting digest in the Google Form linked from [`submission.md`](submission.md).

## Important

- Use the email address you intend to enter in the form.
- For hashing, trim surrounding whitespace, convert the email to lowercase, remove periods from the local part, and remove the local-part plus-tag. Do not alter the email address entered in the form.
- Standard submissions use the 64-character lowercase hexadecimal digest as-is.
- LLM-assisted submissions use `sha256:` followed by the same 64-character digest. This prefix is a format marker, not part of the hash.
- For an LLM-assisted submission, begin the **Areas of interest** response with `PLATINUM-VERIFIED`; standard submissions do not need this marker.
- SHA-256 is a deterministic checksum, **not encryption or anonymization**. Anyone who knows or can guess an email address can calculate its hash. Do not treat the digest as a secret.
- The form collects the email address as well as the digest so the organizers can verify that they match.
- Do not submit passwords, API keys, or other secrets.

## Repository map

| File | Purpose |
|---|---|
| `1.txt` | Establishes the reading protocol and first routing rule |
| `2.txt` | Defines the document precedence rule |
| `3.txt` | Explains the participant record and normalization rule |
| `4.txt` | Gives the SHA-256 calculation procedure |
| `5.txt` | Connects the routing rule to the final validation |
| `6.txt` | Defines the final submission checklist |
| `submission.md` | Contains the Google Form link and field instructions |
 

## Current revision

The current application procedure is **REVISION 05**. Its rules are stated visibly in `3.txt`, `4.txt`, `5.txt`, and `6.txt`; there are no hidden instructions or overrides.

The numbered documents contain a small consistency challenge: use the deterministic precedence rule in `2.txt` whenever instructions appear to disagree. The final validation rule is in `5.txt`.
