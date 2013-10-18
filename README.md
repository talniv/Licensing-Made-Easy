Licensing-Made-Easy
===================
**First, what I suggest, then why I think it is possibly a good idea and lastly my thoughts about implementation (including three very very very lame graphics, which I hope don't put you off this)**

So the gist, no pun, is this: It seems to my noob eyes that it may be the right thing to do to move the license picker to the account settings page, and have whatever license/copyright users choose over there apply to all of the account holder's subsequent repos, unless they opt-in to something else for a specific repo. As part of that setting include attribution info and populate it by default with (c), user email, or for enterprise, company name, etc. Then, either make it freely editable, or, for example for enterprise account, make it freely editable to some entities only.

Even though It's true that the users aren't required to take this step for every repo - because we choose copyright (none) for them - by simply following the GH choice they are actually choosing, even if they don't know it, and that does happen for every repo. 

*1. this simplifies the repo-creation process (one less step)*
Most users have some preference - weak or strong - for their license choice, MIT, GPL, Apache, None (copyright), a private license, or whatever. This means that letting them to choose that license at the account level, and then have that as their default from which they can opt-in for particular repos if they need do, just seems to mean that they will have one less step to take when creating a repo.


*2. I think it fulfills enterprise-specific wishes*
Correct me if I am wrong, please, but to my understanding, companies have an intellectual property policy, and would often not like the idea that every contributor is license-king, or has complete freedom of decision. That might make trouble. It just seems to make sense to give them what they want.

*3. right now, copyright (None) is the GH default...*
The way things are right now is actually making copyright the default for new repos, which to me kind of smells of  copyright restriction advocacy. This way, users who care very little, and therefore don't bother to define a license for every repo just end up choosing plain vanilla copyright, and not necessarily because they want to.

Granted, that doesn't iterate the need for a default for the account settings, and that decision may still very well be copyright or even a specialized license for enterprise. I realize that this is a separate discussion.

*4. account creation is when users have a reason to self-educate about intellectual property and licenses. It's not the repo creation stage.*
Don't you think that when users are creating a repo they just want to get something done? If that's true, this does not sound like the best time to start try understand things about rights, law, what will happen to the code under different settings, etc. And if there is ever a good time, it's when you create an account.

*5. it might help cut down on license interoperability-induced headache*
It seems obvious that when a developer chooses a license for every repo, if she doesn't care very much about one license, she might choose a different one every time, unaware of the ensuing trouble this might strew… then she might try to :ship: permissive-restrictive.

*6. it is a way to have one license or other apply to GISTs too...*
Am I wrong about this? Right now the users writing GISTs don't really have a choice (i.e., they choose copyright). If I'm right, isn't kind of a shame that they are using the most restrictive, often without even knowing it and that collaborators don't know that? If that is true, this is a way to make sure the have one consistent choice for an account holder, which seems the right way to go. 

*7. implementation points + the lame graphics promised at the top*

![screen_shot_2013-10-17_at_2 22 26_pm](https://github-team.s3.amazonaws.com/uploads/general/Screen_Shot_2013-10-17_at_2.22.26_PM.png)

![screen_shot_2013-10-17_at_2 22 51_pm](https://github-team.s3.amazonaws.com/uploads/general/Screen_Shot_2013-10-17_at_2.22.51_PM.png)

![screen_shot_2013-10-17_at_3 09 56_pm](https://github-team.s3.amazonaws.com/uploads/general/Screen_Shot_2013-10-17_at_3.09.56_PM.png)

This obviously leaves wide open many many issues: What to do, for example, if the user changes the license in the account setting or the attribution? Personally I think that the best solution would be similar to the way users are warned about the repercussions of switching from "private" to "public".  Anyway, the point is that there's a lot more thought that needs to be put into this.

I would love to be told if this makes sense in even the most remote way. 
