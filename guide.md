# FleetOptima User Guide

How FleetOptima works, written for the people using it: owners, mechanics and operators.
Each section says what a feature does and why it works that way.


---

## Getting around

### Logging in
Log in with your **username or your email**, and your password (press **Enter** or tap the button).

- **New here?** If your company already uses FleetOptima, your Admin adds you and you get an **invite** (see **Adding someone** below). If you're setting FleetOptima up for your own company, tap **New here? Start free** under the Login button.
- **Forgot your password?** Tap **Forgot password?**, type your username or email, and we'll email you a link to pick a new one. The link works once and lasts an hour. Your old password keeps working until you use it, so if you didn't ask for it, just ignore the email.
- **No email on your account?** Ask your Admin to tap **Reset password** on your user. They'll get a link or a QR code for you.

### Staying logged in
Once you log in, **you stay logged in on that phone or computer**, even if you close it and come back tomorrow. You're only asked again if you haven't opened FleetOptima there in **30 days**, if you **log out**, or if your password changes.

- **Log out** (account menu) ends it on that device only.
- **Sign out everywhere** (Account settings) ends it on every phone and computer at once, including the one in your hand.
- **Changing your password** logs you out everywhere else, but not where you changed it.

*Why:* a mechanic with greasy hands shouldn't have to type a password every morning, and a lost phone shouldn't stay logged in forever. Sign out everywhere fixes that in one tap.

**The first load can take up to a minute.** When nobody has used FleetOptima for a while, the server rests, and the first visit wakes it up. You'll see **"The server is waking up, hang tight."** That's normal; after that it's quick.

### Starting free (signing up your company)
**Login → New here? Start free.** Type your business name, your name, a username, your email and a password, and tick the box to agree to the **Terms of Service** and **Privacy Policy** (both open if you tap them). We email you a link: open it to **verify your email**, then log in. You're the company's **Admin**, and you can add your crew right away.

- **Free for 14 days**, for up to 10 assets. No card to start.
- **After that it's $8 per asset per month.** We'll ask you to pick a plan before the trial ends. Nothing is charged until you agree.
- **Need more time or more assets during the trial?** Get in touch.
- **Trial over and no plan yet?** Everything goes read-only: you can still see it all (and ask us for a copy), you just can't add or change anything until you pick a plan.
- More in **Billing and your plan** below.
- **Didn't get the email?** Check spam, then try logging in: you'll see **Resend** for a new link.

*Why the email check:* so nobody can sign up with someone else's address.

### Home
Home is grouped into sections:
- **Quick actions**: the everyday jobs, as wide buttons on top. Right now that's **New Work Order** (and **Update miles** if you run a vehicle).
- **Maintenance**: what's **due** (red) or **coming up** (amber), most urgent first, if you're allowed to see maintenance. Tap a due one to open its work order, or a coming-up one to open the asset. **See all** lists every one. It's not there when nothing is due.
- **Fleet**: **Assets**, **Work Orders**, **Parts** and **Costs** (Costs only for people allowed to see prices).
- **Admin**: **Users**, **Groups** and **Asset Types**.

You only see the tiles your groups let you use (see **Groups and permissions**). A tile opens that list. To add something new, open its list and tap **+ New** (bottom right).

### Put it on your home screen
FleetOptima runs in your web browser, but you can **install it like an app**: it gets its own icon, opens full screen without the browser's address bar, and has its own spot when you switch between apps. It's the same FleetOptima with the same login, and it updates itself, so there's no app store and nothing to download again.

**Android (Chrome):** open FleetOptima, tap the **⋮** menu (top right), then **Add to Home screen** (or **Install app**), and confirm.

**iPhone (Safari):** open FleetOptima, tap the **Share** button, then **Add to Home Screen**.

*Why:* without the browser's bars there's more room on screen, and nothing covers the buttons at the bottom, like the camera's shutter.

### The top bar
- The **?** opens this guide at the part about the page you're on.
- The **megaphone** sends us feedback (see below).
- **Your initial** in a circle opens the **account menu**: your name and role, **Account settings** (change your password, sign out everywhere, delete your account), **App settings**, **Org settings** (VIN settings, for anyone allowed to change Settings), **Help** and **Log out**.
- **App settings** picks the look: light, dark, or whatever your phone or computer is set to.

