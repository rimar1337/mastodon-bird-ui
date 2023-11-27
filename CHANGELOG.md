### 1.8.3: 2023-11-12

* Add profile link icons for Nostr, Bluesky and Threads
* Truncate too long links in the profile, like Nostr

### 1.8.2: 2023-10-29

* Remove deprecated Local icon
* Remove deprecated Share icon
* Add an icon for Preferences

### 1.8.1: 2023-10-29

* Hotfix for regression with the home icon

### 1.8.0: 2023-10-29

* Improve button border colors in ultra accessible theme
* Do not animate when prefers-reduced-motion is set to reduce, Fixes #95
* Fix profile button icon not horizontally centered
* Fix regression with icon button aligning when not focused
* Fix regression with wrong alignment of the bell icon when activated

### 1.7.9: 2023-10-04

* Improve the visibility of column header borders in advanced view
* Fix border column-header color also in single column mode
* Ultra accessible theme improvements (Readme snippet)
* Add explore__search-results to transparent background color scope
* Add search-results__section__header to color scopes
* Fix collapsible border in tab header
* Make it easier to edit the gap of column-links by splitting the variables in two #86 (thanks @trankten!)
* Add dark banner styles for account-memorial-banner (thanks @DismalShadowX!), follow-request-banner and moved-account-banners, Closes #94
* Fix column back button border

### 1.7.8: 2023-09-24

* Add profile icons for Ko-fi, Patreon, Paypal and Mastodon
* Add new profile icons to the advanced web interface
* Add verified badge styles to user listings
* Fix: Hide pipe from link icons if there is no textual label
* Fix regression with verified labels on multiple column view
* Fix unminified globe icon causing it to randomly disappear #89, Fixes #90
* Fix partial globe icon on light theme
* Fix mention and hashtag color contrast for light theme
* Fix consistency for --icon-boost-notification-filter-bar
* Truncate too long localized unfollow button text in notifications in mobile

### 1.7.7: 2023-09-23

* Add Inactive Global Icons #89 (thanks @0ddfactory!)
* Fix Multi-Column Icon Size #89 (thanks @0ddfactory!)
* Hotfix for offset on boost icon for mobile (thanks @mitexleo!)

### 1.7.6: 2023-09-23

* Fix the x position in recent searches
* Introduce new boost micro-interaction, Fixes #81 #74
* Fix padding in multiple column view
* Fix boost icon
* Add new boost interactions to advanced web interface
* Use `i` modifier to reduce attr selector repetition #84 (thanks @valtlai!)
* Update `--icon-boost-notification-wrapper` to match new boost icon
* Fix light theme icon colors

### 1.7.5: 2023-09-23

* Recognize mispelled GitHub and add an icon
* Recognize empty field and remove pipe
* Hover effect missing in menus, Fixes #79 (Thanks @Roboron3042!)
* Profile view on mobile leaves kebab menu out when the localized "Unfollow" label is longer, Fixes #87 (Thanks @ikke-t!)
* Support for Mastodon 4.2.0

### 1.7.4-nightly: 2023-09-14

* Improve ellipse shaped counter with 10+ notifications, Fix build, Fixes #32 (thanks @Freeplayg!)
* Fix line-height for ellipse shaped counter
* Re-think profile links/labels, Fixes #61
* Fix non-PWA iOS Safari Compose form top header overlap
* If social media, move even further from links
* If the profile item has no link element, show just label icon
* Add Discord and LinkedIn icons
* Add Instagram icon
* Re-think verified link, ditch the idea of name badge, Fixes #61

### 1.7.3-nightly: 2023-09-07

* Add bottom padding for the PWA on iPhones with the home bar #72 (thanks @LetyDoesStuff!)
* Fix top header overlapping in /publish on iPhone
* Fix regression with top header on iPhone in compose view
* Fix mistake in class
* Support 4.2.0-beta3
* Fix missing Active Tab Indicator on Mastodon 4.2.x Instances #73 (kudos to @rimar1337!)

### 1.7.2-nightly: 2023-08-28

* Support Mastodon 4.2.0-beta2
* Tint hashtag bar to the right
* Add pill style hashtags styles for hashtag bar tag list
* Fix regression in tinting hashtag bar
* Fix bullet hover and focus on light theme
* Fix embedded media not displaying in status cards #69 (thanks @LetyDoesStuff!)

### 1.7.1-nightly: 2023-08-12

