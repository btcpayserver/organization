# BTCPay Server Organization

Open-organization, meetings, calendars, project management.

## Calendar

Our [calendar](https://raw.githubusercontent.com/btcpayserver/organization/calendar/events.ical) (an .iCal file) includes upcoming calls.
Qualified issues are automatically added to the calendar, which you can then subscribe to via your favorite calendar tool.

- Copy this URL: [https://raw.githubusercontent.com/btcpayserver/organization/calendar/events.ical](https://raw.githubusercontent.com/btcpayserver/organization/calendar/events.ical)
- In Apple Calendar (desktop), use `File -> New calendar subscriptions`
- In Google Calendar (web), click the small `+` icon next to `Other calendars` in the sidebar and select `From URL`
- Paste the URL and save. New events (if there are any scheduled) should show up right away
- In Thunderbird (desktop), `New Calendar` > `On my network` > `iCalendar (ICS)` and paste the [calendar link](https://raw.githubusercontent.com/btcpayserver/organization/calendar/events.ical) in the location field.
- Calendar tools regularly reload subscribed calendars for updates. How often this happens varies by tool

There are two requirements for an issue to be included:

- The issue needs to include a `UTCTime` meta property following this format: `UTCTime: 2020-10-14 9:00 UTC -7`
- A maintainer needs to add the `call` label to the issue (this prevents spam)
- The calendar auto-updates whenever a new issue is created, or an existing issue is edited

- - -

Thanks to the [Bitcoin Design Community](https://github.com/BitcoinDesign/) for the [inspiration](https://github.com/BitcoinDesign/Meta). 🙏
