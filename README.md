# dunst-notification-history
Get notification history from dunst daemon.
Number of notifications displayed depends on history_length variable in dunstrc

### Warning
Since dunst saves notification time with monotonic timestamps, if you suspend
your computer (or do something that otherwise messes with monotonic time), the
notification times display will be (very) incorrect.

Currently only supports UTC time (no timezones or DST).