* Fix preview cards that are not expanded
* Improve compact and expanded preview card alignments
* Fix status-card__description color on hover
* Thinner scrollbars for advanced web interface on 4.1.6
* Improve advanced UI Getting started view column link, icon and heading alignment
* Improve iPad compatibility of advanced web interface
* Fix button with bell padding on advanced web interface
* Fix wrong width of bottom column-links on mobile
* Fix "About" page's server thumbnail margins on mobile #64 (thanks @LetyDoesStuff!)

### 1.7.0-nightly: 2023-08-01

* Add slight background color for the compose form, Fixes #10
* Fix regression with light theme compose form colors
* Hide autoplaying gifs in notifications (they get annoying if you have favs/boosts on)
* Make embed avatar rounded

### 1.6.9-nightly: 2023-07-30

* Fix star animation for Safari by adding max-height to status bar
* Remove font-stack, let Mastodon users decide the font via settings
* Don't show blank grey URL preview cards if image not found

### 1.6.8-nightly: 2023-07-27

* Fix Replies text in embeds
* Fix embed border
* Make sure embed background is transparent
* Fix rounder border of the embed
* Fix textual replies, boosts and favourites labels on Firefox
* Fix video aspect ratio for Firefox

### 1.6.7-nightly: 2023-07-26

* Add support for mastodon 4.1.5+nightly-2023-07-25
* Add font-weights as CSS variables
* Add new bigger preview card style à la mastodon 4.1.5+nightly-2023-07-25
* Remove duplicate styles
* Fix status card hover and styles for YouTube cards
* Fix changed class for .status-card__image
* Add color for empty preview card
* Fix bottom border radius on status card preview cards
* Fix aspect-ratio for some videos in mastodon v4.1.5-nightly-2023-07-26

### 1.6.6-nightly: 2023-07-25

* Add max-height to reply-indicator to prevent it overlapping compose form
* Add drawer scrollbar styles
* Fix media gallery corners in Safari #56 (thanks @misterzwiebel!)

### 1.6.5-nightly: 2023-07-23

* Combine light purple color scopes
* Add .server-banner__introduction to light purple color scope
* Fix couple of classes in layout-single-column theme and layout-multiple-column theme
* Filtered post styles
* Fix focus overflow for 4.1.4-nightly-20230721
* Fix focus for mouse users on v4.1.4-nighly-20230721
* Fix hover/focus on article that has filtered banner
* Add button:focus to focus color scope, change :focus to :focus-visible
* Increase gap for server-banner__meta
* Add server-banner__number-label to light purple color scope

### 1.6.4-nightly: 2023-07-13

* Fix a regression with modal buttons #42, #46

### 1.6.3-nightly: 2023-07-10

* Fix a regression with privacy dropdown hover color #49

### 1.6.2-nightly: 2023-07-10

* Fix privacy dropdown text color in contrast theme (thanks @misterzwiebel!)

### 1.6.1-nightly: 2023-07-08

* Fix two logos showing on iPad, Safari. Fixes #44 (thanks @misterzwiebel!)

### 1.6.0-nightly: 2023-07-08

* Indicate added to list icon with green color, Fixes #34
* Fix missing comma (thanks @appel!)
* Fix regression with compose form font size on mobile
* Less padding before the status header
* Less margin before the status action bar
* Fix Mastodon UI bug with read more/translate button alignment
* Add smooth hover to status cards
* Hide empty YouTube description
* Add ultra accessible colors to README
* Minor CSS var improvements
* Fix profile media gallery thumbnails' border-radius
* Fix regression with detailed status update font size
* Fix YouTube preview card styles
* Fix video player border-radius
* Add more font-sizes to the --font-size CSS var scope
* Add line height
* Add status__content__read-more-button to font size scope
* Add logo to var
* Improve accessible color areas
* Add lots of more colors to CSS var scopes
* Fix dark colors on high contrast mode
* Fix regression with the advanced web interface for nightly (thanks @vmstan!)
* Add show/hide media icon button styles with border-radius (thanks @MikeHuntington!)
* Add border-radius as a CSS variable
* Add consistent border radius to alt badge
* Add --border-radius-badges CSS variable
* Make badges a bit further from the edge
* Fix regression with lists order on mobile
* Fix the thread line stub when replying in real time
* Fix regression with missing border in detailed status
* Fix threaded line overlapping detailed status
* Fix regression with status-line full being zero height
* Add consistent styles for follow buttons inside the account panel
* Add background color for avatars for transparent avatars to be more distinct
* Fix detailed status in between of threads
* Fix undefined content warning placeholder (thanks @digitalspork!)
* Add visible border around media
* Increase border-radius for media
* Increase border-radius for url preview cards
* Fix read more button position
* Fix multiple columns layout
* Fix media gallery border radius if multiple items
* Make sure read more button icon is always aligned to center vertically
* Fix search icon overlaping with the long search input placeholder text #40 (thanks @itbeard!)
* Fix regression with padding inside a media item
* Fix regression with padding inside a status card in thread
* Fix read more/translate link position
* Remove "No alt" indicator now that 4.1.2-nightly has an indicator for media that has alt
* Add support for Mastodon 4.1.2-nightly-20230703
* Fix lists position on mobile
* Fixed fa-fw (Federated) icon size for mobile view #37 (thanks @itbeard!)
* Fix glitches with sign up and follow notifications on 4.1.2-nightly-20230703
* Fix follow button in notifications
* Fix position of lists icon on mobile

