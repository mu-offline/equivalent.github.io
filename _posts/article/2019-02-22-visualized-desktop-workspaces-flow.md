---
layout: article_post
categories: article
title:  "Visualized desktop workspaces flow"
disq_id: 57
description:
  productivity
---




In my daily setup I use 6 workspaces which I visualize as grid of 3 columns on 2 rows:

> Software implementation of Workspaces can be 6 workspaces columns in 1 row (e.g. OSx, or Cinnamon IDE). The important part is how you "visualize" it.

![Workspaces in grid](https://raw.githubusercontent.com/equivalent/equivalent.github.io/master/assets/2019/visualized-workspaces-flow-workspaces.png)


## Every workspace is dedicated to single purpose

For example because I'm a [Ruby on Rails](https://rubyonrails.org/) web-developer building web-applications my daily
workspaces layout look something like this:


**Workspace1**

* purpose: human interaction frontend testing of the web-application I'm building
* applications:
  - terminal running Ruby on Rails development web server
  - web-browser loading frontend of application I'm building (`localhost:3000`)

**Workspace2**

* purpose: writing backend and frontend code + writing and lunching code tests
* applications:
  - IDE code editor (Vim)
  - terminal in which I lunch my web-application backend tests (RSpec)

**Workspace3**

* purpose: company communication
* applications:
  - [Slack](https://slack.com/) (in the past I use to have Skype/ other IM, or company email. Depending on the company I worked for communication tools)
  - editor (vim) writing down company related notes (E.g. questions I need to ask later on)

**Workspace4**

* purpose: work on remote servers (e.g. when I'm asked to fix a critical production bug, run migrations on staging server, etc.)
* applications:
  - terminal to `ssh` to servers
  - terminal to `scp` stuff from/to servers

**Workspace5**
* purpose: personal - e.g. music, reading personal emails, personal IM, googling funny cats, etc...
* applications:
  - web-browser (I lunch pretty much everything via web-browser)
  - editor (vim) writing down personal notes (E.g. personal todo list)

**Workspace6**
* purpose: anything else
* applications:
  - e.g. VPN tunnel app, or image editor (Gimp) when needed.

Supper important part of this productivity flow is to get into the mindset of what "responsibility" each Workspaces represent.

When I'm working I don't think in terms of:

`I need to check if something is working on the website therefore I need to go to "Workspace 1" and reload "web-browser loading address http://localhost:3000"`

..but rather I think in terms of:


`I need to check if something is working on the website therefore I need to go to "Frontend workspace" and reload "the app"`

> I think of Workspace as  a form of "[bounded context](https://martinfowler.com/bliki/BoundedContext.html) of functionality".

![workspaces as bounded contexts](https://raw.githubusercontent.com/equivalent/equivalent.github.io/master/assets/2019/visualized-workspaces-flow-responsibility-workspces.png)

It's similar like the way you think about your house. You don't think about room1, room2,
room3, ... You think of Bedroom, Bathroom, Living room.

![workspaces as room in the house](https://raw.githubusercontent.com/equivalent/equivalent.github.io/master/assets/2019/visualized-workspaces-flow-rooms-in-your-house.png)

Now that we established the "responsibilities" of workspaces another
important part is the navigation in Workspaces.

## Navigation in responsibility workspaces

Like I've said I visualize my workspaces as 3 columns on 2 rows grid.
That means if I need to switch from "Server stuff" workspace to
"Company communication" workspaces I don't want to think of:

`I need to go "up", "right" and "another right"`

I want to visualize:

`I need to go from "Server stuff workspace" to "Company communication"`

> Same as in a house you don't think of I need to go out of this room, go
> down the hallway, take the vacuum cleaner go out of this room go  left and
> vacuum clean that room. You rather think: "I need from Living room to Storage
> room grab a vacuum cleaner and go clean the Bedroom"

So in order to achieve this you need to set up instant "go to workspaces" navigation
shortcuts in your laptop. For example you can set shortcuts:

PC/Linux:

* `WindowsButton + 1` - go to workspace 1
* `WindowsButton + 2` - go to workspace 2
* ...etc

Mac OSx:

* `CTR + 1` - go to workspace 1
* `CTR + 2` - go to workspace 2
* ...etc

Same way I'm recommending to setup `move window to workspace number` to
better move around application windows (eg: `move this webrowser window from "Personal" to "Company communication" workspace`)

for example


PC Linux:

* `ALT + WindowsButton + 1` - move window to workspace 1
* `ALT + WindowsButton + 2` - move window to workspace 2
* ...etc

Mac OSx:

* `ALT + CTR + 1` - move window to workspace 1
* `ALT + CTR + 2` - move window to workspace 2
* ...etc


I use Ubuntu Linux with Cinnamon IDE. Here is short TIL note [how to setup workspaces in Cinnamon for workspace flow](https://blog.eq8.eu/til/cinnamon-workspaces.html)

> In the past I use to use Mac OSx, native Ubuntu desktop environment (before they made workspaces stupid and not usable in Ubuntu 18.04),
> and several other Linux distros. Everywhere I was able to configure similar setup.
> I cannot give you any recommendation on Windows as I didn't use it for
> over 10 years.

You can set the workspace switch shortcuts to anything that make sense for you
I'll provide just 2 examples I used:

#### 10 finger technique setup

My "switch to workspace" shortcut setup over last 10 years is similar to this:


* `WindowsButton + 1` - go to workspace 1
* `WindowsButton + 2` - go to workspace 2
* `WindowsButton + 3` - go to workspace 3
* `WindowsButton + 8` - go to workspace 4
* `WindowsButton + 9` - go to workspace 5
* `WindowsButton + 0` - go to workspace 6

* `Alt + WindowsButton + 1` - move window to workspace 1
* `Alt + WindowsButton + 2` - move window to workspace 2
* `Alt + WindowsButton + 3` - move window to workspace 3
* `Alt + WindowsButton + 8` - move window to workspace 4
* `Alt + WindowsButton + 9` - move window to workspace 5
* `Alt + WindowsButton + 0` - move window to workspace 6


Reason for this shortcut layout is that I type with 10 finger technique and it's easier for me to
control first row of workspaces with left hand and bottom row with right hand.


![workspaces - 10 fingure technique visualized workspace flow](https://raw.githubusercontent.com/equivalent/equivalent.github.io/master/assets/2019/visualized-workspaces-flow-ten-finger-switch-shortcuts.png)


![workspaces - 10 fingure technique keyboard layut for visualized workspace flow](https://raw.githubusercontent.com/equivalent/equivalent.github.io/master/assets/2019/visualized-workspaces-flow-ten-finger-keyboard.jpg)


#### Side numeric keyboard workspaces

10 years ago before I've learned to type with ten finger method I use to
use side numeric keyboard to represent my workspaces. I had a grid of 3
columns in 3 rows (so 9 workspaces in total)

![workspaces - side numeric keyboard visualized workspace flow](https://raw.githubusercontent.com/equivalent/equivalent.github.io/master/assets/2019/visualized-workspaces-flow-num-pad-switch-shortcuts.png)


![workspaces - side numeric keyboard layout visualized workspace flow](https://raw.githubusercontent.com/equivalent/equivalent.github.io/master/assets/2019/visualized-workspaces-flow-ten-finger-keyboard.jpg)


I don't quite remember what was each workspace purpose but I've used all of them.

## Applications per workspace

I'm running usually one or two applications (maximum three) per workspace.
This is so that on any given workspaces I don't have to do too many `Alt+tab` (switch workspace application)

It doesn't mean that I need to lunch every application on every
workspace every day. There are days when I don't do anything with
remote servers so nothing get lunched on Workspace4

It's more about "where" I would lunch those applications.

## Conclusion

I just gave you one example how I use visualized workspaces flow for
productivity.

For example when I need to do my taxes I will close everything
programming related and I would
open tax related applications only. I have different applications on
different windows (e.g spreadsheet on Workspace 2, government website on
workspace 1, Bank account statements loaded in Workspace 3, etc...)

I use to try to learn 3D modelling and graphics, Music editing and lots
of (other stuff I suck at). I had
completely  different workspaces flows in my head for every hobby.

Point is I was "visualizing it"  mnemotechnically.

It's simmillar how [Mind Palace technique](https://www.youtube.com/watch?v=3vlpQHJ09do) works where
mentalists and magicians memorize huge amount of details by
"visualizing" them.

So please try this for yourself and let me know how you find this
productivity method.

## Other Links

* [WebDeveloper life hacks](https://skillsmatter.com/skillscasts/7455-web-developer-life-hacks) In the talk I talk about other interesting techniques I use for productivity

## Discussion

