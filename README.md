# osu-BeatmapNotifications
Chrome Extension for newly qualified/ranked/loved beatmaps

Extension, the pitch:

Be able to see new qualified, ranked and loved maps at the date that the individual is opening the extension’s tab. As the user is in a Chrome tab, the extension would update it’s data from the server’s database which is created thanks to pull requests to the osu!api, and he would get a notification *(unless he has filtered content)*

How is the extension going to be created (current resources):

https://github.com/heyimstat/osu-BeatmapNotifications
https://github.com/oamaok/ezpp/tree/master/src/static
https://developer.chrome.com/apps/first_app
We expect the actual extension to be an aggregation of HTML, CSS (or SCSS) and JS. The extension seems to be typical web development.
For the extension’s purpose to be fulfilled, we need to create a database within a server that the extension would be able to pull data from. This database (mySQL) would be created and updated thanks to osu!api pull requests *(in the format : https://osu.ppy.sh/api/get_beatmaps?since=2018-07-18&k=keyredacted )* and the data would be filtered with the use of PHP
UI and UX will be wireframed and prototyped before coding the HTML/CSS/JS part.
The proof of concept *(database based on osu!api)* is necessary before engaging in any relevant designing

What are features that are expected to happen within the first version of the published extension?:

We expect the end user to be able to:
See the current date’s beatmaps *(UTC 00:01 to UTC 23:59)*
Be able to switch through qualified, loved and ranked on the extensions main page
Receive notifications upon qual/love/ranking
What are features that are expected to happen within further development of the extension?
See past dates beatmaps *(on a weekly basis for database load purposes?)*
Be able to filter notifications *(ex: only get notifications for Sotarks)*

Future of the project:

The idea behind the proof of concept is being able to create multiple projects (webapp/mobileapp) out of the working database
This would let us, as developers be able to involve ourselves into multiple areas of development with a purpose.
