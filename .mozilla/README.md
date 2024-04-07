
# HOW TO USE

Search 'about:config' on Firefox's search bar and set the following properties:

```
toolkit.legacyUserProfileCustomizations.stylesheets true
layout.css.moz-document.content.enabled             true
extensions.langpacks.signatures.required            false
xpinstall.signatures.required                       false
```

Then copy 'user-chrome/chrome' to your Firefox profile.

Finally, add all '.zip' files as Firefox extensions in 'about:addons'. After that, you're all set.

# Note

For a default Firefox experience (that is, keeping Firefox theme): Copy 'user-chrome/chrome' to your Firefox profile, then add 'blank-page.zip' as an extension.

Otherwise, for a "pinky" experience: Copy 'user-chrome-for-sakura-theme/chrome' to the Firefox profile, then add 'sakura-theme.zip' and 'blank-page-for-sakura-theme.zip' as extensions.

