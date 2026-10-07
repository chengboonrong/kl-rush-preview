# What's new

Versions follow the pattern `MAJOR.MINOR.PATCH-channel`. Everything before 1.0 is a **preview** (anything may change) or a **beta** (all 1.0 content is in, and saves always carry over). See the [roadmap](ROADMAP.md).

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
