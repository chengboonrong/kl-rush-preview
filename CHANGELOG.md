# What's new

Versions follow the pattern `MAJOR.MINOR.PATCH-channel`. Everything before 1.0 is a **preview** (anything may change) or a **beta** (all 1.0 content is in, and saves always carry over). See the [roadmap](ROADMAP.md).

## 0.4.24 Preview (13 October 2026)

- **No more accidental zoom on phones.** On iPhone, a quick double-tap on the pause menu, on the dark background behind a panel or on the language picker could zoom the whole page in, and nothing but a reload zoomed it back out. Double-tap zoom is now off everywhere in the game, and menus still scroll. Thanks to the player who reported it.

## 0.4.23 Preview (13 October 2026)

- **Smoother driving on iPhone.** On devices that run the game on WebGL2 (iPhones switch to it after a graphics restart), each car, bike or bus that came into view froze the game for a split second while its graphics were prepared. All cars now share that work, so busy streets stay smooth. In a test drive at iPhone 15 Plus screen size, the average went from about 39 to 55 frames per second, and the long freezes almost disappeared.
- **Less work for the graphics chip on every device.** Trees, parked bikes and skid marks no longer resend their positions every frame, only when something changes.

## 0.4.22 Preview (13 October 2026)

- **Easier to read.** The headings in the dark boxes on the phone (the card counter's quote and receipt, the fuel pump's total and receipt) are now cream-gold instead of brown on dark teal. With a controller, the selected Resume button in the pause menu stays light, and the yellow ring around the selected item is no longer cut off at the edge of a panel.
- **No punching with a meal in hand.** The punch used to take your hand from under the tray, which left the tray floating in the air.

## 0.4.21 Preview (13 October 2026)

- **Fixes from crash reports.** Loading no longer stops with "Something went wrong while loading" in Brave on iPhone or some apps' built-in browsers. Those browsers add their own scripts to the page, and an error in one of them stopped the game's loading screen.
- In Firefox for iPhone, loading now finishes properly. It used to skip its last steps, so Petaling Street's gates and roof, the detailed cars and the Ultra city textures were missing.
- Fixed a rare error when a crash threw you off a bike and knocked you out during a race.
- When your browser can't start 3D graphics, the loading screen says so instead of showing a code error.

## 0.4.20 Preview (12 October 2026)

- **Cookie-free visit counts** on the public site, so I can see roughly how many people play and which countries they come from. It records page views, country, device, browser and referrer, with no cookies, accounts or saved progress. Details are in [PRIVACY.md](PRIVACY.md). Ad blockers and some privacy browsers block it.

## 0.4.19 Preview (11 October 2026)

- **Side jobs open through the story.** In a new game, taxi fares and the Bas Kota bus route open after *Back in KL*, and food delivery after *Delivery Rookie*. The night race still opens after *Midnight Rempit*. Pressing the job key on a job that isn't open yet tells you which mission opens it.
- Saves from earlier versions keep every job open.

## 0.4.18 Preview (11 October 2026)

- **Retry failed missions from a checkpoint.** Story missions now save a checkpoint on the scooter, lorry, bike and car runs (after each of the first two deliveries, and after losing the police). When you fail, choose to retry from the last checkpoint or quit. Cash already earned isn't paid twice. Works with keyboard, gamepad and touch.
- After three fails in a row at the same checkpoint you can also **skip that part**. A skipped mission still pays its reward but earns no medal.
- Fixed: mission 1 could get stuck on "Follow Faiz" if Faiz was knocked down on the walk. He now gets up and walks on.

## 0.4.17 Preview (11 October 2026)

- **Uncle Muthu is now Uncle Basheer**, and his mamak on Jalan Tun Perak is **Restoran Basheer Maju**, in English, Bahasa Melayu and Simplified Chinese. A mamak is an Indian Muslim restaurant, so the name now fits. Meals, orders and journal entries carry over.
- Faiz's lines that name him have new Malay voice takes, in the same voice as before.

## 0.4.16 Preview (11 October 2026)

- **A map you can zoom and pan.** Pinch or use the + and − buttons on a phone, scroll with a mouse, drag to move, and tap the target button to centre on yourself. On a phone it opens zoomed in on you, and place names stay readable at every zoom.
- Tap near a place on the map to put your waypoint on it. The minimap now shows the distance to an objective or waypoint beyond its edge, and zooms out as you speed up.
- **Better touch controls.** The whole lower-left of the screen answers to the stick: touch anywhere and it appears under your thumb. Action buttons are round and fan out on an arc around your right thumb, with the biggest (Jump on foot, Gas in a car) in the corner. In a car, hold Exit briefly when you're going fast, so you don't bail out by accident.

