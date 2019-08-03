# Polska paczka językowa dla [Flarum](https://flarum.org/)

Paczka zawiera tłumaczenia dla Flarum (kompatybilne z wersją `0.1.0-beta.8.1` lub nowszą) oraz wybranych wtyczek.

## Instalacja

Rozszerzenie instalujemy za pomocą [Composera](https://getcomposer.org/):

```console
composer require rob006/flarum-lang-polish
```

## Aktualizacja

Aktualizacje instalujemy za pomocą [Composera](https://getcomposer.org/):

```console
composer update rob006/flarum-lang-polish
```

## Migracja z `bepro/lang-polish`

Jeśli masz już zainstalowane rozszerzenie [`bepro/lang-polish`](https://github.com/bepropl/lang-polish) musisz:

1. W panelu admina wyłączyć rozszerzenie `bepro/lang-polish`.

2. Odinstalować rozszerzenie za pomocą Composera:

   ```console
   composer remove bepro/lang-polish
   ```
   
3. Zainstalować nowe rozszerzenie za pomocą Composera:

   ```console
   composer require rob006/flarum-lang-polish
   ```

4. Włączyć nowe rozszerzenie w panelu admina.


## Status tłumaczeń głównego silnika Flarum

| Component | Status |
| --- | --- |
| [Core](https://github.com/flarum/core) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/core/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/core/) |
| Validation | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/validation/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/validation/) |


## Status tłumaczeń dla oficjalnych rozszerzeń

<!-- flarum-extensions-list-start -->

| Extension | Status |
| --- | --- |
| [Akismet](https://github.com/flarum/akismet) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-akismet/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-akismet/pl/) |
| [Approval](https://github.com/flarum/approval) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-approval/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-approval/pl/) |
| [Emoji](https://github.com/flarum/emoji) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-emoji/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-emoji/pl/) |
| [Facebook Login](https://github.com/flarum/auth-facebook) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-auth-facebook/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-auth-facebook/pl/) |
| [Flags](https://github.com/flarum/flags) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-flags/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-flags/pl/) |
| [GitHub Login](https://github.com/flarum/auth-github) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-auth-github/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-auth-github/pl/) |
| [Likes](https://github.com/flarum/likes) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-likes/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-likes/pl/) |
| [Lock](https://github.com/flarum/lock) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-lock/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-lock/pl/) |
| [Markdown](https://github.com/flarum/markdown) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-markdown/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-markdown/pl/) |
| [Mentions](https://github.com/flarum/mentions) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-mentions/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-mentions/pl/) |
| [Pusher](https://github.com/flarum/pusher) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-pusher/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-pusher/pl/) |
| [Statistics](https://github.com/flarum/statistics) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-statistics/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-statistics/pl/) |
| [Sticky](https://github.com/flarum/sticky) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-sticky/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-sticky/pl/) |
| [Subscriptions](https://github.com/flarum/subscriptions) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-subscriptions/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-subscriptions/pl/) |
| [Suspend](https://github.com/flarum/suspend) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-suspend/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-suspend/pl/) |
| [Tags](https://github.com/flarum/tags) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-tags/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-tags/pl/) |
| [Twitter Login](https://github.com/flarum/auth-twitter) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-auth-twitter/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-auth-twitter/pl/) |

<!-- flarum-extensions-list-stop -->


## Status tłumaczeń dla rozszerzeń od Friend of Flarum

<!-- fof-extensions-list-start -->

| Extension | Status |
| --- | --- |
| [FoF Byōbu](https://github.com/FriendsOfFlarum/byobu) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-byobu/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-byobu/pl/) |
| [FoF Custom Footer](https://github.com/FriendsOfFlarum/custom-footer) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-custom-footer/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-custom-footer/pl/) |
| [FoF Default Group](https://github.com/FriendsOfFlarum/default-group) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-default-group/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-default-group/pl/) |
| [FoF Discord Login](https://github.com/FriendsOfFlarum/auth-discord) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-auth-discord/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-auth-discord/pl/) |
| [FoF Disposable Emails](https://github.com/FriendsOfFlarum/disposable-emails) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-disposable-emails/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-disposable-emails/pl/) |
| [FoF Follow Tags](https://github.com/FriendsOfFlarum/follow-tags) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-follow-tags/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-follow-tags/pl/) |
| [FoF Formatting](https://github.com/FriendsOfFlarum/formatting) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-formatting/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-formatting/pl/) |
| [FoF FrontPage](https://github.com/FriendsOfFlarum/frontpage) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-frontpage/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-frontpage/pl/) |
| [FoF Gamification](https://github.com/FriendsOfFlarum/gamification) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-gamification/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-gamification/pl/) |
| [FoF GitLab Login](https://github.com/FriendsOfFlarum/auth-gitlab) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-auth-gitlab/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-auth-gitlab/pl/) |
| [FoF Ignore Users](https://github.com/FriendsOfFlarum/ignore-users) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-ignore-users/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-ignore-users/pl/) |
| [FoF Links](https://github.com/FriendsOfFlarum/links) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-links/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-links/pl/) |
| [FoF Masquerade](https://github.com/FriendsOfFlarum/masquerade) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-masquerade/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-masquerade/pl/) |
| [FoF Merge Discussions](https://github.com/FriendsOfFlarum/merge-discussions) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-merge-discussions/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-merge-discussions/pl/) |
| [FoF Open Collective](https://github.com/FriendsOfFlarum/open-collective) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-open-collective/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-open-collective/pl/) |
| [FoF Pages](https://github.com/FriendsOfFlarum/pages) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-pages/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-pages/pl/) |
| [FoF Polls](https://github.com/FriendsOfFlarum/polls) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-polls/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-polls/pl/) |
| [FoF Prevent Necrobumping](https://github.com/FriendsOfFlarum/prevent-necrobumping) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-prevent-necrobumping/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-prevent-necrobumping/pl/) |
| [FoF Reactions](https://github.com/FriendsOfFlarum/reactions) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-reactions/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-reactions/pl/) |
| [FoF Secure HTTPS](https://github.com/FriendsOfFlarum/secure-https) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-secure-https/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-secure-https/pl/) |
| [FoF Sentry](https://github.com/FriendsOfFlarum/sentry) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-sentry/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-sentry/pl/) |
| [FoF Share Social](https://github.com/FriendsOfFlarum/share-social) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-share-social/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-share-social/pl/) |
| [FoF Social Profile](https://github.com/FriendsOfFlarum/socialprofile) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-socialprofile/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-socialprofile/pl/) |
| [FoF Spamblock](https://github.com/FriendsOfFlarum/spamblock) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-spamblock/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-spamblock/pl/) |
| [FoF Split](https://github.com/FriendsOfFlarum/split) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-split/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-split/pl/) |
| [FoF Subscribed](https://github.com/FriendsOfFlarum/subscribed) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-subscribed/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-subscribed/pl/) |
| [FoF URL Transliterator](https://github.com/FriendsOfFlarum/transliterator) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-transliterator/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-transliterator/pl/) |
| [FoF User Bio](https://github.com/FriendsOfFlarum/user-bio) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-user-bio/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-user-bio/pl/) |
| [FoF User Directory](https://github.com/FriendsOfFlarum/user-directory) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-user-directory/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-user-directory/pl/) |
| [FoF Username Request](https://github.com/FriendsOfFlarum/username-request) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-username-request/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-username-request/pl/) |
| [FoF reCAPTCHA](https://github.com/FriendsOfFlarum/recaptcha) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-recaptcha/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-recaptcha/pl/) |

<!-- fof-extensions-list-stop -->


## Status tłumaczeń dla rozszerzeń społeczności

<!-- various-extensions-list-start -->

| Extension | Status |
| --- | --- |
| [Bazaar by Extiverse](https://github.com/extiverse/bazaar) | [![Translation status](https://weblate.rob006.net/widgets/flarum-extensions/pl/extiverse-bazaar/svg-badge.svg)](https://weblate.rob006.net/projects/flarum-extensions/extiverse-bazaar/pl/) |
| [Best Answer by Wiwatsrt](https://github.com/wiwatsrt/flarum-ext-best-answer) | [![Translation status](https://weblate.rob006.net/widgets/flarum-extensions/pl/wiwatsrt-best-answer/svg-badge.svg)](https://weblate.rob006.net/projects/flarum-extensions/wiwatsrt-best-answer/pl/) |
| [Canonical Url by Migratetoflarum](https://github.com/migratetoflarum/canonical) | [![Translation status](https://weblate.rob006.net/widgets/flarum-extensions/pl/migratetoflarum-canonical/svg-badge.svg)](https://weblate.rob006.net/projects/flarum-extensions/migratetoflarum-canonical/pl/) |
| [Discussion views by Michaelbelgium](https://github.com/MichaelBelgium/flarum-discussion-views) | [![Translation status](https://weblate.rob006.net/widgets/flarum-extensions/pl/michaelbelgium-discussion-views/svg-badge.svg)](https://weblate.rob006.net/projects/flarum-extensions/michaelbelgium-discussion-views/pl/) |
| [Flagrow Linguist by Flagrow](https://github.com/FriendsOfFlarum/linguist) | [![Translation status](https://weblate.rob006.net/widgets/flarum-extensions/pl/flagrow-linguist/svg-badge.svg)](https://weblate.rob006.net/projects/flarum-extensions/flagrow-linguist/pl/) |
| [Upload by Flagrow](https://github.com/FriendsOfFlarum/upload) | [![Translation status](https://weblate.rob006.net/widgets/flarum-extensions/pl/flagrow-upload/svg-badge.svg)](https://weblate.rob006.net/projects/flarum-extensions/flagrow-upload/pl/) |

<!-- various-extensions-list-stop -->


## Credits

Paczka bazuje na [rozszerzeniu stworzonym przez bepropl](https://github.com/bepropl/lang-polish) - to on jest autorem 
większości tłumaczeń.

Tłumaczenie dla `moment.js` pochodzi bezpośrednio ze [źródła](https://github.com/moment/moment/blob/2.24.0/locale/pl.js).
