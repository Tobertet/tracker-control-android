# TrackerControl for Android

[![Crowdin](https://badges.crowdin.net/trackercontrol/localized.svg)](https://crowdin.com/project/trackercontrol) [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

*If you have missing features or bugs, join the [community](#communities), use the [issue tracker](https://github.com/TrackerControl/tracker-control-android/issues), or contact Konrad directly (<hello@trackercontrol.org>)!*

TrackerControl is an Android app that allows users to monitor and control the widespread,
ongoing, hidden data collection in mobile apps about user behaviour ('tracking').

To detect tracking, TrackerControl combines the power of the *Disconnect blocklist*, 
used by Firefox, and our in-house blocklist is used, created *from analysing ~2&nbsp;000&nbsp;000 apps*!
Additionally, TrackerControl supports custom blocklists.

This approach
- reveals the companies behind tracking,
- allows to block tracking selectively, and
- exposes the purposes of tracking, such as analytics or advertising.

The app also aims to educate about *your rights* under Data Protection Law, such the EU General Data Protection Regulation (GDPR).

Under the hood, TrackerControl uses Android's VPN functionality,
to analyse apps' network communications *locally on the Android device*.
This is accomplished through a local VPN server, to enable network traffic analysis by TrackerControl.

No root is required, other VPNs or Private DNS are not supported.
No external VPN server is used, to keep your data safe! TrackerControl even protects you
against *DNS cloaking*, a popular technique to hide trackers in websites and apps.

TrackerControl will always be free and open source, being a research project.

## Contents
- [Download / Installation](#download--installation)
- [Suppport TrackerControl](#support-trackercontrol)
- [Communities](#communities)
- [Translation](#translation)
- [Highlights](#highlights)
- [Privacy Notice](#privacy-notice)
- [Cookie Policy](#cookie-policy)
- [Credits](#credits)
- [License](#license)
- [Citation](#citation)

## Download / Installation
*Disclaimer: The usage of this app is at your own risk. No app can offer 100% protection against tracking. Analysis results shown within the app might be inaccurate.*

[<img src="https://camo.githubusercontent.com/70bffd8873ab81e1bb0bccc44e488c3a989e3bd5/68747470733a2f2f692e6962622e636f2f71306d6463345a2f6765742d69742d6f6e2d6769746875622e706e67"
     alt="Get it on GitHub"
      height="80">](https://github.com/TrackerControl/tracker-control-android/releases/latest/download/TrackerControl-githubRelease-latest.apk)
[<img src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png"
      alt="Get it on F-Droid"
      height="80">](https://f-droid.org/app/net.kollnig.missioncontrol.fdroid)

[<img src="https://gitlab.com/IzzyOnDroid/repo/-/raw/master/assets/IzzyOnDroid.png"
      alt='Get it on IzzyOnDroid'
      height="80">](https://apt.izzysoft.de/fdroid/index/apk/net.kollnig.missioncontrol)
[<img src="https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png"
      alt="Get it on Google Play"
      height="80">](https://play.google.com/store/apps/details?id=net.kollnig.missioncontrol.play)

There are multiple versions of TrackerControl.

If you're interested in *blocking* tracking, then best download TrackerControl from [here](https://github.com/TrackerControl/tracker-control-android/releases/latest/download/TrackerControl-githubRelease-latest.apk), from [F-Droid](https://f-droid.org/packages/net.kollnig.missioncontrol.fdroid), or from the [IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/net.kollnig.missioncontrol) F-Droid Repository.

If you're interested in *analysing* tracking and generating factual evidence of it (e.g. for research), then choose the version from [Google Play](https://play.google.com/store/apps/details?id=net.kollnig.missioncontrol.play). The analysis results from this version will usually be more accurate.

## Support TrackerControl

There are many ways in which you can support TrackerControl. Here are a few ideas:

1. Join one of the [online communities](https://github.com/TrackerControl/tracker-control-android#communities) and share your ideas on make the app better.
2. Rate the (feature-reduced version of the) app on [Google Play](https://play.google.com/store/apps/details?id=net.kollnig.missioncontrol.play).
3. Help [translate](https://github.com/TrackerControl/tracker-control-android#translation) the app into your language.
4. Tell your friends how to protect their privacy with TrackerControl.
5. Leave a star on GitHub.

Also, you can always reach out to me directly at hello@trackercontrol.org. I deeply welcome and answer every message.

## Communities

1. Telegram Discussion Group: <https://t.me/TrackerControl>
2. Telegram News Channel: <https://t.me/TrackerControlChannel>
3. Matrix Community: <https://matrix.to/#/!htazLJNOSogSGbSPQL:matrix.org?via=matrix.org>
4. /e/ Community: <https://community.e.foundation/t/trackercontrol-a-way-to-neutralize-in-app-trackers/>
5. XDA Developers: <https://forum.xda-developers.com/android/apps-games/control-trackers-ads-t4161821>

## Translation

If you're missing a translation, feel free to contribute here: <https://crowdin.com/project/trackercontrol>.

Contact me at hello@trackercontrol.org, if you're missing a language.

## Highlights
TrackerControl provides
- *real-time monitoring* of app tracking, including destination companies and countries,
- *granular blocking* of app tracking,
- *one-click data requests* as granted under EU Data Protection Legislation, and
- *ad-blocking* using widely available host files.

<p align="center">
    <img alt="Screenshot of app overview" src="fastlane/metadata/android/en-US/images/phoneScreenshots/1.png" style="margin: 0 auto;" height="100%" width="25%" >
    <img alt="Screenshot of trackers details" src="fastlane/metadata/android/en-US/images/phoneScreenshots/2.png" style="margin: 0 auto;" height="100%" width="25%" >
    <img alt="Screenshot of receiving countries" src="fastlane/metadata/android/en-US/images/phoneScreenshots/3.png" style="margin: 0 auto;" height="100%" width="25%" >
</p>

Contrary to similar solutions, this application does not intercept SSL
connections, minimising privacy risks and allowing for usage on
unrooted Android devices.
Only the meta data about network communications is logged, and displayed
to the users.

Download [here](https://github.com/TrackerControl/tracker-control-android/releases/latest/download/TrackerControl-githubRelease-latest.apk).

## Privacy Notice

TrackerControl does not send any personal data off your device.

TrackerControl allows users to monitor the network communications on their
Android device.
This network data qualifies as personal data, but is only processed
locally on the user's device.

If the user consents, TrackerControl contacts the Google Play Store
to retrieve further information about the users' apps.
The app automatically contacts GitHub to check for updates,
which can be disabled from the app settings.
No personal data is ever shared, other than what is strictly
necessary for network communications (e.g. IP address).

TrackerControl uses the ACRA plugin. This is considered to be a 'good' tracker.
It's open-source, and could be used to collect crash reports automatically
to a server–TrackerControl DOES NOT do this. Instead, the user must app report crashes
manually, via e-mail. ACRA shows a dialog to do this in TrackerControl.

TrackerControl itself never sends any personal data off your device. 

## Cookie Policy

TrackerControl does not use cookies of any kind.

The only information saved on the user's device is non-identifying
and strictly necessary for the operation of TrackerControl:

1. a database of network communications, and
2. user settings.

This information is kept on the user's device until app data is
removed manually by the user (e.g. by uninstalling).

## Credits

The development of TrackerControl was led by Konrad Kollnig (University of Oxford). The underlying network analysis functionality is provided by the [NetGuard Firewall](https://github.com/M66B/NetGuard), developed by Marcel Bokhorst.

TrackerControl would not have been possible without the help of many outstanding minds, including Max Van Kleek, Katherine Fletcher, George Chalhoub, Sir Nigel Shadbolt and numerous app testers and friends.

The app builds upon a range of publicly available resources:

*X-Ray Tracker List:* TrackerControl also uses the tracker blocklist by Reuben Binns, Ulrik Lyngs,
Max Van Kleek, Jun Zhao, Timothy Libert, and Nigel Shadbolt from the [X-Ray project](https://www.sociam.org/mobile-app-x-ray), created *from analysing ~1&nbsp;000&nbsp;000 apps*.
This database was released as part of their 2018 paper on
[Third Party Tracking in the Mobile Ecosystem](https://doi.org/10.1145/3201064.3201089).
The original data can be retrieved [here](https://osf.io/4nu9e/).

*Disconnect Tracker List:* TrackerControl integrates the [Disconnect list](https://github.com/mozilla-services/shavar-prod-lists) of known tracker domains,
that is distributed with the Firefox browser.

*Steven Black's Blocklist*: A state-of-the-art blocklist. This is used as fallback, if no company information is known from the other tracker lists. More [here](https://github.com/StevenBlack/hosts).

*Icons:* The app uses icons made by [bqlqn](https://www.flaticon.com/authors/bqlqn) from [www.flaticon.com](https://www.flaticon.com/), and a [rocket icon](https://www.iconfinder.com/icons/1608817/rocket_icon) by Dave Gandy under the SIL Open Font License.

*GDPR Requests:* For the GDPR requests, the templates from the website [My Data Done Right](https://www.mydatadoneright.eu/) by the NGO "Bits of Freedom" were adopted.

*Country Visualisation*: TrackerControl offers to visualise the countries to which trackers sent data. The code was kindly offered by [Takuma Seno](https://github.com/takuseno/GeoMap). To map IP addresses to countries, TrackerControl includes the GeoLite2 database, created by MaxMind, available from <https://www.maxmind.com>.

*ClassyShark3xodus*: TrackerControl allows to detect trackers in the app code. The signatures to do this are taken from [ClassyShark3xodus](https://bitbucket.org/oF2pks/fdroid-classyshark3xodus/src/master/ClassySharkAndroid/app/src/main/res/values/arrays.xml).

*sniproxy*: TrackerControl uses code that has been derived from an early version of [sniproxy](https://github.com/dlundquist/sniproxy) to parse the Server Name Indication (SNI) in TLS headers in accordance with the associated [IETF standard](https://datatracker.ietf.org/doc/html/rfc3546).

*Peter Lowe's Blocklist*: TrackerControl uses the IP blocklist provided by [Peter Lowe](https://pgl.yoyo.org/adservers/iplist.php). Note that this bans anyone from making money from this, see the [license](https://pgl.yoyo.org/license/).

*DuckDuckGo Tracker Radar*: TrackerControl uses some (but not all) [information](https://github.com/duckduckgo/tracker-radar) that lies at the heart of DuckDuckGo's tracking analysis technologies.

## License
Except where indicated otherwise, this project is licensed under [GPLv3](https://www.gnu.org/licenses/gpl-3.0.html).


## Citation

If you use this project as part of your academic studies, please kindly cite the below articles:

```
@article{kollnig2022_iphone_android,
      title={Are iPhones Really Better for Privacy? A Comparative Study of iOS and Android Apps}, 
      author={Konrad Kollnig and Anastasia Shuba and Reuben Binns and Max {Van Kleek} and Nigel Shadbolt},
      year={2022},
      journal={Proceedings on Privacy Enhancing Technologies}
}

@article{kollnig_before_2021,
      title = {{Before and after GDPR: Tracking in Mobile Apps}},
      shorttitle = {{Before and after GDPR}},
      author = {Kollnig, Konrad and Binns, Reuben and Van Kleek, Max and Lyngs, Ulrik and Zhao, Jun and Tinsman, Claudine and Shadbolt, Nigel},
      year = {2021},
      journaltitle = {Internet Policy Review},
      volume = {10},
      number = {4},
      issn = {2197-6775},
      doi = {10.14763/2021.4.1611}
}

@inproceedings {kollnig2021_consent,
      author = {Konrad Kollnig and Pierre Dewitte and Max Van Kleek and Ge Wang and Daniel Omeiza and Helena Webb and Nigel Shadbolt},
      title = {A Fait Accompli? An Empirical Study into the Absence of Consent to Third-Party Tracking in Android Apps},
      booktitle = {{Seventeenth Symposium on Usable Privacy and Security (SOUPS 2021)}},
      year = {2021},
      isbn = {978-1-939133-25-0},
      pages = {181--196},
      url = {https://www.usenix.org/conference/soups2021/presentation/kollnig},
      publisher = {{USENIX Association}},
      month = aug,
}
```

