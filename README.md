#埃里克·史蒂文·雷蒙德的文章《How To Ask Questions the Smart Way》
# How To Ask Questions the Smart Way
 [Eric Steven Raymond](http://www.catb.org/~esr/)

Thyrsus Enterprises

     <esr@thyrsus.com>
    

Rick Moen

    <respond-auto@linuxmafia.com>
    

Copyright © 2001-2006 Eric S. Raymond and Rick Moen

Table of Contents:

Translations
Disclaimer
Introduction
Before You Ask
When You Ask
Choose your forum carefully
Web and IRC forums directed towards new users often give the quickest response
As a second step, use project mailing lists
Use meaningful, specific subject headers
Make it easy to reply
Write in clear, grammatical, correctly-spelled language
Send questions in accessible, standard formats
Be precise and informative about your problem
Volume is not precision
Don't claim you've found a bug
Grovelling is no substitute for doing your homework
Describe the problem's symptoms, not your guesses
Describe your problem's symptoms in chronological order
Describe the goal, not the step
Don't ask people to reply by private e-mail
Be explicit about your question
Don't post homework questions
Prune pointless queries
Don't flag your question as "Urgent", even if it's for you
Courtesy never hurts, and sometimes helps
Follow up with a brief note on the solution
How to Interpret Answers
RTFM and STFW: How to tell you've seriously screwed up
If you don't understand...
Dealing with rudeness
On Not Reacting Like A Loser
Questions Not to Ask
Good and Bad Questions
If You Can't Get an Answer
How to Answer Questions in a Helpful Way
Related Resources
Special Note for FAQ List Maintainers and Webmasters
Acknowledgements
## Translations

Translations: Bahasa Indonesian Brazilian-Portuguese Chinese Czech Danish Estonian Finnish French German Hebrew Hungarian Italian
Japanese Polish Russian Serbian Spanish Swedish Turkish . If you want to copy, mirror, translate, or excerpt this essay's master copy,
please see Eric's copying policy (which I, Rick Moen, endorse — this local copy, used for pending revisions intended to be re-merged,
and to indulge my preference for Commonwealth spelling and for sundry pedantic usages, exists pursuant to my copyright title to our
joint work, and may not be mirrored).

There are quite a few authorised (i.e., compliant with the copying policy) translations and mirrors, as well as a large number of
unauthorised mirrors (either altered, outdated, or both). The latter are not OK.

## Disclaimer

Many project Web sites link to this document in their sections on how to get help. That's fine, it's the use we intended — but, if
you're a webmaster creating such a link for your project page, please display prominently near the link a notice that we are not your
project's help desk!

We've learned the hard way that, without such a notice, we will repeatedly be pestered by idiots who think having published this
document makes it our job to solve all the world's technical problems.

If you're reading this document because you need help, and you walk away with the impression you can get it directly from the authors,
you are one of those idiots. Don't ask us questions: We'll just ignore you. We're here to show you how to get help from people who
actually know about the software or hardware you're dealing with — but, 99% of the time, that will not be us. Unless you're certain
one of the authors is expert in what you're dealing with, leave us alone and everybody will be happier.

## Introduction

In the world of hackers, the kind of answers you get to your technical questions depends as much on the way you ask the questions as on the difficulty of developing the answer. This guide will teach you how to ask questions in a way more likely to get you a satisfactory answer.

Now that use of open source has become widespread, you can often get as good answers from other, more experienced users as from hackers. This is a Good Thing; users tend to be just a little bit more tolerant of the kind of failures new users often have. Still, treating experienced users like hackers, in the ways we recommend here, will generally be the most effective way to get useful answers out of them, too.

The first thing to understand is that hackers actually like hard problems, and good, thought-provoking questions about them. If we didn't, we wouldn't be here. If you give us an interesting question to chew on, we'll be grateful to you; good questions are a stimulus and a gift. Good questions help us develop our understanding, and often reveal problems we might not have noticed or thought about otherwise. Among hackers, "Good question!" is a strong and sincere compliment.

Despite this, hackers have a reputation for meeting simple questions with what looks like hostility or arrogance. It sometimes looks like we're reflexively rude to new users and the ignorant. However, this isn't really true.

What we are, unapologetically, is hostile to people who seem to be unwilling to think or to do their own homework before asking questions. People like that are time sinks: They take without giving back, and they waste time we could have spent on another question more interesting and another person more worthy of an answer. We call people like this "losers" (and, for historical reasons, sometimes spell it "lusers").

We realise there are many people who just want to use the software we write, who have no interest in learning technical details. For most people, a computer is merely a tool, a means to an end; they have more important things to do and lives to live. We acknowledge that, and don't expect everyone to take an interest in the technical matters that fascinate us. Nevertheless, our style of answering questions is tuned for people who do take such an interest and are willing to be active participants in problem-solving. That's not going to change. Nor should it; if it did, we would become less effective at the things we do best.

We're (largely) volunteers. We take time out of busy lives to answer questions, and at times we're overwhelmed with them. So we filter, ruthlessly. In particular, we throw away questions from people who appear to be losers, in order to spend our question-answering time more efficiently, on winners.

If you find this attitude obnoxious, condescending, or arrogant, check your assumptions. We're not asking you to genuflect to us — in fact, most of us would love nothing more than to deal with you as an equal, and welcome you into our culture, if you put in the effort required to make that possible. It's simply not efficient for us to try to help people who're not willing to help themselves. It's OK to be ignorant; it's not OK to play stupid.

So, while it isn't necessary to already be technically competent, to get attention from us, it is necessary to demonstrate the kind of attitude that leads to competence — alert, thoughtful, observant, willing to be an active partner in developing a solution. If you can't live with this sort of discrimination, we suggest you pay somebody for a commercial support contract, instead of asking hackers to personally donate help to you.

