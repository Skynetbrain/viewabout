# ViewAbout
A Mozilla Firefox / Thunderbird legacy add-on to open up available about: dialogs, including those activated by other extensions.

ViewAbout **will not be ported to WebExtensions** once Firefox 57 is released, because:
* `about:` dialogs such as `about:config`, `about:addons` and `about:debugging` are [privileged and cannot be opened](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/API/tabs/create)
* `about:about` is now available for Firefox

Thus, the last version where ViewAbout will work is 56.

### Standard
1. about:
2. about:about
3. about:accounts
4. about:addons
5. about:buildconfig
6. about:cache (and related)
7. about:checkerboard
8. about:config
9. about:crashes
10. about:credits
11. about:debugging
12. about:devtools-toolbox
13. about:downloads
14. about:healthreport
15. about:home
16. about:license (generic Toolkit license)
17. about:logo
18. about:memory
19. about:mozilla
20. about:networking
21. about:newtab
22. about:performance
23. about:permissions
24. about:plugins
25. about:preferences
26. about:privatebrowsing
27. about:profiles
28. about:rights
29. about:robots
30. about:serviceworkers
31. about:sessionrestore
32. about:support
33. about:telemetry
34. about:webrtc
35. about:welcomeback

### Related to other add-ons
1. [about:me](https://addons.mozilla.org/en-US/firefox/addon/aboutme/)
2. [about:tabs](https://addons.mozilla.org/en-US/firefox/addon/tab-stats/)

### Miscellaneous errors that are seemingly useless
1. about:certerror
2. about:neterror

These windows can be closed using Ctrl (or Cmd)-w. Note that some `about:` menu options may not show up in applications that do not support them.

ViewAbout started initially from a need to view `about:crashes` on Thunderbird.
