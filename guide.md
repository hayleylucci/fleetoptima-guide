# FleetOptima User Guide

How FleetOptima works, written for the people using it: owners, mechanics and operators.
Each section says what a feature does and why it works that way.


---

## Getting around

### Logging in
Log in with the username and password your company's Admin gave you (press **Enter** or tap the button).

**The first load can take up to a minute.** When nobody has used FleetOptima for a while, the server rests, and the first visit wakes it up. You'll see **"The server is waking up, hang tight."** That's normal; after that it's quick.

### Home
Home is grouped into sections:
- **Quick actions**: the everyday jobs, as wide buttons on top. Right now that's **New Work Order**.
- **Fleet**: **Assets**, **Work Orders** and **Parts**.
- **Admin**: **Users** and **Asset Types**.

A tile opens that list. To add something new, open its list and tap **+ New** (bottom right).

### Put it on your home screen
FleetOptima runs in your web browser, but you can **install it like an app**: it gets its own icon, opens full screen without the browser's address bar, and has its own spot when you switch between apps. It's the same FleetOptima with the same login, and it updates itself, so there's no app store and nothing to download again.

**Android (Chrome):** open FleetOptima, tap the **⋮** menu (top right), then **Add to Home screen** (or **Install app**), and confirm.

**iPhone (Safari):** open FleetOptima, tap the **Share** button, then **Add to Home Screen**.

*Why:* without the browser's bars there's more room on screen, and nothing covers the buttons at the bottom, like the camera's shutter.

### The top bar
- The **?** opens this guide at the part about the page you're on.
- The **megaphone** sends us feedback (see below).
- **Your initial** in a circle opens the **account menu**: your name and role, **App settings**, **Org settings** (Admins only: VIN settings), **Help** and **Log out**.
- **App settings** picks the look: light, dark, or whatever your phone or computer is set to.

