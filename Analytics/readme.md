This Sentinel Analytics rule will detect when a previously ingested source of logs disappears.
It evaluates if no new logs has been ingested to a log analyics table in the last 6hrs.
This is dynamic, meaning it will adapt when you add new log sources.

Be aware: This rule requires configuration as alerts show in your environment. 
If you do not expect to see data written to a table for 6 hours or more, be sure to exclude the table in the rule logic.
A few common sources to exclude are included.

Feel free to use this, but don't credit me.
