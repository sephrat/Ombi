# [4.16.0](https://github.com/sephrat/Ombi/compare/v4.2.10...v4.16.0) (2022-03-20)


### Bug Fixes

* :bug: Add UI for Emby recently added cronjob settings ([#4469](https://github.com/sephrat/Ombi/issues/4469)) ([7d47bbe](https://github.com/sephrat/Ombi/commit/7d47bbe92204855bf75d70b8fa548f9c3f3612bc))
* :bug: Fixed the MySQL issue after .net 6 upgrade [#4393](https://github.com/sephrat/Ombi/issues/4393) ([fea7ff0](https://github.com/sephrat/Ombi/commit/fea7ff05139e9ff50c8097fa5389b4ef9ad21a15))
* :bug: Fixed the Request On Behalf autocomplete not filtering correctly ([a8ba2f3](https://github.com/sephrat/Ombi/commit/a8ba2f3544a1c01c57f217c4036a277ab0e67a09)), closes [#4539](https://github.com/sephrat/Ombi/issues/4539)
* :bug: Hides no results message during search. ([#4375](https://github.com/sephrat/Ombi/issues/4375)) ([b819b0e](https://github.com/sephrat/Ombi/commit/b819b0e007e578bf3d8425f19591f87029c64d06))
* :globe_with_meridians: Added Czech and Chinese Simplified to the language list ([68ef366](https://github.com/sephrat/Ombi/commit/68ef366e8525e2c349b9e81704ad8bcca6c347a0))
* **4k:** Hide 'Has 4K Request' column list if 4k feature is disabled ([#4521](https://github.com/sephrat/Ombi/issues/4521)) ([a9a6067](https://github.com/sephrat/Ombi/commit/a9a60678e74d22fa7ba34051a2645db86b600b4a))
* **API:** Fixed an issue where the API key couldn't delete a request [#4489](https://github.com/sephrat/Ombi/issues/4489) ([8e42dbf](https://github.com/sephrat/Ombi/commit/8e42dbf8f78caa51ca891bf3d702c6b0ac401f9c))
* **auto-delete:** :bug: We now also auto delete music requests, this was previously missing ([9fe1f8e](https://github.com/sephrat/Ombi/commit/9fe1f8e988aa31d36e7a685ae19f72d9c8414dc0))
* **availability-rules:** :bug: Fixed a small issue where some shows would not appear as Available even know they had no future unaired episodes listed ([914b096](https://github.com/sephrat/Ombi/commit/914b096781c9b73292a533a010a5dd05ecfd0aac))
* **availability-rules:** :bug: Show the 'Requested' button when a show has all of the episodes marked as requested ([cb7ecf6](https://github.com/sephrat/Ombi/commit/cb7ecf684ac3ab204f329a28baecfd4f6cd408f7))
* **availability:** :bug: Fixed an issue where with 4k content, we could repeat notifications ([f9ebc1c](https://github.com/sephrat/Ombi/commit/f9ebc1cc2e13c7cd335121cd86295b10eda529ba))
* **details:** :bug: Fixed the missing Play on Media server button for 4k content [#4529](https://github.com/sephrat/Ombi/issues/4529) ([68600f3](https://github.com/sephrat/Ombi/commit/68600f3b45376e12dd2ef263d81ca4040c84cbca))
* **discover:** :bug: Display TV + movies on actor page in user language ([#4395](https://github.com/sephrat/Ombi/issues/4395)) ([fe635c7](https://github.com/sephrat/Ombi/commit/fe635c7106bc487ff879bdc8a73bab16cb389b97))
* **discover:** :bug: Fixed an issue where monitored movies in radarr were not correctly represented on the search results ([75b15bc](https://github.com/sephrat/Ombi/commit/75b15bc7cba21f0a14a18c8e64fd52482f5c6325))
* **discover:** :bug: Fixed the issue where there was an option on the discover to request 4k shows (that's not supported currently) ([dcfd688](https://github.com/sephrat/Ombi/commit/dcfd688c8d2337e55fa9c6c33b7c3e80fc560cda))
* **discover:** 🌐 Localize episodes names in TV details ([#4467](https://github.com/sephrat/Ombi/issues/4467)) [skip ci] ([35806ea](https://github.com/sephrat/Ombi/commit/35806ea2d2c866d628cf08577026a02ab04e49d9))
* **discover:** TV shows now display on the Actor Pages ([#4388](https://github.com/sephrat/Ombi/issues/4388)) ([6b716e7](https://github.com/sephrat/Ombi/commit/6b716e722076e3d1e6bf2097c5263645d5ea9edf))
* **email-notifications:** :bug: Fixed the issue where legacy requests were showing broken poster images [#4452](https://github.com/sephrat/Ombi/issues/4452) ([0ece2fd](https://github.com/sephrat/Ombi/commit/0ece2fd6e0eb01e0b7d4d2a01e1a276c7a9c5a51))
* **emby:** :bug: Fixed an issue where we slightly broke the full sync ([332d934](https://github.com/sephrat/Ombi/commit/332d9344d002a5ffd5aeac516c7441dcdec52248))
* **emby:** :bug: Fixed an issue where we were not properly syncing episodes ([75529dd](https://github.com/sephrat/Ombi/commit/75529dd972c5102f3c5234a2acf6fe664a1bcfad))
* **emby:** :bug: Fixed the emby content sync [#4513](https://github.com/sephrat/Ombi/issues/4513) ([2927504](https://github.com/sephrat/Ombi/commit/2927504f0e0b4e7251e69b44e0e30c7ec9519980))
* **emby:** :bug: Fixed the emby content sync [#4513](https://github.com/sephrat/Ombi/issues/4513) ([bd441cb](https://github.com/sephrat/Ombi/commit/bd441cb54fd77d6befb03fae321dc36c29f0de2e))
* **emby/jellyfin:** :bug: A more reliable Emby and Jellyfin sync [skip ci] ([ad677fa](https://github.com/sephrat/Ombi/commit/ad677fa02eb75633014e9c9791c21ed2d6a23229))
* **emby/jellyfin:** :bug: Fixed another issue where we were not correctly displaying the correct status' for movies ([5c0556e](https://github.com/sephrat/Ombi/commit/5c0556e6f44b8997a611f3a4d8e9e4e05d08bd13))
* fix swagger api key auth ([#4483](https://github.com/sephrat/Ombi/issues/4483)) [no ci] ([32ee4e8](https://github.com/sephrat/Ombi/commit/32ee4e88ec05bf610150933974408fbe95ccd7bd))
* **frontend:** add link on logo text ([6d7274a](https://github.com/sephrat/Ombi/commit/6d7274a94ea24343f32fc028984bd3fd5d5f2ee3))
* **issues:** :bug: Added the issue category to the issue 'cards' [#4403](https://github.com/sephrat/Ombi/issues/4403) ([a3739f3](https://github.com/sephrat/Ombi/commit/a3739f375c49f48e34da12f0a74e4e068f12ab40))
* **issues:** :bug: Added the issues back to the details page for TV Shows ([0225000](https://github.com/sephrat/Ombi/commit/02250000c08a253e57d8a0a855c2d30b8a1e5baa))
* **issues:** :bug: Fixed an issue where you couldn't navigate to the details page from TV issues ([1a2825b](https://github.com/sephrat/Ombi/commit/1a2825bf3839b891b16e1dde4030afe53efe090e))
* **issues:** :bug: Fixed where we did not show the poster when an issue is raised for media we do not have a request for [#4402](https://github.com/sephrat/Ombi/issues/4402) ([15e37b5](https://github.com/sephrat/Ombi/commit/15e37b532a83097dbdf1a9fea3eead7d0e211898))
* **issues:** Fix label ID in chatbox page ([#4520](https://github.com/sephrat/Ombi/issues/4520)) ([76882ad](https://github.com/sephrat/Ombi/commit/76882adf231f92e1cdd396239933c13467c112b3))
* **jellyfin:** :bug: Fixed an issue where Jellyfin content was showing the Play on Emby button ([18b167d](https://github.com/sephrat/Ombi/commit/18b167d16a3d682b5060ee36dedbbb069bef09de)), closes [#4542](https://github.com/sephrat/Ombi/issues/4542)
* **localisation:** Localize request types in notifications ([#4516](https://github.com/sephrat/Ombi/issues/4516)) ([e09435d](https://github.com/sephrat/Ombi/commit/e09435da455b12fc429f129372de31e0654da797))
* **media-sync:** Add sanity checks upon media server sync ([#4493](https://github.com/sephrat/Ombi/issues/4493)) ([9915234](https://github.com/sephrat/Ombi/commit/9915234d38d4701c527081ccc21b566980375331)), closes [#4472](https://github.com/sephrat/Ombi/issues/4472)
* **mediaserver:** fixed an issue where we were not detecting available content correctly [#4542](https://github.com/sephrat/Ombi/issues/4542) ([9cdd6f4](https://github.com/sephrat/Ombi/commit/9cdd6f41cdab8825a984905c089611409c53c753))
* **mediaserver:** fixed some more issues in the media server sync and availability checks ([f3ea979](https://github.com/sephrat/Ombi/commit/f3ea979b8bd77842780ce8e6928b16237dd779cf))
* **newsletter:** :bug: Fixed a few small bugs in the newsletter ([21dba4c](https://github.com/sephrat/Ombi/commit/21dba4c524b98b9f2b883d97e7e13329425a8762))
* **newsletter:** Fix newsletter not publishing double episodes ([#4495](https://github.com/sephrat/Ombi/issues/4495)) ([ddf63fb](https://github.com/sephrat/Ombi/commit/ddf63fbed0b9cbe458aec37318758c76b99b2de9))
* **notifications:** :bug: Fixed the DenyReason sometimes not appearing in the notification message [#4409](https://github.com/sephrat/Ombi/issues/4409) ([209e311](https://github.com/sephrat/Ombi/commit/209e31175c95f6ee8909d878d45bf8269a9842d9))
* **notifications:** :bug: This is a fix for some of the duplicate notification issues [#3825](https://github.com/sephrat/Ombi/issues/3825) ([22bb422](https://github.com/sephrat/Ombi/commit/22bb4226ead2d62e8c2c2c05be47d7da621402e2))
* **notifications:** 🐛 Do not notify user upon auto approval of a TV show ([#4432](https://github.com/sephrat/Ombi/issues/4432)) ([3ad3bdd](https://github.com/sephrat/Ombi/commit/3ad3bddd8313d607ee2a39a51a92e61a3673082c)), closes [#4431](https://github.com/sephrat/Ombi/issues/4431)
* **notifications:** fixed an error that could happen when Ombi sends out a issue notification ([7442dcf](https://github.com/sephrat/Ombi/commit/7442dcf59da5d2190cc3087b10402e85bcfcf83b))
* **notifications:** Remove generic admin email in favour of admins' email ([#4519](https://github.com/sephrat/Ombi/issues/4519)) ([b90fc5f](https://github.com/sephrat/Ombi/commit/b90fc5fea771a83e6cf576c71a307066efd59ea4))
* **oauth:** :lock: Fixed the issue where some users running their browsers in a different language could not open the Plex OAuth window ([d5404ea](https://github.com/sephrat/Ombi/commit/d5404eaad7837010d6e4563cd8f7a1009231d362)), closes [#4408](https://github.com/sephrat/Ombi/issues/4408)
* **permissions:** :bug: Improved the security around the role "Manage Own Requests" ([#4397](https://github.com/sephrat/Ombi/issues/4397)) ([334a32b](https://github.com/sephrat/Ombi/commit/334a32bca42f90198d9b720d2bdb710a583be47f)), closes [#4391](https://github.com/sephrat/Ombi/issues/4391)
* **plex:** Fixed an issue where in a rare case we couldn't sync the data [#4502](https://github.com/sephrat/Ombi/issues/4502) ([191318d](https://github.com/sephrat/Ombi/commit/191318ddad5a8148422955bf928f1c49b890e3eb))
* **request-list:** :bug: Fixed an issue where the bulk delete would not work for movie requests ([4b540fb](https://github.com/sephrat/Ombi/commit/4b540fb45bcc389664f0953159802288d005db9f))
* **request-list:** :bug: Fixed an issue where the request options were not appearing for Music requests ([c0406a2](https://github.com/sephrat/Ombi/commit/c0406a2ddebafb03d98ed25cdf7d89dc9a600c7d))
* **requests:** :bug: Fixed an issue where you couldn't approve movies from the request list ([1611ef9](https://github.com/sephrat/Ombi/commit/1611ef9198befbb7a4db50a4f0953e50f29a788f))
* **requests:** :bug: Fixed the approve 4k option on the requests list not working as expected ([c0189da](https://github.com/sephrat/Ombi/commit/c0189dad478ea375beda61ba3bee3f029a39b8e5))
* **requests:** :bug: Fixed the issue where Approving a 4K Request wouldn't send it to the correct 4K radarr instance ([87cb990](https://github.com/sephrat/Ombi/commit/87cb9903db30e1dead25ee8c5ea34305eb084a03)), closes [#4509](https://github.com/sephrat/Ombi/issues/4509)
* **requests:** :bug: Fixed the issue where we could no longer approve TV Requests from the requests list ([19fe4e3](https://github.com/sephrat/Ombi/commit/19fe4e342efe5578c26ab8ba7ee2f2e64bbc9418))
* **search:** Fixed some cases where search wouldn't work correctly ([#4398](https://github.com/sephrat/Ombi/issues/4398)) ([4410790](https://github.com/sephrat/Ombi/commit/4410790bc096826bc11554098f846e3acb59589a))
* **settings:** :bug: Fixed an issue where we were not displaying the excluded keyworks correctly in the TheMovieDbSettings page ([d3b3316](https://github.com/sephrat/Ombi/commit/d3b3316cbac18356b2f6b0912a3deb2c183e6534))
* **Sonarr:** :bug: Fixed an issue where some seasons were not being monitored correctly in sonarr ([60cfd41](https://github.com/sephrat/Ombi/commit/60cfd41f68e9006555c1a419dcff1aaa24b3e09f)), closes [#4506](https://github.com/sephrat/Ombi/issues/4506)
* **sonarr:** :bug: Fixed an issue where we could attempt to add a series to sonarr before sonarr has got all the metadata [#4459](https://github.com/sephrat/Ombi/issues/4459) ([5c691dc](https://github.com/sephrat/Ombi/commit/5c691dc98437a4cd24560ff625414fe05dd22f89))
* **sonarr:** :bug: Fixed an issue where we were sometimes incorrectly setting the state of episodes that are already monitored in sonarr ([fd1acb8](https://github.com/sephrat/Ombi/commit/fd1acb88cbc5e73f91b7f81e6e28ee06d66b277e))
* **sonarr:** Fixed where requesting all seasons would only mark the latest as monitored [#4496](https://github.com/sephrat/Ombi/issues/4496) ([cfb85c2](https://github.com/sephrat/Ombi/commit/cfb85c23d77626b9ec1d99a6cf76497c438d0338))
* **translations:** 🌐 Fix incorrect text translation reference RequestedByOn ([#4420](https://github.com/sephrat/Ombi/issues/4420)) ([202d155](https://github.com/sephrat/Ombi/commit/202d155493c29a6ddd4c5507186bf376a28f4c1d))
* **translations:** 🌐 Localization - Ensuring all of the app including backend are localized [#4366](https://github.com/sephrat/Ombi/issues/4366) ([5e140ab](https://github.com/sephrat/Ombi/commit/5e140ab6183b887a7665f5e870eb0bd05d487ace))
* **translations:** 🌐 New translations %two_letters_code% from Crowdin [skip ci] ([8fbd267](https://github.com/sephrat/Ombi/commit/8fbd267b516ddaa80fd16c091bae532b860fbf45))
* **translations:** 🌐 New translations en.json from Crowdin [skip ci] ([52eda6a](https://github.com/sephrat/Ombi/commit/52eda6ab917a73842bc02b0d8e0c442e564ca8f0))
* **translations:** 🌐 New translations en.json from Crowdin [skip ci] ([1095d52](https://github.com/sephrat/Ombi/commit/1095d524962648a1e427f0bcd8105fa734dd5b60))
* **translations:** 🌐 New translations from Crowdin ([5cfb76c](https://github.com/sephrat/Ombi/commit/5cfb76cad7a25eed8b452bf9c01cef8c32804369))
* **translations:** 🌐 New translations from Crowdin  ([8943a97](https://github.com/sephrat/Ombi/commit/8943a978bf459eaeb496d50c61c4d1506c727366))
* **translations:** 🌐 New translations from Crowdin  ([473c172](https://github.com/sephrat/Ombi/commit/473c1724922515fe376e0b2058ac391807c923f2))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([356c742](https://github.com/sephrat/Ombi/commit/356c7424e0ce8c1c5063b04bc6ed9b809f214d65))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([6fcaecf](https://github.com/sephrat/Ombi/commit/6fcaecf80b766f2d43ac7082d74364238e1638b7))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([132f4d4](https://github.com/sephrat/Ombi/commit/132f4d4e609b7fb7e37f38ee2f395926e2911abe))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([f292006](https://github.com/sephrat/Ombi/commit/f292006a08894a8d0ba899c8c6e9fe863e558dda))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([c6acb45](https://github.com/sephrat/Ombi/commit/c6acb45f8d3f371c0b4024c4272849d0d0cc867f))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([18c220a](https://github.com/sephrat/Ombi/commit/18c220a0cd0d19e45a07d0c319da2b9512778a8a))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([b0f3abb](https://github.com/sephrat/Ombi/commit/b0f3abb9ceebdbe5d6c20af98b7355df2999eb58))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([77d017b](https://github.com/sephrat/Ombi/commit/77d017b3d8ffd1714a2f6efecc8c900d56d062e4))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([f6e9784](https://github.com/sephrat/Ombi/commit/f6e9784367d3678d899ed79bef6caa52005b6661))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([601a877](https://github.com/sephrat/Ombi/commit/601a87762a2ad393ee5fa2fe52052ceeeefb1bef))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([a4a80ba](https://github.com/sephrat/Ombi/commit/a4a80ba4da49733a65e691003646c0f349bd4c5f))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([2961319](https://github.com/sephrat/Ombi/commit/2961319f61e95b2871480152b86ddca3375576a1))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([fc8d108](https://github.com/sephrat/Ombi/commit/fc8d108b660d53f499538328bfc271b05ac47d2b))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([1e03651](https://github.com/sephrat/Ombi/commit/1e03651c3b0eb77e45f9f6c55d31ee672eacd51e))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([c0dd327](https://github.com/sephrat/Ombi/commit/c0dd327426514e305a88750d7c3deb21c194108f))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([2156129](https://github.com/sephrat/Ombi/commit/2156129f175335746f204bb123035c070f518e96))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([aef0368](https://github.com/sephrat/Ombi/commit/aef0368de3aec306245bd1b16bc0de596a20d451))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([a38090b](https://github.com/sephrat/Ombi/commit/a38090b8dde17d1d150af0bca2830ea45d013a0e))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([c5f1d33](https://github.com/sephrat/Ombi/commit/c5f1d3355758a5c3648479d44e50397c7f6c1a9d))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([3846d56](https://github.com/sephrat/Ombi/commit/3846d56a6e561a1b1dc65c385151d90fdd6217ee))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([dafe9c1](https://github.com/sephrat/Ombi/commit/dafe9c1a19d84f00c13f0a51ba90927c24282926))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([edb418a](https://github.com/sephrat/Ombi/commit/edb418a6f05887c68a0c24c48decc691996f97e4))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([dadabf9](https://github.com/sephrat/Ombi/commit/dadabf93e1582a0c39321fd9bf3de3fb11e3f406))
* **translations:** 🌐 New translations from Crowdin [skip ci] ([#4526](https://github.com/sephrat/Ombi/issues/4526)) ([7e9f54f](https://github.com/sephrat/Ombi/commit/7e9f54fc80a09c938184e6be40ce5f49ce9673ef))
* **tv:** Display TV show as requested if all episodes are requested ([#4518](https://github.com/sephrat/Ombi/issues/4518)) ([2ed8c48](https://github.com/sephrat/Ombi/commit/2ed8c48d128a69f0d144c5d332286dbf3b0bdf28))
* **user-management:** :bug: Fixed an issue where you couldn't 'unset' a users custom quality and root folders ([bae96af](https://github.com/sephrat/Ombi/commit/bae96af17f50a80ae3ade235a5ef68d5d2dc12ba))
* **wizard:** :bug: Fixed the issue where the Application Url wasn't validated in the wizard ([33b8d11](https://github.com/sephrat/Ombi/commit/33b8d1111a1c6663d8c0bbd912be4660da7d013f)), closes [#4417](https://github.com/sephrat/Ombi/issues/4417)


### Features

* :sparkles: Upgrade Ombi to .NET 6 ([#4390](https://github.com/sephrat/Ombi/issues/4390)) ([719eb7d](https://github.com/sephrat/Ombi/commit/719eb7dbe37b3a72d264e2f670067518eef70694)), closes [#4392](https://github.com/sephrat/Ombi/issues/4392)
* **customization:** :sparkles: Added possibility for custom favicons ([40af659](https://github.com/sephrat/Ombi/commit/40af6593b668d4712327c18f92f5b7b5a0a65e26))
* **details:** :sparkles: Added the notify button back into the details pages for requests ([8b33cdc](https://github.com/sephrat/Ombi/commit/8b33cdccef83db8794414b247438214b00860fac))
* **email-notifications:** Add a link to Ombi details page in email notifications ([#4517](https://github.com/sephrat/Ombi/issues/4517)) ([a3e97b3](https://github.com/sephrat/Ombi/commit/a3e97b31e2298d95e7deebd71268095b8ed5e9dc))
* **emby:** :sparkles: Added a emby recently added sync! ([a0e1406](https://github.com/sephrat/Ombi/commit/a0e14068f4bc457f8a4a565de71707a8f16c803c))
* **mass-email:** :sparkles: Added the ability to configure the Mass Email, we can now send BCC and we are less likely to be rate limited when not using bcc [#4377](https://github.com/sephrat/Ombi/issues/4377) ([ca655ae](https://github.com/sephrat/Ombi/commit/ca655ae57042dec44106a2f2ef5ba2e6f1019ee4))
* **media-details:** Add Trakt to social icons ([#4522](https://github.com/sephrat/Ombi/issues/4522)) ([d6ae79c](https://github.com/sephrat/Ombi/commit/d6ae79ce9eddbd5b7b888ab1b9f7e342d9d9ff9e))
* **newsletter:** Started to localize the newsletter ([#4485](https://github.com/sephrat/Ombi/issues/4485)) ([b5ec556](https://github.com/sephrat/Ombi/commit/b5ec5562435021ea4b8af07c9b64a3f7249b570a))
* **notifications:** :sparkles: Send new request email notifications to power users ([#4462](https://github.com/sephrat/Ombi/issues/4462)) ([10cc0c0](https://github.com/sephrat/Ombi/commit/10cc0c0951f13221179516f8ff5c44dbecc9a0fd))
* **radarr:** 4K Requests and Radarr 4K support  ([ba88848](https://github.com/sephrat/Ombi/commit/ba88848866b0a9dedb1e79b55c4d81a0fd453843))
* **request-limits:** :sparkles: Added the new request limit options into the user importer ([01d4f4d](https://github.com/sephrat/Ombi/commit/01d4f4d718fe85ac181dae52565fb1b427965b4f))
* **request-limits:** :sparkles: Added the new request limit options to the bulk edit ([03bc23a](https://github.com/sephrat/Ombi/commit/03bc23a74e4308aa6b4c6b25636edcdeb65c1f0e))



## [4.2.10](https://github.com/sephrat/Ombi/compare/v4.2.9...v4.2.10) (2021-10-15)


### Bug Fixes

* :bug: Really really fix it this time? ([543d36e](https://github.com/sephrat/Ombi/commit/543d36e5615341bc8378cac377b843a3dbc1ef99))



## [4.2.9](https://github.com/sephrat/Ombi/compare/v4.2.8...v4.2.9) (2021-10-15)


### Bug Fixes

* :fire: Really fix the base url issue this time ([9f36923](https://github.com/sephrat/Ombi/commit/9f36923c51bfabf9cb026f2da14f9947050af0d9))



## [4.2.8](https://github.com/sephrat/Ombi/compare/v4.2.7...v4.2.8) (2021-10-15)


### Bug Fixes

* :adhesive_bandage: See if this fixes the proxy issue ([74d1aca](https://github.com/sephrat/Ombi/commit/74d1acae499707a7e21401f53eb2bb90c5bb9cfa))
* :bug: Fixed Ombi not writing the baseUrl correctly ([e9cc8b6](https://github.com/sephrat/Ombi/commit/e9cc8b6fe71d3e10c1a901e70227989b3362afe3))



## [4.2.7](https://github.com/sephrat/Ombi/compare/v4.2.6...v4.2.7) (2021-10-14)


### Bug Fixes

* :bug: Fixed the issue parsing TheMovieDB dates. They have broken something... ([6e397e0](https://github.com/sephrat/Ombi/commit/6e397e02e95f894a92e8bf02428efdcac1275b31))



## [4.2.6](https://github.com/sephrat/Ombi/compare/v4.2.5...v4.2.6) (2021-10-14)


### Performance Improvements

* :zap: Use ngxs store for the whole customization section of the app ([97b493d](https://github.com/sephrat/Ombi/commit/97b493d869feee59d360b484a6c59388a2aead1f))



## [4.2.5](https://github.com/sephrat/Ombi/compare/v4.2.4...v4.2.5) (2021-10-14)



## [4.2.4](https://github.com/sephrat/Ombi/compare/v4.2.3...v4.2.4) (2021-10-13)


### Bug Fixes

* **#4344:** :bug: Fixed an issue where we errored on Plex Episode Scan ([cd5532f](https://github.com/sephrat/Ombi/commit/cd5532fa8f7ebbfaf942841398672bafb9a405d4))
* **#4345:** :bug: Fixed the issue where denied requests we not appearing correctly ([5a2f652](https://github.com/sephrat/Ombi/commit/5a2f652a28f5699dd667afef8dde129817e53392))



## [4.2.3](https://github.com/sephrat/Ombi/compare/v4.2.2...v4.2.3) (2021-10-12)


### Bug Fixes

* **user-management:** :bug: Fixed an issue where the Copy users App Link did not generate the correct app link for that user ([8cafcdc](https://github.com/sephrat/Ombi/commit/8cafcdcc3baa85c55d75e43835b2289bbea69b0e))



## [4.2.2](https://github.com/sephrat/Ombi/compare/v4.2.1...v4.2.2) (2021-10-11)


### Bug Fixes

* **search:** :bug: Fixed an issue where changing the filter wouldn't refresh the search results ([10f5e05](https://github.com/sephrat/Ombi/commit/10f5e056c8257f8b8fe954bfbc70d3c3daa7a8e3))



## [4.2.1](https://github.com/sephrat/Ombi/compare/v4.2.0...v4.2.1) (2021-10-11)


### Bug Fixes

* **oauth:** :bug: Fixed an issue where on occasions the Plex OAuth wouldn't work ([ce1ed01](https://github.com/sephrat/Ombi/commit/ce1ed01a5f1a6e99d37a3cf32e53cf5de4f5943b))



# [4.2.0](https://github.com/sephrat/Ombi/compare/v4.1.1...v4.2.0) (2021-10-09)


### Bug Fixes

* **settings:** :bug: Fixed the issue where you couldn't save the Plex settings ([89a856a](https://github.com/sephrat/Ombi/commit/89a856a5d22a5f517702642876652d451f6e9b3e))


### Features

* :sparkles: Added the ability to specify which branch you are on ([777ed2f](https://github.com/sephrat/Ombi/commit/777ed2f3224b91a0acb47c30efa96adaaba46fd2))
* **notifications:** :sparkles: Added Partially Available Notifications ([1ef45dc](https://github.com/sephrat/Ombi/commit/1ef45dc44c93d566a0f04c011bfcefe2009a24b5))



## [4.1.1](https://github.com/sephrat/Ombi/compare/v4.0.1511...v4.1.1) (2021-10-08)


### Bug Fixes

* **4153:** :bug: fixed gravitar issues ([ec963d8](https://github.com/sephrat/Ombi/commit/ec963d869a2bf57edfcfef418e2bf8a1d679d8ca))



## [4.0.1511](https://github.com/sephrat/Ombi/compare/v4.1.0...v4.0.1511) (2021-10-07)



# [4.1.0](https://github.com/sephrat/Ombi/compare/v4.0.1510...v4.1.0) (2021-10-07)


### Features

* :sparkles: Added the ability to specify which branch you are on ([61f3e94](https://github.com/sephrat/Ombi/commit/61f3e94308fb3d239140b73d34c12f1496459989))



## [4.0.1510](https://github.com/sephrat/Ombi/compare/v4.0.1602...v4.0.1510) (2021-10-07)


### Bug Fixes

* :bookmark: Set version to correct number ([1a7b9b5](https://github.com/sephrat/Ombi/commit/1a7b9b50578675532fdb0f656cbaf51306166b84))
* :bug: bump ver ([5207b21](https://github.com/sephrat/Ombi/commit/5207b21f2f98cc63f16a72bd79ecac6abf838139))
* :bug: Pretending to fix a bug ([5351c14](https://github.com/sephrat/Ombi/commit/5351c14cb087f9ecbb37b784724bb35107d17cb8))
* :bug: Set the real tag version now ([9287d83](https://github.com/sephrat/Ombi/commit/9287d83c134e62c9f0a5d271cfd88eefc9dcae39))
* :bug: Stop Devops from building and releasing, GH Actions will now call the APT Build ([1fda2a1](https://github.com/sephrat/Ombi/commit/1fda2a1d37c1182177fdca55e38b98a85dc1fe05))
* :bug: updated contributors PAT ([a1d22db](https://github.com/sephrat/Ombi/commit/a1d22db4d14c63c39e79d47d99cc7ca2efe393df))
* :bug: Upload the correct artifacts ([a249805](https://github.com/sephrat/Ombi/commit/a2498051cfd679dd19206571883a08d77e159e2b))
* try and fix the artifact upload ([fb9ff4c](https://github.com/sephrat/Ombi/commit/fb9ff4ccde9121dce6da379198de225686123457))



## [4.0.1506](https://github.com/sephrat/Ombi/compare/v4.0.1499...v4.0.1506) (2021-09-28)


### Bug Fixes

* :bug: Fixed the issue where the user management login dates were not local time ([97be373](https://github.com/sephrat/Ombi/commit/97be3737700ed7b1ee915dbcd9f44103665d472c)), closes [#2925](https://github.com/sephrat/Ombi/issues/2925)
* :bug: Fixed the issue where we were not generating the newsletter plex mediaserver link correctly ([b6064e9](https://github.com/sephrat/Ombi/commit/b6064e9308ee1218517f54d331c9bd7953ca631e))
* **request-limits:** :bug: Fixed the issue where we were calculating Tv Request limit reset date incorrectly ([ceaec3f](https://github.com/sephrat/Ombi/commit/ceaec3feb0c9fbdab48595d7e425930a39d87ad5))


### Features

* **request-limits:** :card_file_box: Added new user field migrations to mysql and sqlite ([f73bccb](https://github.com/sephrat/Ombi/commit/f73bccbea759fb4aeadc32f94b1ef6c9aecc5e94))
* **request-limits:** :sparkles: Added in the main logic for the new request limits ([70d5bf5](https://github.com/sephrat/Ombi/commit/70d5bf52bff2e321fb1f3d00fd1cd1121a2717b7))
* **request-limits:** :sparkles: Added the UI portion to set the new limits ([978d4ea](https://github.com/sephrat/Ombi/commit/978d4ea33b32d5a8333c75e29d4cd702e434c5f0))
* **request-limits:** :sparkles: Request limits are no longer a rolling date. But reset at the start of the week or month depending on the preference ([364b9f1](https://github.com/sephrat/Ombi/commit/364b9f11afcd470cc2b112cf81cd840316ddc80e))
* **request-limits:** :sparkles: Updated the RequestLimit Rules to use the new refactored service ([e31ee8d](https://github.com/sephrat/Ombi/commit/e31ee8d89213a8fc179db56cc51d3f02648b51ec))
* **request-limits:** :tada: Started on the request limits, applied to the user model ([f5310b7](https://github.com/sephrat/Ombi/commit/f5310b786b43b3c00d392da977c2b3367a5e4e11))



## [4.0.1488](https://github.com/sephrat/Ombi/compare/v4.0.1487...v4.0.1488) (2021-09-18)


### Features

* **discover:** :lipstick: Moved the advanced search to the nav bar for better discovery ([f83abaf](https://github.com/sephrat/Ombi/commit/f83abafdd9fc416c8ca4d99a52b5fc94e0b781fd))
* **plex:** :zap: Use the new Plex Pass includeGuids feature for syncing plex movies ([7c5646d](https://github.com/sephrat/Ombi/commit/7c5646d416372983ac8996b1a6539e671db18c86))



## [4.0.1483](https://github.com/sephrat/Ombi/compare/v4.0.1482...v4.0.1483) (2021-09-16)


### Bug Fixes

* **discover:** :bug: Fixed up the discover lists, ([fc69158](https://github.com/sephrat/Ombi/commit/fc691585976893f69b5c4806147afbd68bdaeb61))



## [4.0.1482](https://github.com/sephrat/Ombi/compare/v4.0.1477...v4.0.1482) (2021-09-08)


### Bug Fixes

* **details:** :alien: Removed the RT API calls from the frontend for now ([99c7289](https://github.com/sephrat/Ombi/commit/99c728918e74805a0b2ecdb72db41d45b57b619e)), closes [#4305](https://github.com/sephrat/Ombi/issues/4305)
* **discover:** :bug: Made the poster images on discover the same size no matter how many results there are ([78b9eef](https://github.com/sephrat/Ombi/commit/78b9eef48322d44e6c393a8075d486580dfe4027))



## [4.0.1477](https://github.com/sephrat/Ombi/compare/v4.0.1476...v4.0.1477) (2021-09-07)


### Bug Fixes

* :bug: Fixed where the Play On {MediaSever} was not appearing for TV Shows ([06b60ee](https://github.com/sephrat/Ombi/commit/06b60ee9d2bab4bef24ba3d9c3a6830a12bc3c0f)), closes [#4303](https://github.com/sephrat/Ombi/issues/4303)



## [4.0.1476](https://github.com/sephrat/Ombi/compare/v4.0.1475...v4.0.1476) (2021-09-07)


### Bug Fixes

* :bug: Small change to the URL we generate for the Play on Plex link ([e8810e8](https://github.com/sephrat/Ombi/commit/e8810e82b1a8ecc28869186f63708f25c423b3d6))



## [4.0.1475](https://github.com/sephrat/Ombi/compare/v4.0.1474...v4.0.1475) (2021-09-06)


### Features

* :sparkles: Added the ability to provide your own custom plex url ([6c6b7bb](https://github.com/sephrat/Ombi/commit/6c6b7bb498f142002e5b407a30896f4aa91a7c6c))



## [4.0.1451](https://github.com/sephrat/Ombi/compare/v4.0.1449...v4.0.1451) (2021-07-27)



## [4.0.1449](https://github.com/sephrat/Ombi/compare/v4.0.1448...v4.0.1449) (2021-07-24)



## [4.0.1448](https://github.com/sephrat/Ombi/compare/v4.0.1447...v4.0.1448) (2021-07-20)



## [4.0.1447](https://github.com/sephrat/Ombi/compare/v4.0.1446...v4.0.1447) (2021-07-20)



## [4.0.1443](https://github.com/sephrat/Ombi/compare/v4.0.1442...v4.0.1443) (2021-07-08)



