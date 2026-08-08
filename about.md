*a long time ago, in an irc far, far away:  
**@ack:** tables are 90% of my use cases for org mode  
**@stormrider:** life is 90% of my uses cases for org mode

There's a story that's gone around MIT forever. In case you didn't know, 
a lot of the computer revolution began with the Tech Model Railroad Club 
in the late 50's. 

There were people that liked to build scenery, and others that got into 
fancier trains and mechanical accessories, but the folks I'm mentioning 
worked on the switchgear. I think they were a committee dedicated to 
programming greasy little analog computers that animated the assembly. 

When the "hulking giant" came to town -- a giant IBM mainframe that took 
paper-tape programs -- they began to take the overnight slots in the 
computer room, building programs, trying to cut instructions down to the 
very minimum. It became an obsession.  One guy known only as "Swede" got the
instructions for a complex operation down to ten lines of assembly, but 
nobody knows what happened to him after that.

## Groceries and a Volkswagen

In fact, it was such an obsession that one of the guys there started trying 
to adapt his thinking and his casual language to the sequential logic of 
computer programs. 

This didn't serve him well, as the story goes: For three Saturdays on end, 
his wife would go to the local grocery to get provisions. When she got home, 
she'd always ask, "You want to help me bring in the groceries?" He would 
simply reply, "No." And then he'd go on working on whatever he was fooling 
with at the moment.

On the fourth Saturday (again, according to legend), she came home, after 
packing a considerable load of supplies in their tiny Volkswagen, and asked 
again. Again he declined, but this time, she blew up.

"What's wrong with you? Why won't you help me with the groceries?"

"You asked me if I wanted to help you bring in the groceries. You didn't ask 
me if I would."

You can see where this probably went, although legends sort of get hazy after 
the punch line. But it illustrates a point about the way frequent computer 
users have their logic and language very much influenced by the machines they 
address. It's the old proverb all over again: you become like your friends, 
even if they're made of silicon and plastic.

## First Brush with UNIX

I logged into UNIX for the first time at Calhoun Community College, in Decatur, 
Alabama, during the summer of 1974. Having been an avid reader since the age of 
5, text and text-processing were very much on my mind. When I encountered a 
system where plain text is the raw material flowing through the pipes, I was 
hooked.  I coded before I could do a lot of other things in life.

The story about the groceries and the Volkswagen gave me a bigger clue: 
Computers and humans both depend on language, but unlike computers, human 
speech conveys an exact meaning even using apparently imprecise language. 
Could the informal programming rules that I learned from UNIX be adapted to 
life?

## UNIX Rules for Life

After about 30 years as a tech writer and frequent programmer, I finally 
settled on a starter set that worked for me. Little did I know that these very 
principles would lead me to org-mode, which would later lead me to find my 
people:

