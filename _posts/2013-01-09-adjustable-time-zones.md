title: At last: adjustable local timezones
date: 2013-01-09

Habitbot now lets you adjust the timezone you're in and will do correct date calculations accordingly. This should let international users use Habitbot and have due dates for goals be counted correctly.

The current default timezone for all users is GMT-8, the timezone of the west coast of the USA, because most of the users are from the USA.

If you want to adjust the timezone, you can do so at any time and it should do the right thing, adjusting the internal date at which you have until to do a task for the local time in that timezone. This is accessible from a new link that appears in the navigation, which takes you to the usual dropdown list of timezones you can select from:

<img src="http://i.imgur.com/4aKNl.png">

<img src="http://i.imgur.com/wXo6b.png">

Due to how dates are stored, you will have to recheck off any goals you've completed for that day.

Habitbot should have shipped with this, so this is partly a bug fix.

Implementing this required significant internal changes to how dates are handled. If you have any problems, please tweet at me at <a href="http://www.twitter.com/fearofcode">@fearofcode</a>.
