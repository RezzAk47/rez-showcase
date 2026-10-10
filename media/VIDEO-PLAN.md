# Video plan: 3 short clips

The three clips are recorded (media/videos/). Each is 20 to 30 seconds, 1280x720 landscape, H.264 MP4 under 1 MB, with captions burned in, no voice and no music. They come from the demo build only.

How they were recorded: a script drove the demo build in a headless Chrome page (real clicks, no browser window, address bar or bookmarks in the picture) with a fresh throwaway data folder, the Premium plan and the invented pub menu. The page was captured frame by frame at 1280x664, a caption strip was added below it with ffmpeg, and the files were exported with all metadata removed. Frames were checked every 2 seconds for real data. The recording script is private and is not in this repo.

## Sample-data setup (all clips)
- Fresh data folder, invented pub menu, REZ_PLAN=premium, "Demo payments" tag visible.
- Staff names: Mara Test (manager), Ben Sample, Noor Demo. Do not use real names or codes.
- Hide the browser bar and bookmarks. No other windows, notifications or Wi-Fi/IP address in frame. Do not show the Tablets or Membership tabs (pairing code, install id).
- Check every frame before posting. Strip metadata from the exported file.

## Clip 1: Take an order (25 s)
Show: floor plan, tap table D1, tap seat 1, add Nachos, add Fried Pickles, tap Send to kitchen.
Captions: "Tap a table." / "Tap a seat, tap dishes." / "Send to kitchen."

## Clip 2: Kitchen and allergy alert (25 s)
Show: split screen or cut. Modify a dish, mark Shellfish allergy, send. Kitchen screen shows the red allergy banner, press Fire, then Ready. The tablet seat colour changes.
Captions: "Mark an allergy." / "The kitchen sees a red alert." / "Fire, Ready, Bump. The tablet updates."

## Clip 3: Split the check and pay (30 s)
Show: a table with 4 seats. Tap Split by seat, then Pay seat 1 with cash, quick-cash button, change shown. Then Split evenly 2 on another table.
Captions: "One check per seat." / "Cash, debit or credit. Demo: no card is charged." / "Or split evenly."
