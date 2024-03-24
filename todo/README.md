# TO-DO

This is a minimal example of creating a "to-do" list in Emissary. Many obvious features have been excluded in order to focus on the core features.

This list is also its own [ActivityPub Actor](https://www.w3.org/TR/activitypub/#actors) and can be followed by other users.  This actor is set to [Announce](https://www.w3.org/TR/activitypub/#announce-activity-inbox) all "child" items as they are created and updated.  In this case, it is individual to-do items are boosted to follower's inboxes.