### Everywhere
- **Refreshed a page?** The back arrow still works: it takes you up one level (a work order → the work order list → Home).
- **Every page has its own web address.** For example, `/assets` is the asset list, `/assets/new` is a new asset, `/work-orders/123` is one work order, and `/parts/123/edit` edits a part. You can bookmark a page or send someone a link to it.
- **The back button walks back one page at a time**, like any website. On the home page, the first back shows **"Press back again to exit"**, and the second one leaves the app.
- **Which version am I on?** The small grey number at the bottom of Home and the login page (like **v0.4.0**). Tap it to see **What's new**: every update, newest first, with a link to the part of this guide that explains each change. It's also under **Org settings → What's new**. Hold the number down to see the exact build, if we ever ask.
- **After an update**, a note shows on Home once: **"Updated to v0.4.0. See what changed."** Tap **What's new** to read it, or **Got it** to hide it until the next update. Don't want these notes? Turn off **Show a note on Home after an update** on the What's new page.
- **"A new version of FleetOptima is ready."** When we update FleetOptima while you have it open, a thin bar shows across the top. Tap **Reload** to get the new version (anything you already saved is safe), or **Later** to finish what you're doing first. *Why:* an open page keeps running the old version until it reloads, and old and new don't always get along.
- **Opening a link to something that was deleted** (or doesn't exist) shows a **Not found** page with a button to go home.
- **Something bugging you? Yell at us.** The megaphone button at the top of every page opens one big box. Say whatever you want, however you want: cussing and CAPS LOCK welcome. The app adds which page you were on and which version you're running, so you don't have to explain any of that.
- **You can copy any text on a details page.** Long-press it (or drag across it with a mouse) to copy a VIN, a part number or a note.
- **Missing something in a dropdown?** Most dropdowns end with **New ...** (New Asset Type, New User, New Measuring Unit). Make it right there, and when you come back it's already picked. *Why:* so you never have to abandon a half-filled form just because one choice was missing.
- **There's more than one way to do most things.** You can start a work order from the home page (**Quick actions → New Work Order**), from the Work Orders list (**+ New**), or from an asset (**Create Work Order**). You can change stock from a part, or by pulling parts on a work order. You can log a reading from the asset's **Readings**, or when you complete a job. Use whichever feels natural. They all do the same thing behind the scenes.

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

### The asset's page
Open an asset and the **essentials** are on top: name, type, operator, reading. Under them are **headers you tap to slide open**:
- **More details**: everything else saved on it (the rest of the VIN lookup, see below).
- **Maintenance**: its maintenance rules, and what's coming up or due (see **Maintenance**).
- **Work orders**: this asset's jobs, newest first. Tap one to open it.
- **Readings**: its current miles or hours, and **Log reading**.
- **Costs**: what its parts cost over the last 6 months, per mile or hour (only if you can see costs).

A header starts closed and doesn't load anything until you open it. Tap it again to close it.

*Why:* an asset collects a lot over the years. The things you check every day stay on top, and the rest is one tap away instead of a long scroll.

### Logging a reading
**The asset → Readings → Log reading.** Type what the odometer or hour meter says now. Readings only go up, so the app stops you if the number is lower than the last one. You can also log one when you **complete a job** (the app asks).

*Why it matters:* maintenance that runs on miles or hours (see **Maintenance**) only knows a truck is due if someone tells it the reading. Costs per mile and per hour come from readings too.

### What's on the form
The form has two parts:
- **The top is how it is right now:** nickname, asset type, **operator** (the person who usually runs it), the **unit** it counts in, and its **current reading**. The reading is named after the unit: **Current miles**, **Current hours** (just **Current reading** until a unit is picked).
- **Specifications are what it is:** the VIN (or serial number), make, model and year. These hardly ever change once they're filled in.

*Why split it:* the things you update all the time sit on top where your thumb is, and the things you set once stay out of the way.

*Why an operator:* so everyone knows who usually runs it, and who to ask when it starts making a noise.

The **unit** fills in from the asset type: a Vehicle counts **Miles**, and you can change it (a truck with an hour meter, say). *Why units matter:* maintenance runs on them. "Every 3,000 miles" and "every 250 hours" only work if the app knows which one this machine counts. Mileage or hours can be typed or **read off a photo of the dash** (camera button; see *Reading it off a photo*).

### The VIN fills in the rest
Enter the VIN any of three ways:
- **Type or paste it.**
- **Scan the barcode** (barcode button in the field) on the VIN sticker. That sticker is usually on the front door jamb. Work vans and trucks tend to have one; many cars don't.
- **Read it off a photo** (camera button) of the VIN plate at the bottom of the windshield. See *Reading it off a photo* below.

Once there's a VIN that passes its **check digit** (a built-in math check every North American VIN has), FleetOptima looks it up with **NHTSA**, the US government's vehicle database, and fills in the make, model, year and more. **VIN settings** (Org settings) decide which of those details sit on the form; the rest go into **More details**, so nothing is thrown away. Anything you already typed is never overwritten.

**More details** holds everything else the VIN lookup found (engine, body style, plant...). You can edit any of it, and your edits stick: looking the VIN up again doesn't overwrite them. *Why keep it all:* you don't need engine size today, but the day you're ordering a part, it's already there.

A VIN that fails the check digit doesn't look anything up. Compare it with the plate. Serial numbers on equipment are saved as entered (in capitals).

### Asset types
**Home → Asset Types.** Every asset is one type. You start with **Vehicle** and **Equipment**, and you can add your own (Trailer, Forklift, Generator...). A type has:
- **Name**
- **Default measuring unit**: what new assets of this type count in (Vehicle → Miles, Equipment → Hours).
- **What's its ID called?**: what the ID number is called on the form, like **VIN** or **Serial Number**. New types start as **Serial Number**; change it to **VIN** for vehicles.

*Why asset types:* they're presets. Pick "Equipment" and the form already knows it counts hours and asks for a serial number, so you're not setting the same things on every machine. Make a type for anything you have a lot of.

---

## People

### Users and roles
**Home → Users** lists everyone in your company. Each person has a **role**:
| Role | Can |
|---|---|
| **User** | Whatever their **groups** allow (see **Groups and permissions** below). |
| **Admin** | Everything, whatever their groups. |

Everyone only ever sees their own company's assets, jobs, parts and people. Tap a person to see when they last logged in.

*Why:* so the person reporting a flat tire can't accidentally delete a coworker's account or change company settings. Give Admin to whoever runs the shop, and groups to everyone else.

### Name and username
Everyone has both. The **Name** is what everybody sees: on lists, on work orders, in history. The **Username** is what they type to log in (they can also log in with their email). They're separate on purpose: fix a name or add a last name (**Matthew** to **Matthew Smith**) and their login stays the same. Only change the **Username** box on **Edit** if they should log in with something new, and tell them when you do.

### Adding someone
**Home → Users → + New.** Fill in their **Name**, a **Username** (what they log in with), their **Email** (optional), their **Role** and their **Group**. Then pick **How will they sign in?**

- **Send an invite** (the usual way): no password from you. After you save, an invite pops up with a **QR code** and a **Copy link** button, and if they have an email, it's emailed to them too. They open it, check their name and username (you can leave the username blank and let them pick), choose a password, and they're in. The invite works once and lasts **7 days**. Making a new one cancels the old one.
- **I'll set their password:** a password box shows. Type one and tell them yourself.

**No email?** That's fine. Show them the QR code on your phone and they scan it with their own phone's camera, or text them the link.

**Each email can only be on one account**, and every username is unique. *Why:* so email login and Forgot password always mean exactly one person, and nobody else's inbox can open your reset link.

### When someone can't get in
Open their user and tap **Reset password**. You get a link and a QR code, same as an invite (emailed too, if you want). Their old password keeps working until they use the link, which works once and lasts **24 hours**. You can also tap **Invite** on anyone who never finished setting up.

### Lost phone, or someone left
Open their user and tap **Sign out everywhere**. It asks first, then logs them out on every phone and computer. A screen they already have open can keep working for up to **15 minutes**, then it's done. If they've left for good, **Delete** their user too. *Why:* a phone left in a truck or a shop computer someone forgot to log out of shouldn't keep a door open.

### Your account
**Account menu → Account settings → Change password.** Type your current password, then the new one twice. Forgot the current one? There's a link to **Forgot password** right there. Changing it logs you out on your other devices.

**Sign out everywhere** (same page) logs you out on every phone and computer, this one too. Use it if you lost a phone or logged in somewhere you shouldn't stay logged in.

**Delete account** (the red button on the same page) asks if you're sure and for your password, and you can't log in again afterward. Your work orders and history stay with the company. **If you're your company's only Admin, deleting your account deletes the company too**: everyone in it loses access. FleetOptima warns you and makes you tick a box first. *Why:* a company with nobody in charge can't add people, change settings or fix anything. Make someone else an Admin first if the company should keep going without you.

**Passwords** need at least 6 characters, with an uppercase letter, a lowercase letter, a number and a symbol.

### VIN settings
**Account menu → Org settings → VIN settings.** Tick which details from a VIN lookup sit on the asset form. The ones that are on are listed first; the rest (there are over a hundred) are under **More fields**. Anything left off still goes into **More details**, so nothing is lost. *Why:* a VIN lookup returns a lot. A plumbing company might care about towing capacity and never about airbags. Keep the form to what *your* people actually look at.

## Groups and permissions
What each person can see and do comes from their **groups**. A group is a set of things people can do, like "Mechanic" or "Operator". Put someone in a group and they can do what it allows.

### The short version
- **Everyone is in one or more groups.** Each group says what its people can do.
- **More groups = more they can do.** Groups only ever *add*. Nothing in one group takes away what another gives.
- **Admins can do everything**, whatever their groups.
- **Someone in no group can't see or do anything yet.** Home is empty for them until you add them to one.
- **Changes take effect right away.** No logging out needed. Their Home catches up the next time they open the app.

*Why it works this way:* it's how Linux does it, and it's the simplest system anyone's come up with. Because groups only add, you never have to figure out *why* someone can't do something. You just look at what their groups give them.

### The groups you start with
Every company starts with these three. Change them, rename them, or make your own.

| Group | Can |
|---|---|
| **Admin** | Everything. |
| **Mechanic** | Assets, work orders and parts: view, add and edit (not delete). Pull and return parts, see costs, log readings. See what maintenance is due and say when it was done (not set up rules). |
| **Operator** | See the trucks, report a problem (a new work order) and log readings. Sees only the work orders they reported. No parts. |

### View, Add, Edit, Delete
Each thing in FleetOptima (assets, work orders, parts...) has four boxes, from least to most power:
- **View**: see the list and open things.
- **Add**: make new ones. **Add without View** means they only see what *they* added. That's how an Operator reports problems and checks on their own reports without seeing everyone else's.
- **Edit**: change them. For work orders, that includes starting and completing a job.
- **Delete**: remove them.

**Edit and Delete need View.** They stay greyed out until View is on, and turning View off clears them. *Why:* you can't fix what you can't see.

You only see the buttons you can use. Without Delete there's no Delete button; without Edit on work orders there's no Start or Complete.

### What each row covers
| Row | What it unlocks |
|---|---|
| **Assets** | The trucks and equipment, their history and maintenance. |
| **Work Orders** | Jobs, their notes, starting and completing them. |
| **Parts** | The parts list, restocking, counting, setting a batch's cost. |
| **Pulling & returning parts** | Taking parts for a job (or Use or toss), and putting them back. |
| **Costs** | Seeing prices and what jobs cost. **Without it, prices are blank everywhere**: parts, batches, a job's parts total. |
| **Mileage** | Logging a reading (miles, hours, whatever the asset counts). |
| **Maintenance (what's due)** | Seeing an asset's maintenance and what's due (View); saying when it was really done, and turning a rule off for one asset (Edit). |
| **Maintenance rules** | Setting up the rules themselves: adding, changing (for all, or one asset's own interval) and removing them. |
| **Asset Types** | The kinds of assets and their measuring units. |
| **Users** | People: adding, changing, removing, and their groups. |
| **Groups** | Making and changing groups. |
| **Settings** | **Org settings** (VIN settings) in the account menu. |

A brand-new feature starts **off** for everyone but Admins, until you tick it for a group. (Companies that start after a feature exists get sensible defaults: new companies' Mechanics can see maintenance and log it done.) *Why:* nothing new shows up in front of your people by surprise.

### Putting someone in a group
**Users → the person → Groups & permissions.**
- Their groups show as **chips** (`MECHANIC ×`). Tap the **×** to take them out of one, or **Add group** to put them in another.
- Tap **Save**. It takes effect right away.

Making someone an **Admin** (their role, on Edit) adds the Admin chip too, so what you see matches what they can do.

### Extra powers for one person (Advanced)
Want one mechanic to also delete parts, without making a whole new group? On their **Groups & permissions** page, open **Advanced permissions** and tick it for just them.
- Boxes their groups already give are **checked and greyed out**. Hold one to see which group gives it ("Granted by Mechanic").
- To take away a greyed box, take them out of that group, or change the group.

*Why:* so you don't end up with a group called "Pops Special Access" for every exception.

### Changing a group
**Home → Groups** lists each group, how many people are in it, and what it can do in plain words.
- Tap one to change its boxes or rename it, then **Save**. Everyone in it gets the change right away.
- **+ New** makes a group (like "Lead Mechanics": put your leads in both Mechanic and Lead Mechanics).
- **Delete this group** asks first and tells you how many people lose what it gives. Their other groups stay.

### The safety rules
- **Every company keeps at least one Admin.** You can't remove or demote the last one.
- **Only an Admin can change or remove an Admin.**
- **Nobody hands out more than they have.** Someone who manages users (but isn't an Admin) can only give the powers they have themselves.
- **Nobody but an Admin changes their own permissions.**
- **Ten wrong passwords in a row locks an account for 15 minutes.**

*Why:* so a shop can let a manager handle people without risking anyone locking the company out of its own app.

---

## Work orders

A work order is one job on one asset: "brakes squealing on Truck 12."

### The list
**Home → Work Orders.** Jobs still to do (**Open jobs**) are on top, newest first. Finished and cancelled ones are tucked into **History** at the bottom: tap it to slide it open.

### Reporting a problem
**Home → New Work Order** (under Quick actions). Pick the asset, give the job a **Title** ("Oil change", "Brakes squealing"), and say **What's wrong**. Notes go in the job's **Details** as you work on it.

As you type the **Title**, the app suggests names your company already used ("oil" → **Oil change**). Tap one to use it, or keep typing something new. *Why:* when every oil change is called "Oil change," FleetOptima can tell they're the same job, which is how maintenance knows a job was done (and, later, which parts it usually takes). Operators, mechanics and owners can all do this. You can also start from the asset itself: open the asset and tap **Create Work Order** (the asset is already filled in).

### Where a job is (its status)
| Status | Meaning |
|---|---|
| **Open** | Reported, nobody's working on it yet |
| **In Progress** | Someone tapped **Start** |
| **Completed** | Done |
| **Cancelled** | Stopped without finishing |

- **Start** moves an Open job to In Progress.
- **Complete** works from Open *or* In Progress. If you open and finish a job in one go, you don't have to tap Start first. It asks for the asset's **reading now** (miles or hours), filled in with the last one: leave it if it hasn't changed, or type the new one.
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

### Details (a job's notes and history)
Every work order keeps a list of what happened, oldest first: reported, started, parts pulled, parts returned, edited, completed or cancelled, plus any notes.
- Each record shows **who** did it and when.
- **Add note** adds your own note (just type it).
- **Details can't be deleted or edited.** If something was wrong, add a note that corrects it. That keeps the history trustworthy.
- Deleting a work order hides it, but its records and its parts history are kept.

---

## Maintenance

A maintenance rule is a job that comes around on a schedule: "**Oil change**, every **5,000 miles** or **6 months**, whichever comes first." FleetOptima keeps count for every asset the rule covers and makes the work order when it's due.

### Adding a rule
**An asset → Maintenance → + Add rule.**
- **Job**: what the work order will be called ("Oil change").
- **Every how many** miles or hours (the asset's own unit), and/or **every** so many days, weeks, months or years. Fill in one or both. With both, **whichever comes first** wins: a timing belt at 5 years or 70,000 miles is due at 5 years even if the truck only did 20,000.
- **Apply to**: who gets it, with how many each choice covers right now: **All Trucks (12)**, **All Ford F-150 Trucks (6)**, **Just Truck 12**. It starts on the narrowest group, not the whole fleet.

You never build groups by hand: FleetOptima works out which assets match from what's on them (type, make, model, year). Add a new F-150 later and it **joins the rule on its own**.

*Why:* 10 trucks shouldn't mean typing the same oil change 10 times.

**Turned a rule off and back on?** It starts counting again from that day's reading (marked "assumed"), so the time it was off doesn't make a job overdue. If the job was really done some other time, set when it was last done.

### "Counting from today"
When you add a rule, FleetOptima doesn't know when each truck last had the job, so it **starts counting from today**, at each one's current reading, and tells you which ones. Their maintenance shows **(assumed)** until someone fixes it.

Know the real date? **The asset → Maintenance → Done when?** Set the day and/or the reading it was done at. "(assumed)" goes away and the count starts from there. If that makes it overdue, the work order shows up right away.

*Why assume instead of asking for every truck:* you can start using it right now and fix the dates as you find them, instead of digging up 10 receipts before anything works.

### Coming up, due, and the work order
Each rule on an asset shows **Next** (the reading and/or date it's due), **Last** (when it was done), and where it stands:

| Shows | Meaning |
|---|---|
| **OK** | Not close yet. |
| **Coming up** | In the last **20%** of the interval: 1,000 miles before a 5,000-mile oil change, about 5 weeks before a 6-month one. |
| **Due** | Time's up. A work order has been made. |
| **Skipped** | Its work order was cancelled; waiting for the next round. |
| **Off** | Turned off for this asset. |

**When it's due, the work order makes itself**, straight onto the list, called by the job's name, with "Auto-generated by maintenance rule" in its details. Nobody approves it first. There's only ever **one at a time**: until that job is finished, the rule doesn't make another.

Miles and hours are checked the moment someone logs a reading. Dates are checked once a day, and whenever someone opens an asset's Maintenance. *Why "coming up" first:* so a due date is never a surprise.

### When the job's done
**Complete** the work order and type the reading (it asks). The rule starts counting again **from when it was actually done**: due at 3,000, done at 4,000, next one at 7,000.

- **Did it before the rule asked?** A job with the **same name** on that asset counts too ("Oil change" done by hand resets the oil change rule). Another reason to use the suggested job names.
- **Done somewhere else** (an outside shop)? Make a work order for it and complete it, so the history stays in one place. Or use **Done when?** on the asset.
- **Cancelled the work order?** That round is skipped: no new one until the next due point. (Want it gone for good? Turn it off, below.)

### Changing a rule
**The asset → Maintenance → Change.** Pick who the change is for:
- **All on this rule**: every asset follows the new interval. Assets with their **own** interval are **left alone** (the app names them).
- **Just this asset**: it gets its **own** interval ("Truck 7 is old: every 3,000"). Later changes for everyone don't touch it.
- **Follow the rule again**: drop its own interval.

*Why:* the fleet changes together (switched to synthetic oil), but the odd truck stays odd.

### Turning it off
- **The asset → Maintenance → Turn off**: no more work orders from this rule **on this asset**. The rest of the fleet keeps it. **Turn on** brings it back.
- **On a work order a rule made → Stop this rule here** does the same, right where you noticed it.

*Why:* anything automatic should be easy to tell "no" at the moment it bugs you.

### Units
A rule counts in **one unit**: a rule in miles only covers assets measured in miles. A truck in kilometers needs its own rule. *Why:* "5,000" can't mean miles on one truck and kilometers on the next.

---

## Costs

**Home → Costs** (if you're allowed to see prices). What parts cost on your jobs:
- Pick a range: **1, 3 or 6 months**, or **Custom** (a number of days, months or years).
- The **total**, and a **bar for each month**.
- **Costing the most**: assets, with their **cost per mile or hour**. Tap one to see just that asset.
- **Used up the most**: parts, with how much was used. Tap one to open the part.
- Stock still **waiting for a price** (see *When nobody knows what it cost*), and anything used up or lost **outside work orders**.

Each asset's page has the same thing for that asset under **Costs** (last 6 months; **See costs** for more).

**Parts only for now:** labor and outside shop bills aren't counted yet.

---

## Billing and your plan
**Account menu → Org settings → Billing & plan.** Only Admins can change the plan.

### The free trial
Every new company gets **14 days free**, for up to **10 assets**, with no card. The account menu shows how many days are left (under your name). In the last **5 days**, a note shows on Home with **Pick a plan** and **Need more time or assets? Email us**, and your Admins get an email 5 days before, the day before, and when it ends.

**Need longer, or more than 10 assets to try it properly?** Tap **Email us** (it fills in your company name) and tell us. We'll sort it out.

### Picking a plan
FleetOptima is **$8 per asset per month**. On **Billing & plan**, pick how many assets you want to pay for with **−** and **+** (it shows the monthly total), then tap **Pick a plan**. You go to our payment company's secure page (Stripe) to enter your card, then come back here. It takes a few seconds to say **Paid plan**.

- You can't pick fewer than the assets you already have. To pay for fewer, retire (delete) the ones you don't use first, then come back. Nothing is ever deleted for you.
- Your card number goes to Stripe, never to FleetOptima.

### Changing it later
- **More assets:** tap **+** and **Add to my plan**. Before anything happens, a box shows **exactly what it charges your card now** (just the rest of this month on the extra ones) and the new monthly amount after. Tap **Charge $...** to go ahead, or **Cancel**. If the card doesn't go through, nothing changes.
- **Fewer assets:** tap **−** and **Pay for ... instead**. It asks first too: the lower amount starts on your next bill, and this month isn't refunded. Same rule: not below your active assets.
- **Card, invoices or cancel:** opens Stripe's page, where you change your card, see and download every invoice, or cancel.
- **When's the next bill?** Billing & plan says **Next bill: (date) · $...**.
- **Canceled?** It keeps working until the end of the month you paid for. Billing & plan says **Canceled: works until (date)**, then it goes read-only (see below). Pick a plan again any time.

### If a payment fails
You'll see **"Your last payment didn't go through. Update your card by (date)"** on Home. FleetOptima **keeps working** until that date while the card is retried (about two weeks). Update the card under **Card, invoices or cancel** before then. If it still hasn't gone through by the date, the plan is canceled and FleetOptima goes **read-only** (see below) until a plan is picked again.

### Read-only
If the trial ends without a plan, or the plan is canceled, FleetOptima goes **read-only**: everything is still there and you can look at all of it, but nothing can be added, changed or deleted. You'll see **"FleetOptima is read-only right now"** if you try. Pick a plan (or email us) and it all opens back up right away. Nothing is lost.

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
| "Your session expired. Please log in again." | You haven't used FleetOptima on this device in 30 days, your password changed, or someone signed you out everywhere. Log in again and carry on. |
| "You don't have permission to do that." | Your groups don't allow this. Ask your Admin (see **Groups and permissions**). |
| "Error 108: Too many wrong passwords..." | Ten wrong tries in a row. Wait 15 minutes, or ask your Admin. |
| "That link has expired or was already used." | Invite and reset links work once and run out. Ask for a new one (or use **Forgot password**). |
| "That password isn't strong enough." | At least 6 characters, with an uppercase letter, a lowercase letter, a number and a symbol. |
| "Check your email: verify your address before logging in." | Open the link we emailed when you signed up. Tap **Resend** if you can't find it. |
| "Your current password isn't right." | Type the password you log in with now (or use **Forgot password**). |
| "This account was deleted." | That account was deleted. Your Admin can add you again. |
| "Error 206: Can not add asset. Fleet size limit reached." | Your company is at its asset limit. Retire one you don't use, or get in touch for more. |
| "Error 208: A user with this username already exists." | Usernames are unique. Pick another. |
| "Error 219: An account with that email already exists." | That email is already on an account. Try **Forgot password**, or use another email. |
| "Error 212: Every organization needs at least one admin." | That's the last Admin. Make someone else an Admin first. |
| "Error 213: You can't give permissions you don't have yourself." | Ask an Admin to do it. |
| "Error 214: You can't change your own permissions." | Ask an Admin. |
| "Error 215: A group with this name already exists." | Pick another name. |
| "Error 216: Only an admin can change an admin." | Ask an Admin. |
| "That doesn't exist anymore." | Someone deleted it. |
| "FleetOptima is read-only right now..." | Your company's trial is over or its plan was canceled. An Admin can pick a plan under **Org settings → Billing & plan** (see **Billing and your plan**). |
| "Payments aren't set up yet. Email us..." | Tap **Email us** and we'll set your plan up for you. |
| "Error 232: Pay for at least as many assets as you have." | Pick a number at least as big as your active assets. |
| "Error 234: You have more active assets than that..." | Retire (delete) the assets you don't use first, then lower the plan. |
| "That's lower than the last reading... Readings only go up." | Odometers and hour meters don't go backward. Check the number. |
| "Set how often: a reading, a time, or both." | A maintenance rule needs miles/hours, a time, or both. |
| "Error 222: A maintenance rule needs a job name and at least one interval..." | Same: give it a name and how often. |
| "Error 223: That isn't a field this asset type's rules can match on." | The rule tried to match on something this type doesn't use. Pick from the Apply to list instead. |

