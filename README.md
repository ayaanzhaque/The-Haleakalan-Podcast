[![Netlify Status](https://api.netlify.com/api/v1/badges/b32dac90-12bd-4a6d-ac9c-bd70d0039be7/deploy-status)](https://app.netlify.com/sites/thehaleakalan/deploys)

# [The-Haleakalan-Podcast](http://thehaleakalan.tech)
Website for "The Haleakalan Podcast" by the Haleakala Empire

"The Haleakalan" is a podcast that provokes critical thinking about mentally stimulating world issues, life events, and really anything... hosted by 7 high school students.

Spotify: https://open.spotify.com/show/1qhyTJiMHELF96Kc32syPA

Youtube Channel: https://www.youtube.com/channel/UC0RqUV92ON_4kUMqXMLEGyw/featured

Subscribe: https://www.youtube.com/channel/UC0RqUV92ON_4kUMqXMLEGyw?sub_confirmation=1

Featured in the Saratoga Falcon: https://saratogafalcon.org/content/juniors-launch-podcast-tackling-range-intriguing-topics

## Youtube to Anchor.fm Github Action

Instructions for using Youtube to Anchor.fm Github Action Automation, which allows for automatic upload of Youtube Podcast Episodes to Anchor.fm.

Code for Github Action: https://github.com/ayaanzhaque/youtube-to-anchorfm-haleakalan

**Edits must be made in this file**: https://github.com/ayaanzhaque/youtube-to-anchorfm-haleakalan/edit/master/episode.json

To upload video, open and edit [`episode.json`](https://github.com/ayaanzhaque/youtube-to-anchorfm-haleakalan/edit/master/episode.json) by changing the `id:` to the new Youtube video ID. To get Youtube video ID, press the share button, and copy the ID after the .be/. Then press commit changes.

To view status of upload, click [here](https://github.com/ayaanzhaque/youtube-to-anchorfm-haleakalan/actions). Wait 3-5 minutes for upload to finish. 

To update Anchor.fm account credentials, go [here](https://github.com/ayaanzhaque/youtube-to-anchorfm-haleakalan/settings/secrets/actions). 
