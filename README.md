# playmaker

## Briefly
Uploads specified spotify albums as playlists to your youtube music account.

Is an Azure function app (python), which using a timer trigger functino to publish spotify albums specified in \playmakerpy\spotifyalbums.py to your youtube music account specified by the channel_id in local.settings.json (private/specify your own).

When published to the azure cloud (as a function app) the function "timer" runs everyday at 5 am (UTC) specified by the CRON expression in  \timer\function.json.
