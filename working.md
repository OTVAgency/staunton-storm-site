# Staunton Storm preview handoff

Updated October 25, 2026.

## Scope
Publish the supplied V2 HTML in OTVAgency/staunton-storm-site. Preserve stauntonstorm.com, DNS, and all existing sites.

## Source
Original file received from the user: staunton-storm-preview-v2.html. It is copied byte-for-byte to index.html.
SHA-256: 1fa699014f1e2a0477f33d567e0b7847791d8215b87e4d351dc6da1c7bd73b0e.

## Validation
- Both inline scripts pass Node syntax checks. No external scripts or local asset paths are required.
- Internal anchors resolve; no duplicate element IDs.
- All 16 current-class and Mom/Dad/Student/Family combinations update the year, role, selected states, and preview caption.
- Alumni boundary years 1950 and 2026 and sample 2006 work; out-of-range, decimal, and empty input show validation errors.
- Product filters show the expected products. Keyboard tab navigation switches the class panels.
- All seven embedded images load in the desktop browser.

## Publishing configuration
GitHub Pages publishes main / root using .nojekyll. Preview address: https://otvagency.github.io/staunton-storm-site/. No custom domain or CNAME. Check GitHub Pages deployment status for the latest publication.

## Functional boundary
Shop by Class previews design concepts; it does not add class-specific products to the live store. Existing shopping links retain their original destinations.

## Access
The GitHub connector previously returned 403 Resource not accessible by integration on writes. The signed-in OTVAgency browser session supports uploads, commits, and Pages administration.

## Uploaded source verification
Source uploaded in commit 8c6e15784f5b0c2549713191bd7b0ab6144b8bb7. GitHub index.html blob d5d9cdc0f5e09830d91f0d04a82b7068de5f0f81 matches the supplied file exactly. Pages source was saved as main / root after upload; this handoff commit triggers its first branch publication.
