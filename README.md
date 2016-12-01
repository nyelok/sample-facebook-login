# sample-facebook-login

The facebook example on their site is a bit confusing. I found this one to be a bit more
straightforward. With that said, I don't think there is anything wrong with the first one.
It was just confusing. So here is a working example. It does use an activity. 

The only mistake that I made with this one was in the AndroidManifest file make sure
to add the meta-data tag INSIDE the application node. If you add it outside, you will get
a NPE trying to pass the app id to fb.

![logging in](https://www.evernote.com/l/AGUWGMN9biFEApKT1u1UbumL5dVYoIJpmgE)
![logging in](https://www.evernote.com/l/AGWfezgbTXhFn4e9gZEMt-moBem-46bYIMY)

*note: This example also uses 4.5 of the fb sdk