## 0.4.15 Preview (11 October 2026)

- **Every Faiz line in the story now has a voice**, thirteen new Malay lines across the homecoming, durian, rempit, sports-car and Merdeka missions.
- **Women on the street chat aloud** too: Malay, Chinese and Indian women say "Eh, where are you going? Come, eat first." in the same range of accents as the men, from Kelantan and Sarawak Malay to Mandarin, Cantonese and Hokkien.
- The voices have now been reviewed, and tested on a real phone.

## 0.4.14 Preview (11 October 2026)

- **The Rimba has a detailed new body**, with proper wheels and tinted glass. It loads after the title screen, and falls back to the old body if the files fail to load. The other cars keep their simpler models for now.
- Front seats sit lower, so drivers' heads stay under the roof.

## 0.4.13 Preview (11 October 2026)

- **A real durian.** A durian bought at the Jalan Alor stall now sits on the tray as an opened fruit: spiky green-to-brown husk, five yellow pods.
- Carried meals sit on your right hand where the camera can see them, instead of being hidden behind your body.
- On phones, the meal panel no longer covers the Interact button or the stick.
- Food journal: search works in your own language (try 榴梿), and buttons and filters are easier to read.

## 0.4.12 Preview (11 October 2026)

- **Fewer touch buttons.** On phones and tablets, buttons appear only when they would do something: Interact when something nearby can be used, Ride near a vehicle, Nitro once fitted, Job in taxis, buses and bikes. Walking with nothing nearby now shows 7 buttons instead of 11, and each button keeps a fixed place.
- Tap the minimap to open the city map. Pause, Phone and Camera sit beside it.
- The "Get in" prompt names the vehicle you would actually get into, and no longer offers a wrecked car.

## 0.4.11 Preview (10 October 2026)

- **The city speaks.** Faiz and Uncle Basheer speak Malay in the first missions, with subtitles in English, Bahasa Melayu or Simplified Chinese. Passers-by sometimes call out "Eh, where are you going? Come, eat first." in Malay, Manglish, Mandarin, Cantonese or Hokkien. Auntie Mei Ling (Petaling Street), Uncle Lim (Jalan Pudu) and Priya (KL Sentral) call out when you walk up.
- The voices are AI-generated with VoxCPM2 (Apache 2.0); Settings and About & credits say so.
- A smaller first download: speech and a few extras only load when needed.

## 0.4.10 Preview (10 October 2026)

- **Petaling Street is covered.** A steel roof on red columns runs the length of the street, with translucent panels in red, blue, green, yellow and white, and rows of big red lanterns that glow at night. A Chinatown gate stands at each end. All business names on the signs are invented.
- Under the roof, the camera stays below the lanterns.

## 0.4.9 Preview (10 October 2026)

- **Eight local car bodies** join traffic, parked cars, the garage and the showroom, including a family MPV with seven seats. Cars use parody names in English, Bahasa Melayu and Simplified Chinese.
- The showroom has group and car pickers, with camera, seat, colour and night options.

## 0.4.8 Preview (10 October 2026)

- Smoother city rendering: buildings share GPU data instead of uploading it again for each one. Graphics quality is unchanged.

## 0.4.7 Preview (9 October 2026)

- **Food culture.** Sit at a mamak table, order a food and a drink, eat and linger. Street vendors sell their dishes. New serving models for roti canai, roti tisu, nasi lemak, cendol and teh tarik.
- **The Food journal** on your phone lists 42 Malaysian dishes, with category, cuisine and region filters. Eat the five starter dishes to earn the **Jom Makan** badge.
- Saves update to a new version with an empty food collection. Your progress is kept.

## 0.4.6 Preview (9 October 2026)

- **Preview experiments** (Settings → Preview experiments, all off by default): a Petromas fuel stop near Dataran Merdeka with petrol, diesel and a subsidised fuel price, an in-game MyCard wallet with IC and licence, a driving school with quizzes, a Touch 'n Go card, and a paid monorail ride. These use an invented IC and fixed game prices, not real services.
- Saves are protected: a second tab, or a save from a newer version, can no longer overwrite your progress.

## 0.4.1 Preview (8 October 2026)

- **A new pocket dashboard** with missions, records, map, weather, radio, settings, controls and fullscreen, plus separate touch layouts and control guides for walking and driving.
- On phones the minimap moved to the top-left, clear of the stick.
- Fixed: overlapping touches, rotation and menus no longer leave controls stuck "held". The radio shows whether it is really playing.

## 0.4.0 Preview (8 October 2026)