1. Keep it simple. It's cheaper and easier to carry around.
2. Do one thing well (at a time), because multitasking is a lie.
3. Network: You were born to connect.
4. Say what you mean; nothing is truer than the truth.
5. Hack, because someone's trial and error is the only way to learn anything, but keep a voltmeter handy, so you don't become a memorable lesson in failure.
6. Be who you are: Even a bent wire can carry a great light.
7. Use leverage -- a bigger hammer isn't always the best answer.
8. Use what you have. Never for dig diamonds with a brick of gold.
9. Have faith; all things are possible, except maybe skiing through a revolving door (stolen from the ✱fortune✱ program.
10. Think ahead, but don't worship your plans. Remember, today is the first day of the rest of your learning experience.

## ed >> vi >> emacs

I didn't start with org-mode, actually. I remember my first foo, created with 
the ed line editor. It was September, 1974, sitting on the floor in our living
room, on a Silent 700 paper terminal that my dad had acquired for use in his
job. 

Bill Joy hadn't even written vi yet -- that watershed weekend was still three 
years in the future. It was an amazing experience for a fifteen-year-old, 
admitted at 14 to take computer classes at a local college because my dad was 
a part-time instructor and full-time polymath.

## Research UNIX

Fifth edition UNIX had just been licensed to educational institutions at no 
cost, and since this college was situated squarely in the middle of the 
military-industrial complex, scoring a Hulking Giant was easy. Finding good 
code to run it? That was another issue, until Bell Labs offered up a freebie.

Here was an OS which took all that complexity and translated it to simple 
logic: everything is a file; small is beautiful; do one thing well. Didn’t 
matter that it was cranky and buggy and sometimes dumped your perfectly-okay 
program in the bit bucket. It was a thrill to be able to do something without 
having to obsess over the math underneath.

## Abstraction

In short, what made UNIX and C usable and beautiful was abstraction. You 
didn’t have to worry (much) about the low-level details if you didn’t feel 
like it. You could focus on pure logic and abstract entities without having 
to “break the fourth wall,” as actors say. 

You could take little pieces — like “ls” and “cat” and “awk” and “sed” — and 
you could assemble a script or a C program that would grant your wish. And 
that was exhilarating and exciting and fabulous.

At some point, I caught onto the idea of abstracting my day, with plain 
journal files labeled YYYYMMDD, in a special directory in /var/log. I still 
have those going way back. The format was simple, but using the files soon 
became complex:

```
***personal journal of stormrider
tue, aug 04, 1992 / 712904400
sweetmorn, confusion 70, 3158 YOLD

***fortune -s
Cold hands, no gloves.

***appts
09:00 staff meeting, conf rm
18:30 dinner with amit & bonnie

***to do
finish revisions on x-windows book
do syllabus for advanced C class
read some in Stevens & Rago
shower
shave
dress
take out the trash otw to work
.
.
.

***daily journal
06:43 - man, didn't sleep well
last night; i think i'm overdoing
it on the coffee at work; maybe i
should cut back some?
.
.
.

```

The unwieldy part came with all the repeated tasks, and tasks that got carried 
over from one day to the next (or didn't get finished). I had to copy 
yesterday's file, change all the key info, sort out the todo list, erase 
yesterday's journal, and generally do far too much work to keep my journal up.

I did it, but intermittently, supplanting it with post-it notes, pads, 
planners galore, palm pilots, palmtop computers, etc. It seemed like every day 
I was badly copying tasks from one day to the next. Meanwhile, my 
unwillingness to use Windows didn't give the the luxury of Outlook, when it 
came along.

I got turned onto ✱*emacs** sometime somewhere along the way. A fellow coder 
used it, and thought I might enjoy it. He was right, and it stuck as my 
editing platform of choice. **org-mode✱ hadn't come along yet. 

## A Modem in the Woods

Eventually, I started telecommuting, and we moved to my wife's family farm, 
about an hour outside New Orleans, in the woods. At that time, Internet was 
still dial-up, so command-line Linux with emacs was a performance hack.

Sometime not long before Katrina hit, I stumbled across org-mode. I'd already 
used outline mode for some period of time (can't remember how long), and 
org-mode seemed like a logical follow-on from there.

Over time, org-mode just grew, and I grew with it. All the features made it 
easy for me to both do what seemed natural for me, and do things in a way that 
felt like they supported my principles. Gradually, my other methods of keeping 
track of things faded away, except for my alarm clock.

Even when smart-phones took off, I was always trying to find some way to send 
org files over to my phone and use them there. I think I even wrote some 
lua code in an iPhone wiki app to emulate org-mode with my files, though it 
was not fully satisfactory.

* An org-mode Resume

I'd been wanting to get on with an open-source company for a long time, but 
hadn't found the right position, one that really matched my skills. Then one 
Saturday, while I was waiting for my wife to meet me for some community event 
we were hosting, I saw a position that virtually described me. I started to 
write a resume, but then decided that I would just take the job description 
elements, one-by-one, put them in an org file, and send them to the hiring 
manager.

Long-story short, almost everyone on this team used emacs, and org-mode, and 
lots of other .el packages that I also used every day. I got the job, and it
retired me, which brings me up to the present.

## emacs and My Principles

I am not a rabid open-source person.  My main backpack load is still Mac,
iPhone, and Apple Watch, though I use emacs extensively on them.  Unless I'm
in a situation where I can't pull out a laptop -- about 30% of the time -- I 
use emacs for everything: email, git, IRC, web-browsing, organization,
reminders, time-keeping....  In short, everything.

Granted, emacs isn't the simplest user interface, but it becomes second nature. 
After that, you'll find yourself accidentally erasing cells in your Google 
spreadsheet when you hit "C-x C-s" to try to save (good thing there's an undo).
But the fact that you can use the same text for multiple functions: 
appointments, task states, task notes, clocking time, building an agenda, 
sending email, project planning, percentage completion, .... The list is too 
long to quote, but just a simple statement, like "Get the discourse publishing 
tool working," can become the nucleus for a whole cycle's work and all the 
actions that go with it.

The window-driven nature of emacs makes it easy to switch tasks when you have 
to (just open another buffer) and then switch back later, and more quickly 
link back to where you were; not to mention that, if you become adept at 
using the agenda, you can keep yourself on track and move other things 
around with ease, and without any fear that they'll get lost.

Since I'm set up to send email, IRC, Mattermost, etc., directly from org-mode 
tasks, it's easy to track where I am. But even if I used another app, it's 
still really easy to just cut and paste a note next to a task and then set 
a follow-up time to prod, all without breaking your train of thought. You're 
literally still looking at the work you're doing while you're messaging about 
it, so there's that.

You have the entire outline in front of you for whatever you're working on, 
so presentations, show-and-tell sessions, and status reports are really 
simple to give, whether verbally or in writing. It's easy to (a) tell the 
truth, because you can see it at a glance, and (b) not stumble around trying 
to remember, which often leads us to embellish, just to keep the conversation 
moving.

If it doesn't do what you want, you've got customizable variables, a huge 
library of packages, strong macro capability, and push-come-to-shove, emacs 
lisp, though I rarely have to go there, TBH. Just be sure to make a backup 
before you change anything, so you don't have to try to backtrack fifty 
different changes to figure out which one broke (the voltmeter warning above).

Org-mode matches my thinking style. Not true for everyone, but I tend to 
outline or mindmap (which you can do with org-mode, with the right .el 
package).

Org-mode seriously leverages the power of plain text, in that you can either 
use the shortcuts to add an appointment, add tags, search tags -- or you can 
just do it by hand, because all of the special notation is plain text. 
Leveraging human language in this way is helpful to me.

Org-mode and emacs give me a stable platform that works everywhere, even on 
a printout. I don't need license fees, special extensions, subscriptions, 
add-on tools, or constant updates to keep my life humming.

Org-mode has justified my faith, as has emacs. Lots of tools I've used 
break, crash, or get killed by absorption (I once liked Astrid, e.g., but 
it suddenly got sold and went away). And no other tools do everything I want 
without switching apps. Org-mode and emacs are pretty much here to stay, 
especially since there is no license fee, and I can keep a self-contained 
version backed up at home, should it ever stop being distributed.

If I'm busy, I don't have to worry about keeping my outline clean. I can 
stop in the middle of notes for another project, hit return, enter a to do 
for later (and tag it and schedule it to pop up later), and then move that 
to someplace more suitable later. The agenda will clean it up and put it in 
perspective for me. Or I can search for it, or pull up all open to-do items 
(even by tags), or.... There are just too many ways to throw things ahead 
without losing my train of thought.

## A Weird Kind of Heaven

Okay, those are my reasons, and why life is 90% of my use cases for org-mode, 
but what's the other 10%?

Well, it's only wishful thinking, but if we get to pick our environment in 
the afterlife, I would choose one of those large, paneled offices off of a 
raised floor mainframe room. You know the ones: the stained carpet squares, 
the laminated pressboard desks, the sqeaky swivel chairs, and the 
half-working flourescents. And a terminal on the desk that runs nothing but 
emacs and org-mode. And a Volkswagen full of groceries every week.

Here's hoping. ;-)
