# The impfstoff.link API has been taken offline - this does not work anymore!

## impfresher-berlin
Quick &amp; dirty impftermin checker for doctolib

Absolutely no responsibility on getting it to work on your machine.

Using the impfstoff.link API & a free sound fx.
https://impfstoff.link/

The page will request open appointments every 15 seconds & keep a log of active Termins.
When a Termin oppertunity opens up in one of the vaccination centers - it will show the link, play a sound & open a tab in doctolib.

Very basic, no security or specials features - there are many better ways possible.
But this works for me.

Tips : 
- make sure you accept popups
- You should run a CORS changer chrome plugin to be able to read from the API
- For security reasons - run it on localhost so you can limit this to this page only.
- Disabling CORS in general is a bad idea & a security risk.


If you have any improvements just get it on the hub.
I have used no node or other framework, just very basic html & javascript to get te job done & save me some time refreshing doctolib.

=> The API fetching data is not mine, just using what is out there.
Check https://github.com/guicheffer/impfstoff.bot for a bot you can run on twitter/telegram.

Also note - at the moment there are hardly any appointments available.
