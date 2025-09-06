Supposed to be able to do this: (What is in the TRAINING_WHEELS)

"
- League Page is constantly being updated and improved. Check back on your repo periodically and whenever you see the `fetch update` button, click `fetch update` and commit the changes to get the upgrades
> ![fetch upstream](https://storage.googleapis.com/nfl-player-data/fetchUpstream.jpg)

<br />

- Another way to know there's an update available is if you see the following notification on your League Page:
    > ![update notification](https://storage.googleapis.com/nfl-player-data/updateNotification.jpg)
    
    <br />

    - To see what's changed in the newest updates (bugs fixed, features added, etc.), check the [CHANGELOG](https://github.com/nmelhado/league-page/blob/master/CHANGELOG.md)

    <br />

    - **If you first created your league before August 7th, 2021**, you may encounter `merge conflicts` when trying to fetch upstream.
        - In that situation (if you are new to coding), copy the contents of your managers page and your homepage text and delete your repo. Re-follow this guide and re-deploy your page.
        - There should be **NO merge conflicts going forward**.

    - **WARNING:** There may be merge conflicts in `package-lock.json`. *This should be very rare.*
        - Follow these instructions to [resolve the conflict](https://docs.github.com/en/github/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github). For the most part, you'll most likely want to keep the changes from master (the second change)
"

What I ended up finding work was:
1. Open Terminal in VS Code in the Remote Repository
2. Type "git fetch upstream"
3. Type "git checkout master"
4. Type "git merge upstream/master"

This should import all of the changes that has been made by the original author of the website. It should show all of the changes, review them and see if it changes any of the updates I made for our individual league.

Should also show conflicts (if any), pick which one you want.

After go through and confirming all of the changes, in Source Control of VS Code add a message (if not already populated) and click Commit.

A Pop-up with happen about staging, click Yes. Then click Sync Changes. This should update GitHub and make everything active. 