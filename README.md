HowTO Use:
----------

1. Build "phone book"
2. Send message

HowTO build phone book:
-----------------------

You can build phone book in two ways. In both you need to recive email from
inReach device to get response link[RES_LINK] like:
https://inreach.garmin.com/textmessage/txtmsg?extId=xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxx&adr=cb1986ster%40gmail.com
So if you have it, go to terminal and do :

> $ inreach-link-to-guid "https://inreach.garmin.com/textmessage/txtmsg?extId=xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxx&adr=cb1986ster%40gmail.com"

> Looking for GUID for link...

> yyyyyy-yyyy-yyyy-yyyy-yyyyyyyyyy

> $ inreach-pd name yyyyyy-yyyy-yyyy-yyyy-yyyyyyyyyy

or

> $ inreach-pb-from-link name "https://inreach.garmin.com/textmessage/txtmsg?extId=xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxx&adr=cb1986ster%40gmail.com"

> Looking for GUID for link...

> Got yyyyyy-yyyy-yyyy-yyyy-yyyyyyyyyy

> Saved lr => yyyyyy-yyyy-yyyy-yyyy-yyyyyyyyyy

Now you read to easy sending message.

HowTO send message:
-------------------

First build your "phone book", it will help you a lot!
Sending is easy run inreach, then provide adres to send message(name from pb or full GUID) and message.
