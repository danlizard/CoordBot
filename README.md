*Coordinates Bot*

---

This bot can find objects by coords and coords of objects.
Functions:

1. *Input:* _<type> longitude <number>_ (where number is between -90 and 90, -90 is south pole) - the bot returns a list of <type> objects with langitude <number>.

2. *Input:* _<type> latitude <number>_ - just like _longitude_.

3. *Input:* _<type> coords <number-1> <number-2>_ (first number is latitude, second is longitude) - the bot returns the <type> object with the given coords, or "nope" if no such object is present.

4. *Input:* <name> (where name is the name of the place) - the bot returns the coords of <name>. If <name> is too big to be described by one set of coords, the bot returns the coords of <name>'s center.