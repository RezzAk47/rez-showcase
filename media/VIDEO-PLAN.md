# Demo videos: how they were made

The three clips are in [videos/](videos/). Each is 24 to 29 seconds, 1280x720 landscape, H.264 MP4 under 1 MB, with captions burned in, no voice and no music. They come from the demo build only.

How they were recorded: a script drove the demo build in a headless Chrome page (real clicks, no browser window, address bar or bookmarks in the picture) with a fresh throwaway data folder, the Premium plan and the invented pub menu. The page was captured frame by frame at 1280x664, a caption strip was added below it with ffmpeg, and the files were exported with all metadata removed. Frames were checked every 2 seconds for real data. The recording script is private and is not in this repo.

## Sample-data rules (all clips)
- Fresh data folder, invented pub menu, Premium plan, "Demo payments" tag visible.
- Staff names: Mara Test (manager), Ben Sample, Noor Demo. No real names or codes.
- No browser bar, bookmarks, other windows, notifications or Wi-Fi/IP address in frame. The Tablets and Membership tabs (pairing code, install id) are not shown.
- Every frame checked before posting. Metadata stripped from the exported files.

## Clip 1: Take an order (24 s)
File: [clip-1-take-an-order.mp4](videos/clip-1-take-an-order.mp4)
Shows: floor plan, tap table D1, tap seat 1, add Nachos and Fried Pickles, tap Send to kitchen.
Captions: "Tap a table." / "Tap a seat, tap dishes." / "Send to kitchen."

## Clip 2: Kitchen and allergy alert (29 s)
File: [clip-2-kitchen-allergy.mp4](videos/clip-2-kitchen-allergy.mp4)
Shows: on table D3, seat 2, open Fried Pickles, mark a Shellfish allergy, send. The kitchen screen shows the red allergy banner; Fire, then Ready; the tablet seat colour changes; Bump clears the ticket.
Captions: "Mark an allergy." / "The kitchen sees a red alert." / "Fire, Ready, Bump." / "The tablet updates." / "Bump clears the ticket."

## Clip 3: Split the check and pay (27 s)
File: [clip-3-split-and-pay.mp4](videos/clip-3-split-and-pay.mp4)
Shows: table D4 with 4 seats, Split by seat, pay seat 1 with cash using a quick-cash button, change shown. Then table D6 split evenly 2 ways and paid guest by guest.
Captions: "One check per seat." / "Cash, debit or credit. Demo: no card is charged." / "Or split evenly, 2 to 9 ways." / "Each guest pays their share."