### 1.5.7: 2023-06-09

* Fix icon bubble position on single column layout
* Fix missing px unit
* Fix typo on selector (thanks @tribela!)

### 1.5.6: 2023-05-14

* Fix toggle track color
* Add column hashtag list styles
* Add hashtag context menu background
* Fix search background color
* Some fixes for light mode in advanced web interface

### 1.5.5: 2023-05-13

* Fix width when zooming in on the advanced web view

### 1.5.4: 2023-05-13

* Support multiple columns
* Fix active scrollbar thumb color
* Move compose panel to the right
* Hide the elephant from advanced web view
* General improvements to the advanced web view, like wider width
* Fix duplicate class before .account__header__bar

### 1.5.3: 2023-05-07

* Fixes #25, User avatars in notifications are sometimes links to my profile instead of theirs (thanks @carlwgeorge!)

### 1.5.2: 2023-04-28

* Hot fix the bookmark hover icon

### 1.5.1: 2023-04-28

* Fix server information links not visible after logging in, Fixes #22 (thanks @fofwisdom!)
* Fix follow_requests order #24 #23 (thanks @tribela!)

### 1.5.0: 2023-04-26

* Fix regression with the threaded border color

### 1.4.9: 2023-04-26

* Fix content warning alignment, should be baseline instead of top
* Add gap between the cw title and show-button
* Increase contrast of show button
* Fix cw button color in notifications
* Fix hover size of the bookmark icon when in detailed status
* Fix detailed status bar bookmark icon color on hover
* Add account header handle to color light purple scope
* Fix follow button color being different than the rest

### 1.4.8: 2023-04-22

* Fix admin sign up notification glitch, Fixes #19 (thanks @llamacucumber!)
* Change some leftover shaded colors to more Mastodon deep purple variant rather than Twitter blue

### 1.4.7: 2023-04-09

* Fix the sparkle and circle position on Explore tab on mobile
* Fix star animation frame 7 (thanks @kde3kko!)
* Remove duplicate min-width definition #16 (thanks @kde3kko!)
* Remove gradient that is no longer used, Fixes #17 (thanks @kde3kko!)

### 1.4.6: 2023-04-09

* Increase right padding for left column link hover #13 (thanks @kde3kko!)
* Fix character counter color when it's over the limit, Fixes #14 (thanks @kde3kko!)
* Fix hover colors on the Explore tab, when un-boosted but hover supported

### 1.4.5: 2023-04-08

* Move follow notification closer in line to the follow button
* Fix follow notification general alignment issues
* Align column link heart icon better
* Fix un-boost action color and animation
* Fix un-bookmark color
* Fix un-boost color when numbered item on Explore page

### 1.4.4: 2023-04-08

* Fix sparkle position on mobile devices
* Fix circle position on mobile devices
* Fix number color on hover when the star is not activated yet
* Fix number color when the star is active
* Fix active tab color staying active when the tab is not active on mobile
* Fix heart is not active when it's activated over the star

### 1.4.3: 2023-04-06

* Fix new notification types
* Fix a typo that caused reblog notification styles to crash
* Reset some 4.1.2 paddings
* Fix navigation-panel overflow scroll
* Hide verification url from follow notifications
* Fix boost message line spacing
* Fix regression with status message padding
* Fix: If notification content is empty and there's only attachment, remove gap
* Fix inconsistencies in paddings of the notification content
* Fix too much space if there is no content in regular statuses before attachment
* Fix follow notification spacing between avatar and an user
* Fix status__prepend boost icon 1px alignment
* Prevent the star from being highlighted when the button is focused, especially while logged out, Fixes #9
* Do not force compose form scrollbar when not needed
* Fix search popout in Mastodon 4.1.2