If you decide to come to us for help, you don't want to be one of the losers. You don't want to seem like one, either. The best way to get a rapid and responsive answer is to ask it like a person with smarts, confidence, and clues who just happens to need help on one particular problem.

(Improvements to this guide are welcome. You can e-mail suggestions to esr@thyrsus.com or rick@linuxmafia.com. Note, however, that this document is not intended to be a general guide to netiquette, and we will generally reject suggestions not specifically related to eliciting useful answers in a technical forum.)

## Before You Ask

Before asking a technical question by e-mail, or in a newsgroup, or on a Web site chat board, do the following:

Try to find an answer by searching the Web.

Try to find an answer by reading the manual.

Try to find an answer by reading a FAQ.

Try to find an answer by inspection or experimentation.

Try to find an answer by asking a skilled friend.

If you're a programmer, try to find an answer by reading the source code.

When you ask your question, mention having done these things first; this will help establish that you're not being a lazy sponge and wasting people's time. Better yet, display what you've learned from doing these things. We like answering questions for people who've demonstrated they can learn from the answers.

Use tactics like doing a Google search on the text of your error message (searching Google Groups, as well as Web pages). This might well take you straight to fix documentation or a mailing list thread answering your question. Even if it doesn't, saying "I googled on the following phrase but didn't get anything promising" is a good thing to include in e-mail or news posting requesting help.

Take your time. Do not expect to be able to solve a complicated problem with a few seconds of Googling. Read and understand the FAQs, sit back, relax, and give the problem some thought before approaching experts. Trust us, they will be able to tell from your questions how much reading and thinking you did, and will be more willing to help if you come prepared. Don't instantly fire your whole arsenal of questions, just because your first search turned up no answers (or too many).

Prepare your question. Think it through. Hasty-sounding questions get hasty answers, or none at all. The more you do to demonstrate having put thought and effort into solving your problem before seeking help, the more likely you are to actually get help.

Beware of asking the wrong question. If you ask one that is based on faulty assumptions, J. Random Hacker is quite likely to reply with a uselessly literal answer, while thinking "Stupid question...", and hoping the experience of getting what you asked for, rather than what you needed, will teach you a lesson.

Never assume you're entitled to an answer. You're not; you aren't, after all, paying for the service. You will earn an answer, if you earn it, by asking a substantial, interesting, and thought-provoking question — implicitly contributing to the experience of the community, rather than merely passively demanding knowledge from others.

On the other hand, making clear your ability and willingness to help the solution-development process is a very good start. "Would someone provide a pointer?", "What is my example missing?", and "What site should I have checked?" are more likely to get answered than "Please post the exact procedure I should use", because you're stressing genuine willingness to complete the process, if someone can just point you in the right direction.

## When You Ask

Choose your forum carefully
Be sensitive in choosing where you ask your question. You're likely to be ignored, or written off as a loser, if you:

post your question to a forum where it's off topic

post a very elementary question to a forum where advanced technical questions are expected, or vice-versa

cross-post to too many different newsgroups

post a personal e-mail to somebody who is neither a personal acquaintance nor personally responsible for solving your problem

Hackers blow off inappropriately targeted questions, in order to try to protect their communications channels from being drowned in irrelevance. You don't want this to happen to you.

The first step, therefore, is to find the right forum. Again, Google and other Web-searching methods are your friend. Use them to find the project Web page most closely associated with the hardware or software giving you difficulties. Usually, it will have links to a FAQ (Frequently Asked Questions) list, and to project mailing lists and their archives. These mailing lists are the final places to go for help, if your own efforts (including reading those FAQs you found) don't find you a solution. The project page may also describe a bug-reporting procedure, or have a link to one; if so, follow it.

Shooting off an e-mail to a person or forum you're unfamiliar with is risky at best. For example, don't assume the author of an informative Web page wants to be your free consultant. Don't make optimistic guesses about whether your question will be welcome: If you're unsure, send it elsewhere, or refrain from sending it at all.

When selecting a Web forum, newsgroup, or mailing list, don't trust the name by itself too far; look for a FAQ or charter to verify your question being on-topic. Read some of the back traffic, before posting, so you'll get a feel for how things are done, there. In fact, do a keyword search for words relating to your problem, on the newsgroup or mailing list archives, before you post. It may find you an answer, and, if not, it will help you formulate a better question.

Don't shotgun-blast all available help channels at once; that's like yelling, and irritates people. Step through them.

Know what your topic is! One of the classic mistakes is asking questions about the Unix or Windows programming interface in a forum devoted to a language or library or tool portable across both. If you don't understand why this is a blunder, you'd be best off not asking any questions at all, until you get it.

In general, questions to a well-selected public forum are more likely to get useful answers than are equivalent questions to a private one. There are multiple reasons: One is simply the size of the pool of potential respondents. Another is the size of the audience; hackers would rather answer questions that educate many people than questions serving only a few.

Understandably, skilled hackers and authors of popular software are already receiving more than their fair share of mis-targeted messages. By adding to the flood, you could in extreme cases even be the straw that breaks the camel's back — quite a few times, contributors to popular projects have withdrawn their support because collateral damage in the form of useless e-mail traffic to their personal accounts became unbearable.

## Web and IRC forums directed towards new users often give the quickest response

Your local user group, or your Linux distribution, may advertise a Web forum or IRC channel where new users can get help. (In non-English-speaking countries, new-user forums are still more likely to be mailing lists.) These are good first places, to ask, especially if you think you may have tripped over a relatively simple or common problem. An advertised IRC channel is an open invitation to ask questions there, and often get answers in real time.

In fact, if you got the program that is giving you problems from a Linux distribution (as common today), it may be better to ask in the distro's forum/list before trying the program's project forum/list. The project's hackers may just say, use our build.

