# Changelog

All notable changes to IPTV AiSubs, newest first. The number in parentheses is the build number
shown in the app under Settings and in the web interface sidebar.

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
