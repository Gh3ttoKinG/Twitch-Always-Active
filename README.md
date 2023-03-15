# Twitch-Always-Active
Twitch is probably just using the Visibility API since the `window.focus` & `window.blur` also tiggers when you are just in the browser menu or address bar.
Source: https://www.designcise.com/web/tutorial/how-to-detect-if-the-browser-tab-is-active-or-not-using-javascript
So this stops triggering the `visibilitychange` event on the `document` level and makes Twitch believe it's always in the foreground.

Javascript version of https://openuserjs.org/scripts/lp0101/Always_Focused_Twitch/
You can run it as a UserScript from the source above with a browser extension like TamperMonkey or use this version as a bookmark and click it on each stream tab.

Credits go to [Nestramutat-](https://www.reddit.com/user/Nestramutat-/) on Reddit:
https://www.reddit.com/r/Twitch/comments/eub56j/i_wrote_a_simple_userscript_to_stop_twitchs/
