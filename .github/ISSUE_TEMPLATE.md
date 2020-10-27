---
title: Error
assignees: {{ payload.sender.login }}
labels: bug
---
Someone just pushed, oh no! Here's who did it: {{ payload.sender.login }}.
action is {{ tools.context.action }}
event is {{ tools.context.event }}
payload is {{ tools.context.payload }}