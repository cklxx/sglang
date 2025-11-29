# Issue #14070 Debug Re-try Prompt

Here is a suggested English reply for the reporter after adding the extra debug logs:

---
Hi! We’ve added extensive debug logging around NixlKVSender (send, poll, abort, destructor, and handle-release paths) to pinpoint remaining leaks. Could you please rerun your repro with the latest branch and share the logs? The new log lines include room IDs, handle counts, and release progress so we can see exactly where cleanup stops. Thanks!
---
