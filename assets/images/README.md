# Images

Unzip the generated artwork here. The page expects these 17 exact filenames:

cover-couple.png, cover-arch-frame.png, venue.png, story-meet.png, story-travel.png,
story-proposal.png, reception.png, timeline-divider.png, dress-code.png, welcome-party.png,
first-dance.png, hotel.png, rsvp-envelope.png, gifts.png, closing-couple.png,
background-texture.png, icon-sheet.png

JPEG data under these .png names is fine (browsers detect the real format). Any missing file shows a soft watercolor-wash placeholder instead of a broken image.

icon-sheet.png must be a 4 columns × 3 rows grid with evenly sized cells, in this order:
rings, ceremony arch, cocktail, dinner plate / cake, music/dance, dress, suit / hotel, gift, envelope, calendar-heart.

Envelope cover (in addition to the 17):
- `envelope.png` — the sealed envelope on the tap-to-open cover. Cropped to the envelope; the flap clip and
  seal position in `index.html` are measured on this exact image (hinge y 2.97%, tip x 49.85% / y 66%),
  so a replacement envelope needs those numbers re-measured.
- `envelope-lining.png` — the patterned liner shown inside the flap and pocket when the envelope opens.