Before posting to any Web forum, check if it has a Search feature. If it does, try a couple of keyword searches for something like your problem; it just might help. If you did a general Web search before (as you should have), search the forum anyway; your Web-wide search engine might not have all of this forum indexed recently.

There is an increasing tendency for projects to do user support over a Web forum or IRC channel, with e-mail reserved more for development traffic. So, look for those channels first, when seeking project-specific help.

## As a second step, use project mailing lists

When a project has a development mailing list, write to the mailing list, not to individual developers, even if you believe you know who can best answer your question. Check the documentation of the project and its homepage for the address of a project mailing list, and use it. There are several good reasons for this policy:

- Any question good enough to be asked of one developer will also be of value to the whole group. Contrariwise, if you suspect your question is too dumb for a mailing list, it's not an excuse to harass individual developers.

- Asking questions on the list distributes load between developers. Individual developers (especially the project leader) may be too busy to answer your questions.

- Most mailing lists are archived, and the archives are indexed by search engines. Somebody could find your question and the answer on the Web, instead of asking it again in the list.

- If certain questions are seen being asked often, developers can use that information to improve the documentation or the software itself, to be less confusing. If those questions are asked in private, nobody has a complete picture of what questions are asked most often.

If a project has both a "user" and a "developer" (or "hacker") mailing list or Web forum, and you're not hacking on the code, ask in the "user" list/forum. Don't assume you will be welcome on the developer list, where they're likely to experience your question as noise disrupting their developer traffic.

However, if you're sure your question is non-trivial, and you get no answer in the "user" list/forum for several days, try the "developer" one. You would be well advised to lurk there for a few days, before posting, to learn the local folkways. (Actually, this is good advice on any private or semi-private list.)

If you can't find a project's mailing list address, but see only the project maintainer's address, go ahead and e-mail the maintainer. However, even in that case, don't assume the mailing list doesn't exist. Mention in your e-mail your unfruitful attempt to find an appropriate mailing list. Also mention that you don't object to having your message forwarded to other people. (Many people think private e-mail should remain private, even if nothing in it is secret. By allowing forwarding, you give correspondents a choice in handling your mail.)

## Use meaningful, specific subject headers

On mailing lists, newsgroups, or Web forums, the subject header is your golden opportunity to attract qualified experts' attention, in around 50 characters or fewer. Don't waste it on babble like "Please help me" (let alone "PLEASE HELP ME!!!!"; messages with such subjects get discarded, by reflex). Don't try to impress us with the depth of your anguish; use the space for a super-concise problem description, instead.

One good convention for subject headers, used by many tech support organizations, is "object - deviation". The "object" part specifies what thing, or group of things, is having a problem. The "deviation" part describes observed deviation from expected behaviour.

Stupid:
HELP! Video doesn't work properly on my laptop!

Smart:
X.org 6.8.1 misshapen mouse cursor, Fooware MV1005 vid. chipset

Smarter:
X.org 6.8.1 mouse cursor on Fooware MV1005 vid. chipset - is misshapen

The process of writing an "object-deviation" description will help you organise your thinking about the problem in more detail. What is affected? Just the mouse cursor, or other graphics, too? Is this specific to the X.org version of X? To version 6.8.1? Is this specific to Fooware video chipsets? To model MV1005? A hacker who sees the result can immediately understand what you're having a problem with and the problem you're having, at a glance.

If you ask a question in a reply, be sure to change the subject line to indicate you're asking a question. A Subject line resembling "Re: test" or "Re: new bug" is less likely to attract useful amounts of attention. Also, pare quotations of previous messages, to the minimum consistent with cluing in new readers.

Don't simply hit Reply on an existing list message, to start an entirely new thread: This will limit your audience. Some e-mail readers, like mutt, allow the user to sort by thread, and then hide messages in a thread by folding the thread. Such users will never see your message.

Changing the subject isn't sufficient. Mutt, and probably other e-mail readers, looks at other information in the e-mail's headers to assign it to a thread, not the subject line. Instead, start an entirely new e-mail.

On Web forums, the rules of good practice are slightly different, because messages are usually much more tightly bound to specific discussion threads, and often invisible outside those threads. Changing the subject when asking a question in reply is not essential. Not all forums even allow separate subject lines on replies, and nearly nobody reads them when they do. However, asking a question in a reply is a dubious practice in itself, because it will be seen only by those who're watching this thread. So, unless you're sure you want to ask the people currently active in the thread, start a new one.

## Make it easy to reply

Finishing your query with "Please send your reply to..." makes it quite unlikely you'll get an answer. If you can't be bothered taking even the few seconds required to set up a correct Reply-To header in your e-mail agent, we can't be bothered to take even a few seconds to think about your problem. If your e-mail program doesn't permit this, get a better e-mail program. If your operating system doesn't support any e-mail programs permitting this, get a better operating system.

In Web forums, asking for a reply by e-mail is outright rude, unless you believe the information may be sensitive (and somebody will, for some unknown reason, let you but not the whole forum know it). If you want an e-mail copy when somebody replies in the thread, request that the Web forum send it; this feature is supported almost everywhere, under options like watch this thread, send e-mail on answers, etc.

## Write in clear, grammatical, correctly-spelled language

We've found by experience that careless, sloppy writers are usually also careless, sloppy thinkers and coders (often enough to bet on, anyway). Answering questions for careless, sloppy thinkers is not rewarding; we'd rather spend our time elsewhere.

So, expressing your question clearly and well is important. If you can't be bothered to do that, we can't be bothered to pay attention. Spend the extra effort to polish your language. It doesn't have to be stiff or formal — in fact, hacker culture values informal, slangy, and humorous language used with precision. However, it has to be precise; there has to be some indication that you're thinking and paying attention.

