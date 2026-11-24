# Is minulo safe? Does it see my Instagram password?

When an app blocks other apps with Screen Time, Apple gives it opaque tokens instead of app names. minulo doesn't see your Instagram password either: there is no minulo account, and you type your password on Instagram's own sign-in page inside the app, which sends it straight to Instagram.

## What to check yourself
1. When you open Instagram in minulo, sign in on Instagram's own page. Two-step verification works the way it normally does.
2. When your iPhone asks for Screen Time access, pick apps in Apple's app list. minulo gets tokens, not names, so it can't tell which apps you chose.
3. On the US App Store, minulo's privacy label lists only Data Not Linked to You. Apple notes that developers write these labels and Apple doesn't verify them.
4. To stop, delete the app. Your records on the iPhone are erased and you are signed out of every network inside it. Removing the Screen Time permission ends the blocks.

## What minulo sends and keeps
- Anonymous usage data and error reports go to PostHog, tied to a random ID the app makes. Error reports have URLs, @names and email addresses removed.
- Login cookies, your records and your settings stay on your iPhone.
- The script minulo adds to a page reads the text on screen to find things like suggested posts, but it doesn't save or send that text.

## Other apps like this
- **SocialLite** and **UNDOOMED** also show each network in their own in-app browser, where you sign in on the network's website.
- Compare the privacy label each developer gives Apple: SocialLite lists Identifiers under Data Used to Track You, while UNDOOMED and minulo list none there.

## FAQ
### Does minulo change the Instagram app?
No. No iPhone app can edit what another app shows. Reels are hidden only inside minulo.

### What happens to notifications while minulo blocks an app?
On iPhone, while minulo blocks an official app, that app's notifications don't arrive, and minulo doesn't deliver them in its place. Pro users can turn on DM notifications (beta) so Instagram DM notifications still arrive while Instagram is blocked, except during Sleep mode, Focus time in Work mode or after the daily limit. On Android, minulo only puts its own screen over a blocked app when you open it, so that app's notifications still arrive.

### Is it for children?
It is not meant for children under 13. It works on iPhone and Android, and there's a Mac app too.

More detail: [Is minulo safe? What it can see and what it can't](https://minulo.app/en/is-minulo-safe.html?ref=github-en-safe-1116)

Written by the minulo developer.
