# Steve Crusader versus the Earth

## Introduction

Welcome to Steve Crusader versus the Earth! Any resemblence this may have to
the popular comic franchise Scott Pilgrim versus the World by Bryan Lee
O'Malley and (and the cult hit movie) is completely intentional.

Throughout your journey as Steve Crusader, you will modify the files:
- Members.txt
- Rowena.txt

You will create the files:
- Setlist.txt OR Album.txt

You won't modify the files:
- README.md (this file)

Let's get started!

## Setup

Do this if you haven't already:
- Pair up.
- Fork this repo (ONE person).
- Clone your fork to local (BOTH people).

## Start a band

First, you and your partner want to start a rock band! Because you'll both be
working side by side on some songs, why don't you both make new branches to
work on?

- BOTH of you make a new branch named with your first name.

## Write a setlist and first album

You'll need some songs to play as a band! Decide who's in charge of writing
the setlist, the list of songs you'll perform when you play live in restaurants
or bars, and who's in charge of writing the songs for the first album, which,
no doubt, will be fire.

- ONE partner writes the setlist, the OTHER writes the first album.
- Create Setlist.txt or Album.txt, respectively.
- Fill it in with a list of songs. They can either be real songs (covers) or
totally made up songs! It can be as long (or short) as you want.
- Add, commit, and push your changes to your respective remote branches.
- You might have to follow git's directions to push the current branch and set the remote as upstream.

## Woo Rowena Blossoms with a song

You see this amazing girl at a party that night! Her name is Rowena Blossoms
and it's love at first sight. You can totally see a future with her, like, with
jetpacks. She knows so many things that you didn't; apparently, bread makes you
fat! She's so cool and you know that you have to woo her with a song of your
own composition!

- Open the file Rowena.txt.
- Edit it so it's not so awful.
- Add, commit, and push your changes to your respective remote branches.

## Nope, that didn't work! Backtrack!

You stride up to Rowena, confident and ready to win her love with a song you
wrote yourself that totally doesn't blow! Except it does because both you and
your partner sing your songs to her at the same time. You both go all :( and
you wish that that hadn't happened! But because this is Steve Crusader against
the Earth, you can just load a previous save or reset to the last checkpoint
or what have you.

- Find the commit hash of your previous commit where you edited Rowena.txt.
- Copy that commit hash.
- Revert that commit using the commit hash you copied.
- Push to remote.

## Regroup as a band

Whew, that was a close call! Good thing you haven't ruined your chances with her
forever. That would have been bad. Anyways, now that all the heavy songwriting
is done, you regroup as a band and share what you've written!

- Merge your branches into master and push to the remote repo. Remember that
you need to checkout to master before you merge your branch into master!

## Enter members

Your first gig's coming up! Before you perform, you need to settle who's
playing what role in the band. Unfortunately, the owner of the venue has given
you BOTH a form to fill out with the names and roles of members.

- Checkout to your own branch (the one you made earlier).
- Open the file Members.txt in the text editor of your choice.
- Follow the directions, saving when you're finished.
- Add and commit your changes. Merge your branch into master when you're done.
- When the second person merges their branch, there should be a merge conflict!

Oh no! It looks like there's a conflict as to who does what in the band. Work
with your partner to resolve it. Stay together as a band!

- Resolve the merge conflict together by doing the following:
- A file with merge conflicts will have the merge conflicts marked like
```
<<<<<<< Your changes
the content on your branch
=======
the content on their branch
>>>>>>> Their changes
```
- Agree on changes and delete all the `<<<<<<<`, `=======`, and `>>>>>>>` lines added by Git.
- Don't forget to add the file to mark the conflict as resolved!
- Commit and push to remote.

## Woo Rowena Blossoms with a song (round two!) as a band!

Luckily for you, Rowena Blossoms is at your first concert and sees you on stage
rocking out, and she's really impressed by how far your songwriting skills have
come and how cool you are in general! Even the record label agent sitting next
to her is impressed and immediately wants to sign you guys! It looks like
things are turning around for you!

- Make sure your remote repo is all up to date and all your latest changes are
pushed.
- Go to GitHub and open a pull request on the original repo you forked from
at the very start of this lab (steve-crusader-against-the-earth).

## Fight her six malicious prior lovers

This part is all up to you. Good luck!

## Conclusion

I hope you enjoyed Steve Crusader versus the Earth and I hope you learned
something from today's talk on Terminal and Git usage. Seriously, Git is
really cool and an absolute lifesaver in hackathons and even on programming
homeworks. But I'm sure you don't need me to tell you that.

Comments? Questions? Complaints? Medical bills from being beaten to a pulp
by Rowena Blossoms's six bad previous romantic interests? Email me at
jzhanson@andrew.cmu.edu (please don't actually send me your medical bills).