Spell, punctuate, and capitalise correctly. Don't confuse "its" with "it's", "loose" with "lose", or "discrete" with "discreet". Don't TYPE IN ALL CAPS; this is read as shouting, and considered rude. (All-smalls is only slightly less annoying, as it's difficult to read. Alan Cox can get away with it; you can't.)

More generally, if you write like a semi-literate boob, you'll very likely be ignored. Writing like a l33t script kiddie hax0r is the absolute kiss of death, and guarantees you'll receive nothing but stony silence (or, at best, a heaping helping of scorn and sarcasm), in return.

If you're asking questions in a forum not in your native language, you'll get a limited amount of slack for spelling and grammar errors — but no extra slack at all for laziness (and yes, we can usually spot the difference). Also, unless you know what your respondent's languages are, write in English. Busy hackers tend to simply flush questions in languages they don't understand, and English is the Internet's working language. By writing in English, you minimise the chance of your question being discarded unread.

## Send questions in accessible, standard formats

If you make your question artificially hard to read, it's more likely to be passed over in favor of one that isn't. So:

Send plain text e-mail, not HTML. (It's not hard to turn off HTML.)

MIME attachments are usually OK, but only if they're real content (such as an attached source file or patch), and not merely boilerplate generated by your e-mail client (such as another copy of your message).

Don't send e-mail in which entire paragraphs are single multiply-wrapped lines. (This makes it too difficult to reply to just part of the message.) Assume your respondents will be reading e-mail on 80-character-wide text displays, and set your line wrap accordingly, to something less than 80.

However, do not wrap data (such as log file dumps or session transcripts) at any fixed column width. Data should be included as-is, so respondents can have confidence they're seeing what you saw.

Don't send MIME Quoted-Printable encoding to an English-language forum. This encoding can be necessary when posting in a language ASCII doesn't cover, but many e-mail agents don't support it. When they break, all those =20 glyphs scattered through the text are ugly and distracting — or may actively sabotage the semantics of your text.

Never, ever expect hackers to be able to read closed proprietary document formats like Microsoft Word or Excel. Most hackers react to these about as well as you would to having a pile of steaming pig manure dumped on your doorstep. Even when they can cope, they resent having to do so.

If you're sending e-mail from a Windows machine, turn off Microsoft's stupid "Smart Quotes" feature. This is so you'll avoid sprinkling garbage characters through your e-mail.

In Web forums, do not abuse smiley and HTML features (when they're present). A smiley or two is usually OK, but coloured fancy text tends to make people think you're lame. Seriously overusing smileys and colour and fonts will make you come off like a giggly teenage girl, which is not generally a good idea unless you're more interested in sex than in answers.

If you're using a graphical-user-interface e-mail client, (such as Netscape Messenger, MS Outlook, or their ilk), beware that it may violate these rules when used with its default settings. Most such clients have a menu-based "View Source" command. Use this on something in your sent-mail folder, verifying sending of plain text without unnecessary attached crud.

## Be precise and informative about your problem

Describe the symptoms of your problem or bug carefully and clearly.

Describe the environment in which it occurs (machine, OS, application, whatever). Provide your vendor's distribution and release level (e.g.: "Fedora Core 2", "Slackware 9.1" etc.).

Describe the research you did to try and understand the problem before you asked the question.

Describe the diagnostic steps you took to try and pin down the problem yourself, before you asked the question.

Describe any possibly relevant recent changes to your computer or software configuration.

Do the best you can to anticipate the questions a hacker will ask, and answer them in advance in your request for help.

Simon Tatham has written an excellent essay entitled How to Report Bugs Effectively. I strongly recommend you read it.

## Volume is not precision

You need to be precise and informative. This end is not served by simply dumping huge volumes of code or data into a help request. If you have a large, complicated test case that breaks a program, try to trim it and make it as small as possible.

This is useful for at least three reasons. One: Being seen to invest effort in simplifying the question makes it more likely you'll get an answer, Two: Simplifying the question makes it more likely you'll get a useful answer. Three: In the process of refining your bug report, you may develop a fix or workaround, yourself.

## Don't claim you've found a bug

When you're having problems with a piece of software, don't claim you've found a bug, unless you're very, very sure of your ground. Hint: Unless you can provide a source-code patch fixing the problem, or a regression test against a previous version that demonstrates incorrect behaviour, you're probably not sure enough. This applies to Web pages and documentation, too; if you've found a documentation bug, you should supply replacement text and a note as to which pages it should go on.

Remember, many other users aren't experiencing your problem. Otherwise, you would have learned about it while reading the documentation and searching the Web. (You did do that before complaining, didn't you?) This means that very probably it's you who're doing something wrong, not the software.

The people who wrote the software work very hard to make it work as well as possible. If you claim you've found a bug, you'll be implying they did something wrong, and will almost always offend them — even if you're correct. It's especially undiplomatic to yell "bug" in the Subject line.

When asking your question, write as though you assume you're doing something wrong, even if you're privately pretty sure you've found an actual bug. If there really is a bug, you'll hear about it in the answer. Play it so the maintainers will want to apologise to you if the bug is real, rather than so you'll owe them an apology if you've messed up.

## Grovelling is no substitute for doing your homework

Some people who get that they shouldn't behave rudely or arrogantly, demanding an answer, retreat to the opposite extreme, of grovelling. ("I know I'm just a pathetic new user, but...".) This is distracting, and unhelpful. It's especially annoying when it's coupled with vagueness about the actual problem.

Don't waste your time, or ours, on crude primate politics. Instead, present the background facts and your question as clearly as you can. That is a better way to position yourself than by grovelling.

Sometimes, Web forums have separate places for new-user questions. If you feel you do have a new-user question, just go there. However, don't grovel there, either.

## Describe the problem's symptoms, not your guesses

It's not useful to tell hackers what you think is causing your problem. (If your diagnostic theories were such hot stuff, would you be consulting others for help?) So, make sure you're telling them the raw symptoms of what goes wrong, rather than your interpretations and theories. Let them do the interpretation and diagnosis.

Stupid:
I'm getting back-to-back SIG11 errors on kernel compiles, and suspect a hairline crack on one of the motherboard traces. What's the best way to check for those?

Smart:
My home-built K6/233 on an FIC-PA2007 motherboard (VIA Apollo VP2 chipset) with 256MB Corsair PC133 SDRAM starts getting frequent SIG11 errors about 20 minutes after power-on during kernel compiles, but never in the first 20 minutes. Rebooting doesn't restart the clock; powering down overnight does. Swapping out all RAM didn't help. The relevant part of a typical compile session log follows.

Since the preceding point seems to be a tough one for many people to grasp, here's a phrase to remind you: "All diagnosticians are from Missouri." That US state's official motto is "Show me" (earned in 1899, when Congressman Willard D. Vandiver said "I come from a country that raises corn and cotton and cockleburs and Democrats, and frothy eloquence neither convinces nor satisfies me. I'm from Missouri. You've got to show me.") In diagnosticians' case, it's not a matter of skepticism, but rather a literal, functional need to see whatever is as close as possible to the same raw evidence that you see, rather than your surmises and summaries. Show us.

## Describe your problem's symptoms in chronological order

The clues most useful in figuring out something that went wrong often lie in the events immediately prior. So, your account should describe precisely what you did, and what the machine did, leading up to the blowup. In the case of command-line processes, having a session log (e.g., using the script utility) and quoting the relevant twenty or so lines is very useful.

If the program that blew up on you has diagnostic options (such as -v for verbose), check for options useful in adding debugging information to the transcript.

If your account ends up being long (more than about four paragraphs), it might be useful to succinctly state the problem up top, and then follow with the chronological tale. That way, hackers will know what to watch for, in reading your account.

## Describe the goal, not the step

If you're trying to find out how to do something (as opposed to reporting a bug), begin by describing the goal. Only then, describe the particular step towards it, on which you're blocked.

Often, people seeking technical help have a high-level goal in mind, and get stuck on what they think is one particular path towards the goal. They come for help with the step, but don't realise the path is wrong. It can take substantial effort to get past this.

Stupid:
How do I get the color-picker on the FooDraw program to take a hexadecimal RGB value?

Smart:
I'm trying to replace the color table on an image with values of my choosing. Right now, the only way I can see to do this is by editing each table slot, but I can't get FooDraw's color picker to take a hexadecimal RGB value.

The second version if the question is smart. It allows answers suggesting tools better suited to the task.

## Don't ask people to reply by private e-mail

Hackers believe solving problems should be a public, transparent process, during which the first try at an answer can and should be corrected, if someone more knowledgeable notices incomplete or incorrect data. Also, helpers get some of their reward for being respondents from being seen to be competent and knowledgeable by their peers.

When you ask for a private reply, you're disrupting both the process and the reward. Don't do this. It's the respondent's choice whether to reply privately — and, if he or she does, it's usually because he/she thinks the question is too ill-formed or obvious to be interesting to others.

There is one limited exception to this rule. If you think the question may attract a number of similar answers, then the magic words are "e-mail me and I'll summarise answers for the group". It is courteous to try and save the mailing list or newsgroup a flood of substantially identical postings — but you must keep the promise to summarise.

## Be explicit about your question

Open-ended questions tend to be perceived as open-ended time sinks. Those people most likely to be able to give useful answers are also the busiest (if only because they take on the most work themselves). People like that are allergic to open-ended time sinks; thus, they tend to be allergic to open-ended questions.

You're more likely to get a useful response if you're explicit about what you want respondents to do (provide pointers, send code, check your patch, whatever). This will focus their effort, and implicitly put an upper bound on the time and energy a respondent must allocate for helping you. This is good.

To understand the world experts live in, think of expertise as an abundant resource, and time to respond as a scarce one. The less time commitment you implicitly request, the more likely you are to get an answer from someone really good and really busy.

So, it's useful to frame your question to minimise the time commitment required for an expert to field it — but this is often not the same thing as simplifying the question. Thus, for example, "Would you give me a pointer to a good explanation of X?" is usually a smarter question than "Would you explain X, please?". If you have some malfunctioning code, it's usually smarter to ask what's wrong with it than to request someone to fix it.

## Don't post homework questions

Hackers are good at spotting homework questions; most of us have done them ourselves. Those questions are for you to work out, so you'll learn from the experience. It is OK to ask for hints, but not for entire solutions.

If you suspect you've been passed a homework question, but can't solve it anyway, try asking in a user group forum or (as a last resort) in a "user" list/forum of a project. While the hackers will spot it, some of the advanced users may at least give you a hint.

## Prune pointless queries

Resist the temptation to close your request for help with semantically-null questions like "Can anyone help me?" or "Is there an answer?" First: If you've written your problem description halfway competently, such tacked-on questions are at best superfluous. Second: Because they are superfluous, hackers find them annoying — and are likely to return logically impeccable but dismissive answers like "Yes, you can be helped" and "No, there is no help for you."

In general, asking yes-or-no questions is a good thing to avoid unless you want a yes-or-no answer.

## Don't flag your question as "Urgent", even if it is for you

That's your problem, not ours. Claiming urgency is very likely to be counter-productive: Most hackers will simply delete such messages as rude and selfish attempts to elicit immediate and special attention.

There is one semi-exception: It can be worth mentioning if you're using the program in some high-profile place, one hackers will get excited about; in such a case, if you're under time pressure, and you say so politely, people may get interested enough to answer faster.

This is a very risky thing to do, however, because the hackers' metric for what is exciting probably differ from yours. Posting from the International Space Station would qualify, for example, but posting on behalf of a feel-good charitable or political cause would almost certainly not. In fact, posting "Urgent: Help me save the fuzzy baby seals!" will reliably get you shunned or flamed, even by hackers who think fuzzy baby seals are important.

If you find this mysterious, re-read the rest of this HOWTO repeatedly, until you understand it, before posting anything at all.

## Courtesy never hurts, and sometimes helps

Be courteous: Use "Please" and "Thanks for your attention" or "Thanks for your consideration". Make it clear you appreciate time spent helping you for free.

To be honest, this isn't as important as (and cannot substitute for) being grammatical, clear, precise, and descriptive, avoiding proprietary formats, etc.; hackers in general would rather get somewhat brusque but technically sharp bug reports than polite vagueness. (If this puzzles you, remember that we value a question by what it teaches us.)

However, if you have your technical ducks in a row, politeness does increase your chances of getting a useful answer.

(We must note that the only serious objection we've received from veteran hackers to this HOWTO concerns our previous recommendation to use "Thanks in advance". Some hackers feel this connotes an intention not to thank anybody afterwards. Our recommendation is to either say "Thanks in advance" first and thank respondents afterwards, or express courtesy in a different way, such as by saying "Thanks for your attention" or "Thanks for your consideration".)

## Follow up with a brief note on the solution

Send a note after the problem has been solved, to all who helped you: Let them know how it came out, and thank them again for their help. If the problem attracted general interest in a mailing list or newsgroup, it's appropriate to post the followup there.

Optimally, the reply should be within the thread started by the original question post, and should have 'FIXED', 'RESOLVED', or an equally obvious tag in the subject line. On mailing lists with fast turnaround, a potential respondent who sees a thread about "Problem X" ending with "Problem X - FIXED" knows not to waste time even reading the thread (unless he/she personally finds Problem X interesting), and therefore can use that time solving a different problem.

Your followup needn't be long and involved; a simple "Howdy — it was a failed network cable! Thanks, everyone. - Bill" would be better than nothing. In fact, a short and sweet summary is better than a long dissertation, unless the solution has real technical depth. Say what action solved the problem, but you need not replay the whole troubleshooting sequence.

For problems with some depth, it's appropriate to post a summary of the troubleshooting history. Describe your final problem statement. Describe what worked as a solution, and indicate avoidable blind alleys. Name the names of people who helped you; you'll make friends that way.

Besides being courteous and informative, this sort of followup will help others searching the mailing-list / newsgroup / forum archives to know exactly which solution helped you, and thus may also help them.

Last, and not least, this sort of followup helps everybody who assisted feel a satisfying sense of closure, about the problem. If you aren't a techie or hacker, yourself, trust us: This feeling is very important to the gurus and experts you tapped for help. Problem narratives trailing off into unresolved nothingness are frustrating things; hackers itch to see them resolved. The goodwill scratching that itch earns you will be very, very helpful to you, next time you need to pose a question.

Consider how you might be able to prevent others from having the same problem in the future. Ask yourself if a documentation or FAQ patch would help. If the answer is yes, send your patch to the maintainer.

Among hackers, this sort of behaviour is actually more important than conventional politeness. It's how you get a reputation for playing well with others, which can be a very valuable asset.

## How To Interpret Answers

RTFM and STFW: How To Tell You've Seriously Screwed Up
There is an ancient and hallowed tradition: If you get a reply reading "RTFM", the person who sent it thinks you should have Read the Fucking Manual. He/she is almost certainly right. Go read it.

RTFM has a younger relative. If you get a reply that reads "STFW", the person who sent it thinks you should have Searched the Fucking Web. He/she is almost certainly right. Go search it. (The milder version of this is when you're told Google is your friend!)

In Web forums, you may also be advised to search the forum archives. In fact, someone may even be so kind as to provide a pointer to the previous thread, where this problem was solved. However, don't rely on this consideration; do your archive-searching before asking.

Often, the person sending either of these replies has the manual or the Web page with the information you need open, and is looking at it, as he or she types. These replies mean your respondent thinks (a) the information you need is easy to find, and (b) you will learn more if you seek out the information than if it's spoon-fed to you.

You shouldn't be offended by this; by hacker standards, he or she's showing you a rough kind of respect simply by not ignoring you. You should instead thank that person for grandmotherly kindness.

If you don't understand...
If you don't understand the answer, don't immediately bounce back a demand for clarification. Use the same tools you focussed on your original question (manuals, FAQs, the Web, skilled friends), to understand the answer. Then, if you still need to ask for clarification, exhibit what you've learned.

For example, suppose I tell you: "It sounds like you've a stuck zentry; you'll need to clear it." Then: Here's a bad followup question: "What's a zentry?" Here's a good followup question: "OK, I read the man page; zentries are only mentioned under the -z and -p switches. Neither of them says anything about clearing zentries. Is it one of these, or am I missing something here?"

Dealing with rudeness
Much of what looks like rudeness in hacker circles is not intended to give offence. Rather, it's the product of the direct, cut-through-the-bullshit communications style natural to people who're more concerned about solving problems than about making others feel warm and fuzzy.

When you perceive rudeness, try to react calmly. If someone really is acting out, very likely, a senior person on the list or newsgroup or forum will call him or her on it. If that doesn't happen, and you lose your temper, very likely the person you lose it against was behaving within hacker community norms, and you'll be considered at fault. This will hurt your chances of getting the information or help you want.

On the other hand, you'll occasionally run across quite gratuitous rudeness and posturing. The flip-side of the above is that it's acceptable form to slam real offenders quite hard, dissecting their misbehaviour with a sharp verbal scalpel. Be very, very sure of your ground, before you try this, however. The line between correcting an incivility and starting a pointless flamewar is thin enough that hackers themselves not infrequently blunder across it; if you're a new user or outsider, your chances of avoiding such a blunder are low. If you're after information rather than entertainment, it's better to keep your fingers off the keyboard than risk this.

(Some people assert that many hackers have a mild form of autism or Asperger's Syndrome, and are actually missing some of the brain circuitry lubricating 'normal' human social interaction. This may or may not be true. If you're not a hacker, yourself, it may help you cope with our eccentricities if you think of us as brain-damaged. Go right ahead. We won't care; we like being whatever we are, and generally have a healthy skepticism about clinical labels.)

In the next section, we'll talk about a different issue; the kind of "rudeness" you'll see when you misbehave.

## On Not Reacting Like a Loser

Odds are you'll screw up a few times, on hacker community forums — in ways detailed in this article, or similar. And you'll be told exactly how you screwed up, possibly with colourful asides. In public.

When this happens, the worst thing you can do is whine about the experience, claim to have been verbally assaulted, demand apologies, scream, hold your breath, threaten lawsuits, complain to people's employers, leave the toilet seat up, etc. Instead, here's what you do:

Get over it. It's normal. In fact, it's healthy and appropriate.

Community standards do not maintain themselves: They're maintained by people actively applying them, visibly, in public. Don't whine that all criticism should have been conveyed via private e-mail: That's not how it works. Nor is it useful to insist you've been personally insulted when someone comments that one of your claims was wrong, or that his/her views differ. Those are loser attitudes.

There have been hacker forums where, out of some misguided sense of hyper-courtesy, participants are banned from posting any fault-finding with another's posts, and told "Don't say anything if you're unwilling to help the user." The resulting departure of clueful participants to elsewhere causes them to descend into meaningless babble, and become useless as technical forums.

Exaggeratedly "friendly" (in that fashion) or useful: Pick one.

Remember: When that hacker tells you you've screwed up, and (no matter how gruffly) tells you not to do it again, he/she's acting out of concern for (1) you and (2) his/her community. It would be much easier for him/her to ignore you and filter you out of his/her life. If you can't manage to be grateful, at least have a little dignity; don't whine, and don't expect to be treated like a fragile doll just because you're a newcomer with a theatrically hypersensitive soul and delusions of entitlement.

## Questions Not to Ask

Here are some classic stupid questions, and what hackers are thinking when they don't answer them.

Q: Where can I find program or resource X?
Q: How can I use X to do Y?
Q: How can I configure my shell prompt?
Q: Can I convert an AcmeCorp document into a TeX file using the Bass-o-matic file converter?
Q: My {program, configuration, SQL statement} doesn't work
Q: I'm having problems with my Windows machine. Can you help?
Q: My program doesn't work. I think system facility X is broken.
Q: I'm having problems installing Linux or X. Can you help?
Q: How can I crack root/steal channel-ops privileges/read someone's e-mail?
Q:	
Where can I find program or resource X?

A:	
The same place I'd find it, fool — at the other end of a Web search. Ghod, doesn't everybody know how to use Google, yet?

Q:	
How can I use X to do Y?

A:	
If what you want is to do Y, you should ask that question without pre-supposing use of a method that may not be appropriate. Questions of this form often indicate a person not merely ignorant about X, but also confused about what problem Y they're solving and too fixated on the details of their particular situation. It is generally best to ignore such people, until they define their problems better.

Q:	
How can I configure my shell prompt?

A:	
If you're smart enough to ask this question, you're smart enough to RTFM and find out yourself.

Q:	
Can I convert an AcmeCorp document into a TeX file using the Bass-o-matic file converter?

A:	
Try it and see. If you did that, you'd (a) learn the answer, and (b) stop wasting my time.

Q:	
My {program, configuration, SQL statement} doesn't work

A:	
This isn't a question, and I'm not interested in playing Twenty Questions to pry your actual question out of you — I have better things to do. On seeing something like this, my reaction is normally of one of the following:

do you have anything else to add to that?

oh, too bad; I hope you get it fixed.

and this has exactly what to do with me?

Q:	
I'm having problems with my Windows machine. Can you help?

A:	
Yes. Throw out that Microsoft trash and install an open-source operating system like Linux or BSD.

Note: you can ask questions related to Windows machines if they are about a program that does have an official Windows build, or interacts with Windows machines (i.e., Samba). Just don't be surprised by the reply that the problem is with Windows and not the program, because Windows is so broken in general that this is very often the case.

Q:	
My program doesn't work. I think system facility X is broken.

A:	
While it's possible you're the first person to notice an obvious deficiency in system calls and libraries heavily used by hundreds or thousands of people, it's rather more likely you're utterly clueless. Extraordinary claims require extraordinary evidence; when you make a claim like this one, you must back it up with clear and exhaustive documentation of the failure case.

Q:	
I'm having problems installing Linux or X. Can you help?

A:	
No. I'd need hands-on access to your machine to troubleshoot this. Go ask your local Linux user group for hands-on help. (You can find lists of user groups inside the Linux User Group HOWTO.)

Note: questions about installing Linux may be appropriate if you're on a forum or mailing list about a particular Linux distribution, and the problem is with that distribution; or on local user groups' forums. In this case, be sure to describe the exact details of the failure. However, do careful searching first, with "linux" and all suspicious pieces of hardware.

Q:	
How can I crack root / steal channel-ops privileges / read someone's e-mail?

A:	
You're a low-life for wanting to do such things, and a moron for asking a hacker to help you.

## Good and Bad Questions

Finally, I'm going to illustrate how to ask questions in a smart way by example; pairs of questions about the same problem, one asked in a stupid way and one in a smart way.

Stupid: Where can I find out stuff about the Foonly Flurbamatic?
This question just begs for "STFW" as a reply.

Smart: I used Google to try to find "Foonly Flurbamatic 2600" on the Web, but I got no useful hits. Does anyone know where I can find programming information on this device?
This one has already STFWed, and sounds like he might have a real problem.

Stupid: I can't get the code from project foo to compile. Why is it broken?
The querent assumes somebody else screwed up. Arrogant git....

Smart: The code from project foo doesn't compile under Nulix version 6.2. I've read the FAQ, but it doesn't have anything in it about Nulix-related problems. Here's a transcript of my compilation attempt; is it something I did?
He or she's specified the environment, has read the FAQ, has shown the error, and isn't assuming his/her problems are someone else's fault. This one might be worth some attention.

Stupid: I'm having problems with my motherboard. Can anybody help?
J. Random Hacker's response to this is likely to be "Right. Do you need burping and diapering, too?" followed by a punch of the delete key.

Smart: I tried X, Y, and Z on the S2464 motherboard. When that didn't work, I tried A, B, and C. Note the curious symptom when I tried C. Obviously the florbish is grommicking, but the results aren't what one might expect. What are the usual causes of grommicking on Athlon MP motherboards? Anybody got ideas for more tests I can run, to pin down the problem?
This person, on the other hand, seems worthy of an answer. He/she has exhibited problem-solving intelligence, rather than passively waiting for an answer to drop from on high.

In the last question, notice the subtle but important difference between demanding "Give me an answer" and "Please help me figure out what additional diagnostics I can run, to achieve enlightenment."

In fact, the form of that last question is closely based on a real incident in August 2001 on the Linux-kernel mailing list (lkml). I (Eric) was the one asking the question that time. I was seeing mysterious lockups on a Tyan S2462 motherboard. The list members supplied the critical information I needed to solve them.

By asking the question in the way I did, I gave people something to chew on; I made it easy and attractive for them to get involved. I demonstrated respect for my peers' ability, and invited them to consult with me as a peer. I also demonstrated respect for the value of their time, by telling them the blind alleys I'd already run down.

Afterwards, when I thanked everyone, and remarked how well the process had worked, an lkml member observed that he thought it had worked not because I'm a "name" on that list, but because I asked the question in the proper form.

Hackers are in some ways a very ruthless meritocracy; I'm certain he was right, and that if I had behaved like a sponge I would have been flamed or ignored, no matter who I was. His suggestion of writing up the whole incident as instruction to others led directly to composition of this guide.

## If You Can't Get an Answer

If you can't get an answer, please don't take personally that we don't feel we can help you. Sometimes, the members of the asked group may simply not know the answer. No response is not the same as being ignored, though admittedly it's hard to spot the difference from outside.

In general, simply re-posting your question is a bad idea. This will be seen as pointlessly annoying. Have patience: The person with your answer may currently be asleep, in a different time-zone.

There are other sources of help you can go to, often sources better adapted to a novice's needs.

There are many on-line and local user groups who are enthusiasts about the software, even though they may never have written any software themselves. These groups often form so people can help each other, and help new users.

There are also plenty of commercial companies you can contract with for help, both large and small. (Red Hat and SpikeSource are two of the best known; there are many others.) Don't be dismayed at having to pay for a bit of help! After all, if your car engine blows a head gasket, chances are you would take it to a repair shop, and pay to get it fixed. Even if the software didn't cost you anything, you can't expect support to always come for free.

For popular software like Linux, there are at least 10,000 users per developer. It's just not possible for one person to handle the support calls from over 10,000 users. Remember, even if you must pay for support, you're still paying much less than if you'd needed to buy the software as well (and support for closed-source software is usually more expensive and less competent than support for open-source software).

## How To Answer Questions in a Helpful Way

Be gentle. Problem-related stress can make people seem rude or stupid, even when they're not.

Reply to a first offender off-line. There is no need of public humiliation for someone who may have made an honest mistake. A real new user may not know how to search archives, or where the FAQ is stored or posted.

If you don't know for sure, say so! A wrong but authoritative-sounding answer is worse than none at all. Don't point anyone down a wrong path simply because it's fun to sound like an expert. Be humble and honest; set a good example for both the querent and your peers.

If you can't help, don't hinder. Don't make jokes about procedures that could trash the user's setup — the poor sap might interpret these as instructions.

Ask probing questions to elicit more details. If you're good at this, the querent will learn something — and so might you. Try to turn the bad question into a good one; remember, we were all new users once.

While just muttering RTFM is sometimes justified, when replying to someone who is just a lazy slob, a pointer to documentation (even just a suggestion to google for a key phrase) is better.

If you're going to answer the question at all, give good value. Don't suggest kludgey workarounds, when somebody is using the wrong tool or approach. Suggest good tools. Re-frame the question.

Help your community learn from the question. When you field a good question, ask yourself "How would the relevant documentation or FAQ have to change, so nobody has to answer this again?" Then, send a patch to the document maintainer.

If you did research to answer the question, demonstrate your skills rather than writing as though you pulled the answer out of your butt. Answering one good question is like feeding a hungry person one meal, but teaching that person research skills by example is teaching him/her to grow food for a lifetime.

## Related Resources

If you need instruction in the basics of how personal computers, Unix, and the Internet work, see The Unix and Internet Fundamentals HOWTO.

When you release software or write patches for software, try to follow the guidelines in the Software Release Practice HOWTO.

## Special Note for FAQ List Maintainers and Webmasters

Many Web sites, newsgroups, and other on-line forums link to this HOWTO, as a guide for new users. The authors are glad for you to do so. However, please add next to the link in bold type a note about our not being your project's help desk: We get far too many queries from users who assume otherwise.

## Acknowledgements

Evelyn Mitchell contributed some stupid questions, and inspired the "How To Give A Good Answer" section.

