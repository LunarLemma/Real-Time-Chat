# Real-Time-Chat
Hey there, for now I am just building a MVP.
---
This simple application aims at implementing websockets to support real-time communication. This chat has a few scope.
* An admin-user can create a new chat session.
* It controls few properties of the chat, such as
    * Name.
    * start_time.
    * chat(active/inactive).
    * slow_down_chat(rate limiting).
    * multiple users can join the room and send messages.
    * the messages have an upvote feature.
    * If chat message reach more than x upvotes, move it to a priority section.
    * If chat messages reach more that y upvotes, send admin an alert to interact.

This code is probably, just the backend for now.