# PRIMER PRIME
## Computers as I understand them

by Stuart P. Bentley

## Foreword

I'm not sure where I learned the stuff I'm going to write here. I think it
started somewhere around Wikipedia, then spiralled off into perusing the Jargon
File, sprinkled with some loose Googling into long-forgotten 1993 home pages
and archived posts to mailing lists. Raymond Chen's blog,
[The Old New Thing][], contributed a lot to my understanding of the history of
Windows.

[The Old New Thing]: http://blogs.msdn.com/b/oldnewthing/

There's no real authority to any of this: I wasn't around for pretty much all
of the stuff I'm going to write about. Most of this is me half-remembering
things I read on the Internet somewhere and filling in the gaps with
over-simplistic interpretations and assumptions that fit the narrative I've
arbitrarily constructed.

Since I'm writing this as a text document on GitHub, if you read this and
notice that I've got something rather wrong, you can suggest an edit by
submitting a GitHub pull request, or just email me at:

<stuart@testtrack4.com>

This document is formatted as Markdown with footnote syntax.

## Introduction

Computers are more of a story than a science. Programming is less about
understanding complex mathematical theories than it is about knowing why people
made the weird decisions that shaped every interaction we have with computers
to this day.

## Chapter 1: Everything Before The Sixties

The first computers ever invented are generally agreed to be Charles Babbage's
Difference Engine and Analytical Engine, mechanical devices designed around the
1840s. Lady Ada Lovelace (daughter of Lord Byron) wrote a sequence of
operations that could be performed using the Analytical Engine, that would be
the first computer program ever.

However, while Babbage's designs for the machines were complete by the time of
Babbage's death in 1871, a working Difference Engine wouldn't be built until
nearly a century later, and a completed, working Analytical Engine, as of June
2015, [has never been built][Plan 28]. As a result, the widespread influence of
these particular machines that Babbage envisioned never materialized: when the
first computers as we think of them were built around the time of World War II,
their builders did it from scratch, with little to no awareness of how the
Analytical Engine would have worked.

[Plan 28]: http://www.plan28.org/

Here are the lessons of this story that are relevant today:

1. The most detailed plans will never be more than a historical footnote if you
   can't carry them out.
2. Just because something's possible with current technology, doesn't mean you
   should *try* it with current technology.
3. Female programmers were here first.

The two most influential developments of the nineteenth century on modern
computers would be much more pedestrian: the telegraph and the typewriter.

### The Electric Telegraph

The notion of sending messages electrically had been in discussion since the
eighteenth century, but ran into problems around the notion of long-distance
transmission. You can't just string one wire the whole way for very long
distances, since eventually the electric current can't make it from one end
of the cable to another.

#### The Relay Switch

Relays are how this got fixed: you'd take from a new, locally-generated
electric source, and then re-transmit the electrical state of your input by
having that input magnetically pull the switch for the new electricity.
(This ended up being really useful for building more complex electrical
machines, prototyping the domain of solid-state electronics, but that's a
whole separate topic from this current telegraph/typewriter narrative.)

Ultimately, practical implementations of electrical telegraphs didn't really
start until about a century later.

#### Cooke and Wheatstone

The UK's Great Western Railway had one of the earliest
electrical telegraphs, which started out using six parallel electrical cables,
so as to make figuring out the letter being communicated "easy" by following
a series of left/right branches. However, these six parallel cables ended up
requiring a lot of maintenance, and as the cables would get damaged, the
operators (who had quickly gotten used to which series of switches referred
to which letters) would need to devise more complex codes using fewer
switches.

Meanwhile, in America, Samuel Morse was devising a telegraph system that used
a single line to transmit its messages, along with a specially-designed code.

#### Morse Code

#### An Appreciation for Binary/Digital

#### Punched Paper Tape

#### Baudot code

### The Typewriter

#### Western Union

### The Telephone

The pendulum swung back to an analog technology

#### Bell

### The TeleType

### IBM & EBCDIC

## Chapter 2: The Sixties

### ASCII