### 1.4.2: 2023-04-05

* Fix offset of the star micro-interaction in the Explore view
* Fix star/unstar interactions on mobile
* Fix sparkles not showing up on mobile devices
* Fix strange horizontal overflow in between-resolutions (min-width: 1175px) and (max-width: 1330px)
* Fix compose form not resizing on mobile devices
* Fix some unprefixed classes
* Fix unread private message background
* Fix conversation border color
* Fix private message attachment list padding
* Fix favoriting private message styles
* Fix icon-button--with-counter hover shade offset
* Fix follow notifications on Mastodon 4.1.2
* Add support for Mastodon 4.1.2

### 1.4.1: 2023-04-05

* Attempt to fix #8
* Make the star icon in notification slightly bigger
* Fix star always popping when already faved
* Fix a regression with number color on hovering the star

### 1.4.0: 2024-04-05

* Fix a regression with z-index, autosuggest not clickable if compose form expanding
* Make scrollbars more visible
* Accessibility: Add max-height to compose form (thanks @rmattila74@mastodo.fi!)
* Accessibility: Revert resize: true in compose form (thanks @rmattila74@mastodo.fi!)
* Implement star animation and micro-interaction
* Replace sidebar heart icons with star icons
* Add instructions for switching to heart icon
* High contrast theme color improvements
* Add high contrast icons

### 1.3.9: 2023-04-04

* Remove thread-line height no longer needed with the new structure
* Fix compose form getting behind footer on desktop (thanks @lari@suomi.social!)
* Fix: Restrict scrollbars in the single column view only (thanks @folini@mastodon.uno!)
* Fix trending hashtags color leaking to the advanced view
* High contrast theme support (color dim is currently more vivid there)

### 1.3.8: 2023-04-03

