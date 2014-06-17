Pidgin-unsent_messages-patch
============================

The first patch adds a new feature called unsent messages.
It keeps a track of all the unsent messages (messages typed but not sent). If the user happens to close the chat window that has the unsent messages then a warning message is shown accordingly.
The second change: On hitting a given search in the conversation log the total number of searches found in the present conversation log is displayed. However, if no match for the given search is found then "No match" is displayed. On an empty search field the name of the log along with its date is then displayed.
The third change highlights the quick find search results. Also on hitting a new search the previous highlights are unmarked accordingly.