**A living city**
- **Traffic reacts**: cars brake and honk at crashes, then steer round wrecks, your stopped car and roadblocks.
- **Police roadblocks** from three stars: cars across the road ahead, with a gap at three stars, a stinger at four and no gap at five. On the classic driving, police now ram, PIT, brake-check and box you in.
- **Time of day**: quiet streets and joggers at dawn, office crowds and full mamak at lunch, and a **pasar malam on Petaling Street** from 6:30 pm.
- **With the new physics** (Settings → Driving physics → New (experimental), then reload): police and nearby cars are real physics cars, so PITs, spin-outs and pile-ups happen, and people hit by a car tumble (no gore) and get back up. Classic remains the default.

**中文（预览） and more**
- **Simplified Chinese** joins English and Bahasa Melayu (Settings or the title screen). It's a machine-translated preview with some corrections, Malaysian wording (德士, 罗厘, 嘛嘛档) and place names kept in Malay. Full review by Malaysian Chinese speakers is still pending. Spot a mistake? Tell us with the Feedback button.
- Existing saves migrate to schema 2, preserving language and progress.
- **A new look**: a Malaysian number-plate logo, road-sign place names, and tips from Radio Pecut FM and a teksi driver in Manglish and BM.
- **Settings → About & credits**, including our inspiration: 臺北狂飆 Taipei Rush by @aicodewithme.
- **Settings → Benchmark**: a one-minute test of how smoothly the game runs on your device, with a score, a recommended setting, and an optional anonymous result that helps us make the game run better on more phones.
- **Settings → Display → Performance stats**: the diagnostic box defaults Off, including with `?perf`. On or Off applies immediately and is saved for your next visit. Show FPS stays separate.

**Smoother**
- Roughly **half as many draw calls** in busy streets and chases, so busy scenes run more smoothly, especially on phones.
- **Settings → Graphics engine**: if your browser's graphics keep resetting, the game switches that device to a steadier mode (WebGL2) by itself; you can switch back here.
- The taxi streak bonus now caps at RM 5 a fare. Mission replays pay a quarter of mission rewards and in-mission cash; improved-medal bonuses remain full.

## 0.3.4 Preview (8 October 2026)

- **Long sessions stay smooth**: cars, pedestrians and the collectible cats were never fully cleared from memory after they left the street, so memory crept up during long drives and chases, which phones handle badly. They're now freed properly, and memory stays flat.

## 0.3.3 Preview (7 October 2026)

- **Pause menu on phones in landscape**: the logo was cut off at the top, "Quit to Title" fell off the bottom, and the "Best in landscape" tip could cover the menu. The pause menu now fits, and the tip only shows on the title screen.

## 0.3.2 Preview (7 October 2026)

- **Title screen on big phones in landscape** (like an iPhone 15 Plus in Safari): the Controls button was hidden behind the bar at the bottom. All menu items now fit above it.

## 0.3.1 Preview (7 October 2026)

- **Character selection**: your character now faces you instead of showing its back, and stands beside the menu instead of behind it. On phones it used to be hidden completely.

## 0.3.0 Preview (7 October 2026)

**Driving feel, part 1**

