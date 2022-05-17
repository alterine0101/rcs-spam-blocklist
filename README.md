# Collaborative blocklist for RCS spams

This repository contains a set of number blocklists which abused Google's RCS Business Messaging API for spam purposes.

This repository is built as a response to an [ongoing attempt](https://twitter.com/ishanagarwal24/status/1526200768398692353?s=20&t=QrVhfq7Ak5Xb7LVA8Jp36A) in pushing personal loan advertisements towards millions of Indian users through the use of RCS. Since RCS itself utilizes common Internet protocols compared to traditional (GSM) SMS protocols, these messages will still be delivered to the user's device even under the Airplane Mode (with standby Internet connection) and with original SIM cards removed!

Our defense heavily rely on **vCard**, a contact interchange file format which dates back into the '90s. Since vCard files are already supported in Android since its very beginning, and vCard file are just regular plaintext file, we can track a list of blocklisted numbers into Git and publish them for the peace of mind.

By publishing vCards to the public, everyone can activate the same blocklist by these three little steps:

1. Downloading these vCards
2. Importing them into Contacts
3. Block the recently-imported contact directly through the app

And let Google Messages respect the blocklisted contacts easily.

## License

We decided to release this dataset under the [CC0](https://creativecommons.org/share-your-work/public-domain/cc0/).