### Everywhere
- **Every page has its own web address.** For example, `/assets` is the asset list, `/assets/new` is a new asset, `/work-orders/123` is one work order, and `/parts/123/edit` edits a part. You can bookmark a page or send someone a link to it.
- **The back button walks back one page at a time**, like any website. On the home page, the first back shows **"Press back again to exit"**, and the second one leaves the app.
- **Opening a link to something that was deleted** (or doesn't exist) shows a **Not found** page with a button to go home.
- **Something bugging you? Yell at us.** The megaphone button at the top of every page opens one big box. Say whatever you want, however you want: cussing and CAPS LOCK welcome. The app adds which page you were on and which version you're running, so you don't have to explain any of that.
- **You can copy any text on a details page.** Long-press it (or drag across it with a mouse) to copy a VIN, a part number or a note.
- **Missing something in a dropdown?** Most dropdowns end with **New ...** (New Asset Type, New User, New Measuring Unit). Make it right there, and when you come back it's already picked. *Why:* so you never have to abandon a half-filled form just because one choice was missing.
- **There's more than one way to do most things.** You can start a work order from the home page (**Quick actions → New Work Order**), from the Work Orders list (**+ New**), or from an asset (**Create Work Order**). You can change stock from a part, or by pulling parts on a work order. Use whichever feels natural. They all do the same thing behind the scenes.

### Adding, changing and deleting
- **Add:** open a list and tap **+ New** (bottom right).
- **Change:** open the thing and tap **Edit**, then **Save**.
- **Delete:** open it and tap **Delete**. The app asks first, because you can't undo it from the app. Deleting hides it everywhere, but its history is kept: a deleted asset's work orders and records stay on the books. *Why:* a truck you sold last year still had real repairs and real costs, and your totals shouldn't change because it's gone.

---

## Assets

An asset is one vehicle or piece of equipment: "Truck 12," "the Bobcat."

### Adding an asset
**Home → Assets → + New.** Pick the **asset type** first: a **Vehicle** asks for a **VIN**, and **Equipment** asks for a **Serial Number** instead.

### Naming an asset
Give it a **Nickname** ("Truck 12," "Stella," "the Bobcat") and that's what it's called everywhere: lists, dropdowns, work orders. No nickname? It shows the **last 6 characters of the VIN** ("VIN: ...123456"). Nothing at all? **Unnamed asset**, which is your hint to give it a name.

*Why nicknames:* nobody in a shop says "the one ending in 4C7". They say "Truck 12." The app should talk the way you do.

### What's on the form
The form has two parts:
- **The top is how it is right now:** nickname, asset type, **operator** (the person who usually runs it), and its **mileage or hours** with the unit they're counted in.
- **Specifications are what it is:** the VIN (or serial number), make, model and year. These hardly ever change once they're filled in.

*Why split it:* the things you update all the time sit on top where your thumb is, and the things you set once stay out of the way.

*Why an operator:* so everyone knows who usually runs it, and who to ask when it starts making a noise.

The **unit** fills in from the asset type: a Vehicle counts **Miles**, and you can change it (a truck with an hour meter, say). *Why units matter:* maintenance runs on them. "Every 3,000 miles" and "every 250 hours" only work if the app knows which one this machine counts. Mileage or hours can be typed or **read off a photo of the dash** (camera button; see *Reading it off a photo*).

### The VIN fills in the rest
Enter the VIN any of three ways:
- **Type or paste it.**
- **Scan the barcode** (barcode button in the field) on the VIN sticker. That sticker is usually on the front door jamb. Work vans and trucks tend to have one; many cars don't.
- **Read it off a photo** (camera button) of the VIN plate at the bottom of the windshield. See *Reading it off a photo* below.

Once there's a VIN that passes its **check digit** (a built-in math check every North American VIN has), FleetOptima looks it up with **NHTSA**, the US government's vehicle database, and fills in the make, model, year and more. **VIN settings** (Org settings) decide which of those details sit on the form; the rest go into the **Extra Data** card, so nothing is thrown away. Anything you already typed is never overwritten.

**The Extra Data card** holds everything else the VIN lookup found (engine, body style, plant...). You can edit any of it, and your edits stick: looking the VIN up again doesn't overwrite them. *Why keep it all:* you don't need engine size today, but the day you're ordering a part, it's already there.

A VIN that fails the check digit doesn't look anything up. Compare it with the plate. Serial numbers on equipment are saved as entered (in capitals).

### Asset types
**Home → Asset Types.** Every asset is one type. You start with **Vehicle** and **Equipment**, and you can add your own (Trailer, Forklift, Generator...). A type has:
- **Name**
- **Default measuring unit**: what new assets of this type count in (Vehicle → Miles, Equipment → Hours).
- **Identifier label**: what the ID number is called on the form, like **VIN** or **Serial Number**.

*Why asset types:* they're presets. Pick "Equipment" and the form already knows it counts hours and asks for a serial number, so you're not setting the same things on every machine. Make a type for anything you have a lot of.

---

## People

### Users and roles
**Home → Users** lists everyone in your company. Each person has a **role**:
| Role | Can |
|---|---|
| **User** | Use the app day to day: assets, work orders, parts. |
| **Admin** | Everything a User can, plus adding and removing people (including other Admins) and **Org settings**. |

Everyone only ever sees their own company's assets, jobs, parts and people.

*Why roles:* so the person reporting a flat tire can't accidentally delete a coworker's account or change company settings. Give Admin to whoever runs the shop.

### VIN settings (Admins)
**Account menu → Org settings → VIN settings.** Tick which details from a VIN lookup sit on the asset form. The ones that are on are listed first; the rest (there are over a hundred) are under **More fields**. Anything left off still goes into the **Extra Data** card, so nothing is lost. *Why:* a VIN lookup returns a lot. A plumbing company might care about towing capacity and never about airbags. Keep the form to what *your* people actually look at.

---

## Work orders

A work order is one job on one asset: "brakes squealing on Truck 12."

### Reporting a problem
**Home → New Work Order** (under Quick actions). Pick the asset, say what's wrong, and add any details. Operators, mechanics and owners can all do this. You can also start from the asset itself: open the asset and tap **Create Work Order** (the asset is already filled in).

### Where a job is (its status)
| Status | Meaning |
|---|---|
| **Open** | Reported, nobody's working on it yet |
| **In Progress** | Someone tapped **Start** |
| **Completed** | Done |
| **Cancelled** | Stopped without finishing |

- **Start** moves an Open job to In Progress.
- **Complete** works from Open *or* In Progress. If you open and finish a job in one go, you don't have to tap Start first.
- **Cancel job** works from Open or In Progress.
- Status can only change through these buttons, not by editing the job, so every change is recorded.
- A completed or cancelled job can't be started, completed or cancelled again.

### Parts on a job
- **Pull part** opens a search. Type a name, a part number or a barcode, or tap the **scan** button and point the camera at the box. Pick the part, then say how many.
- **Not in the system yet?** Type its name and tap **Add "..." as a new part** (or scan a box nobody has scanned before). Fill in what it's measured in, how many you have and what each cost, and you're straight back to pulling it. You never leave the job.
- Parts leave stock **right away**, so two people can't grab the same last filter. If there isn't enough on the shelf, the app tells you how many are there.
- The **Parts** section shows how much of each part the job has and what it cost, plus the **parts total** for the job. Measured parts say their unit (**4 qt Castrol 5W-30**); parts counted one by one say **2 x FRAM PH3614**.
- **Return** puts unused parts back on the shelf, and the job's cost goes down by exactly what they were charged.
- **Forgot to log a part before finishing?** Pull part and Return still work on **completed and cancelled jobs**. The job stays finished, and its records say the change was **added after the job was completed**, so nobody mistakes it for something that happened during the job. Nothing that's already there gets edited.

### Cancelling a job
When you cancel a job that still has parts out, the app lists them under **Back on shelf**, all ticked, because a cancelled job usually didn't happen. **Untick anything that got used up** (oil already poured in, a part that turned out to be defective); it stays charged to the job. A cancelled job can still have a cost.

### Records (a job's history)
Every work order keeps a list of what happened, oldest first: reported, started, parts pulled, parts returned, edited, completed or cancelled, plus any notes.
- Each record shows **who** did it and when.
- **Add note** adds your own note (just type it).
- **Records can't be deleted or edited.** If something was wrong, add a note that corrects it. That keeps the history trustworthy.
- Deleting a work order hides it, but its records and its parts history are kept.

---

## Parts and stock

### Quantities
Quantities can be decimals: **4.5 quarts** of oil is fine. Each part has a **measuring unit** (quarts, units, gallons...). A part must have one, and if it's missing the app tells you to pick one.

### Barcode
Optional. It's the code on the box (UPC). Some shops use it as their part number, so when you search by code, FleetOptima checks **both** the barcode and the part number.

If one barcode matches more than one part, the app asks **Which one?** and lists them.

**Scanning:** the first time you use the scan button, your browser asks to use the camera. Say yes (you won't be asked again on that site). Scan a box once and the part remembers its barcode; after that, a scan finds it straight away.

The scan button is in three places:
- **Pull part** on a job: a known box goes straight to "how many"; a new one starts a new part.
- **The Parts list** (barcode icon, top right): a known box opens that part; a new one opens **New Part** with the barcode filled in.
- **The Barcode field** on New Part / Edit: fills the field. If that barcode is already on another part, the app says so and offers to open that part instead, so you don't make a duplicate.
- **The VIN field** on a new asset (Serial Number on equipment): scan the barcode on the **VIN sticker**. The app finds the VIN inside it (it knows the extra "I" some stickers add, and the square Data Matrix codes on newer ones), and a good VIN fills in the vehicle details just like typing it (see *Assets*). If what it read doesn't pass the VIN's check digit, it's still put in the field, with a warning to compare it to the sticker, and no details fill in. On equipment, a serial number tag is filled in exactly as scanned.

### How stock is counted: oldest first
Every time stock comes in, it's kept as its own batch with **its own price**. When parts are used, the **oldest batch is used first** (first in, first out).

Why: prices change. If you bought 5 quarts at $6 and later 5 at $7, a job that uses 7 quarts is charged **(5 × $6) + (2 × $7) = $44**, which is what that oil actually cost. FleetOptima never averages prices.

### The buttons on a part
| Button | What it does |
|---|---|
| **Restock** | Stock came in: how many, and the cost each. Creates a new batch at that price, which becomes the part's latest price. Don't know the cost? Leave it blank (see below). |
| **Count** | "The shelf says 4": enter what's actually there and stock changes to match. If the shelf has less, the missing amount comes off the oldest batches; if it has more, the extra is added at the latest price. |
| **Use or toss** | Stock leaving **without** a work order. A **reason is required**: used outside a work order, defective and thrown out, returned to the store, lost, or other. |

**Stock never leaves silently.** Every change either belongs to a work order or has a reason.

You can't change the quantity by editing the part. Use Restock, Count or Use or toss. (Coming soon: typing a new number on Edit will ask "restock, shelf count, or used/tossed?")

### Reading it off a photo (no barcode)
Some fields have a **camera** button: **VIN** (Serial Number on equipment), **mileage / hours**, and **part number**. Use it when there's no barcode, like a VIN plate behind the windshield, your dashboard, or a label on the old part.
1. Tap the camera. Use **1x / 2x / 3x** to zoom in until the number fills the screen (what you see is what gets read), then take the photo. Digital dashboard numbers read much better big.
2. The photo comes back with a **box around every bit of text** the app found, each with a little **tag showing what it read**. Compare the tag with the real thing underneath.
3. The app's best guess is **green, thick, with a check mark**. Everything else is red. Tap a different box (or its name in the list below) if the guess is wrong.
4. If one character is off, fix it in the box at the bottom. Then tap **Use ...**.

**VINs get extra checking.** Worn plates get misread in predictable ways (a 6 read as a 5, an 8 as a B), and a VIN can never contain I, O or Q. If what was read fails the check digit, the app tries those common mix-ups, keeps only the fixes that pass, and asks NHTSA which ones are real vehicles. The guess says what it changed ("Fixed 5 → 6 at position 6") so you can check it against the plate. If more than one fix is real, there's no guess: you pick. If NHTSA can't be reached, the check-digit guess stands and says it wasn't checked.

**Mileage / hours** only picks whole numbers of 3 digits or more (with a decimal for hour meters), so the speedometer's "60" or a trip meter label won't be guessed.

Nothing saves until you tap Save on the form, and the photo itself isn't kept. Tips: hold steady and avoid glare. You can hold your phone upright or turned on its side, whichever fits what you're reading.

### When nobody knows what it cost
A jug that was already on the shelf, a box from who-knows-when: leave **Cost each** blank instead of guessing. The stock is saved and usable, but marked **Cost needed**: on the part's Stock list, on its History, and on any job that used it ("+ cost needed on some" after the parts total).

When you find the receipt, open the part and tap **Set cost** on that batch. The cost fills in everywhere at once, including the jobs that already used it. A cost can only be filled in once like this. A cost that was already known never changes, so job totals stay trustworthy.

Why not just put $0? Because $0 looks like a real price, and the owner's numbers would quietly be wrong. A blank that says "cost needed" is honest.

### Stock and History
- **Stock** lists the batches that still have something left, oldest first, with what each one cost.
- **History** lists every change to the part's stock, newest first: restocks, pulls for work orders, returns, counts and adjustments, with their reasons.

---

## Messages you might see
| Message | Meaning |
|---|---|
| "Only X on hand." | You tried to pull more than the shelf has. |
| "Error 211: Pick a measuring unit..." | The part needs a measuring unit. Pick one from the list. |
| "Can't go from Completed to ..." | That job is already finished. |
| "Press back again to exit" | You're on the home page. One more back leaves the app. |
| "The server is waking up, hang tight." | First visit in a while. Give it up to a minute. |
| "Can't reach the server right now." | Check your internet, then try again. |
| "Your session expired. Please log in again." | You've been logged in a long time. Log in again and carry on. |
| "You don't have permission to do that." | Your role can't do this (for example, only Admins add people). Ask your Admin. |
| "That doesn't exist anymore." | Someone deleted it. |

