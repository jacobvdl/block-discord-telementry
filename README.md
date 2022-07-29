
# Block Discord Telementry

A simple adblockplus filter to block discord telemetry on browsers.


## Installation
### Install AdBlockPlus
Install [AdBlockPlus](https://adblockplus.org/en/download) (Available on Chrome, Firefox, Opera, Safari, Edge, Internet Explorer, and Yandex Browser)

### Add the filter list
Go to the Advanced tab in the AdBlockPlus settings then click add a new filter list. Put https://raw.githubusercontent.com/jacobvd0/block-discord-telementry/main/filter.txt as the URL then click add. After that AdBlock plus should be blocking discord telementry (You can see this in the blocked ads statistic)
![Example](https://raw.githubusercontent.com/jacobvd0/block-discord-telementry/main/images/filterlist.png)

## FAQ

#### How do you block telementry on the discord app?

You can do this by installing [OpenAsar](https://openasar.dev/) which has settings to block it which are enabled by default (OpenAsar is against discord's TOS as it is a client modification but I don't know of any cases of people being banned for using it).

#### Doesn't the setting in the privacy tab already do this?

No, it Doesn't. You're still sending requests to their "science" url which is used for telementry purposes.

