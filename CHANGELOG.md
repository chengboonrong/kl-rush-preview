# What's new

Versions follow the pattern `MAJOR.MINOR.PATCH-channel`. Everything before 1.0 is a **preview** (anything may change) or a **beta** (saves always carry over, and new content still arrives before 1.0). See the [roadmap](ROADMAP.md).

## 0.9.4 Beta (25 October 2026)

KL Rush as a desktop app, and fixes to the full map, the SMART Tunnel and touch screens. Your save carries over.

- **A desktop app for Windows, macOS and Linux.** [Download it](https://github.com/chengboonrong/kl-rush-preview/releases/latest) next to playing in the browser. It carries the whole game, so it plays offline, and opens links in your browser. It starts full screen (F11 switches) and keeps its own save: move your progress across with Settings → Export backup in the browser and Import backup in the app. The [README](README.md#desktop-app) explains opening it the first time. The Windows and Linux apps are new and not yet tried on real machines; on Linux systems that block user namespaces (Ubuntu 23.10 and later), it may not start.
- **The full map inside KLIA and Subang** shows the place you're in, with the game's own photo of KLIA and Subang's Skypark, and you can set a waypoint anywhere there. KLIA and Subang no longer carry a "coming soon" stamp.
- The full map's Layers panel shows every switch at once on every screen. Its last row was cut off on landscape phones.
- **SMART Tunnel:** police never set up a roadblock in the tunnel or on its ramps, and your own car, left in the tunnel as it closes in the rain, goes to the impound with a message instead of staying in the closed tube.
- At Subang's Skypark, the planes no longer cause graphics errors once they finish loading.
- On touch screens, a mission's countdown and the speed and fuel panel no longer cover the objective, and tips and money appear under it.
- A train or monorail ride always ends with you on foot and in view.
- Menus and buttons show one focus ring everywhere, small close buttons are easier to tap, and the mission card fits the screen.

## 0.9 Beta (24 October 2026)

Genting Highlands is built and being checked behind the scenes: the mountain road, Awana and its cable car, and the hilltop resort. It opens in a later update. This release brings a small music fix. Your save carries over.

- The KL Rush theme no longer plays twice over itself when it stops and starts again within two seconds, and quitting to the title stops it until your next tap there.

## 0.8.6 Beta (23 October 2026)

Music of the game's own. Your save carries over.

- **The KL Rush theme**, the tune from the trailers, now plays as the game opens, from your first tap on the title into the first seconds of play, and again while a place outside KL loads.
- **Ride music:** the same tune in its own arrangement on monorail and underground rides (Rhodes, soft pads and a light kompang) and on the KLIA Ekspreso (a steady train pulse and airy synths). It fades in as you board and out as you step off.
- The music follows the Music slider, dips under story lines, and never plays over the car radio: turn the radio on and the theme fades out.

## 0.8.5 Beta (23 October 2026)

A fix for iPhones on the compatible graphics mode. Your save carries over.

- **The title screen no longer freezes for seconds** on WebGL2, the graphics mode iPhones switch to after a graphics reset, while the characters' graphics are prepared, and Play answers at once. Where the browser can prepare graphics in the background, it now does. Something that has just come into view can appear a few frames late.

## 0.8.4 Beta (23 October 2026)

Follow-ups to 0.8.3's fixes, and a traffic fix for KL's two-level roads. Your save carries over.

- **Out of breath, Amir runs** instead of walking, until the bar is a third full or you let go of sprint, so holding sprint is about as fast as before and still ahead of police on foot at one star.
- **Menus turn down only the rain and the street sounds.** The radio and music keep their level, so the phone's Radio app plays as before.
- **iPhone:** while the game is muted or its volume is at zero, your own music or podcast keeps playing.
- A crash on AKLEH or in the SMART Tunnel no longer stops the traffic on the street below or above it, and an ambulance or fire engine up on the deck no longer makes the junctions underneath give way.

## 0.8.3 Beta (23 October 2026)

Three fixes from your reports. Your save carries over.

- **Stamina:** an empty bar leaves Amir out of breath, so he can't keep sprinting in short bursts.
- **Quiet menus:** every menu that pauses the game stops your engine, horn and sirens and turns the rain and street sounds down. Before, the engine kept running behind some of them.
- **iPhone sound in silent mode:** on Safari 17 and later the game plays its sound with the silent switch on. Nothing plays while the page is hidden.

## 0.8.2 Beta (23 October 2026)

Fewer stutters the first time you see a place. Your save carries over.

- **Graphics prepared before you see them.** Petaling Street, the graffiti lane, the SMART Tunnel and the planes overhead prepare their graphics in the background as you approach, and a place you travel to (KLIA, the expressways, Subang) prepares behind its loading card, so its first frames no longer stall.
- The SMART Tunnel's bend now stops a car and the camera where its walls are drawn.

## 0.8.1 Beta (23 October 2026)

The story and the street speak Cantonese, the SMART Tunnel's tube is rebuilt, and a round of fixes. Your save carries over.

- **Cantonese voices (广东话).** The story's voiced lines, the street call-outs and the cashiers' greetings are spoken in KL Cantonese. Settings → Voice now appears: Auto gives Simplified Chinese players Cantonese, with Chinese captions, and everyone else Malay and Manglish; either can be picked in any language. A few call-outs with no Cantonese take keep their Malay ones. The voices are AI-generated and not yet reviewed by native speakers.
- **The SMART Tunnel's tube, rebuilt** to look like a real road tunnel: panelled walls with road grime at their foot, a drain and kerb, a cable tray, lamps in housings, a dark ceiling with jet fans on frames, and a lit KELUAR KECEMASAN emergency exit every 125 m. The open cuttings at each end have precast panels too.
- **Kapcai Thief:** you now catch him with a tackle. He goes down, then kneels with his hands up. It isn't a crime: no report, no wanted stars.
- **Late for the Exam:** Nurul waits at the bus stop by the Lake Gardens gate on Jalan Kuching and rides pillion on her brother's kapcai.
- **Passengers ride with you.** A passenger who got into your car, in five encounters and mission 18, used to stay at the kerb until you were 90 m away. Passengers now ride inside a car, and pillion on a motorbike.
- **The stars** are points across the whole sky. They used to draw as short streaks, and the northern half of the sky had none.
- **More number plates**, so two cars in view rarely share one.
- The tunnel's bend no longer has a notch in its wall, its fans no longer have dark halos on High, and no dotted shadow runs down the cuttings' lanes.

## 0.8 Beta (23 October 2026)

A tunnel under the city that closes in heavy rain, and five more strangers who need a hand. Your save carries over.

- **The SMART Tunnel.** A tunnel modelled on KL's runs under the city from Jalan Syed Putra to Jalan Jelatek: one tube, two lanes each way, 10 m down. Cars and taxis use it, as in the real one, and the signs at the portals bar motorcycles and lorries.
- **Closed for flooding.** In heavy rain the tunnel closes. The phone, the radio and the signs warn you, the gates shut five game minutes later once nobody is inside (an empty car is towed out first), and it reopens 30 game minutes after the rain stops.
- **Five more encounters.** New "?" marks open as the story goes on, and the completion screen now counts eleven:
  - **Illegal Tow:** a crew with no council markings is hauling a tourist's rental car away from Jalan Bukit Bintang. Take her friend's car, ram the tow lorry until the car comes off its lift, and drive it back.
  - **Late for the Exam:** a student at the Lake Gardens missed her bus. Ride her to the exam hall on her brother's kapcai before 08:00 (she waits between 06:00 and 07:00).
  - **Kapcai Thief:** a man tried to ride off on a stallholder's kapcai at Petaling Street. Chase him into the market and catch him on foot.
  - **The Busker's Gear:** a man drove off with a busker's amplifier on Bintang Walk. Ram his car to a stop in the band's van, take the amp from the boot and carry it back.
  - **Lost Cat:** Uncle Raj's cat Oyen ran off at the Lake Gardens. Follow her meow round the lake and carry her back. It opens once you have found five cats.
- The encounters' "?" marks no longer show at KL's spots while you are at KLIA, on the expressways or at Subang.
- A story character whose model fails to load no longer stops the next one from loading.

Not yet: formula racing and a race weekend at Sepang are built and stay off until their checks are done; the Cantonese voices come later; and the five new encounters are text only.

## 0.7.1 Beta (19 October 2026)

The story speaks. Your save carries over.

- **Malay and Manglish voices.** Every voiced line of the story, across Arcs 1 to 3, is now spoken, each character in a voice of their own: Faiz, Uncle Basheer, Inspector Nadia, Suresh and Bos Tunda. People on the street, drivers and the police call out too, in a man's or a woman's voice to match who is speaking. The voices are AI-generated and were chosen take by take; native speakers review them before 1.0.
- **The cashiers greet you** when you walk into a chain shop.

## 0.7 Beta (19 October 2026)

Leave the city: take the train to KLIA, drive the south expressway through a toll plaza, or take the Federal Highway west to Subang. Your save carries over and opens in KL.

- **Beyond KL.** Each place outside the city loads when you go there. Your car, its fuel, your passengers, your money and your wanted level come with you. The phone's new Travel app lists KLIA Terminal 1, KLIA Terminal 2 and Subang, each with the way there and the fare. No flights are on sale.
- **KLIA.** The KLIA Ekspreso (cash or card) runs from KL Sentral to Terminal 1, then Terminal 2. Walk Terminal 1's departure hall and contact pier, cross Terminal 2's skybridge and watch planes taxi under it. Departure boards list the flights, and stalls sell food.
- **The south expressway to KLIA**, between oil palm estates: a toll plaza where you tap your Tolak 'n Go card (short of balance, top it up at the kiosk), a speed camera, an R&R with petrol and teh tarik, and the KLIA exit to the terminal car park. The Sepang exit is signed but closed until the circuit opens.
- **The Federal Highway to Subang**, past motorcyclists in their own lane and under the flyovers, to the Skypark Terminal: nasi lemak inside, and a viewing spot at the runway end where turboprops land. After 22:00 the runway is quiet.
- **Airport jobs** at KLIA, with an airside pass: tow baggage carts to a departing jet before its doors close, giving way to taxiing planes; refuel the parked aircraft in order with the bowser; push an airliner back from its gate on time; and drive the airport limousine to KL (a D licence).
- **Bomba Sukarela and Ambulans.** After Lorong Api, join the volunteer fire crew and put out bin, stall and parked-car fires with the engine's hose. After Cepat, Uncle!, drive the ambulance and bring patients to Hospital KL quickly and smoothly. Each job has three ranks with rewards.
- **Walk into every shop.** The chain shops open their doors: walk the aisles past the fridges and the counter, look out at the rain, and leave. At closing time you're asked to leave before the shutter comes down. Nothing is for sale.
- **Planes over KL.** Turboprops drift low towards Subang and jets cross high towards KLIA, with blinking lights at night.
- **Businesses and six encounters.** After the finale, buy into Uncle Basheer's second branch and Faiz's breakdown business; each pays a small income every game midnight. "?" marks on the map lead to six short encounters with strangers, from a teh tarik contest to leading a wedding convoy. The completion screen counts them.
- **Touch controls that fit.** The stick and buttons scale to your screen, tablets get their own layout, and a keyboard attached to a tablet hides them. Settings → Controls → Touch adds auto-accelerate and tilt steering (it asks for motion access; nothing it reads is saved).
- **Built like the city.** KLIA's terminals, apron, aircraft and train, the expressways, Subang and the shop interiors are built in Blender, with people and traffic, the way KL's streets are.
- In the first mission, Uncle Basheer's lines now all sound like the same man.

Not yet: pay, fares and business prices may still change; the places outside KL have no satellite view on the map yet; the cashiers greet you in text for now; and the Malay and Manglish story voices come next, in 0.7.1.

## 0.6.9 Beta (19 October 2026)

A small fix to a feature still being tested; nothing changes in normal play. Your save carries over.

## 0.6.8 Beta (19 October 2026)

The people of KL, closer up. Your save carries over.

- **Detailed people near you.** The few people nearest you on the street are now detailed anime-style 3D characters, in nine everyday looks: a banker carrying his helmet, a cafe owner in a denim apron, an office uncle with grey hair and glasses, a schoolboy in uniform, a student with a tote, a sound technician with headphones and a tool belt, a producer with a crossbody bag, an aunty in a tudung and baju kurung, and a schoolgirl in a white tudung. Everyone further off keeps a simpler look in the same clothes, so someone walking closer gains detail without changing who they are.
  - They're our own, made from the sample models "AvatarSample_C" by VRoid Project and "VRM1_Constraint_Twist_Sample" by pixiv Inc., and credited in the game.
- **Faiz, Uncle Basheer and Inspector Nadia, dressed anew.** Faiz in an olive work shirt and cargo trousers; Uncle Basheer older, with grey hair and beard, a light-blue shirt and a dark apron; Inspector Nadia in a dusty-pink tudung, a navy overshirt and her ID card on a lanyard.

## 0.6.7 Beta (18 October 2026)

Steadier loading just after the title, and two rare faults fixed. Your save carries over.

- **The city's extra details load one after another.** Right after the title, Amir's look, most of the Blender scenery, the story cast and the easter eggs now arrive one at a time instead of all at once, to make Safari's graphics resets on iPhone less likely. They still appear within the first seconds of play.
- **Bus shelters and sign poles** no longer stay as plain boxes when the street kit loads after the street details.
- **A car's detailed wheels or glossy paint** no longer fail to load in a rare case right after the title.

## 0.6.6 Beta (18 October 2026)

A graphics fix for iPhone. Your save carries over.

- **One graphics reset no longer slows your iPhone down for good.** Safari on iPhone sometimes resets the game's graphics while the city loads ("Your browser reset the game's graphics"). The game used to switch that phone to the compatible graphics mode for good after one reset, and on an iPhone that mode runs at about half the frame rate. Now the first reset only offers a reload; a second within a day still switches, and Settings → Graphics engine switches back. If your iPhone already uses the compatible mode, choose Auto there.

## 0.6.5 Beta (18 October 2026)

A loading fix for iPhone. Your save carries over.

- **iPhone loads no longer stop at 91%.** On some iPhones the loading screen stopped at 91% with "Something went wrong while loading: popErrorScope failed". It now carries on.

## 0.6.4 Beta (18 October 2026)

The story cast in anime style. Your save carries over.

- **The story cast in anime style.** Faiz, Uncle Basheer, Inspector Nadia, Suresh and Bos Tunda are now anime-style 3D characters, each dressed for their part: Faiz the mechanic in a workshop-green hoodie with a "BENGKEL FAIZ" patch and a red rag in his back pocket; Uncle Basheer in a short-sleeved shirt with a pen in the pocket and a mamak apron; Inspector Nadia in a tudung and a blue jacket with her badge; Suresh the clerk in a waistcoat; and Bos Tunda in a black jacket with the TUNDA logo, a company-yellow shirt, a gold watch, keys and a walkie-talkie. They load after the title screen or when their part of the story opens; until then, they keep their earlier look.
  - Basheer and Nadia are our own, made from VRoid Project's and pixiv's sample models. Faiz, Suresh and Bos Tunda are from VRoid Hub: "Messy Haired Boy" by Dyzium, "Bearded Trial" by Benji and "黒スーツの大男" by 陽気婢. All are credited in the game.
- **Everyone else in anime style.** Pedestrians, drivers, police and the other people in missions get toon shading, anime eyes, pointed fringes, rounder limbs and slightly larger heads.

## 0.6.3 Beta (18 October 2026)

The police headquarters and the shophouse back lanes, rebuilt. Your save carries over.

- **Police headquarters rebuilt.** Ibu Pejabat Polis was a dark glass box with a sign stuck on it. It is now a government block in pale concrete with sun louvres, on a podium with a police-blue fascia, with an entrance canopy in the blue-and-white chequer, stair towers at both ends, a radio mast and three flagpoles.
- **Shophouse back lanes.** The backs of the shophouse rows were flat colour. Every unit's back now has a door under a concrete hood, windows with sills, vents, a soil pipe and a water meter, and air-conditioners or a laundry pole, each wall weathered in its own colour.

## 0.6.2 Beta (18 October 2026)

The police have to find you. Your save carries over.

- **The police search for you.** The police used to know where you were even when no one could see you. Now, once no officer, patrol car or helicopter has you in sight, they go to where you were last seen and search there: patrol cars drive there, officers on foot run there, and the helicopter circles over it. No new roadblocks appear on your route until they spot you again. Getting out of sight and away now loses them.

## 0.6.1 Beta (18 October 2026)

Amir in anime style, the dishes in 3D and Faiz's workshop rebuilt. Your save carries over.

- **Amir in anime style.** Amir is now an anime-style 3D character: dark layered hair, a red oversized hoodie, black cargo pants and white trainers. He has his own idle, walk, run, jump and punch animations, his hair and hood move as he does, and he blinks. He keeps the look everywhere: driving, on a bike, carrying a tray, eating at a stall, knocked down and getting up. He loads after the title screen (about 2 MB); until then, Amir keeps his earlier look.
  - The model is "Red hoodie" (Ake) by Akemenos, from VRoid Hub, used under its conditions of use. The animations are from Quaternius's Universal Animation Library (CC0). Both are credited in the game.
- **Dishes in 3D.** In the Food journal, each of the 17 dishes has a View in 3D button: the dish close up on a marble kopitiam table, to turn and zoom. The stalls serve the same models, on the table or in your hands.
- **Bengkel Faiz rebuilt.** Faiz's workshop in Kampung Baru is now a real bengkel, with a zinc roof, a car lift, a workbench, tyre stacks and an engine crane. Cars still drive straight in.
- **Fried bee hoon.** The Petaling Street stall's "Mee Hoor" was a typo; it is now Fried bee hoon (Bihun goreng, 炒米粉).
- **Fixes:** no empty dark pill in the middle of a phone screen before the first subtitle; walking into a wall stands still instead of running in place; in a five-foot way, the camera stays in front of the arcade columns.

## 0.6 Beta (17 October 2026)

The end of the story and a city half again as wide. Your save carries over.

- **Arc 3, Kota Kita: missions 15 to 22.** Faiz, Inspector Nadia and Suresh take down Bos Tunda's clamp-and-tow racket, and the arc ends with the credits.
- **Three new side jobs:** Tunda (tow broken-down and illegally parked cars), Tarik Kereta (find and bring back 12 cars on a credit company's list) and monorail driver. A completion screen on the phone counts everything you've done.
- **A bigger KL.** The map grows from 9 × 9 to 13 × 13 blocks, with seven new districts: Titiwangsa, Setapak, Ampang, Mid Valley, Bangsar South, Bangsar and the Federal Highway.
- **Malaysian streets:** JKR-style road signs, street names at every junction, black-and-white kerbs, monsoon drains a wheel can drop into, footbridges, bus stops and motorcycle lanes.
- **AKLEH**, the elevated highway over Jalan Ampang, two more flyovers and a south interchange.
- **Chain shops:** 38 parody shopfronts (99 Siput Mart, 6-Twelve, FamilyMat, MR BUAT, Watsup and Jagaan) that open and close on the game clock.
- **A new look for the city:** rainforest hills on the horizon, rain trees, new lamps, traffic lights and bus shelters, and new facades for condos, flats, offices and link houses.
- **Screenshots and photo mode.** Press K or use the phone's Camera app; the Gallery keeps your last 30 on your device. Photo mode freezes the game so you can frame the shot.
- **Controllers and mice:** remap any button, button pictures that match your controller, rumble, and a left-handed preset.
- **Voices** for mission 1, with a voice volume setting and subtitles.
- **Chinese for every line** (still a draft), and a way to report a translation.
- **Install the game as an app** and play offline after the first visit.
- **A new phone:** it stands at the screen's edge with the Petronas Towers at dusk as its wallpaper and colour app icons, and longer apps open beside it.
- **Accessibility:** do any hold with one press, a high-contrast HUD, and menus that work with a controller alone.
- The in-game phone is now held in your hand on screen.

## 0.5.8 Beta (17 October 2026)

- **Easter eggs (彩蛋).** Eleven rare moments now hide around KL, each only in its own weather, hour and place: a rainbow after the rain, fireworks over KLCC at midnight (every night on New Year, Merdeka and Malaysia Day), shooting stars on clear nights, wau over Dataran Merdeka and the Lake Gardens, a pontianak under a banana tree in Kampung Baru, a woman in white hitching a ride on an empty road at night, a toyol on a five-foot way, an empty ghost monorail at 3 a.m., a biawak crossing at a river bridge that traffic stops for, monkeys on the Bukit Nanas path, and a UFO over the Twin Towers. Nothing to collect and nothing saved; in free roam you might meet one an hour.
- Kampung Baru has banana trees.

## 0.5.7 Beta (16 October 2026)

- **Ride the underground trains.** After you board, you watch the train pull out, follow it down the tunnel past the stops in between, and step off at your station to walk out through the gates. Skip still jumps to the end.
- **Station entrances look like KL's.** Each of the 11 entrances now shows a way down, with stairs or escalators and handrails, in one of three styles taken from photos of the real ones: open stair wells, small pavilions and angular canopies. A lit banner over each shows the station's name and line badge, and they light up at night.
- **The full map is a satellite photo of KL.** It zooms out smoothly to all of Malaysia, with places the game hasn't built yet censored until their update arrives. A new Layers button hides any kind of icon.
- The train ride panel is now a low bar along the bottom, so the platform stays in view on a phone held sideways.

## 0.5.6 Beta (16 October 2026)

- **A new monorail livery.** Rempit KL's own white with rose chevrons and a graphite skirt replaces 0.5.5's blue wave, which looked too much like the real KL Monorail's. The monorail cabs no longer have a driver.
- **Underground trains pull in before you board.** The train now stops just as Board appears, and the next-train board keeps showing "Tiba" while it stands at the platform.
- The end walls at Bukit Bintang and Pasar Seni no longer shimmer, and the underground halls no longer glow too brightly at night or take on the rain and haze outside.
- You wait facing a train door, TRX's posters no longer hide behind its wall fins, and you can't walk into the corners of the monorail piers.

## 0.5.5 Beta (16 October 2026)

- **KL's rail stations, rebuilt from photos of the real ones.** All 11 underground stops have their own look. Kelana Jaya line stops have white ceiling grids, stainless screen doors and yellow diamond boarding boxes. Kajang line stops have dark slatted ceilings, black granite and white piers. Each has its own colours and end wall, like Pasar Seni's blue confluence and Bukit Bintang's red angles.
- **Signs read like KL's:** station codes (KJ10, KG16), Malay above English, line maps, and next-train boards that show the direction. Parody ads go up on the walls.
- **Trains arrive from the tunnel,** with shaped noses, lit windows, seats and riders. The Kajang line train is wider, with a black face.
- **Monorail platforms** get cream platform gates that open at the train's doors, a black-and-ochre checkerboard floor, a ribbed roof on white arches, wall fans and red LED next-train boards. The trains got a new livery and a driver, both changed again in 0.5.6.
- Merdeka and TRX use simple interim designs until a cultural review.

## 0.5.4 Beta (16 October 2026)

- **Haze (jerebu).** On dry days, smoke haze can roll in for a few hours: the towers fade into a warm grey murk and the sun turns into a dim orange disc. Rain washes it out. Settings → Haze turns it off.
- **A mission title card** shows while a story mission loads, with the sun bears.
- **Police take the place of traffic in a chase.** The streets thin out as the stars rise, so there are still cars to steal.
- **Cepat, Uncle!:** the ambulance gets through. Traffic gives way to it at junctions, it eases round queues, and a tow crew clears the lane's lorries once you've moved them.
- A mission character knocked down by a car gets back up into their part, so a mission can no longer get stuck.
- Monorail stations, rail entrances, the underground camera and the city map are clearer. The map now shows the Kelana Jaya and Kajang lines. Traffic no longer waits for ever behind someone standing in the road.

## 0.5.3 Beta (16 October 2026)

- **Set waypoints with a controller.** On the city map, the left stick moves a cursor, A sets or clears a waypoint there, RT and LT zoom, and B closes the map. While the map is open, the controller no longer moves you.
- **Play on a phone or tablet with a controller or keyboard** and the on-screen controls get out of the way. Touch the screen to bring them back.
- The right stick turns the camera at the same speed on every screen. It turned twice as fast on 120 Hz screens.
- The game reads the controller you last pressed, so a USB receiver or wheel plugged in first no longer hides yours.
- Losing the controller while you play pauses the game.

## 0.5.2 Beta (16 October 2026)

- **Sun bears on the loading screen.** A Malayan sun bear and her cub stand on the street in front of the skyline, and the mother waves when the lights come on.
- **No more freeze when you change the graphics setting.** A small card with the loading screen's skyline and the sun bears shows while the new setting applies, instead of the game stalling for a moment. Screen readers announce it.
- The loading screen uses less graphics memory, which helps on phones.
- The title screen's language switch, version and small print are easier to read.

## 0.5.1 Beta (16 October 2026)

- **Petrol stations look like Malaysian petrol stations.** A lit canopy with downlights, a tall price pylon by the road, pumps on raised islands, a glowing kiosk front and black-and-white kerbs. Hell, Petronanas and BolehPetrol each have their own colours, logo and lettering.
- **The Jalan P. Ramlee flyover stands on piers**, and views that face it and the diagonal streets run faster.
- **Cepat, Uncle!:** skipping to the last checkpoint no longer fails the mission at once. The same skip in Lorong Api and Malam Bola now moves your vehicle clear too.
- **Traffic lights** show their red, amber and green bulbs again.
- Signs at the petrol stations and the JBN · JPG and driving-school counters no longer read backwards from the street.
- Dataran Merdeka's tag now says the Malayan flag first rose there in 1957. Independence was proclaimed at Stadium Merdeka.

## 0.5.0 Beta (14 October 2026)

The first beta. From now on, your saves always carry over.

- **Eight new story missions (Arc 2).** Faiz and Uncle Basheer take on the tow-lorry crew. You follow a tow lorry, cater a wedding feast in a thunderstorm, help the volunteer fire crew, take night photos for Inspector Nadia and escort an ambulance to Hospital KL. Mission 1 now also teaches you to drive.
- **Motorbikes on real physics.** Bikes lean into corners and throw you off in a crash. Midnight Rempit is raced on them.
- **Liga Malam:** eight night races on a ladder, four on a kapcai and four in a car. Gold in all eight wins two gold vehicles.
- **Fuel.** Three petrol stations: Hell, Petronanas and BolehPetrol. Pump by hand, tap your MyCard for subsidised RON95, don't put in the wrong fuel, and buy a jerrycan or pay for a tow when you run dry.
- **Your MyCard and driving licences.**
  - Lose your MyCard and replace it at the counter at Pudu Sentral.
  - Learn to drive lorries and taxis, then pass a real road test.
  - Police roadside checks hand out saman. Pay them on your phone before they get more expensive.
- **Getting around.**
  - Pay with a Tolak 'n Go card or cash at Kedai 24 Jam stores.
  - Ride every monorail stop, plus the Kelana Jaya and Kajang lines through an underground station.
  - Deliver parcels by train as a courier.
- **New jobs and things to do.** Job ranks for taxi, delivery and Bas Kota. Mekanik Bergerak repair shifts. A photo album of 12 KL landmarks.
- **New places.** The Jalan P. Ramlee flyover and two diagonal streets in the old town, a graffiti lane off Petaling Street with a 16th cat, and the Wisma Senja rooftop in Bukit Bintang with KL Tower and the Petronas Towers in view.
- **Controls.** Prompts show the right key, controller button or touch button. Every menu works with a controller. First-time tips explain the new features, and you can turn them off.
- Fuel, licences, the driving school, the card and rail rides are on for everyone. You can turn each of them off in Settings → Game systems.
- Traffic lights change now, and traffic waits behind you at a red light.

## 0.4.27 Preview (14 October 2026)

- **Five stars is serious now.** More patrol cars and more officers on foot come after you, and police motorbikes join from 4 stars, riding into lanes and onto pavements. At 5 stars an armoured police truck rams you off the road and drops a squad of four officers when you're on foot.
- **A police helicopter** at 4 and 5 stars circles overhead, with a searchlight on you at night. While it can see you, your stars won't fade. Get under a roof or put a building between you and it.
- Police cars, motorbikes and the truck knock you down for the arrest; they don't run you over.

## 0.4.26 Preview (14 October 2026)

- Police cars drive onto the pavement again to reach you when you're on foot.

## 0.4.25 Preview (14 October 2026)

Fixes from player reports. Thank you for writing in.

- **The police catch you now.** Before, police cars couldn't find their way to you on foot, so five stars never ended in an arrest. Now they drive right up, officers outrun a sprint from 3 stars and tackle you, and more officers come on foot. Your stars only fade when no officer can see you.
- **Someone calls 999.** Punch someone with no police around, and the person you hit or someone who saw it calls the police. A star follows a few seconds later.
- **Busier streets.** Cars now appear much closer to you, so the street you're on has traffic, especially on phones on Low graphics. Stand in front of a car to stop it, then take it.
- **A gentler start.** New games start at 4:30 in the afternoon, and no rain starts until the first mission is done. In Chinese, the first mission is now called 欢迎回到 KL.
- **A way out of Sungai Klang.** The railings by the river now stop you. If you end up in the water, walk into the wall to climb out, or choose **Get me out** in the pause menu.

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
