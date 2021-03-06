# Open Source Project
___
***Author***: Olivier Perdaens \
***NOMA***: 23821600 \
***DATE***: 2020 \
***Open Source Project***: [NextCloud](https://github.com/nextcloud/server)
___

## Project
### Domoticz
At first, my choice was to work on the [Domoticz](https://github.com/domoticz/domoticz) open source project, since I use it for personal project home. \
I spotted a bug in the configuration of the "AccuWeather" daemon, but after setting the developpement environement up, I realised that this bug was already fixed, but simply the fix was still not merged to the stable version of the software. I had to find another project ...

### NextCloud
It took me a while to find a project in which I'm interested in since I was looking for a project useful to me and where "simple" issues where "available".

NextCloud is an open source plateforme to handle file storage on a dedicated host (raspberry pi, own server, ...). The software propose a lot of functionalities such as rights management, shared folder, third party applications, ...

#### Issue
After read lot of issues, I found [this issue](https://github.com/nextcloud/server/issues/23849). The explanation of the issue let me understand that it was a small issue in the css configuration and I'm quite confortable with it since I create website in my free-time.

Some icons in the navigation-bar of the setting's page were vanishing when the "nav-item" text overflows.

#### Submitting my contribution
After modifying slightly the source code (3 lines changed), I introduced a [pull request](https://github.com/nextcloud/server/pull/24378). The modifications I made were solving the issue but changes slightly the visual aspect of the setting's navigation-bar.

#### Reviews of my contribution
The little change in the visual aspect of the navigation-bar was mentioned by one of the reviewers of my pull request.
So I shortly explained why I had to make this changes and promise to dig deeper to keep the fix of the icon's problem and still keep the initial visual aspect.

#### To Be continue
At this time, I'm still working on this slight visual change. And I'll update this report as soon as updates occurs !
