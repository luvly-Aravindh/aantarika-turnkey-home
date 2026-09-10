Aantarika funnel, preview build
===============================

Deploy in 20 seconds:
1. Go to  https://app.netlify.com/drop
2. Drag this whole ZIP (or the unzipped folder) onto the page.
3. Netlify gives you a live link. Share it with the client.

Files:
  index.html        The landing page (opens first).
  thank-you.html    Shown when the visitor qualifies.
  not-qualified.html Shown when the visitor does not qualify (with the reason).

How the client can test the flow:
  QUALIFIES   -> Bengaluru location + budget 25 lakh or above
                 -> "great fit" step -> Confirm -> thank-you.html
  NOT A FIT   -> location "Outside Bangalore" OR budget "Below 25 lakh"
                 -> not-qualified.html, which explains why and offers a
                    "go back and update my answers" button.

Note: this is a preview. The scheduling calendar, WhatsApp and email are not
connected yet, so the qualified path shows a "Confirm my consultation" button
in place of the live calendar.