- **A new loading screen**: Kuala Lumpur's skyline at dusk lights up window by window as the game really loads, from the street up, with the percentage beside it. When everything is ready the tower beacons switch on and the city fades into the title screen. If loading ever gets stuck, a Reload button appears.
- **Try the new driving physics**: Settings → Driving physics → **New (experimental)**, then Reload. Cars, vans, the bus and the lorry get real suspension and tyre grip, kerbs you can feel, slides, rollovers (your car rights itself after a couple of seconds), crash damage from the real impact, and an automatic gearbox. Classic stays the default. **Tell us which you prefer** with the Feedback button: reports now say which one you were driving. Motorbikes and traffic keep the classic model for now.
- **Crash camera**: hit something hard and the game drops into slow motion with a dramatic roadside shot, then snaps back. Not with Camera motion set to Reduced, and mission timers slow down too, so it's fair.
- **Sound**: engines rev through their gears (the kapcai, the scooter's drone, the turbo whistle on buses and lorries), tyres squeal and scrub, kerbs thump, and crashes go from a knock to a crunch to breaking glass.
- **Faster to start**: less to download before the title screen, and repeat visits reuse what's already downloaded.
- **iPhone**: sound comes back after a phone call or locking the screen.

## 0.2.3 Preview (7 October 2026)

Fixes from the first anonymous error reports.

- **iPhone: graphics reset during play.** Safari sometimes resets a page's graphics, for example when the phone is short on memory or the game is in the background. The game used to freeze. Now it saves your progress and shows a Reload button, or reloads by itself when you come back from another app.
- **Rotating the phone while the game loads** no longer causes an error.

## 0.2.2 Preview (7 October 2026)

**Gamepads**
- **Menus work with a gamepad**: the title screen, pause menu, phone, settings and food menus. Move with the D-pad or left stick, select with A, go back with B. Start pauses and resumes. Before, you could pause with a gamepad but not get out again.
- **Driving**: holding the left stick diagonally now accelerates while you steer.
- **New buttons**: D-pad left opens the phone; D-pad right starts or stops a taxi, bus or delivery job.
- The Controls screen now shows the full gamepad layout.

**Touchscreen laptops**
- Mouse look works again. Touch the screen and the touch controls appear; use the mouse or trackpad and they hide.

## 0.2.1 Preview (7 October 2026)

- The mission "Hot Wheels" is now called **"Hot Car"** in English. The Malay title, "Kereta Panas", is unchanged.
- **Phones in landscape with Safari's toolbars showing**: the title screen no longer covers the menu. The tip line is hidden, the menu is tighter, and the full-screen hint moves to the top right.
- **Confirmed on an iPhone 15 Plus**: 0.2.0 loads in about 5 seconds, down from about a minute in 0.1.x, and runs at about 60 fps.

## 0.2.0 Preview (7 October 2026)

**New options in Settings**
- **Save backup**: export your progress to a file and import it again, on the same device or a new one.
- **Camera motion: Reduced**: no camera shake or colour fringing, and calmer speed effects. It switches on automatically if your device asks for less motion.
- **Subtitle size**: S, M, L or XL.
- **Marker colours: Colour-blind safe**: map icons, routes and mission markers switch to a palette designed for colour-blind players. Your own waypoint route is now dashed, so it differs by shape too.
- **Key remapping** (Controls): change any keyboard key, and the on-screen hints follow your keys.
- **Graphics quality** now changes instantly, without reloading.
- **Error reports**: anonymous crash reports help fix problems on devices the developer doesn't have. You can turn them off; see [PRIVACY.md](PRIVACY.md).

**Fixes**
- **iPhone and iPad**: fixed a hang during loading that could stop the game from ever reaching the title screen, and made loading much lighter. If the graphics do stop responding, the game now says so and offers a Reload button instead of loading forever.
- Saves from every earlier version keep their progress.

## 0.1.2 Preview (7 October 2026)

- **Phones**: the game asks you to turn your phone sideways when it's upright, and a one-time tip recommends landscape and full screen.
- **iPhone full screen**: Safari can't make web pages full screen, so the Fullscreen button now shows how to add KL Rush to your Home Screen. Opened from there, it runs full screen in landscape with its own app icon.
- **Loading on phones**: the loading screen warns that the first load can take up to a minute. Feedback reports now include how long loading took on your device, which helps make it faster.

## 0.1.1 Preview (6 October 2026)

- New **Support** button on the title screen and pause menu, linking to [Ko-fi](https://ko-fi.com/chrischeng9297). Donations are optional; the game stays free.
- The title screen now fits small phones: the top buttons are icon-only, and the menu no longer pushes the logo off the screen.

## 0.1.0 Preview (6 October 2026)

The first public preview.

**In the game**

- **The city**:
  - An open-world Kuala Lumpur with the Petronas Twin Towers, KL Tower, Merdeka 118, the Sultan Abdul Samad Building, Masjid Jamek, Masjid Negara, Central Market, KL Sentral, Petaling Street and Jalan Alor.
  - The Sungai Klang runs through it, and a monorail line keeps to its timetable.
- **Weather and street life**:
  - A day/night cycle and afternoon rain: wet roads, puddles and umbrellas.
  - Hawker steam, parked kapcai, and 98 different shophouse fronts.
- **Getting around**:
  - Cars, kapcai, buses and a sports car.
  - Left-hand traffic with signals, overtaking and bikes filtering between lanes.
  - Police with five wanted levels.
- **Things to do**:
  - Six story missions with medals and replays.
  - Taxi, delivery, city bus and street-race side jobs.
  - A garage with vehicles, upgrades and paint. Stray cats to find.
- **Options**: English and Bahasa Malaysia; keyboard and mouse, gamepad and touch controls; high, medium and low graphics.
- **Feedback button** on the title screen and pause menu.

**Known limits in this preview**

- Not yet tested on many real phones. Please report how it runs on yours.
- Cars can't flip or roll yet; crashes are simple. Real vehicle physics is planned.
- About 30–40 minutes of story so far.
- No accessibility options yet (key remapping, subtitle size, reduced camera shake).
- First load can take several seconds while graphics are prepared.
