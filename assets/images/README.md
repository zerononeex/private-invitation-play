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
- `envelope.png` — portrait envelope (1116×2000) that fills the phone screen on the cover. The flap clip and
  seal position in `index.html` are traced from this exact image (hinge = image top, flap tip / seal at
  x 49.82% / y 36.3%), so a replacement envelope needs those numbers re-measured.
- `envelope-lining.png` — patterned liner on the back of the flap.
- `ribbon-bow.png` — peach satin bow (green background removed) tied on the card; it unties in three pieces.
