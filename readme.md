# ow—draft #1

*Is there a reason for why I am here, pushing keystrokes and committing my changes to the server, to the git-master of this project?*

## 0. Intro

This `readme.md` file wants to delineate not how to outline a `readme.md` file—that changes on a basis per basis project—, but rather what does such file represent. It is, in fact, your way to interact with other people on a platform like [github.com](https://github.com). It is, in fact, a way to establish your identity as a worker, amongst other workers.

Such artefact connects you with a larger network of people, machines, and materials. Therefore, it might be useful to reposition the `readme.md` file into a broader context of relations (with your peers, the server and yourself), instead of just conceive it as a mere informational working document.

// § //

Contents:

1. [Ethics](#1-ethics)
2. [Participation](#2-participation)
3. [Peer production](#3-peer-production)
4. [Transparency](#4-transparency)
5. [Maintenance Work](#5-maintenance-work)

## 1. Ethics

Create a new `readme.md` file in which you outline the intentions and objectives of the repository:
* What’s the aim of the project? Are you forking someone else project—thus supposedly improving it—or did you create a fresh new repo?
* How do you expect to use this code? 
* Why are you sharing it over on github? Is there a desire of being part of the/a community or is it simply a backup plan? Or, rather, is it just that you connect using the `git` version control system to github so strongly that you think it’s not possible to use solely `git` on your local machine?

For now, adding a simple description (one-liner!) of the repository is enough. Over time, and especially when you will `push` the final `commit` to at least reach the version 1.0 of the project, you’ll have (a) enough material, (b) hopefully a clearer idea of its purposes and (c) a bit more time to invest in the explanation and/or documentation of the repository.

This first step of creating and taking care of the `readme.md` file brings with itself different implications:
* For whom am I working and why do I want to document all this?
* Who’s watching me doing this? is it for this reason that I am doing it?
* Do I have and/or do I expect an audience?

Depending on your personal reality, you’ll reply to the above questions in a particular way. There after, some other points might be:
* Am I part of a community?
* Do I feel the obligation to share, improve and take part in a general (and particular) discourse or in many? (e.g. forking cool projects that I like in order to improve them and spread them in my circles; feeling the right to take as much free code as possible and use it in my own retributed projects without ethical consequences, since it has been put out there and nobody will ever know).
* What are the dynamics of these communities and more specifically of these artefacts, tools, and means of productions?

This is the realm of the *ethics*: from the moment you delineate your first words into the `readme.md` file, you assume a particular position and therefore contribute to the place where you published such mentioned repository in a specific manner. Outlining the `readme.md` file is the first act to enter the discussion in which other contributors are taking part. This place of discussion is the working place. And it is a working place also when you are developing your own personal projects in your free time mostly for your own interests. The `readme.md` file, hence, becomes the first form of identity able to mediate your work with the interests of other people hanging out in a working environment like [github.com](https://github.com).


## 2. Participation

The `readme.md` file is a personal statement about the work that you’re doing, and it positions itself inside a broader space of actions (e.g. the politics of a community).

Depending on your own interests and needs, it might be that you’re working on a personal project just on your own or, on the other side, you might be collaborating on someone else’s project—which at this point could be considered solely initiated by this someone else, but since the many contributions by other different enthusiastic people, not anymore his *own thing*; it depends.

This passage marks a move from a personal space of action and connected morality, to a broader stage in which ethics have their own importance: you publish your repository somewhere over the internet and you are willing to let other people inspect your project and taking part in it, if they wish so.

The value of the `readme.md` file lies exactly in this: it welcomes others to a possibile conversation. The `readme.md` file is a subjective effort in making readable and understandable what you did or what you just started doing.

*How does this happen*? Here some common actions you can do using git:
* `commit` (one or several changes you made on your files, gathered together and ready to be sent up to the server).
* `push` (up a `commit` to the server).
* `pull` (down from the server the latest updated version of a repository project).

And specifically, for collaborate on a project with other people:
* `fork` (a project repository→cloning it to your own `git` profile in order to have a separated identical copy on which you can work without creating problems with the “original” one).
* `pull request` (a way to ask to the user who made the original repo you are collaborating on, if your changes are okay or not).
* `open an issues` (tracking and solving bugs found throughout the repo you are using).

The words chosen for the verbs to perform these actions and interact, through the system, with other contributors, might result at first a bit intimidating. After a couple of times, anyway, they will give the opposite feeling, one of clarity and self-confidence in one’s own actions.

You `forked` this repository and it is still everything under control even in the scary case you were about to screw up the whole thing, since your were working on your personal copy of that project. `Pull requests` and `issues` are much more effective for a back and forth dialogue than for a simple exchange of new (improved) code. Github instills a certain dose of confidence in the horizontality of such tools—you can either reach out your code buddy or an important developer you admire who’s working at google—without the same possible intimidation that there could be through email or even on twitter. One reason for this is the easiness with which you can talk about something with someone, while editing it at the same time. It’s like being around the same table and play with modeling clay together.

Make sure your `readme.md` file inspires this kind of openness, not necessarily in the statements you are posing, but in the underlying sensation one might have while reading it. Being clear in the kind of resonance that you’d like to have with the community will help you in establishing the type of interaction you will receive back, later on.


# 3. Peer production

`git` is a system that works as an invisibile set of files inside the folder which you decide to use as your project repository.
What it does is to keep track of every change you implement to the files living in that folder: it’s like an invisible layer of pre-punched holes in your timecard. In fact, it’s you the one who decides when to really mark a change, or a series of changes, to the project: what you did, then, is a `commit` to the repository.

In this sense, usually the first file that you create and then `commit` to the repository is the `readme.md` file—it’s not necessary but it usually helps you to at least give a brief description of what’s going on in that repo.

Whenever you make changes to your project, it’s good practice to `commit` those edits to `git`(and often consequently to github), in order to have a log of what has been done up until that point.

> I’m doing this, done, commit; I’m doing this, done, commit; *rhythm*

*How can you help to contribute on someone else’s project?*

1. Make sure you are logged in on one of the many services which let you share git-repositories online (e.g. github, bitbucket).
2. Find a repository which you like.
3. Click on the `fork` button; in this way a copy (duplicate) of the repository will be created inside your own profile and you can immediately start to work on it (the content of the repository has been `pulled` down to your own `git`profile).
4. When you are done with the changes, just `push` it back to the master repository (the original source from which you `forked` it) and ask for a `pull request` session. Other people (*users?*) involved in the repository (from the original creator of the repository to other contributors who forked the project as well) will receive a notification.

It’s then a matter of discussing those changes in the `issues` section of the repository. Exactly here, peers dynamics take place.

Peer production between disparate users happens, instead, in the `pull request` section. After having submitted a new feature to the main project you’re contributing, just whistle to the project manager you’d like to discuss something you made: a back and forth collaboration between the two parts will start (and ideally more people can enter the discussion).

Some people use the `pull request` feature to send themselves things to review:

1. Open a new `pull request` at the end of the day before going to bed.
2. Wake up the day after early in the morning, and while checking your email, read the notification you sent to yourself 6-8 hours before.
3. Go back to work and complete the request.

A technique like this, let someone almost completely abstract her himself from the reality of working alone on a project, gaining a rather new magic level of interaction between two temporal-based version of her himself.

Conversely, the same feature can be intensely used to debate if there’s still one original creator of the project: what happen when the contributors take more and more voice in the discourse of it? How does the original creator feel like, especially when he she moved to the position of project manager? Does she he take the role of the Art Director or of the janitor? Since she he’s still in charge of deciding which `pull requests` to accept and to `merge` to the master project and which not, but at the same time has to possibly manage a mountain of other `pull requests` because the project got quite some popularity, where does he she position him herself?

It is maybe here that the `readme.md` file becomes once again valuable in expressing a clear position on how you prefer to lead the project. The tools are there to keep the processes go smoothly, but you decide on which intensity to keep going.

## 4. Transparency

In designing a better system to remotely collaborate on code-based project, `git`for sure emphasises on asking for clarity and preciseness on the side of the user.
“Add a comment to your commit” might still seem too friendly, meaning an open-ended question, which could turn into a field of experimental poetry or lazy vagueness.
But that `commit` goes up on your `commit history` and will stay there forever, unless you’re gonna delete the whole repository.

So how does one deal with it? Are there any specific writing style, at least suggested ones, to better comply with the tracking system?

Some questions:
* Is it better to capitalise the first letter of the first word of the sentence or not?
* Do you use present tense or past tense (e.g. “fix a typo” or “Fixed a typo”)?

Both points are mostly a matter of the people you are working with in a specific repository, or, even better, just up to you if the project is one of your personal ones. Then, anyway, deciding upon a specific style will enhance your way of working. How would you react in reading, after a couple of days, that you “Fixed a typo” and now there is still a bug due to that edit? Would it not be better if, instead, you would have opted for the “fix a typo”, for the here and now? In doing so, all the future problems might still be seen as in the realm of possibilities, since the present tense gives a feeling of an active ongoing project, not of an action done and archived in the past.

As you’re building a micro public space, what’s your policy on the element of discoverability and surprise? Though ornamenting a `readme.md` file on github is probably not the smartest of choices, since it’s the first text you see when you open up the project page, other techniques like disseminating in some of your other working files small ascii art drawings (such as in the `style.css` file), might result in an act of pleasure for the ones stumbling upon it.

Keeping a rhythm within your project makes visibile certain patterns: how much time you `commit` to your repository and what’s your level of health about it. Meaning, `have you ever curse inside the comment section of one of your commit?` That’s an example. Another sign is the level of responsiveness you are able to keep up in replying to open `issues` and `pull requests`. Being transparent is a sign of showing up and being present when it’s needed, not of sharing also the most useless piece of personal annotation (cfr. “for the sake of it”).

Maintaining well-defined purposes on your `readme.md` file and adopting pro-active behaviours when people start to play with your code is a nice way to back up your credibility and self-assurance on the projects you take on.

## 5. Maintenance Work

> It is clear, when you clean it, when you take care of it, how shiny it is.

Setting up a project and keep it in order, to make it work smoothly, drains your energies. Even more if you have to add a layer of sociality on top of it and let your own small baby go in someone else’s hands. It hurts and it’s rewarding.

Think of the `readme.md` file as the blueprint of your house, its internal rules, and the way you would live in it were you on your own, with your friends or with people you met the other day.

Moreover, it needs a constant maintenance work. Keep it tidy and up-to-date. Change your policies over time when the circumstances ask for it. Don’t be ashamed to undue what you wrote last week, a manifesto on the internet is stronger when it moves. You are not deceiving anyone, since your `commit history` speaks clear for your actions: did you say something completely different a month ago which now is causing quite some problems to a few people using your project? It’s as simple as going back in time and check how that same paragraph was formulated, or why you deleted it abruptly.

Putting at disposal your code means you have to take care of it three times more:

1. Make it readable for the outside.
2. Being available for changes and collaborations.
3. Keep on work on it, it has a user-base now.

°_° 

Now.

Clear on your mind: don’t make sociality winning over productivity and don’t make productivity winning over sociality. Don’t think about the market; think about the permanent immanent movement aiming slightly upwards. Keep that thing moving on.