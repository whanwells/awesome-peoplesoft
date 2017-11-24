# Awesome PeopleSoft [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of PeopleSoft things, inspired by other [awesome](https://awesome.re/) lists.

*Contributions welcome, but please read the [guidelines](contributing.md) first.*

## Contents

- [Articles/Tutorials](#articles-and-tutorials)
  - [Security](#security)
  - [DPK](#dpk)
  - [Fluid](#fluid)
  - [PeopleCode](#peoplecode)
  - [Event Mapping Framework](#event-mapping-framework)
  - [Branding](#branding)
- [Resources](#resources)
- [Community Ideas](#community-ideas)
- [License](#license)

## Articles and Tutorials

### Security

- ERPScan's TokenChpoken Series
  - [Overview of Architecture](https://erpscan.com/press-center/blog/peoplesoft-security-part-1-overview-of-architecture/)
  - ["Decrypting" AccessID](https://erpscan.com/press-center/blog/peoplesoft-security-part-2-decrypting-accessid/)
  - [PeopleSoft SSO & TokenChpoken Attack](https://erpscan.com/press-center/blog/peoplesoft-security-part-3-peoplesoft-sso-tokenchpoken-attack/)
  - [PeopleSoft Pentest Using TokenChpoken Tool](https://erpscan.com/press-center/blog/peoplesoft-security-part-4-peoplesoft-pentest-using-tokenchpoken-tool/)
- ERPScan's Oracle PeopleSoft Security Configuration Series
  - [Introduction](https://erpscan.com/press-center/blog/eas-sec-oracle-peoplesoft-security-configuration-part-1/)
  - [Patch Management](https://erpscan.com/press-center/blog/peoplesoft-security-configuration-part-2-patch-management/)
  - [Default Accounts](https://erpscan.com/press-center/blog/peoplesoft-default-accounts/)
  - [Unnecessary Functionality](https://erpscan.com/press-center/blog/eas-sec-oracle-peoplesoft-security-configuration-part-4-unnecessary-functionality/)
  - [Open Remote Management Interfaces](https://erpscan.com/press-center/blog/eas-sec-oracle-peoplesoft-security-configuration-part-5-open-remote-management-interfaces/)
  - [Insecure Settings](https://erpscan.com/press-center/blog/eas-sec-oracle-peoplesoft-security-configuration-part-6-insecure-settings/)
  - [Unencrypted Connections](https://erpscan.com/press-center/blog/eas-sec-oracle-peoplesoft-security-configuration-part-7-unencrypted-connections/)
  - [Access Control and SoD Conflicts](https://erpscan.com/press-center/blog/eas-sec-oracle-peoplesoft-security-configuration-part-8-access-control-sod-conflicts/)
- JOLTandBleed
  - [PeopleSoft JOLTandBleed](https://erpscan.com/press-center/blog/peoplesoft-joltandbleed/) - Overview of the JOLTandBleed vulnerability.
  - [The Oracle (PeopleSoft/Tuxedo) JoltandBleed Vulnerabilities: What You Need to Know](https://blog.rapid7.com/2017/11/20/the-oracle-peoplesoft-tuxedo-joltandbleed-vulnerabilities-what-you-need-to-know/)
- [PeopleSoft Passwords Decryption](https://erpscan.com/press-center/blog/peoplesoft-passwords-decryption/) - How to decrypt configuration passwords and tips to help protect yourself.
- [`pscipher`, `psvault` and Web Server Passwords](http://psadmin.io/2017/01/31/pscipher-psvault-and-web-server-passwords/) - A look at password encryption for the web server.
- [Limit PeopleSoft Vulnerabilities](http://psadmin.io/2015/06/09/limit-peoplesoft-vulnerabilities/) - Tips for hardening your installation.
- [Understanding the Check Token ID in PeopleTools 8.56](http://psadmin.io/2017/10/25/understanding-the-check-token-id-in-peopletools-8-56/)

### DPK

- [Dealing with Missing Required OS Packages](http://psadmin.io/2016/07/05/linux-dpk-dealing-with-missing-required-os-packages/) - Get required Linux packages installed.
- [Explaining the `site.pp` File](http://psadmin.io/2016/06/07/explaining-the-site-pp-file/)
- [Encrypt `psft_customizations.yaml` Passwords](http://psadmin.io/2016/10/25/encrypt-psft_customizations-yaml-passwords/)
- [Multiple `PS_CFG_HOMEs` with the DPK](http://psadmin.io/2016/08/10/multiple-ps_cfg_homes-with-the-dpk/) - Use custom Puppet code to create multiple `PS_CFG_HOMEs`.
- [Enable Tuxedo Domain Features with the DPK](http://psadmin.io/2016/10/12/enable-tuxedo-domain-features-with-the-dpk/) - Bug fix for setting Tuxedo features on Windows.
- [Building a PIA Domain](http://psadmin.io/2016/09/07/advanced-dpk-building-a-pia-domain/)
- [Advanced WebLogic Configuration with the DPK](http://psadmin.io/2016/07/19/advanced-weblogic-configuration-with-the-dpk/)
- [Apply CPU Patches with Deployment Packages](http://psadmin.io/2017/05/02/apply-cpu-patches-with-deployment-packages/)

### Fluid

- [Three Simple Tips for Fluid Beginners](http://www.peoplesoftjournal.com/2016/10/three-simple-tips-for-fluid-beginners.html) - Create tab bars and header panels, and set the page title at runtime.
- [Fluid Navigation Collections](https://github.com/RicardoWood/PeopleStuff/wiki/Fluid-Navigation-Collections)
- [How to Deploy Homepages, Tiles, and Branding](https://peoplesoftih.blogspot.com/2016/11/things-learned-during-our-855-rollout.html)
- [PeopleSoft Fluid Push Notifications](https://peoplesoftih.blogspot.com/2017/10/push-notifications.html)
- [<kbd>Ctrl</kbd> + <kbd>J</kbd> on Mobile Devices](https://pe0ples0ft.blogspot.com/2016/03/fluid-ui-ctrlj-on-mobile-devices.html)
- [New Window Feature Workaround](https://pe0ples0ft.blogspot.com/2017/01/flud-ui-new-window-feature-workaround.html)
- [Using Oracle JET](https://pe0ples0ft.blogspot.com/2016/05/peopletools-855-using-oracle-jet-jquery.html)
([Part 2](https://pe0ples0ft.blogspot.com/2016/05/peopletools-855-using-oracle-jet-jquery_29.html),
[Part 3](https://pe0ples0ft.blogspot.com/2016/05/peopletools-855-using-oracle-jet-jquery_30.html),
[Part 4](https://pe0ples0ft.blogspot.com/2016/06/peopletools-855-using-oracle-jet-jquery.html)) - Use Oracle JET with PeopleTools 8.55+.

### PeopleCode

- [Implementing Google Authenticator in PeopleSoft](http://www.peoplesoftmods.com/2fa/implementing-google-authenticator-in-peoplesoft/) - Steps and code to use two factor authentication in PIA.
- [Generating QR Codes in PeopleSoft](http://www.peoplesoftmods.com/2fa/generating-qr-codes-in-peoplesoft/)

### Event Mapping Framework

- [Hello World and Quirks](https://pe0ples0ft.blogspot.com/2016/10/emf-hello-world-and-quirks.html) - Simple example to get familiar with the framework.
- [Related Content/Event Mapping for Components not registered in the Portal](https://pe0ples0ft.blogspot.com/2017/02/rc-emf-for-components-not-in-portal-menu.html)
- [Event Mapping Framework Migration](https://pe0ples0ft.blogspot.com/2016/12/event-mapping-framework-migration.html) - Migrate definitions using Application Designer.

### Branding

- [Fluid Branding](http://pe0ples0ft.blogspot.com/2015/06/peopletools-854-branding-part-5a-fluid.html)
([Part 2](http://pe0ples0ft.blogspot.com/2015/11/peopletools-854-branding-part-5b-fluid.html),
[Part 3](http://pe0ples0ft.blogspot.com/2015/11/peopletools-854-branding-part-5c-fluid.html),
[Part 4](http://pe0ples0ft.blogspot.com/2016/03/peopletools-854-branding-part-5d-fluid.html))
- [PeopleTools 8.55 Branding](https://pe0ples0ft.blogspot.com/2016/03/peopletools-855x-branding-part-i-what.html)
([Part 2](https://pe0ples0ft.blogspot.com/2016/04/peopletools-855x-branding-part-ii.html),
[Part 3](https://pe0ples0ft.blogspot.com/2016/04/peopletools-855x-branding-part-iii.html))
- [Customizing `DEFAULT_THEME_TANGERINE`](https://pe0ples0ft.blogspot.com/2014/11/peopletools-854-branding-part-1.html)
([Part 2](https://pe0ples0ft.blogspot.com/2014/11/peopletools-854-branding-part-2.html),
[Part 3](https://pe0ples0ft.blogspot.com/2014/12/peopletools-854-branding-part-3.html))
- [Customizing `DEFAULT_THEME_TANGERINE_ALT`](http://pe0ples0ft.blogspot.com/2015/05/peopletools-854-branding-part-4a.html)
([Part 2](http://pe0ples0ft.blogspot.com/2015/06/peopletools-854-branding-part-4b.html),
[Part 3](http://pe0ples0ft.blogspot.com/2015/09/peopletools-854-branding-part-4c.html),
[Part 4](http://pe0ples0ft.blogspot.com/2015/11/peopletools-854-branding-part-4d.html),
[Part 5](https://pe0ples0ft.blogspot.com/2016/05/peopletools-854-branding-part-4e.html))

## Resources

- [PeopleSoft Weekly](https://peoplesoftweekly.com/) - Articles and commentary delivered weekly.
- [The PeopleSoft Administrator Podcast](http://psadmin.io/category/podcast/)
- [PeopleSoft Wiki](http://peoplesoft.wikidot.com/)
- [Cooperative PeopleTools Reference](http://www.go-faster.co.uk/peopletools/) - Index of PeopleTools database tables.

## Community Ideas

*These ideas need your votes!*

- [Lifecycle Management](https://community.oracle.com/community/support/peoplesoft/install_upgrade_-_psft/content?filterID=contentstatus[published]~objecttype~objecttype[idea])
- [PeopleTools](https://community.oracle.com/community/support/peoplesoft/peopletools_-_psft/content?filterID=contentstatus[published]~objecttype~objecttype[idea]&sortKey=score)

# License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [William Wells](https://github.com/whanwells) has waived all copyright and related or neighboring rights to this work.
