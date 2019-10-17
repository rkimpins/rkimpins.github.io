---
layout: post
title:  "Vim vs Emacs"
date:   2019-10-14 11:27:00 -0600
categories: jekyll update
---

## What? Vim? Emacs? 
No, we aren't talking about the cleaning supply and the fast-food chain burger. (Not funny).  
Vim and Emacs are both powerful text editors that have been around since the dawn of time.
Despite being released 27 (43 for Vi) and 40 years ago respectively[^fn1], they are still around and kicking,
and as popular as ever. According to the [2019 Stack Overflow Survey][so_link], 25.4% of
respondents chose Vim as their development environment, and 4.5% for emacs. Considering
the incredible pace that tech moves at these days, that's pretty darn good. But why?  
I could give you a brief history of Vim and Emacs, and explain what Vi is, but I can't
do a better job then the Wikipedia pages. For the curious, check our [Vim][vim_link] and [Emacs][emacs_link].
Anyways, let's Dive into it.


# Table of Contents
1. [What's so great about Vemacs?](#whats-so-great-about-vemacs)
2. [What's the difference?](#whats-the-difference)
3. [So which should I use?](#which-is-better)
4. [Summary](#summary)


## What's so great about Vemacs
I personally use Vim, but a lot of the reasons that people still use these editors apply to
both. If you are an Emacs user, just :%s/\cVim/Emacs  
1. **Those shortcuts though!**   
  When I was trying to learn Vim, I kept track of all the shortcuts a learned in a text document.
  Man did that get out of hand quickly. Don't believe me, check <a target="_blank" rel="noopener noreferrer"
  href="/assets/vim_cheat_sheet.txt">this</a> out.
  That's right, 675 lines. That's not even a flex, there are just so many shortcuts, and I haven't even
  scratched the metaphorical surface of what Vim can do. I also found <a target="_blank" rel="noopener noreferrer" 
  href="http://www.rgrjr.com/emacs/emacs_cheat.html"> this</a> helpful for Emacs.
2. **Infinite Customizability**  
  As a programmer, we like to be in control of the environments we work in. If we are going to
  spend so much of our life typing code, what we type into better be set up just how we like it. No way are we going
  to waste time doing a 3-second task several times when we can spend an hour automating it.
  As always, a <a target="_blank" rel="noopener noreferrer" href="https://xkcd.com/1319/">relevent XKCD.</a>
  Seriously though, that is one of the strengths of Vim. Through the .vimrc files, you can remap whatever 
  keybindings you want, make personal custom commands, and once you get into Vim or python scripting, 
  you can get real nutty. Shortcuts are what I live for. I'm sure I will make a post just praising them.
3. **Simplicity**
  I definitely appeciate this about these two editors. They are so incredibly simple (specifically regarding
  their interface). When you are
  new to something, it's nice to have all the fancy UI bells and whistles that increase the intuitiveness of use. But, when
  you live and breathe something, they just get annoying. I know what I need to do, just get out of my way
  and let me do it. I will admit that Vim is not particularly beginner-friendly. If you are anything
  like me, the first time you encountered it, you struggled to exit, let alone use it. Once you get
  the hang of it though, you will appreciate all that it can do. Things that seemed crazy at first
  (I'm looking at you, hjkl to navigate, instead of arrow keys), start to make a lot of sense.

## What's the difference

# Modal? More Like Total...ly makes sense
Yeah, it sounded better in my head. Moving on.
Vim is modal, and Emacs isn't (unless you make it). This really threw me for a loop.
Want to type something. NOPE, you are in Normal Mode. You just deleted three lines, split the window, jumped to the
bottom of the file, replaced every a with a capital A, filed your taxes, and pasted those three lines again. Whoops.
When I say Vim is modal, I mean that depending on the "mode" you are in, keys will do different things. For example, 
if you try to type "Ddogs are great" in normal mode, you just deleted an entire line, and type "re great:". 
There are other modes like Normal mode (used for running commands, like copy, delete line, etc),
Visual mode (text selection, think highlighting), and Cmdline mode (Used to run command line
commands).
While all these modes can be a 
big frustration to anyone learning Vim, once you get used to it, it starts to make a lot of sense. When you write code,
you send 10% writing code, and the other 30% staring at it, looking for what is breaking it, and the other 60%
inserting 400 "cout << "You made it here" << endl;" because you really should just spend the time to learn the debugger,
but nobody has time for that. By keeping Vim modal, you get a ton of movement commands and useful text editing without
your fingers ever leaving the home row. This keeps things fast and avoids the notorious "Emacs Pinky" (finger pain
from how to stretch the fingers so far for certain key combinations).

# Beyond Text Editing, aka, where my ignorance of Emacs becomes clear
Disclaimer: I haven't spent nearly enough time in Emacs to be giving my opinion. Anyway, here's my opinion.  
While Vim does have some scripting that lets you extend its functionality, it's not nearly as clean as Emacs.
Emacs is designed for people that
want to live and breathe Emacs. You can edit text, play Tetris, email your family (just do it, they worry about you), 
browse the web, turn down your thermostat, start a revolution, post on Reddit, probably regret it, and anything
else your curious little mind can imagine. Vim is more designed to be opened, make your text edits, and close
it again. If you are one of those Vim superusers who think they can do all these things in Vim, ~~fight me~~
great, I'm so glad you are reading my blog.

## Which is better
I may primarily use Vim, but my perfectly balanced, unbiased, well thought out, objectively correct opinion is that
Vim is better. Thank you and goodnight.  

Okay, in all seriousness, this is what I think. I think the Vim shortcuts and layout are brilliant, and solely 
in terms of text editing, I think Vim is the winner. On the other hand, I feel Emacs has a bit more power
and support when it comes to additional features, like syntax support. If you want to edit your code, use Vim.
If you want to edit, compile, run, search StackOverflow, run again, then check your mail, use Emacs.

## You didn't really say which was better? Which should I use?
Neither. BAM. That's my hot take. Thank goodness I don't know how to let readers comment (or have readers), 
otherwise, I would be in trouble.

In all seriousness, there are a ton of incredible IDE's out there, and almost every single one I've used
so far can easily port in Vim key bindings. The best part of Vim is the keybindings and shortcuts, and the
fact that you can get them anywhere is beautiful.

## Summary
Vim is great. Emacs is great. Both have there strengths and weaknesses, and at the end of the day, you
can just get the shortcuts in your favorite IDE anyways. That said, Vim will always have a special place in my heart, and not
because it makes me feel like an elite programmer. Okay, that's part of it, but Vim set me down the road of shortcuts. 
Nothing feels better than taking annoying, repetitive tasks, and automating them and completing them with a shortcut.
Vim got me hooked on learning shortcuts, and that has bled over to every other facet of my life
(specifically when I use my computer). Firefox? SHORTCUTS! Linux? SHORTCUTS! Matlab? SHORTCUTS! (but they aren't
very good). Walking to Campus? SHORTCUTS!  

Us Vim and Emacs users may have our disagreements, and it can be fun to play up our rivalry in a playful way, but at
the end of the day, at least we don't use Notepad++.


*References:*

[vim_link]: "https://en.wikipedia.org/wiki/Emacs"
[emacs_link]: "https://en.wikipedia.org/wiki/Vi"
[so_link]: https://insights.stackoverflow.com/survey/2019
[^fn1]: [<a href="https://en.wikipedia.org/wiki/Vi">wiki</a>, <a href = "https://en.wikipedia.org/wiki/Emacs">wiki again</a>]