* Improve thread line structure to be more reliable, see [this diff](https://github.com/mastodon/mastodon/compare/main...ronilaukkarinen:mastodon:feat-thread-lines)
* Fixes for thread line structure if there's more depth
* Fix thread line not showing up for scenarios where there are only 2 threads
* Fix thread line on last items when multiple threads have one orphan
* Fix secondary button border color
* Fix not all conversations linked properly
* Make scrollbar styles more thin

### 1.3.7: 2023-04-02

* Add muted poll to the CSS var color scope
* Allow resizing the compose form
* Change sidebar's sizing to match Twitter's #7 (thanks @Freeplayg!)
* Show more in server banner
* Fix overflow if the compose form is resized
* Limited conversations/threads support with fallback (see issue [#4](https://github.com/ronilaukkarinen/mastodon-bird-ui/issues/4))

### 1.3.6: 2023-04-01

* Fix confirmation modal text color (thanks @jaoler@suomi.social)
* Add more colors to CSS var scope
* Fix relative time color being too bright

### 1.3.5: 2023-03-30

* Fix poll input field colors
* Accessibility: Add focus ring to poll input answer while composing
* Revise follow and unfollow hashtag icons so that the + x are more distinct

### 1.3.4: 2023-03-29

* Accessibility: Fix focus for list toggle (thanks @MerriNet@mastodon.social!)
* Accessibility: Fix focus ring on :focus-visible on column-links
* Add follow and unfollow hashtag icons (thanks for the idea @jaoler@suomi.social and @lari@suomi.social)

### 1.3.3: 2023-03-29

* Hide navigation-panel scrollbars on Firefox on desktop
* Hide lists by default, show the list of lists on hover (thanks for the idea @laukanhenkka@mastodonsuomi.fi!)
* Order preferences menu before lists
* Add order to all desktop column-link items

### 1.3.2: 2023-03-28

* Fix destructive button border color
* Show green followed icon in the profile following/followers account wrapper
* Add `--width-side-panel` for side panel widths
* Fit content to iPad landscape view (thanks @jarilehtinen!)
* Fix horizontal scrollbar on some iPad views

### 1.3.1: 2023-03-28

* Fix regression in the mobile nav: Column-links not same height
* Fix bell icon alignment on mobile
* Fix ellipsis icon alignment on mobile

### 1.3.0: 2023-03-27

* Add compose form warning to the CSS var scope
* Remove shadow from compose form warning
* Nav panel: Make the whole row clickable #5 (thanks @Freeplayg!)
* Fix direct message active icon in light theme

### 1.2.9: 2023-03-26

* Change font stack to CSS variable
* Add verified color as variable
* Fix verified colors in profile

### 1.2.8: 2023-03-26

* Fix button-tertiary color on light theme

### 1.2.7: 2023-03-26

* Light theme
* Fix shadow in privacy-dropdown__value
* Add icons to CSS variables for easier customization
* Add other found colors to the color var scopes
* Fix content warning tag color
* Fix focusable toot color

### 1.2.6: 2023-03-25

* Fix weird padding bug on button-tertiary hover
* Respect the user's choice to use light theme
* Stylelint: Update specificity rules
* Add dark colors for about page

### 1.2.5: 2023-03-24

* Remove language-dropdown__dropdown box-shadow
* Remove privacy-dropdown__dropdown box-shadow
* Fix language-dropdown__dropdown background color
* Fix compose poll styles
* Fix search popout glitch on mobile
* Announcement styles

### 1.2.4: 2023-03-23

* Dark colors for search popout
* Full width search popout on mobile
* General heading improvements
* Fix actions-modal selection colors

### 1.2.3: 2023-03-23

* Fix bookmark button styles on mobile when focusing on the button
* Fix list links on desktop if they are too short
* Fix read more button alongside translate button
* Revert already boosted content hiding on Explore tab
* Fix boost icon fix when re-boosting on mobile
* Fix mistakes in the CSS, double dots and other mistakes
* Fix report window colors #3

### 1.2.2: 2023-03-19

* Fix cancel button styles
* Fix private message reply icon and alignment
* Fix report/filter modal colors
* Remove gap at the end of navigation panel
* Fix translate link styles

### 1.2.1: 2023-03-17

* Consistent position for no alt tag with other media tags
* Hide footer buttons in modals
* Fix some situations where too high number can cause icon to shrink
* Add compose history modal header to border color scope
* Fix tertiary button border on hover
* Fix styles for admin report notifications (thanks [@koyu](https://koyu.space/@koyu))
* Fix notification-update alignment (thanks [@koyu](https://koyu.space/@koyu))
* Fix dropdown menu history item styles
* Hide already boosted posts on Expore tab
* Fix follow notification avatar too close to text
* Fix styles for admin sign up notifications (thanks [@koyu](https://koyu.space/@koyu))
* Fix tertiary button hover border

### 1.2.0: 2023-03-15

* Consistency in follow/unfollow button hover and focus colors
* More distinct :focus-within to text inputs
* Hilight search icon when searching emojis
* Fix emoji-mart search icon color
* Add more consistent colors for emoji-mart
* Fix columns for RTL (thanks [@ButterflyOfFire](https://mstdn.fr/@ButterflyOfFire))
* Fix default relationship follow button color
* Improve relationship follow focus action on mobile
* Fix missing audio player alignment
* Fix audio player border-radius
* Use CSS Selectors Level 4 Working Draft :has for missing alt tag media instead of opacity

### 1.1.9: 2023-03-13

* Fix blur overlay on iPad
* Fix compose form z-index on mobile
* Add green/red indicator in the follow/unfollow button in notifications
* Add missing stylelint-order package
* Fix iOS Safari issue #1

### 1.1.8: 2023-03-12

* Remove width hack for mobile
* Add unit tests
* Remove SCSS related rules
* Fix broken Safari build
* Fix mobile scrollability issues in general
* Fixes for iPad
* Fixes for Android Chrome
* Fixes for logged out mobile view
* Order three dots last on mobile
* Fix list-editor inline button dimensions
* Fix disabled action buttons pointer-events and style
* Make autosuggest-textarea__suggestions dark
* Remove autosuggest-textarea__suggestions extra box-shadow
* Fix audio-player width on regular feed
* Improve blurred ui header on mobile and iPad
* Better Mastodon (Light) support
* Added more elements to the color scopes
* Add border radius to media
* Mark media with alt text missing with text "Alt text missing"
* Add embed input background color
* Add hover transition for article-items

### 1.1.7: 2023-03-11

* Fix detailed status bar icon bubble alignment on Windows
* Add character-counter to the dim color scope
* Fix focusable toot color
* Fix theme when Mastodon (Light) Site theme is enabled
* Add more elements to var scopes

### 1.1.6: 2023-03-11

* Add consistent notification filter bar icons
* Add text icons to dim color scope
* Add compose button border-radius
* Fix active boost animation
* Simplify the hover and focus shade

### 1.1.5: 2023-03-11

* Improve trends heading
* Fix account relationship hover background bubble
* Order column-links on mobile: Home, Explore, notifications, lists

### 1.1.4: 2023-03-10

* Fix border color tint towards the Mastodon brand color
* Fix some cases where threaded line is cutting short
* Order icons in mobile based by most used first
* Make the column link 1/4 of width of the screen on mobile
* Fix account relationship icon color

### 1.1.3: 2023-03-10

* Fix status action bar button hover bubble alignment
* Fix heart animation position on mobile
* Fix avatar size on certain situations
* Fix dim hex in SVG icons
* Fix wrong variable in avatars
* Fix threaded line position on first post
* Fix shade in the bio of "For you" user accounts
* Improve follow user icon in notifications
* Use brand color in notification icons
* Add list-adder modal styles
* Add icons from open source versions of Iconoir, Ionicons and Feather
* Make icons consistent across views
* Color privacy dropdown

### 1.1.2: 2023-03-09

* Fix the heart animation on the icons with counter
* Fix notification title overlapping with polls
* Fix avatar space alignment with long usernames
* Reset padding from attachment-list on reply indicator
* Fix boost animation
* Fix detailed status button bubbles
* Fix gap between list-adder list item and icon

### 1.1.1: 2023-03-09 

* Fix always spinning boost button
* Improve alignment of the bottom items on mobile
* Fix empty-column-indicator on mobile
* Add more dim colors to variable scope
* Add focused text color to inputs
* Add list adder modal styles
* Fix heart animation in profile feed
* Fix incorrect preview card title color
* Fix list item width on mobile

### 1.1.0: 2023-03-09

* Add .account to color-border section
* Fix hover on account type of notifications
* Fix top margin on mobile
* Fix hover bubble dimension under actions
* Fix action buttons alignment on mobile
* Disable action focus bubble on mobile
* Fix retweet focus color on mobile

### 1.0.9: 2023-03-09

* Fix hover colors on boost and star buttons
* Fix 1px jump on activating the spark animation
* Fix horizontal 1px jump on animation
* Fix retweet button animating on each load
* Fix unread notification background color on hover

### 1.0.8: 2023-03-09

* Replicate animated heart with sparkles
* Add retweet icon animation

### 1.0.7: 2023-03-09

* Fix Publish button not reachable on mobile if file is attached to the post
* Fix column-link background sticking too long
* Fix active retweet counter color
* Make default buttons round

### 1.0.6: 2023-03-09

* Fix video-player alignment
* Improve mobile bottom bar spacing
* Lists view styles

### 1.0.5: 2023-03-09

* Improve unread notification style to be more subtle without left border
* Add accent color to home icon in notifications
* Fix wrapping issues of the notification title
* Add more space between trends
* Remove side bar scrolling bar while retaining scrollability
* Hack to display notification message title on one line
* Fix direct message indicator on detailed status
* Poll color improvements
* Fix profile suggestion styles
* More consistent icon sizes for mobile bar

### 1.0.4: 2023-03-09

* Change server stats label to lowercase and dim
* Increase notification home icon size
* Make counter a bit closer to the icon
* Fix explore__search-header background on mobile
* Fix general avatars
* Fix line-height on buttons
* Visual indicator about direct messages [#22158](https://github.com/mastodon/mastodon/issues/22158#issuecomment-1353661031)
* Default to full-width images in link previews [#21874](https://github.com/mastodon/mastodon/issues/21874#issuecomment-1332556018)
* Better, more subtle private message ribbon on the right corner

### 1.0.3: 2023-03-08

* Change button secondary color dimmer
* Fix dim account name
* Slightly less padding after status-prepend
* Fix icon size leaking to link svg
* Mobile: Fix horizontal scrollbars
* Replace icons for detailed view

### 1.0.2: 2023-03-08

* Fix like icon and boost icon on detailed post
* Fix like icon hover when already active
* Add `--color-brand-mastodon-threaded-line`
* Fix badge border color
* Fix mobile icon size consistency
* Add heart to column-link icon
* Fix secondary button
* Fix polls
* Fix search icon
* Fix follow hashtag button not visible
* Fix account relationship icon size

### 1.0.1: 2023-03-08

* Add `--color-accent-dark`
* Make badge background color more vivid
* Fix overlapping follow notification display name
* More subtle box-shadow for dropdown-menu
* Fix profile icon button styles
* Fix subscribe button styles

### 1.0.0: 2023-03-08

* First stable release
