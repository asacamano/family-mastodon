# family-mastodon
My notes about exploring Mastodon to use as a family server.

## Raw setup notes

* Got a plan with masto.host.
* Followed their setup process.
* Imported a blocklist from https://codeberg.org/oliphant/blocklists - see also https://writer.oliphant.social/oliphant/the-oliphant-social-blocklist
* Under `Preferences -> Administration`:
    * Go to `... -> Server Rules`, and set up your rules. You can see [examples](https://mastodon.social/about) at the big instances. You should also think about the [Mastodon Server Covenant](https://joinmastodon.org/covenant). I went for short and simple: be kind to everyone, the mods are always right.
    * Go to `... -> Server Settings -> Branding page`, and fill it out, pick a headerimage, etc.
      * I wanted a specific email (e.g. admin@example.com) and not my personal email as the admin email (but then I forwarded it to my main email)
      * I put Elephants from [Pixabay](pixabay.com) in the thumbnail.
    * Under `... -> Server Settings -> About`, add a bit more information, and then chose who you want to share your domain blocks with, and if you want a custom privacy policy.  I chose to keep the default, but I think I might need to revise that to allow younger family members.
    * Under `... -> Server Settings -> Registration`, you probably want to approve signups, both to keep it to the family, but also to avoid bots and trolls.
    * Under `... -> Server Settings -> Discovery`, I went for privacy-preserving within the local server:
        *  Check "Enable trends", and "Allow trends without prior review", but not "Use trends as the landing page".
        *  Check "Opt users out of search engine indexing by default" - if users want to be more plublic, they can choose to do so.
        *  Uncheck "Allow unauthenticated access to public timelines" - again, keep things private to the local server.
        *  Check "Publish aggregate statistics about user activity in the API" and "Publish list of discovered servers in the API" - as these are fairly privacy-friendly options that are good for the Mastodon community as a whole.
        *  Check "Enable profile directory" - this lets users chose whether they want to be discoverable.
        *  I set up an "announcements" account to pin for server related announcements - even though Mastodon has an  announcements feature. 
    *   
      
