# Lab8-Starter
How are graceful degradation and service workers related?
- Graceful degradation and service workers are related because both aim to keep websites functional even when things go wrong. Service workers use the principle of graceful degradation by initially assuming a strong internet connection, but try to maintain functionality when the connection is slow or unavailable. They do this by using previously cached content, allowing users to continue using the site. For example, if a live request fails, a service worker can provide an older, saved version of the content. This ensures the website remains usable even offline or with a poor connection, instead of simply failing. Service workers help websites remain reliable under less-than-ideal conditions.

[Link to website](https://emngi.github.io/Lab8_Starter/)
![Progressive Web Apps Screenshot](/Lab8_Starter/assets/images/PWA.png)
