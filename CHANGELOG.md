# Changelog

All notable changes to IPTV AiSubs, newest first. The number in parentheses is the build number
shown in the app under Settings and in the web interface sidebar.

## 2.4.4 (3296)

This release brings search and favourites to Live Sport — a Favorites window with each team's and player's info and news — more leagues and tables from TV listings, places beside the names, ±10 s buttons and the playback time on the picture, and a faster Xtream refresh that falls back to a backup server.

## New Feature

### Search and favourites in Live Sport

- **Teams and players by name.** A search field beside Favorites looks through every view and league at once: "man city", "sinner" or "psg" find the team or the player, and the list shows their matches live, to come and played. The sport addon's search finds players with no match on the page too — "szobo" finds Dominik Szoboszlai · Liverpool — and the list shows his club's matches.
- **Follow from the search.** Every team and player found has a star. A player can be followed on his own (his club's matches come with him) or with his club.
- **The Favorites window.** The Favorites chip opens a window like Settings: Every match, All favorites and Favorite sports on top, then your Players, Teams and Sports. Picking a favourite shows its matches and switches on the views they are in (Live, Today, Upcoming, Results).
- **Favourite sports as a filter.** + Sport adds any sport, not only those with a match now — netball, field hockey or padel too — found by typing.
- **A favourite's info.** A long OK on a favourite offers Remove or Info. Info shows what is known of it: playing now, the next and the last match, the last results, a team's record, place and news, a player's profile and news — for a club with no match in the schedule too.
- **Web interface:** the Sport page searches the same way, with the same stars.

### More leagues from TV listings

- **Matches the schedule lacks** — Serbian and Croatian leagues, lower divisions and more — come from TV listings, with the channels that show them, country by country ("TV listing: Arena Sport 1").
- **Their league tables too,** with promotion, play-off, play-out and relegation in colour.
- **A second opinion on the kick-off:** another source's start shows when it differs ("Other source: TDB 18:30").
- **EuroLeague with live scores** and its table.
- **A source chooser** (ESP, TDB, SRC, ELA, EPG): each source alone or several together.

### Places and rounds

- **A place beside every name** where a table or a ranking has one: a team's place in the table of the match's own competition — its league, or the European cup it plays in — and a tennis player's world ranking, "(150+)" for one outside its top 150. On the web interface too.
- **The tennis round in the match header:** "ATP Basel · Round 1 (R32)", the qualifying rounds too.
- **The match's own rounds on the draw chips** (QR1, R32, R16, Quarterfinal, Semifinal, Final); a tournament's full draw under Tables keeps every round, doubles too.

### ±10 s and the playback time on the picture

- **±10 s buttons beside Pause,** for phones above all, where there is no remote: Quick menu → Other → Controls shown on picture (off by default). On VOD, recordings, DVR timeshift and most catch-up.
- **The playback time on the picture,** like the clock: remaining, elapsed / remaining, elapsed / total, the end, or clock / end, in the corner you choose — Quick menu → Other → Playback time on picture, or Settings beside the clock. Only where the end is known.

### A faster Xtream refresh

- **Only what changed is written:** a big list's refresh no longer rewrites every entry, and the movie and series lists are processed on several cores at once.
- **A failing server falls back to the provider's backup servers,** one after the other.

## Added

- **Addons: a new version is shown and taken in one press.** In the addon browser (app and web) "Update" stands in place of "Installed" when the addon's server runs a newer version, and the Refresh chip says which version it brings in. Live Sport offers to update the sport addon when its server runs a newer one; Settings shows its version.
- **Live Sport: Guide events on or off** (Settings chip): the programmes found only in your TV guides. Many of them are not live, so a new install has them off, and switching them on shows a short warning. The sources' matches are still matched with your guides.
- **Live Sport: the Settings chip** holds the provider, the countries and the sources in one window; the league chooser narrows by typing; the chosen sports and leagues are kept per profile.
- **Every match has a time span and a progress strip:** the guide's end when a channel's guide names the match, else the sport's usual length.
- **Reminders:** a bell in the TV guide, and a reminder from the player's guide too.
- **Phone: reminders and recordings with the app closed.** The exact alarm needs no permission, and Settings → Recordings / DVR → Background recording shows the notifications, the exact alarm and the battery state, each leading to its system switch.
- **Provider groups: the Favorites folders merged by name,** like the group's other folder lists; an order you set yourself still comes first.
- **Live Sport on TV:** a refresh or a channel search shows its progress in the In progress window, and the TV menu's progress icon turns.

## Changed

- **Live Sport: the match you watch stays** in the list even when it is over; it goes a minute after you pick another.
- **Live Sport: more accurate channel hints:** from a TV listing only on the listing's own country's channels; a channel named for several matches at once comes after the sure ones; a match in your guide and in a TV listing shows under both sources, once.
- **Live Sport on TV: a denser right panel,** so more channels fit; on phones the match header shows the surnames.

## Fixed

- Fixes in Live Sport, provider groups, the provider picker, the addon manager, the refresh progress and memory use.

## 2.4.3 (3240)

This release brings reminders for programmes and matches — with a DVR recording for a match — the channel changes after a list refresh, new movies and series in the Library, tennis draws and more sports in Live Sport, and a longer, more accurate TV guide from the EPG sources you add.

## New Feature

### Reminders (TV guide and Live Sport)

- **A programme or a match, one reminder away.** In the TV guide's programme window, and in Live Sport's match view on the bell beside the start time: when it comes (at the start or up to an hour before) and what it does — an alert, or a switch to the channel at the start after a 15-second countdown. Your last choice is the next reminder's default.
- **With the app in the background,** Android does not let an app come to the front by itself: a notification comes instead, and when you open the app it tells you the programme is already on.
- **A match's DVR recording too.** The match's reminder window has a Recording chip: it records the match's best channel for as long as the sport usually takes (football 2:00, tennis 3:00, others 2:30), changeable from 1:30 to 4:00. When the schedule moves the match, the recording moves with it. A red dot marks the recorded matches.
- **A Telegram message as well.** A reminder can also message your Telegram through a bot of your own: set it up on the web interface under Integrations → Telegram, linked per profile.
- **Web interface:** a bell in the programme lists, Media → Reminders, and the reminder and recording on each match of the Sport page.

### Channel changes

- **What a list refresh changed.** After a provider's list is refreshed: the new channels, the gone ones (marked when they were a favourite) and the renamed or moved ones, for the last five refreshes of each provider. In the Library on the Channel changes tile; on the web interface under Providers → Changes.

### New movies and series

- **New movies and New series tiles in the Library:** the titles added since you last acknowledged them, whatever folder they are in, with every filter and order of the folder grid.
- **Favourites filter on the VOD grids:** your Favourite VOD, or the titles of your favourite folders.

### Tennis draws (Live Sport)

- **Every running tournament, round by round.** Under the Tables chip, Tennis has the draws next to the rankings: singles and doubles, from qualifying to the final, opening on the round in play. Each match on a card with the games of every set in one line; a live match shows its live score, and OK opens the match view.
- **From the match view.** On a tennis match the draw is the default view on the left, on the match's own round; the Draw chip beside the tournament name opens it too. On the web interface: Sport → Draws.

### More sports in Live Sport, from the TV guide

- **The sports the schedule does not carry** — water polo, swimming, athletics, handball, volleyball, cycling, golf, snooker, gymnastics, figure skating and more — come from your own TV guides. A programme whose title opens with the sport's name, in the guides' many languages, is a broadcast; one competition at one time, on whichever channels, is one event, with its own row in the sport chooser.
- **One race, one row.** The same competition named in different languages ("Il Lombardia", "Tour de Lombardie", "Lombardei-Rundfahrt") is one event, and so is a channel's broadcast that two guides title differently.

### A longer TV guide

- **EPG days ahead, 1 to 14 days** (Settings and the web interface's EPG settings, 8 by default): how far ahead the guide is stored.
- **The next source continues a channel.** When a channel's guide ends in one source, the next source that has it continues from there, so a short provider guide no longer hides a longer one you added.
- **Your added sources, in your order.** On the web interface's EPG sources page each added source shows how far its guide reaches, and the ↑/↓ buttons set their order: per channel, the first source with a programme wins and the next ones continue it. The provider's own guide stays first, and it can be switched off on its own while the added sources keep matching its channels.

### Always-on clock

- **The time, or the date and time, always on the picture,** in the corner you choose: from the player menu or Settings → Player interface. Faint and without a box, it drifts a few pixels each minute against OLED burn-in.

## Added

- **Live Sport shows each event's time** in place of "Live": its start and, where the TV guide says, its end — red while it runs, with a bar of how far it is. A running match's clock or time on court stays beside its league.
- **Live Sport lists the channels in your languages first:** the audio track's first and second language from Settings, then the rest.
- **Live Sport offers a refresh** when the channel lists or TV guides behind it are a day old, and asks about a provider whose guide or live channel refresh is switched off; the channel search runs again after the refresh.
- **Running tasks on the TV menu:** every refresh, download and backup in progress shows above the clock on the side menu; OK opens them with their progress and Cancel. The provider window shows its providers' refreshes on top.
- **Web interface:** Sport → Matching lists the event channels that matched no match; the EPG "Refresh now" can refresh the active provider (or provider group) only; the IMDb ratings refresh moved under Integrations → IMDb.

## Changed

- **More accurate matching of the TV guides you add.** A channel's country comes first — from its name, a trailing country mark or its group — so it never takes another country's channel of the same name. Provider labels and accents no longer hide a name; a look-alike name with another number, or a "+" channel, is not taken for the channel; stand-in "No Data" programmes are left out.
- **A channel change loads the stream once,** instead of up to three times: less work for the box's decoders and no extra provider connection while switching.
- **A decoder that does not start says what to do:** when the device's hardware video decoder fails and no fallback can play the stream, the error suggests restarting the device if other streams fail too.
- **Live Sport:** a tennis channel showing the match on court is listed first, a doubles broadcast is no longer a singles match's channel, and a tour's general broadcast is listed only on channels that hold the tour's rights in their area. Arabic-named event channels are matched to their matches, and F1 Academy races are no longer listed as Formula 1. The tabs are Live, Upcoming, Today and Results; the Tables menu folds by sport.
- **Chips:** an active chip is marked by its thin frame with white text; yellow means the focused one.

## Fixed

- **The folder header search works again** in Movies and Series, and the Favourite movies view searches your favourite folders only.
- **Presets no longer change the subtitle languages:** a preset describes the AI engine only; the source and target language stay as you set them.
- **A tennis draw that failed to load** is tried again after 30 seconds instead of five minutes.

## 2.4.2 (3194)

This release brings a quick menu for the remote and a beta channel for the Fire TV build: switch it on, and new features arrive for testing before they go out to everyone. The remote's "Open main menu" now opens the menu where you are, and forced subtitles can be kept on.

## New Feature

### Quick menu

- **Your own places, one button away.** Set any button to "Quick menu" (Remote control → Elsewhere, a long press works too). It opens a small window with the places you picked, two to a row with their icons; OK goes there, Back closes it.
- **Pick and order the places.** Library, Live TV, the TV guide, Movies, Series, Favorite VOD, Discover, Live Sport, History, Settings and every other place of the app's navigation. Ten common ones are in it from the start; choose and order them on the Remote control screen or on the web interface (System → Remote control → Quick menu).

### Beta updates (Fire TV)

- **Try new features early.** Settings → Version and updates → Beta updates (on the web interface: System → Updates). Switched on, the in-app update also offers the pre-releases published here on GitHub, marked "beta"; the normal download link stays on the released version.
- **Leaving the beta.** Switched off, a beta build stays until the next normal release passes it. Going back at once needs a reinstall, as Android does not install an older version over a newer one: make a backup first, remove the app, then install the normal release.

## Added

- **Live Sport on a button.** Live Sport can be set to a remote button of its own, as the other places.
- **Forced subtitles always on.** A new switch turns on a stream's forced subtitle track (the foreign-language lines and on-screen signs) even when no subtitle was chosen, whatever its language. In the app under Language, on the web interface under Subtitles → Settings.

## Changed

- **"Open main menu" stays where you are.** On Live Sport, Favorite VOD, Discover and Settings the focus steps onto the page's own menu item, and the page stays open. On a title page it goes one level up, to the place it was opened from, and opens the menu there in the same press.
- **Library from a button or the quick menu** puts the focus on the Library's tiles, not on the menu.
- **Web interface:** the Subtitles page has a Settings sub-tab (the subtitle style moved there too).

## Fixed

- Opening Live Sport from the menu no longer moves the focus onto the menu's Library item a moment later.

## 2.4.1 (3177)

This release brings Live Sport: the day's matches, paired with your own channels and EPG, with a live picture, live scores, tables, player profiles and followed teams, on TV and phone. Around it, the TV menu opens over the content with its names, addons can be browsed and added inside the app, and Live TV's EPG view behaves like the channel list.

## New Feature

### Live Sport

- **The day's matches, on your channels.** Live Sport is a new place in the menu. It reads today's matches from a sport addon and looks them up on your own channels and in your EPG: event channels named after the match, programmes naming both sides, and a tour broadcast while a match of that tour is played. Every match shows which channels carry it, best first, with the provider and the quality.
- **A sport addon is needed.** Live Sport works with a Stremio-style addon that serves a sport catalog. Fire TV builds list one in the addon browser's Recommended row; the menu item appears once an addon is installed.
- **Match view.** OK on a match opens it: the live picture of a channel on the right, the channels under it, and on the left a live scoreboard, the live data or the league table, switchable at the head. OK on a channel shows it in the small picture, OK again goes full screen.
- **Live data.** Events, minute by minute, statistics, lineups with player profiles, form (last five and head to head), and the match report after the final whistle, where the addon has them.
- **Tables and results.** League tables from the Tables chip or from a match; a side's results and its coming matches from its own menu. The tennis world rankings as a table.
- **Follow teams and players.** OK on a name follows it; a small star marks them everywhere, and the Favorites filter shows only their matches.
- **Filters.** Live / Today / Upcoming / Results views, a sport and league tree, your followed teams, the providers to search (all, the active one, a group, one provider) and the countries of the channels.
- **Tennis.** ATP and WTA tours as groups, a tennis scoreboard in the row and in the match view (sets in order, the running set in the live colour), time on court from the moment the match was seen running, and tour broadcasts ("ATP/WTA Tennis") in a section of their own.
- **Formula 1.** Race weekends as sessions with their channels, the championship standings and driver profiles.
- **Live scores as they change.** An addon that pushes sends every change at once; the page reads the others every 30 seconds while something is live.
- **Fast.** The channel search runs with several providers and guides at once in a window of a day and a half, and the last result is kept on disk: the page opens with it at once, even after a restart, and refreshes behind "Refreshing…".
- **On the phone too.** The same page by touch; a match opens as its own page, the tracker goes full screen with a tap.

## Added

- **Addons: browse in the app.** The Addons list has "Browse addons" next to Add; it shows the same catalog as the web interface, and an addon can be added from it.
- **Backup** includes Live Sport's followed teams, country filter and provider scope.
- **Web interface:** a Sport page with the same matches, filters and channel lists.

## Changed

- **TV menu opens over the content.** On Back to the menu, the narrow side menu opens to the right with the items' names beside the icons and a soft edge; the content behind it does not move. It closes as the focus leaves.
- **Chips.** A chip that is on has a thin frame and a yellow label; the focused chip has a thicker frame.
- **Live TV, EPG view.** Back on a programme goes to the channel name first, then to the folders; after choosing a folder the folders stay up until OK on a channel, as in the Channels view; the programme description sits on the same card as the channel info.
- **Channel list.** The focused row shows the running programme alone, a size larger; the next programme is in the panel above.
- **Live Sport icon.** A trophy instead of a ball in the menu and on the web.

## Fixed

- Leaving Live Sport closes its channel; Live TV starts with the logo video, and no second connection is opened.
- Back from a side's match list keeps the focus in the match view.
- A match with only tour broadcasts starts with the live scoreboard in the picture and the focus on the first broadcast; a tour channel starts only on OK.

## 2.4.0 (3102)

This release turns Favorite TV into Live TV, one place with a channel scope and a guide view that swaps only the list for the grid, on TV and phone. It adds provider groups that work as one provider, IPTV favourite movies and series, hiding of folders and channels, a refresh schedule of its own for every provider, and a TV menu you arrange yourself. It is also faster: source and subtitle searches fill in as the answers arrive, the start is lighter, and the menu's pages come back at once.

## App

### Live TV

- **One place for live TV.** Favorite TV is now Live TV. At its top, a scope dropdown (Favorites, All channels, Channels with catch-up) and a Channels / EPG switch.
- **Only the list changes.** In the EPG view the channel list turns into the guide's grid; the header, the folders and the live picture stay, nothing reloads. The switch shows where there are channels for the grid: in an open folder.
- **The guide lives here.** The separate EPG menu item is gone; the remote's EPG button opens Live TV's EPG view in the current scope.
- **Catch-up channels as a list.** "Channels with catch-up" lists the provider's channels that have an archive, played live like the others.
- **Back on TV.** From a channel, Back goes up to the folders, then to the view switch, then to the menu. In the grid, the time row is the top.
- **On the phone too.** The same scope and view switch at the top of Live TV, by touch.

### Provider groups

- **Several providers as one.** Put providers in a group and activate it: Live TV, Movies, Series and catch-up show every member's folders in one list, each marked with its provider. A folder always opens with its own provider.
- **Across the group.** Channel search, number jump, Continue watching and Discover's "available" badge cover every member.
- **Shared favourites.** Favorite TV shows every member's folders in one list, in the group's own order; arranging it leaves the providers' own orders as they are.

### Favorite movies and series

- **Per provider, beside Favorite TV.** Every provider has its own Favorite movies and Favorite series. A provider folder added there is a live link: new titles show up by themselves, with the same counts and "new" marks.
- **Your own folders.** A film's long press offers your favourite folders, where single titles can be collected; a new folder can be made there too.
- **One switch.** "All movies | Favorite movies" in the folder list's header, remembered per kind. Continue watching leads both views.
- **Long press on a folder** adds it to the favourites or takes it out.

### Hiding folders and channels

- **Long press to hide.** On TV, a folder's or a live channel's long press offers to add it to the favourites or to hide it. Hidden items count nowhere, and nothing is deleted: the web interface restores them.

### Provider refresh

- **An hour of its own.** Every provider can refresh at its own hour, or not at all.
- **Choose the parts.** Live channels, movies, series and the EPG can be refreshed or skipped one by one; a skipped part stays as it is.
- **Expiry warning** per provider.

### TV menu

- **Your items, your order.** Choose which items the side menu shows and in what order, in Settings next to the Library's blocks or in the web interface. By default: Library, Live TV, Movies, Series, Favorite VOD, Discover, Live Sport, History.
- **Movies and Series.** They open the Library's catalogue at once and show how many new titles arrived; on the favourites view, only the favourites' new titles.
- **Live Sport.** A new place, coming soon.
- **Everything fits.** Smaller icons at rest and full size on focus; the version number moved under Settings.
- **Phone.** Movies and Series in the bottom bar too, and a tighter narrow side bar in landscape.

### Faster

- **Sources as they arrive.** The addon source list fills in as each addon answers instead of waiting for the slowest one, and up to eight addons are asked at once. An addon still searching shows "…".
- **Subtitle search.** Subtitle addons are asked at once instead of one by one, and every source's results show as they come.
- **A lighter start.** Favourites from another device or a backup that cannot be linked here yet are no longer retried at every start, which removes a long background sync job.
- **Instant returns.** Going back from Favorite VOD, Live Sport or Settings is immediate.
- **Favorite VOD.** The first opening shows placeholders until the order is ready, never an empty or half list.

### Addons

- **Titles without an IMDb ID** are searched by their TMDB ID at the addons that accept it.
- **Add a release by torrent ID.** When nothing is found, a release can be added by its tracker torrent ID at an addon that offers this; a season pack lists its episodes.
- **File size** in the ranked list and in the media info, so releases can be compared before you play or download.

### Fire TV

- **Updates with less space.** The update downloads straight into the system installer as a single copy, after a space check, and a failed attempt leaves nothing behind.

### Fixes

- Discover opened from the menu starts on its first card, also with an addon source, without the Library flashing up first; the same for Favorite VOD.
- History opened from a page's menu or the remote goes into its list.
- Movies and Series opened from the menu show their catalogue on the first try.
- The AI subtitles have an even background without the banded shadow.
- Poster cards have the same size in Favorite VOD, My media and RSS as in the VOD grid.
- The VOD folder header no longer has a "← Groups" chip; Back does the same.

## Web interface

- **Provider groups** in their own submenu after Providers: create, edit, activate.
- **IPTV movie and series favourites:** the Channels page adds VOD folders as live links, and the Favorites page has their own tab.
- **Hide and restore channels** on the Channels page, one by one or in bulk; a hidden row is greyed.
- **Side menu:** its items and their order.
- **Providers:** refresh hour, parts and expiry warning per provider; the VOD customisation moved next to the VOD lists under Channels.
- **Backup** includes provider groups, provider marks and hidden items (they can be left out); restoring adds them without removing anything.

## 2.3.3 (3046)

This release rebuilds the provider VOD grid in the Favorites style, with poster cards that show release, added and episode dates, the Discover filters and rating sorts, and a title index that makes repeat sorting fast. After every list refresh it shows what is new, down to the folder.

## App

### VOD poster grid

- **Favorites-style cards.** Provider movies and series now use the Favorites poster grid with its S/M/L size; the poster stays the provider's. Under the title, a film shows its release date and, where the provider gives it, the day it was added; a series shows its newest aired episode and the newest one available at the provider ("Available: S2E5").
- **The date of the details page.** A card identifies its title by the provider's own TMDB id, as the details page does, so the date on the card is the date on the details page.
- **Chip header.** The category list has a compact chip header (count, Country, Lists, Search); inside a folder: Year, Order, Search and the Discover filters.

### Order and filters

- **One row per criterion.** The order menu lists Original, Title, Date, Added, Date digital, Popularity, TMDB rating and IMDb rating once each; picking the active one again reverses it, as on Favorites and Discover.
- **Discover filters.** Time window, genre, minimum IMDb score, original language and "not watched", the same chips as on Discover.
- **The Date order follows the cards.** Titles are ordered by the day shown on their card.
- **Original by default, or one order for every folder.** Every device switches once to the provider's own order as the default; "For every folder" at the bottom of the order menu makes the chosen order the default of all folders. Settings and the web interface name the orders as the chip does ("Title ↑" instead of "ABC").
- **Repeat sorting is fast.** A title index keeps what was resolved for each title. The first sort of a folder still asks the provider and TMDB; every later order or filter on it is near instant, also after a restart.
- **Starts at the top.** A new order, filter, year or search starts the grid at the top of the new list, and the filters reset when you open another folder.

### New titles

- **What came with the refresh.** After a list refresh the Library tiles show how many new films and series arrived, and the folder cards their share ("757 movies · 12 new"). A filled "N new" chip at the end of the top row shows only the folders that hold something new, and inside a folder only its new titles. A series counts as new when the provider adds an episode.
- **Got it.** "Got it" acknowledges what is there now: in the folder list for all folders, inside a folder for that folder only. Films and series are acknowledged separately, per profile.
- **Straight to them.** When something is new, opening Movies or Series and entering a folder start on the "N new" chip, and a folder opened from the filtered list shows its new titles at once. With nothing new, the focus goes where it always did.
- **One-time database update.** The first start after updating optimizes the channel database once; on very large lists this takes a few tens of seconds.

### Navigation on TV

- **Back on the menu always exits.** On the side menu, Back always offers to exit; inside a page it first steps to the page's header or switch, then to the menu.
- **Back in the VOD grid goes to the header first**, as on Favorites and Discover.
- **The focus stays put.** After switching provider it stays on the provider item of the menu, and opening History no longer throws it onto Library.

### Details page

- **Compact media info.** The media info is a small chip ("4K DV") that leaves room for the date and length; frame rate and tracks open on press.

### Fixes

- Titles named like "EN -4K EN -4K Title 4K (2022)" are found on TMDB again.
- An empty answer from the provider is no longer kept for long, so the details page fills in on the next look.

## Web interface

- **Default title order:** every order the app offers, named as in the app.

## 2.3.2 (3026)

This release makes the web interface opened inside the app on a TV roomier, with a side menu that scrolls and a Back button that closes it.

## Web interface

### On a TV, inside the app

- **Roomier layout.** The web interface opened from the app on a TV is laid out wider, like on a laptop, and scaled to the screen, so tables and forms fit instead of breaking their headings letter by letter. Phones and browsers are unchanged.
- **Side menu scrolls.** Pushing the pointer down at the bottom of the side menu now scrolls it, so the lower menu items can be reached.
- **Back closes it.** The Back button leaves the web interface at once instead of stepping back through every page you opened. On a phone Back still goes to the previous page, and the close button leaves.

### Progress

- Cloud sync, addon import and export, and creating a backup now show their progress.

## 2.3.1 (3019)

This release turns the player's Stream Info into a full diagnostics panel with health dots, lets MKV films and episodes from addons and providers play at their own refresh rate, adds an optional 50 Hz mode for TV broadcasts, and switches every device to the compact lists, FIX navigation and the narrow menu.

## App

### Stream Info

- **Everything in one panel.** The Stream Info chip in the player's top bar opens five sections: Source, Video, Audio, Network and System. A row shows only where the source has a value: a live channel has no file name or size, and with the MPV player there are no dropped frames or underruns.
- **Source:** the addon's name, the server's host name only (never an account or password), the file name, its size and the average bitrate.
- **Video:** resolution, frame rate, the TV's current mode with its refresh rate, codec and bit depth, the HDR type with the Dolby Vision profile and its base layer, HDR metadata (mastering, MaxCLL, MaxFALL), bitrate, decoder and dropped frames.
- **Audio:** the track, the output (passthrough or decoded PCM), the output device (HDMI, ARC/eARC, Bluetooth, USB, speaker) and underruns.
- **Network and System:** download speed, buffer ahead, live delay and playback path; the app's share of the CPU, memory, chip temperature and CPU clock. The system values are measured only while the panel is open.
- **Health dots.** Measured values carry a green, yellow or red dot: dropped frames, underruns, download speed, CPU, memory and temperature. The display row turns yellow when its refresh rate does not divide into the video's frame rate, which makes pans judder.

### Refresh rate

- **MKV from addons and providers.** MKV films and episodes from addons (TorBox, Real-Debrid and others), Xtream series and M3U or Stalker VOD now switch the TV to their own refresh rate (24, 23.976, 25 or 50 Hz), as files from network shares already did. The frame rate is read from the bytes the player downloads anyway, without an extra request, so single-connection providers are not affected. Stream Info shows the exact value, 23.976 instead of 24.
- **TV broadcasts at 50 Hz.** A new option under Settings → Playback & interface → Playback UI → Resolution and refresh rate: live TV and catch-up switch the TV to 50 Hz once, when playback starts, and stay there while you change channels. Broadcasts in Europe run at 25 or 50 frames per second, so motion is smooth instead of juddering at 60 Hz. The switch blanks the screen for 1–2 seconds once. Off by default.

### Layout

- **Compact, FIX and narrow on every device.** Updating switches every device once to Compact spacing, the narrow icon menu and FIX navigation in the channel lists, also where an earlier version had stored the old look (changing the palette alone used to store it), and in your saved appearances. A choice you make afterwards is kept.
- **The same Discover header for every catalog.** An addon with a single catalog now gets the shared filter bar at the top with the list's title under it, like addons with several catalogs. Its buttons used to sit next to the title, on the same line.

## Web interface

- **Picture:** TV broadcasts at 50 Hz, with its explanation behind the "?".

## 2.3.0 (3014)

This release brings fully customisable colours with your own palettes, a rebuilt TV guide with a live picture, folders and three channel lists, a one-row TV Discover with service logos, programme info that follows the focus in Favorite TV and Live TV, Discover in the side menu, and a much lighter background load on TV boxes.

## App

### Colours

- **Change every colour.** Settings → Playback & interface → Appearance → Own colours starts from the colour scheme you use and lets you change any of its 88 colours: backgrounds, cards, accents, text, the folder and group tiles. The app shows the result as you go, and Cancel restores what you had. Remote-friendly colour grid on TV.
- **A whole theme from five colours.** Pick a background, card, accent, AI and text colour, and the other shades are mixed from them.
- **Your own palettes.** Save your colours under a name: they appear in the colour scheme list next to the built-in ones, and can be exported, copied and imported.
- Brand colours (IMDb and TMDB badges), subtitle colours and the shades over videos stay as they are.

### TV guide

- **Live picture in the corner.** The top bar is half as tall, without ‹ Now ›, and the live picture sits in the top-right corner. By default the first OK on a channel's name shows it in the small picture and the second opens it full screen with the same player, without restarting it; until then our video logo plays there. A new setting (Settings → Playback & interface → TV browsing → TV guide live picture) starts it as soon as a row has the focus. The channel playing is marked in the grid.
- **Stays as it was.** Back from full screen, the guide is where you left it instead of loading again, and when you change channel in full screen, the guide and the small picture follow.
- **Folders as in Favorite TV.** The folders open in the programme panel's place: the guide opens on them, Back on the channel names brings them back, and OK loads a folder with the focus on its first channel. Back on the folders goes to the list switch, and Back there to the menu.
- **Three lists.** A small drop-down switches between Favorites, All channels (every Live TV group of the provider, hidden groups left out) and Channels with catch-up. The guide remembers the list and the open folder for each provider.
- **Time span on the time row.** Step up from the first channel onto the time row and change the span shown with Left/Right, from 1 to 6 hours. A long OK on a channel's name brings the guide back to now.
- **Easier to read.** A wider channel column where long names take a second line, a taller programme panel whose description fills it, and twice as many rows with Compact spacing, on phones too.
- **Faster start.** On a cold start, rows the stored guide covers show their programmes at once instead of waiting for the whole guide to be prepared, and "Loading EPG" shows only while a full guide downloads.

### Favorite TV and Live TV

- **Programme info on focus.** The panel beside the live picture shows the focused channel's programme at once, even when the picture starts only on OK, as in the guide. Settings → Playback & interface → TV browsing → Programme info beside the picture brings back the old behaviour, where the panel follows the picture. The description now fills the panel instead of stopping after two lines.
- **Programme (EPG) in the channel menu.** A long OK on a Favorite TV channel opens the player's EPG screen for it: every programme with its full text, catch-up for past programmes and DVR recording for coming ones.
- **Guide progress on every row** in Compact lists, not only on the focused one.
- The "add channels" welcome screen no longer flashes up when Favorite TV opens.

### Discover

- **One row at a time on TV.** Discover shows a single row, with its title and picture above it and the names of the following rows below, with an arrow; the rows you passed follow the title. The filter bar keeps the row you were on.
- **Service logos.** Rows named after a streaming service show its logo, matched against TMDB's list of about 900 services, with the service's App Store icon where there is one. The logos are stored once on the device.
- **Minimum IMDb rating** drop-down after Genre (any, 5+ to 9+). It uses the IMDb score, and the TMDB score where IMDb has none.
- **Watched filter:** off it reads All (open eye), on Unwatched (closed eye), in Favorites and My media too.

### Side menu

- **Discover in the menu,** and a new order: Library, Favorite TV, EPG, Favorite VOD, Discover, History. Opened from the menu, Back steps onto its menu item and the page stays, as with Favorite VOD; opened from the Library's tile, Back returns to the Library.

### Addons

- **Version and updates.** The addon list shows each addon's version, when it was last updated, and New version when the addon's server offers a newer one. The app checks once a day; Update applies it.

### Performance

- **Much lighter cloud sync.** A sync round no longer builds its whole package twice when nothing has changed. On TV boxes each build took up to a minute and a half of a full processor core, every few minutes, and made everything sluggish. Data with no change since the last round is checked again every 30 minutes; a sync started by hand still compares everything.
- **No repeated name matching.** A channel whose name matches no guide entry is no longer searched for again on every request, which kept the processor busy with large guides.

## Web interface

- **Appearance and Colors** under System → Interface: set the colours by clicking on a picture of the app, save named palettes, export and import them.
- **TV browsing:** TV guide live picture (on focus or on OK) and Programme info beside the picture.
- **EPG settings:** the TV guide's time span.
- **Integrations → TMDB:** the stored service logos can be cleared.
- **Addons:** version, update date and the New version alert.

## 2.2.2 (2973)

This release brings a live timeshift you can rewind for hours and keep as a recording, a compact TV layout with twice as many rows on screen, a slimmer icon menu that can stay beside every page, the compact layout and the TV's quick channel list on phones, a single History timeline, and a simpler Discover filter.

## App

### Live timeshift

- **Rewind live TV.** Start timeshift, a new button in the player on live channels and a programmable remote action, records the channel into your recordings location (internal storage, USB drive or network share) and switches the player to that recording. From then on you can pause, rewind and fast-forward back to the moment you started it, however long ago. Live jumps to the newest part, about 10–20 seconds behind the broadcast.
- **Keep it if you want.** DVR → Save current timeshift turns it into an ordinary recording, from its start until you stop it. An unsaved timeshift is deleted when you change channel, stop it or leave the player, and it never shows among your recordings.
- It replaces the earlier timeshift chip, which kept only about five minutes. Timeshift needs the Media3 player and does not run alongside AI subtitles.

### Compact layout

- **Twice as many rows.** Settings → Playback & interface → Appearance → TV spacing has a new choice, Compact. Live TV and Favorite TV then use one-line rows of equal height: as many whole rows as fit (about twelve), eight under the live preview, and 2×5 folders with their names in the small folder list. The focused row opens up as a larger card over its neighbours (a channel with a bigger logo and two lines of guide, a group or folder with its channel count and buttons), while its place on the grid stays, so whole-row stepping works as before. The header of the preview browser is half as tall, and its info box takes a single line.
- **What is playing stays marked.** The channel you are watching and the open folder keep a light highlight, also when the focus is elsewhere.
- **Compact everywhere.** With Compact spacing the player's quick list, the recently watched channels panel, History and the file browser get compact rows as well, and the list shown while channels load has the compact size, so nothing jumps when they arrive. The compact folder grid steps whole rows like the channel lists and never shows a cut-off row.
- **The new default.** Compact spacing and the narrow icon menu are the starting point on new installs, on devices where these settings were never changed, and after resetting the appearance. A choice you made earlier is kept.
- Live TV: starting the preview no longer makes the channel list jump.
- Stepping through a channel list no longer flashes a placeholder "Live" on the focused row before its programme appears.

### Side menu

- **Slimmer icon menu.** The icon-only menu (Settings → Playback & interface → Appearance → Left menu → Icons only — narrow) is about as wide as a channel row, with the version at the top and the clock and date in the middle. The focused item shows its name under the icon, a little wider than the menu. The menu stands slightly away from the screen edge, so the focus frame stays fully on screen.
- **Stays beside every page.** Auto-hide the side menu on TV (Settings → Playback & interface → TV browsing) now applies everywhere. When it is off, the menu stays next to Favorite VOD, Discover, My media, RSS releases, the TV archive, the TV guide, TMDB pages, Settings and the other full-screen pages, and each page fits whole cards into the remaining width. When it is on, these pages fill the screen as before.
- **A working menu on Favorite VOD and Settings.** Back moves from the page to the menu; Right or OK takes you back to where you were, OK on another item opens it, and Back on the menu asks whether to exit.
- **Instant hiding.** The auto-hiding menu now disappears and returns in one step instead of a stuttering slide.

### Remote control

- **Favorite VOD shortcut.** A new action opens Favorite VOD; the action that opens your TV favorites is now called Favorite TV.
- **Discover opens Discover.** The Discover action used to open the release notes; now it opens Discover.
- **Start timeshift** is a new action for Live TV buttons. The rewind and forward actions can now be put on Live TV buttons as well, where they seek in a running timeshift.

### Phone

- **Menu on every page.** The side menu in landscape and the bottom bar in portrait stay beside Favorite VOD, Discover, My media, Settings and the other pages too, with the page's own item selected. In portrait the bottom bar always shows the names; the icon-only style is for the side menu in landscape.
- **Compact mode.** Settings → Playback & interface → Appearance → List spacing → Compact (the default): channel, group and folder rows are about two-thirds as tall and still easy to tap. In Favorite TV's folders, Select and Sort move into a channel's long-press menu, and their bar shows only while you select or reorder.
- **Small-screen view in landscape.** With Small-screen mode in landscape (live preview) switched on (Settings → Playback & interface → Browsing), Live TV and Favorite TV open straight in the last folder when the phone is in landscape: the live preview and the folders on top, the channels below, as on TV. Back goes to the full list.
- **The TV's quick channel list.** The player's quick list of channels and episodes is now the TV's side panel: on the left in landscape, with the picture beside it, and full screen in portrait with a close button. The panel has a stronger background, the current channel is cyan, large system fonts no longer cut off a row's second line, and the player controls step aside while it is open.

### History

- **One timeline.** Films, episodes and channels are in a single list by the time you opened or watched them, latest first, so the top is always what you did last. Under All, a small TV or VOD mark tells them apart; catch-up programmes count as TV.
- **A live channel opens in its own list.** Started from History, a channel opens in its favorites folder, with the folder's name and numbering, or else in its own group, so the quick list shows that list with its guide.

### Player

- **Steady recently watched panel.** Moving through the recently watched channels no longer makes the selected row jump to the edge and back, and the panel lists the last 20 channels instead of 10.

### Favorite VOD, Discover and files

- **Watched / Unwatched with an eye.** The watched filter in Discover, Favorites and My media switches between Watched (open eye: watched titles are shown too) and Unwatched (closed eye: only titles you have not seen). The watched toggle on a film's TMDB page uses the same eyes.
- **Favorite VOD:** the header reads Filter, Date, Any time, Genre, and Watched / Unwatched at the end. The provider line under the cards is gone, so the cards are shorter; availability is shown on the TMDB page.
- **Simpler Discover filter.** Title age, minimum rating, minimum votes and decade are gone, and values saved earlier no longer hide anything unseen. Original language has its own drop-down after Genre, and Any time offers Last 12 months. The Filter button stays only on rows where it still has something to set (date, region, release type, provider, runtime). Series work the same way.
- **Files:** whole-row stepping as in the channel lists, thinner rows with Compact spacing, and My media and Pin to home as buttons next to the sort instead of two rows at the top of the list.

### TMDB pages

- **Smoother opening on TV.** The blurred backdrop is made once, in software, so opening and scrolling no longer stutter on bigger TVs, and devices without GPU blur show it blurred too.
- **Readable title bar.** The title bar sits on a slight shade, and on TV the scrolled list fades out softly under it instead of being cut off.

## Web interface

- **Interface mode** (TV or touch) moved from the Remote control page to System → Interface → Interface mode. It stays reachable from a browser, since the wrong mode can lock you out of the TV's own settings.
- **TV spacing** offers the new Compact choice under System → Interface → TV browsing.

## 2.2.1 (2938)

This release brings a jump-back button and a recently watched channels panel for the remote, fixed whole-row navigation for channel lists, the TV guide and cards (now the default), a cleaner TV look with a frame only on the focused item, and TMDB pages that open with the title's poster.

## App

### Remote control

- **Jump to the last watched channel.** A new action, "Last watched channel (back and forth)", switches between your last two live channels. Put it on any programmable button; the remote's Last/Recall button does it by default. You land in the list you came from, so Up/Down continues there.
- **Recently watched channels panel.** Another programmable action opens your recently watched channels in a side panel on the right. It is built from History, and a live channel only counts after 3 seconds of watching, so channels you just zapped through stay out. A channel picked there opens in its favorites folder, or else in its own group.
- **Separate button layouts for Live TV, Movies & series, and Elsewhere.** A button can do one thing while you watch live TV, another while you watch a movie or an episode, and keep its own function on every other screen. New for movies and series: seek ±10 seconds or ±1 minute, previous and next episode. Where an action does not apply, the button simply does its usual job, without a message. Arrows, OK and Back always work in open player menus and lists, and no mapping applies while you type in a text field. Your existing layout moved to Live TV; its parts that also make sense for movies were copied there once.

### Channel lists and TV guide

- **Fixed navigation, now the default.** Settings → Playback & interface → TV browsing → Channel navigation: Fixed or Scroll. In Fixed mode the list does not glide; the focus moves, and the list steps a whole row when the focus reaches the second-to-last row going down or the second row going up. Rows sit on a fixed grid sized so that whole rows fill the list, with no cut-off row. Scroll mode uses the same grid and glides instead. It applies to channel, group and folder lists (list and grid view), History, the TV guide, the quick channel list and the recently watched panel.
- **The focus keeps up.** Holding Up or Down no longer lets the focus run off the list, and in Scroll mode the 5-row jump with Left/Right glides in one go.
- **Quick channel list in a side panel.** On TV the quick list opens as a full-height panel on the left, right on the current channel, without first showing the top of the list. The focused row is cyan, ▶ marks the channel you are watching, and logos are 16:9. The folder bar and the season and episode lists use the same style, and the player controls step aside while the panel is open. Phones keep the old layout.
- **The focused row stands out more.** Its highlight reaches into the gaps above and below, so the row looks bigger instead of squeezed.
- **TV guide:** Left/Right no longer gets stuck on overlapping programmes, and Up/Down no longer stops at a channel that has no guide data or is still loading.
- Favorite TV: the active folder in the top bar is filled cyan instead of having a thin outline.

### Cards

- **Fixed instead of Fade.** Card navigation's Fade mode is now Fixed: the row changes at once, without the fade effect and the work behind it. After the update both card and channel navigation start in Fixed mode; a choice you make afterwards is kept.
- **Left/Right stays in the row.** At the end of a row in My media and RSS releases, the focus no longer jumps to another row or to the header, in both modes, as in Favorites.
- **Focused cards** show a brighter fill and the zoom, without a frame.
- Discover: a card alone in its row is no longer cut off at the sides when focused, and paging down quickly no longer crashes.

### TV look

- **A frame only on the focused item.** On TV the faint outlines around cards, rows, boxes, drop-down menus and the TMDB header are gone; a frame now marks the focus and nothing else. Phones keep their outlines.
- **Switched-on chips are cyan**, with a very faint, darker frame that differs from the focus frame; switched-off chips are white. This also fixes the Discover header, where some chips looked switched on when they were not.
- **Player chips:** the subtitle and audio chips are the same height as the others (on phones too), the focus frame of the bottom chips stays steady, the top chips have a frame only when focused, and the zap info cards show just their dark background.

### TMDB pages

- **Open with the title's poster.** On TV the card's poster appears at once, large, while the page builds up behind it; then it softens into the page's background and moves with the page as you scroll. The page no longer draws itself block by block. When the page is opened from a place that does not know the poster (RSS, History, Stremio cards), the palette's colours cover it instead.
- The Stream sources button has a subtle dark background, so it stays readable over the picture.

### Addons and IMDb

- **Addon sources follow the channel navigation** setting (Fixed or Scroll), with the same zoomed focus as the channel lists.
- **More shows in addons.** When TMDB has no IMDb ID for a series, the app looks it up on TVmaze by title and accepts only an unambiguous match, so addon sources can be searched for those shows too.
- **An IMDb score for every title, right away.** The app keeps a local index of the full daily IMDb dataset (about 1.7 million titles), so cards show their IMDb score at once, and Discover prepares the scores of every row ahead. Building the index takes about half a minute in the background, once a day.

## Web interface

- **TV browsing** settings under System → Interface: card navigation, channel navigation, live preview, folder list size and side menu. A change applies on the TV at once.
- **Remote control:** Live TV, Movies & series and Elsewhere have their own button layouts, with the new actions.

## 2.2.0 (2900)

This release brings faster, steadier TV navigation with a choice of fade or scroll between card rows, your own 1–10 ratings synced with Simkl and rateable on IMDb by QR code, and a Library you can trim and reorder. It also contains 2.1.19, which was not released on its own.

## App

### TV navigation

- **Fade or scroll between card rows.** On TV, moving to another row of cards now fades over to it by default instead of scrolling the list. Settings → Playback & interface → TV browsing → Card navigation switches between Fade and Scroll. It applies to Discover, Favorites, RSS releases and My media, and to the cast and recommendation rows of a detail page.
- **Instant response to the remote.** Every key press is answered at once; a transition or a loading card never holds up the next step.
- **The column stays.** Moving up or down keeps the focus in the same column on screen, also into a shorter last row and into the horizontal rows of a detail page.
- **Thinner focus border** throughout the app. A focused card is enlarged from the very first frame and keeps its size during the transition. Cast cards are all the same height, and stepping sideways on a detail page no longer shifts the page.
- **Changed filters stand out.** A filter or sort at its default value looks neutral; a changed one keeps a muted outline that differs from the focus.
- **Faster cards.** A card on screen and the same card being prepared ahead share one download, and a missing score is fetched without waiting.
- Settings: focused items no longer zoom and are no longer cut off at the edges.
- Cast cards: a long role can use the free line under a short name, without changing the row height.

### Phones

- **Cards as fast as on TV.** Scrolling prepares the rows below, swiping a row prepares the next cards, and a card appears as soon as its poster is loaded.
- **The same cast cards and chips as on TV.** Cast cards are all the same height, with the name and role sharing their lines; an active chip is outlined instead of filled.

### Ratings

- **Your own ratings.** Rate movies, series and single episodes from 1 to 10: Rate on the detail page, and in an episode's info window. Ratings are kept per profile.
- **Rate on IMDb.** On TV a QR code opens the title in the IMDb app on your phone, where you rate it with your own IMDb account; OK on the code shows it full screen. On a phone, a button opens the IMDb app (or the browser).
- **Rate button in the player** for movies and episodes with TMDB data, never for live TV or other videos. Switch it on under Quick settings → Controls shown on picture; it sits at the right end of the seek bar, with the IMDb QR code too.
- **Simkl sync.** Movie and series ratings sync both ways with Simkl; episode ratings stay in the app.
- **Ratings in backup and cloud sync**, as a separate item per profile.

### Discover, Favorites and Library

- **Choose and order the Library blocks.** Settings → Playback & interface → Interface → Library blocks: switch blocks off, move them with the arrows, or return to the default order. Blocks the profile cannot use can be hidden too.
- **Series by date: latest episode first.** For series, Date sorts by the last aired episode, and "Date digital" is gone from their sort menu.
- **Favorites: the header stays** while the list scrolls, and the focused row moves to the top, as in Discover, My media and RSS releases.
- **Back goes to the Movies/Series switch first** in Favorites, My media and RSS releases, as in Discover; a second Back leaves.
- **Fresher IMDb scores.** The app looks for the new daily IMDb data every hour and uses it at once; when MDBList has a more up-to-date score (more votes), that one is shown.
- Favorites: the "Check availability" button and its background scan are gone.

### Trailers

- **Favorite button** in the trailer reel: ★ shows whether the title is a favorite and adds or removes it at once.
- **Trailers on phones:** the buttons fit in portrait, a seek bar lets you drag through the trailer, and Back closes it instead of leaving a white screen, also after a visit to the title's details.

## Web interface

- **Ratings** in Title Finder: your rating of a title and of each episode, and a link to rate it on IMDb.
- **Interface page** (System → Interface): choose and order the Library blocks.
- Backup and cloud sync list "My ratings (titles and episodes)" as their own item.

## 2.1.19 (2893)

Not released on its own: its changes are part of 2.2.0.

## 2.1.18 (2871)

This release brings Simkl sync, trailers for every addon catalog, free channel numbering in Favorites and hideable channel groups.

## App

### IPTV

- **Set a channel's number directly.** Long-press OK on a channel in a Favorite TV folder and choose "Channel number". With continuous numbering, a number that belongs to another folder moves the channel into that folder, exactly to that number. Another provider's folder only accepts it if it is an MPF folder.
- **Move up / Move down works in A–Z order too.** The first manual move switches the channel order to Custom, starting from the order you see.
- **Hidden groups stay hidden.** Groups hidden on the web interface are left out of the channel browser, of search results across groups and of the catch-up groups in the TV guide. Nothing is deleted, and channels already in your favorites stay there.
- The channel numbering mode (per folder, continuous or off) follows a change made on the web interface immediately.

### Addons

- **Sources: one row per release.** When an addon lists the same release in several resolutions, they share one row with a button for each (for example 1080p · 2.10 GiB, 720p · 1.38 GiB); ◀ ▶ switches between them.
- **Trailers for addon catalogs.** Every addon catalog in Discover gets a Trailers menu. It plays the trailers of the list's titles in the order shown and follows the filter, order, time and genre settings.

### Discover and trailers

- **Not seen switch.** Hides watched movies, and ended or canceled series you have watched. Continuing series stay, because a new season is coming. The trailer reel skips them too.
- **Endless trailer reel.** When a list ends, the next list starts; after the last one, the first one again.
- **Order by digital release date** in Discover and in the movie and series favorites.
- **Longer time filters:** last 60, 90 and 120 days. The trailers' "Now in cinemas" and "New on digital" lists follow the time filter; without one, "Now in cinemas" covers the last 120 days instead of 60.
- **Cinema rows without foreign re-releases.** An old film re-released somewhere else (say, in Argentina) no longer shows up under "Now playing in cinemas" or "Coming soon".
- **Choose the trailer regions.** The trailer lists (cinemas, digital releases, series) are collected from the countries you pick on the web interface, as many as you like; by default they follow the TMDB language (English → United States). A checkbox lets Discover's cinema rows use the same countries, so a row and its trailers match.
- **Rows glide.** Moving between Discover rows scrolls at a steady, even pace instead of snapping. The rows ahead and behind are prepared in advance, and background loading (posters, scores, paging) pauses while the list moves, so the motion stays smooth.
- TMDB trailer lists follow the Discover order, time and genre settings instead of a random order.
- The Trailers menu moved to the end of the second row: Filter – Order – Time – Genre – Trailers.
- TMDB lists are always available; the separate checkbox is gone.
- The trailers' subtitle button shows whether subtitles exist and whether they are on.

### Other

- **Loading instead of jumping lists.** While a list's final order is being assembled (digital-date or IMDb sorting, the Not seen filter, a catalog's first page), placeholder cards of the exact final size stand in; you can already move across them, and the focus lands on the matching real card. The placeholders wave gently in the app's colors, and a card appears only once its poster and dates are final; the score badge fades in instead of popping up.
- **Simkl sync.** Watched movies and episodes (with the real watch time) and favorites sync both ways with Simkl, for TMDB titles. Connect under Integrations on the web interface.
- The seek bar shows the remaining time, with a minus sign, under the elapsed time.
- Dates follow the format of the selected language.
- The Discord community is linked under Support.

## Web interface

### IPTV

- **Favorites:** a channel numbering selector and an "Add folder" field at the top of the list.
- **Channel numbers can be typed in every order** (A–Z switches to Custom on the first change) and beyond the current page. With continuous numbering, a number of another folder moves the channel into that folder.
- **A ★ before each channel name** shows which folders contain the channel, and copies or moves it into other folders — MPF folders included, so one list can collect channels from several providers.
- **Hide channel groups.** Hide or Show per group, or for the selected groups. Hidden groups are greyed out and can be restored. The group list can show the original order or the visible groups first, and "Select on this page" picks the visible, the hidden or all groups.
- Groups have an "Open" button, like favorite folders, instead of the small Browse link.

### Other

- System → Trailers has two tabs: Subtitles, and Regions with a searchable country list.
- System → Picture is split into tabs: Resolution and refresh rate, Decoding.
- A Simkl page under Integrations: connect, sync now and disconnect.
- A Community section with the Discord link in Help.

## 2.1.17 (2838)

This release fixes large Xtream series catalogs and makes trailers stop with a clear message when YouTube blocks playback.

## Fixed

- **Large Xtream series catalogs now import.** With providers listing tens of thousands of series, a TV box could import zero series while channels and movies were fine: the series list was loaded in one piece and ran out of memory. It now loads row by row, like the movie list.
- If the series list still fails to load, the import summary says so instead of silently showing zero series.

## Changed

- **Trailers stop when YouTube blocks them.** When YouTube asks your network to "confirm you're not a bot", the trailer reel no longer skips through the whole list. After three failed trailers in a row it stops and shows YouTube's message. ▲ tries the next trailer; Back closes the reel.

## 2.1.16 (2836)

- Trailer interface improved

## 2.1.15 (2827)

The headline for this release: a trailer channel in Discover — pick a list and its trailers play back to back, the next one already loading.

## New Feature

- **Trailers ▾ in Discover.** Movies: Coming soon to cinemas, Now in cinemas, Coming soon to digital, New on digital, Digital in the last year. Series: New series coming soon, New seasons coming soon, Most popular series, Ended in the last year. Trailers play one after another; the next one preloads while the current one plays.
- **Title page from the reel.** Pause and press ▼ to open the title's page (add it to favourites, check sources); press Back and the reel continues where it stopped.

## Added

- Reel caption: IMDb score, cinema and digital release dates for movies, last and next episode with air date for series.
- Web interface: System → Trailers, with the trailer subtitles switch.

## Changed

- Lists follow the film data language's region: cinema dates of that country, digital releases of that country (topped up from the US when few), series from the networks and streamers available there. Lists start shuffled and keep growing in the background.
- Trailer language: the preferred audio language first, then the film data language, then English — in the reel and on the title page. Trailer subtitles follow the preferred subtitle languages.
- Reel controls: ▲ next, ▼ subtitles on/off.
- Discover top row: Movies/Series, Trailers, source, size, refresh, search; the source button shows only its name.
- The first trailer starts faster.

## Fixed

- A slow-loading first trailer was skipped.
- A trailer addon's video that cannot be embedded no longer drops the title; the TMDB trailer plays instead.
- Switching a trailer addon off no longer keeps its old videos.

## 2.1.14 (2785)

The headline for this release: addons now follow the profile — each profile sees only its own addons, and switching one off no longer touches the other profiles.

## New Feature

- **Addon on/off per profile.** Disable in one profile keeps the addon running in every other profile; Enable brings it back for that profile only. Works in the app's addon manager and in the web interface.

## Changed

- Addon lists (the app's addon manager under Add, and the web interface) show only the addons allowed for the current profile. A profile without addon management sees no Remove/Disable buttons and no Browse, New addon or Import tabs.
- Seek bar: the seek offset (for example +2:42) sits under the time in smaller digits, and the bar no longer shifts when seeking starts.
- Web interface: Radio stations moved from Addons to Providers, and the tab only appears when a radio addon is installed and allowed for the profile.

## 2.1.13 (2778)

The headline for this release: play any channel in VLC — or another player on your computer or phone — straight from the web interface.

## New Feature

- **Web interface: external player.** Every channel and favourite row has two new buttons next to ▶ (play in app):
  - **VLC direct** hands the provider's stream link to the player on your computer or phone.
  - **VLC proxy** streams through the box instead: provider credentials stay on the device, and HLS streams are relayed as well.

  On a computer the button downloads a small .m3u that opens in VLC or any player that reads playlists; on a phone or tablet it opens VLC directly.

## Added

- Web interface: an icon for every main-menu item.

## Changed

- Web interface: the ▶ and VLC buttons of the channel list sit in one row at the same height.

## 2.1.12 (2773)

- Stalker: portal refusal reasons shown
- Stalker: moved and subfolder portals
- Stalker: more reliable channel loading
- AI subtitles: retired stream links renew
- WebUI: Stalker device identity kept
- WebUI: Integrations in the main menu
- Episode list: wider, with scores
- Episode details in a wider window
- Episode trailers from trailer addons too
- Addon sources in a wider window
- Unfinished playback returns to the source list

## 2.1.11 (2769)

- Hold to seek: smoothly accelerating
- Seek bar shows when it ends
- WebUI: own TMDB and OMDb keys
- Discover: one filter bar for all lists
- IMDb scores from IMDb's own data
- Addon movies: multi-connection download

## 2.1.10 (2756)

- WebUI in the app, even without Wi-Fi
- WebUI on TV: remote-driven pointer
- Actor page: bio, sortable filmography
- Addons from the VOD details page too

## 2.1.9 (2749)

- Trailer button: trailer addon videos
- WebUI: browse and install addons
- Subtitles sent with addon streams
- Recommendation addons on detail pages
- Decoding: hardware only, tunneling
- WebUI: device gauge in the sidebar
- After-credits scene info on movies
- Radio addons as a channel list
- WebUI: search and add radio stations

## 2.1.8 (2733)

- MDBList ratings on detail pages
- MDBList fills in missing IMDb scores
- Ratings as icons, also for episodes
- Poster play badge: titles in My media
- WebUI: Integrations menu for API keys

## 2.1.7 (2726)

- Addons: add via WebUI with a QR code
- Web interface completely redesigned

## 2.1.6 (2706)

- Profiles: Media tiles switchable per profile
- Profiles: allowed addons per profile
- Profiles: a new addon joins your own list
- Kids profile: closed, no addon management
- Movie and series favorites per profile
- Watched marks and resume per profile
- Cloud sync: data types per profile
- Cloud sync: addon and network-file progress
- Pairing code without a repeated sync
- Refresh: a truncated list no longer replaces the catalog
- WebUI: profile access and addon list
- WebUI: sync choices save at once

## 2.1.5 (2700)

- AI subtitles on addons: instant start
- AI subtitles: WebDAV and 5.1 audio
- AI subtitle look kept, CC-sized
- Voice-over: tighter timing, right order
- Addons first in source picker
- Presets: AI switch on top, closes on pick
- Torrent start: clear errors, more reliable
- WebUI: RSS feed parameters visible
- Subtitle font and weight, live preview
- WebUI: subtitle style with preview
- Simpler resolution and refresh setting
- WebUI: resolution and refresh rate

## 2.1.4 (2680)

- Audio, subtitles: remembered choice, two languages
- Subtitle timing, new customize panel
- Addons: manage in app, import/export
- Series: redesigned cards, up-to-date episode lists
- Playback fixes
- UI fixes

## 2.1.3 (2645)

- Gemini CC translation: fewer missed lines
- Subtitle search: source filter, file match
- Subtitle translation keeps its output
- Episode list in the player, addons too
- UI fixes
- Other minor fixes

## 2.1.2 (2623)

- HLS or TS choice per provider
- UI refinements

## 2.1.1 (2609)

- AI translation: better for Korean, Japanese, Chinese
- Gemini 3.5 Flash-Lite speech recognition works
- Presets: Gemini 3.1 Flash-Lite translation
- Existing subtitles: own translator and model

## 2.1.0 (2598)

*Stremio-compatible addon support*

- Addon sources for movies and episodes
- Discover: Addons view with catalogs
- Addon titles in Continue watching and Favorites
- Live TV: TS or HLS per channel

## 2.0.12 (2500)

- Video playback: faster start on Continue
- Favorites VOD: focus behaviour fixed
- Bug fix for Android 13 phones
- Phone: TMDB portrait view fix

## 2.0.11 (2487)

- External player: SMB and WebDAV files

## 2.0.10 (2483)

- Rename channels in favorites
- Phone: Back from the player returns where you were
- Phone: confirm before removing a favorite
- Phone: Library fits on one screen
- External player from the player menu

## 2.0.9 (2469)

*New episode alerts*

- New episode badge on release day
- RSS feed editing in WebUI
- Smoother navigation and focus on TV
- Manual TMDB match correction
- RSS and Torrent refinements
- Recordings list: choose what to show

## 2.0.8 (2447)

*Torrent and TV archive*

- Torrent: technical sheet per download (tracks, resume, play, TMDB)
- WebDAV without WebUI
- New Torrent tile: manage clients, downloads and limits directly in the app.
- Recordings and catch-up share one TV archive, with easier download folder selection.
- The web interface adds torrent management and quicker programme search and recording.
- More reliable network recordings and easier access to your own media.

## 2.0.7 (2411)

*Tidier web interface*

- Simpler menus and clearer programme guide and file browsing.
- Backups now include SMB shares and RSS feeds.
- Fresh IMDb ratings and easier recording and download folder selection.

## 2.0.6 (2389)

*Torrent clients and WebDAV*

- Manage Transmission and qBittorrent profiles from the web interface.
- Browse and play WebDAV media, with connection details included in encrypted backups.
- More reliable scheduled recordings and media scanning across multiple sources.

## 2.0.5 (2381)

*Torrent downloads and watch history*

- Start Transmission downloads from RSS and watch them while downloading.
- Completed downloads appear automatically in your media library.
- Separate TV and movie history, with easier playback resume.

## 2.0.4 (2332)

*Smoother playback and trailers*

- Match display refresh rate to the film.
- Choose trailer language, subtitles and alternate videos.
- Improved title search and film information language settings.

## 2.0.3 (2300)

*Customizable player controls*

- Choose which player buttons are visible.
- Improved live search filters and lower sync memory use.

## 2.0.2 (2290)

*Personal appearances*

- Save named appearances and choose new app-wide fonts.
- Choose your backup filename.

## 2.0.1 (2283)

*More reliable playback and imports*

- Faster SMB browsing and more stable movie playback.
- Resume downloaded and shared movies from their title page using the preferred source.
- Improved Stalker import, sign-in and catch-up.

## 2.0.0 (2265)

*A refreshed Library*

- New appearance styles, artwork and an optional icon-only sidebar.
- Reorganized Library with easier IPTV and favorites setup.
- More reliable TV navigation, recordings and live voice-over.

## 1.8.18 (2231)

*Background downloads*

- Downloads continue in the background and can resume after an interruption.
- Download speed is visible on the web interface.

## 1.8.17 (2222)

*Sync and AI improvements*

- More reliable favorites and watch-progress sync.
- Fewer incorrect AI captions and more accurate voice-over costs.
- Updated AI models and prices, with smoother playback and nightly refreshes.

## 1.8.16 (2184)

*Device pairing and sync*

- Pair devices with a code and manage cloud sync from the app.
- Changes and deletions sync more reliably with less data transfer.
- Find new favorite releases more easily; nightly guide refreshes are more reliable.

## 1.8.15 (2137)

*Simpler cloud sync*

- A setup code transfers the NAS connection to another device.
- Sync uses less data and skips unchanged content.

## 1.8.14 (2129)

*Six-screen Multiview*

- Build and save a Multiview layout directly from the player.
- Watch up to six channels, with clearer provider connection limits.

## 1.8.13 (2112)

*Faster TV browsing and cloud sync*

- Quicker channel switching and programme information throughout the channel list.
- Redesigned catch-up with favorites and easier downloads.
- Encrypted cloud sync for favorites and watch progress, plus selectable TV or touch mode.

## 1.8.12 (2075)

*Better provider compatibility*

- Direct TS playback helps providers with unreliable live stream playlists.
- Clearer provider errors and lighter programme guide traffic.

## 1.8.11 (2065)

*Provider connection improvements*

- Set a custom User-Agent and check the account's connection limit.
- More compatible M3U imports and more stable stream playback.

## 1.8.10 (2047)

*Release dates and automatic refresh*

- Episode dates follow your time zone, with easier date filtering.
- Scheduled nightly provider and guide refreshes, plus an updated TV-readable guide.

## 1.8.9 (2010)

*Trailers inside the app*

- Watch trailers without leaving the app, with remote controls and subtitles.
- More titles have trailers, with language fallback when needed.
- Optional nightly refresh keeps provider lists and the guide up to date.

## 1.8.8 (1984)

*A clearer Library*

- Reorganized Library tiles with a dedicated RSS entry and one local media section.
- Improved sorting, series grouping and remote focus.

## 1.8.7 (1930)

*Your own media library*

- Scan your movie and series folders into a library with posters and direct playback.
- Search multiple subtitle sources and download season packs.
- Set preferred audio and subtitle languages; copy, move or delete multiple files together.

## 1.8.6 (1900)

*Voice-over and resumable downloads*

- Read subtitle tracks aloud, with or without translation.
- Resume interrupted downloads and watch files while they download, including on network shares.
- A web file browser adds transfers, pinned folders and playback on TV or computer.

## 1.8.5 (1873)

*Network media and file browsing*

- Play and record directly on SMB network shares.
- Browse local and network files with copy, move, rename and delete.
- Pin folders for quick access and check available storage space.

## 1.8.4 (1846)

*Smarter title and subtitle search*

- Compare provider releases by language and quality.
- Clearer Discover lists and streaming availability by region.
- Subtitle search starts with the correct title and episode.

## 1.8.3 (1812)

*Find where to watch*

- See streaming services and your IPTV sources together on title pages.
- Play individual episodes and keep your preferred source.
- New Discover and availability filters, with clearer media details.

## 1.8.2 (1774)

*Playback and network improvements*

- Better Dolby audio compatibility and subtitle support in MPV.
- More complete provider matches and quicker update checks.
- Save named proxy and VPN profiles in encrypted backups.

## 1.8.1 (1759)

*Unified movie and series favorites*

- One favorites page with folders, availability checks and release alerts.
- Keep watched episodes and resume playback from the title page.
- The web interface and backups include the same favorites and watch progress.

## 1.8.0 (1676)

*Automatic subtitle sync*

- Align subtitles to the soundtrack automatically, including across languages.
- Find and download OpenSubtitles tracks directly from the player.
- Browse new cinema and streaming releases with ratings and favorites.

## 1.7.1 (1625)

*Free access and richer title pages*

- All app features became free; AI providers still charge separately for API usage.
- TMDB title and episode details add trailers, cast and filmographies.
- Improved programme guide navigation and voice selection.

## 1.6.4 (1599)

*Stalker portals and network options*

- Add Stalker/MAG portals for live TV, movies, series and recordings.
- Clearer programme guide and channel filtering.
- Proxy settings and a built-in WireGuard VPN in the Fire edition.

## 1.6.3 (1558)

*Subtitle translation on recordings*

- Rolling captions can be translated on saved recordings, including after seeking.

## 1.6.3 (1556)

*Backup servers and radio*

- Add multiple backup servers and play audio-only radio stations.
- More reliable live subtitle translation.

## 1.6.3 (1553)

*TV grids and channel numbering*

- Choose poster grid density and favorite channel numbering.

## 1.6.3 (1549)

*Faster Multiview setup*

- Multiview layouts open and save faster on the web interface.

## 1.6.2 (1545)

*Faster library navigation*

- Channel lists and movie folders open faster, even with large providers.

## 1.6.1 (1537)

*Guide and live captions*

- Guide updates keep existing programmes available while refreshing.
- Optional live captions wait for complete sentences before translation.

## 1.6.0 (1527)

*Open beta*

- Paid app features became temporarily available without a subscription during open testing.

## 1.6.0 (1522)

*Plans and playback improvements*

- Manage app plans and restore purchases; AI provider usage is billed separately.
- Improved translations across 26 languages and more reliable VOD favorites.
- Switch player engines without losing playback position.

## 1.5.5 (1512)

*Translation on recordings and catch-up*

- AI subtitle translation works on recordings and catch-up playback.
- Playback speed is remembered across episodes.

## 1.5.4 (1510)

*Clearer AI controls*

- Start subtitle translation or audio-based AI from the corresponding track menu.
- Adjust subtitle appearance and see daily AI costs in the player.
- Switch series episodes without leaving playback.

## 1.5.3 (1484)

*Continue movies and series*

- Resume movies and series with reliable episode order and watched status.
- Dedicated media favorites and Continue Watching, with better TV focus restoration.

## 1.5.2 (1477)

*Compact TV browsing*

- Browse folders and channels beside live preview, with quick access to history and providers.
- Improved TV navigation and stronger connection and web interface protection.

## 1.5.1 (1465)

*Custom remote controls*

- Assign short- and long-press actions and choose how live preview starts.
- Live preview on wide mobile screens and more reliable large catalog imports.

## 1.5.1 (1461)

*Seamless live preview*

- Switch between preview and fullscreen without interrupting playback or AI processing.
- A short release summary appears after updates.

## 1.5.0 (1450)

*TV browsing improvements*

- Faster channel search and more flexible favorites views.
- More accurate AI cost tracking and more stable live preview.

## 1.4.9 (1430)

*Multiview*

- Watch up to four channels with audio switching and fullscreen expansion.
- New browsing filters and more reliable large libraries.

## 1.4.8 (1414)

*Renewed movie and series browsing*

- Detailed title pages, easier episode selection and new sorting and filtering options.
- More reliable TV navigation, seeking and AI playback.

## 1.4.7 (1392)

*Your own subtitle library*

- Upload SRT subtitles through the web interface and use them across your videos.
- Customize subtitle appearance and timing, with optional AI translation.

## 1.4.6 (1383)

*More consistent voice-over*

- Improved speaker voice matching, timing and programme volume recovery.
- The full Google TTS voice catalog is available again.
