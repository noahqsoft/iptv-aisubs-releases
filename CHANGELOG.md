# Changelog

All notable changes to IPTV AiSubs, newest first. The number in parentheses is the build number
shown in the app under Settings and in the web interface sidebar.

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
