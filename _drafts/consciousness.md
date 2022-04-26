---
layout: post
title: Consciousness is not computation
date: 2022-02-19
categories: ml
image:
  feature: constellations3.jpg
---

Spend enough time in the tech world, and you will sooner or later find that it
is a common article of faith that computers will one day gain consciousness.
With powerful enough computers and sophisticated enough AI, the reasoning goes,
it is inevitable that eventually computers will become conscious just as we
are.  In fact, some are even bolder and claim that this isn't just something
that will happen way off in the distant future, but that the age of conscious
computers is upon us already.  David Chalmers [famously][1] [argued][2] that we
must be open to the idea that any feedback system, even one as simple as a
thermostat, is conscious, even if in a limited way.  And recently AI researcher
Ilya Sutskever [speculated][3] that today's neural networks may be conscious.

The idea is admittedly an attractive one.  At the core of the philosophy of
mind is what Chalmers called "the hard problem of consciousness."  How can
purely physical processes give rise to the apparently subjective experience of
consciousness?  This problem has bedeviled philosophers from the time of
Descartes, and I think it's fair to say that none of them put forward any
especially compelling explanations.

But as computers developed in the middle of the 20th century, a promising idea
emerged.  It went like this: Perhaps the brain is like a computer and the mind
is like a computer program.  What is important, then, is not so much the
specific hardware of the brain, but the computer program that it is running.
This idea seemed to break the stranglehold of the purely physical and introduce
an abstract, non-physical entity that sits on top of the hardware, which seems
to neatly correspond to the way that consciousness seems to sit on top of the
brain. [[^7]] After centuries of fruitless efforts by philosophers at explaining
the origin of consciousness, it's easy to see how this new paradigm became
popular, particularly in the tech world as computers started to surpass humans
in a variety of tasks.

But the idea that consciousness is ultimately just a matter of running the
right kind of computer program is wrong. [[^8]]   Computation alone is
insufficient to produce consciousness.

This is, as I understand it, not a radical position among philosophers of the
mind these days.  John Searle in the 1980s cast doubt on the idea with the
Chinese Room argument.  The argument I'm putting forward here is, at root,
substantially similar to Searle's argument, but I've 

The idea that consciousness could be computation gained some
currency back in the 1960s and 1970s as general purpose computers were being
developed and the theoretical tools to formally study computation were
codified.  It was clear as this was happening that a new paradigm was emerging.
Explaining conciousness had been one of the thorniest problems of philosophy
since the time of Descartes --- could this radical new paradigm of computation
explain it?

But a handful of arguments in the late 1970s and early 1980s cast doubt on this
new idea, with John Searle's Chinese Room argument being the most influential.
The Chinese Room argument has had its share of critics, but today, some forty
years later, my sense is that it has .

But I think that the point that the Chinese Room argument is really making can
sometimes get obscured by the details of the thought experiment, so 


This position started to gain some currency among philosophers who studied
philosophy of mind back in the 1960s and 1970s as the [TODO funnctionalism?] .
As general purpose computers were being developed and the theory behind
computer science , and was clear that a new paradigm was emerging.  Explaining
conciousness had been one of the thorniest problems of philosophy since the
time of Descartes --- could this radical new paradigm of computation explain
it?  the idea is But a trio of three counter-arguments around the same time.  Philosophy moves fairly slowly, but I
think it's safe to say that today, 50 years on, the position that consciousness
is computation is not widely held.


The argument that consciousness is not computation [TODO footnote note that
computation may be *necessary*, but it cannot be sufficient] has two parts.
The first is that  [qualia exists] .  The second half is that computation
cannot produce these feelings.


## Some preliminaries

### What I mean by "consciousness"

Before getting too deep we need a working definition of consciousness.  This is
one of the trickiest concepts to define rigorously since it seems that a
rigorous definition of consciousness practically requires a theory of
consciousness itself.  To make matters worse, in these kinds of discussions it
oftentimes gets mingled with related ideas of self-awareness, intelligence, and
executive function.  But in this post I am interested only in consciousness as
a sort of perception --- an awareness of being, or, more loosely, "what it
feels like to be something."

This aspect of consciousness is sometimes called "qualia." [[^1]]  I won't
rehearse the classic arguments for the existence of qualia since, like
Descartes, I regard my own qualia as an empirical fact --- indeed, perhaps the
only empirical fact that I can know for certain. [[^6]]  Of course given any
position in philosophy you can find *some* philosopher who has made the case
for it, and Daniel Dennett has made the case that [qualia does not exist][6].
But I will leave it to you to reflect upon your own existence and ask if you do
believe yourself to be conscious.  If so, we can proceed from there.  If you do
not believe yourself to be conscious, then the rest of this argument doesn't
matter anyway since, well, you're not conscious.

So if we accept that qualia exists (which, after all, seems intuitively
sensible), we are burdened with the apparently impossible task of explaining
how consciousness is generated by physical processes.  This is, in Chalmers's
words, the "hard problem of consciousness."

#### Consciousness is observer independent

It's worth pausing here and noting one property of consciousness that will be
of use to us later: consciousness is independent of external observers.  By
this I mean that my consciousness does not depend on other observers perceiving
me to be conscious.  Even if everyone else in the universe should deny that I
am conscious --- or if those other observers did not exist at all --- this
would have no bearing on my own consciousness.  If, in a terrible catastrophe
all life on Earth should perish, except by some strange fortune my own,
my consciousness would not suddenly dissipate.

### What is computation?

We also need a working definition of computation.  Fortunately here we are on
much firmer ground than we are when trying to define consciousness.
Computation, in the broadest sense, is the manipulation of symbols according to
an algorithm.  The largest and most important category of computation is the
set of algorithms which can, in principle, be executed on a Turing machine.  As
far as we know, every algorithm that can be run on a physical computer can also
be run on a Turing machine. [[^2]]

#### What is a computer?

There is then the companion question of what exactly constitutes a computer.
Now, a Turing machine is a purely mathematical abstraction, like a circle or a
fractal.  We can manifast things in the real world which can be well modeled by
a circle, but the abstract idea of a circle is distinct from a drawing of a
circle.

Likewise we can build an object in the real world which can model the behavior
of the abstract Turing machine.  And, more practically, we can build devices
whose behavior, while not identical to that of a Turing machine, can compute
the same things.  We call such devices computers.

It's important to understand exactly what the physical computer is.  It is a
device which has physical states, and whose physical states map onto the
states of a Turing machine.  The Turing machine is a mathematical
abstraction, whereas the computer is a mapping of physical states onto that
mathematical abstraction.  We can, for example, make a correspondance between
the voltage levels in a CPU register with the state of the Turing machine;
likewise we can make a correspondance between the magnetic moments on the hard
drive with the states of the Turing machine's ticker tape.

#### How accurate does a computer need to be?

We generally expect computers to be deterministic.  If we run the same program
twice, the computer should generate the same results. [[^9]]  But achieving
complete determinism is impossible.  Sometimes, very rarely, the computer will
make a mistake --- a cosmic ray, for example, will fly through and flip a bit
somewhere.  [[^3]]  If we decide that a machine is not a computer simply because
it ever makes *any* errors, we will have to conclude that there are no
computers at all in the real world.  And if computers don't exist, then
consciousness cannot be computation.

But it's not necessary to impose such a strict requirement.  We don't need to
ask that the computer *never* make a mistake.  We only need to require that the
computer not make a mistake when we run our program.  If, during the program's
execution, every abstract state of the ideal Turing machine can be mapped on to
a physical state of the system, we can say that the system is computing the
algorithm.  If it makes a mistake somewhere and breaks that correspondance,
then it stops being a computer for the time being, or at least a computer
corresponding to that particular Turing machine.

This definition of a computer as a mapping between the physical states of a
system and the abstract states of a Turing machine is powerful because it
abstracts away the internal physical workings of the computer.  The computer
can use transistors or vacuum tubes or something else entirely, and we can just
focus just on what the abstract Turing machine is doing.  As long as the states
and outputs correspond to what you would get with a Turing machine, no matter
what physical mechanism is producing those states and outputs, we can fairly
call the device a computer.  Computer scientists don't need to know anything
about Kirchhoff's laws to determine whether $$P = NP$$.

## Consciousness in a field of rocks

Since computation is independent of the physical mechanism it uses to transform
its states and produce outputs, we can imagine (impractical) computers that are
made out of things other than electronics.  We can create mechanical computers
out of [Legos][7] or [balls tumbling down a pegboard][4].  A wonderful cartoon
from [XKCD][5] imagined an individual who finds himself in a vast desert filled
with rocks.  To allay his boredom, he manipulates the rocks on the desert to
produce a computer and in so doing, simulates the entire universe, instant by
instant.

Now, if consciousness were a consequence of pure computation, it would be
possible to write a clever computer program (let's call it `consciousness.py`)
that, when executed on a big enough computer, produces a conscious being.  But
computation is independent from the physical substrate that the computation is
performed on.  So if a powerful supercomputer can produce consciousness by
running `consciousness.py`, we should also be able to produce a conscious being
by running the same `consciousness.py` program by running it with enough Legos
or by manipulating enough rocks in a desert.

## Does iron become conscious when it's hot?

Now it already seems implausible to me that a vast desert of rocks being
manipulated into various patterns is conscious.  What exactly is conscious
here?  What happens if I accidentally kick a rock to the side --- have I killed
whatever ghostly being inhabits these rocks?  Nevertheless, simply asserting
its implausibility is not the most compelling argument.  Sure, it is hard to
imagine what it means for this vast desert of rocks to be conscious, but there
are lots of unintuitive things in this world.  We shouldn't let our prejudices
as to what substrate consciousness *should* exist in prevent us from accepting
that it could very well exist in a substrate which is unfamiliar to us. [[^5]]

But let's follow where this argument takes us.  Rather than manipulating rocks
in a desert, let's imagine a bar of iron heated past the Curie temperature.
Each atom in the bar has a magnetic moment which points either up or down.  For
simplicity, let's assume that the bar is very hot and that the magnetic moment
of each atom is randomly flipping between up and down.  Moreover we have the
means to observe whether the magnetic moment of every atom in the bar is up or
down at any given time.

I want to determine if this bar of iron is consciousness, so I examine its
atoms to see if it is running `consciousness.py`.  I designate the first $$N$$
atoms to be input bits, another $$N$$ atoms to be internal states of the Turing
machine, and then another $$N$$ atoms to be outputs.  Then I look at the
magnetic moments of those atoms sampled at different time steps and see if they
correspond to the inputs, outputs, and intermediate states of
`consciousness.py` by designating a moment pointing "up" as a 1 and a moment
pointing "down" as a 0.  Naturally, there is no correspondance so I conclude
that the bar of iron is not conscious.

Simultaneously, however, my friend Alice performs the same observation.  But
rather than designating atoms pointing "up" as a 1 and a moment pointing down
as a 0, she considers an atom pointing up to be a 1, unless it's the first atom
in teh bar, in which case it's a 0.  Naturally, she, too, observes no
correspondance with `consciousness.py` and concludes that the bar of iron is
not conscious.

But another friend of mine, Bob, makes the same observation, but uses a
slightly different encoding.  He considers an atom pointing up to be a 1,
unless it's the second atom in the bar, in which case it's a 0.  Simiarly Carl
performs the same observation, but in his encoding, an atom pointing up is a 1
unless it's the third atom, and so on.  Eventually we get to Ada, who encodes
an atom pointing up as a 1 unless it's the first or second in which case it's
a 0.  Then Barbara, who encodes an atom pointing up as a 1 unless it's the
first or third.

Continuing this, we can imagine an enormous crowd of observers staring at this
iron bar, each using a unique encoding of atomic states to bits.  With a
sufficiently large number of observers, one of them will, by chance, happen to
observe that the states of the atoms correspond exactly to the bits of a Turing
machine computing `consciousness.py`.  This observer will then conclude that
the bar of iron is a computer running `consciousness.py` and is therefore
concsious.

But!  If a single observer can correctly determine that the bar of iron is
conscious, we must conclude that the bar of iron is conscious for *everybody*,
because concsiousness is observer independent.  If true honest-to-God
concsiousness is just a matter of running `consciousness.py`, we have indeed
found someone who has correctly observed the bar of iron to run
`consciousness.py` and we must conclude that the bar of iron *really is
conscious*.

To go further, I have not specified what `consciousness.py` is, and presumably
there are many possible `consciousness.py` programs.  There is
`alices_consciousness.py`, `bobs_consciousness.py`, along with
`joes_consciousness.py` and `your_consciousness.py`, which are the programs
that generate Alice's, Bob's, my own, and your consciousnesses, respectively.
The iron is running *all of them*.  So not only is the bar of iron conscious,
it contains my consciousness, your consciousness, and *all possible
consciousnesses*.

And of course there's nothing special about the iron itself.  We could make the
same argument with any system where we can map states to bits.  We could
imagine doing the same thing with a large enough number of coin tosses or the
locations of atoms in the air of a room.  In all cases we are forced to
conclude that a sufficiently large system contains all possible
consciousnesses.  So the proposition that consciousness is computation leads
quite inextricably to a sort of panpsychism.  But even if we could stomach a
classical panpsychism that has a vague sense that all things are conscious,
even if in a very limited way, this goes far beyond that.  We are forced to
conclude that large groups of atoms aren't merely conscious in some vague
sense, but they contain *all* consciousnesses, including our own.

## Computers can still be conscious!

Now I want to be quite clear about the position I am arguing for.  By saying
that consciousness is not computation, I am *not* claiming that computers are
not or never can be conscious.  We could imagine a world in which consciousness
is, for example, produced by electric fields that fluctuate in the right
patterns.  Perhaps, in such a world, my laptop running `consciousness.py`
produces the right patterns just as the neurons in the brain do, and becomes
conscious.

But in this world, consciousness is, at root, a *physical* phenomenon, not a
purely computational phenomenon.  Computation may be necessary to produce
consciousness, but my claim is that it cannot be sufficient.  Yes I can run
`consciousness.py` on a digital computer and produce a conscious being, but if
I run the same program on the "rocks in a desert" computer or the "hot iron
bar" computer, I will not.  In this case, consciousness is then
hardware-dependent.  But computational phenomena are independent of the
hardware they are run on. If consciousness were a purely computational
phenomenon, this would not be possible.  Any machine that runs the same
computation would produce the same phenomenon.

If we are to claim that a GPU executing a neural network is conscious, we have
to explain what it is about this specific, physical system that is producing
consciousness.  We cannot invoke the pure computation alone.

## Syntax is not semantics

The argument that computation is not consciousness can be summed up in a single
slogan: syntax is not semantics.  All computers can do is shuffle lumps of
matter around, whether that be rocks in a vast desert, or states of voltage .
But these lumps of matter have no intrinsic meaning.  The only reason we call a
box with a CPU in it a "computer" is because the operation of the voltages
across different parts of the CPU happen to map onto bits that we have defined,
and when these voltages interact they do so according to the rules of a set of
logical operations which we have defined.  But there is no meaning to the
physical system apart from what we, as external observers, have imposed on it.

Of course it is simplest to build a computer where the high voltage states
correspond to 1s and the low voltages states 0s.  But there is no requirement
to build a computer that way.  We could build a perfectly valid computer where
the high voltage states of even valued states correspond to 1s and where they
correspond to 0s in the odd valued states.  The system only "computes" because
of the way we have encoded information.

So computer simulations can never , since the "simulation" is not an
independent system.  It is only defined in terms of its relation to an external
observer.  A simulation of a brain cannot produce consciousness any more than a
simulation of the weather can produce rain.

## So what is consciousness then?

The idea that consciousness comes from computing a particular kind of program
is seductive because it seems to lay out a path towards understanding where
consciousness comes from.  If only we could write a clever enough computer
program, we could figure it out.

But if consciousness is not computation, then what is it?  This, of course, is
perhaps the hardest problem there is.  I don't claim to have the answer to this
question, but I think there are a few properties of consciousness that we have
to explain if we want a good theory of consciousness.

### Consciousness is in the brain

The first most basic fact about consciousness is that consciousness seems to be
very closely linked to the brain.  This has been suspected since antiquity and
modern neuroscience backs up this intuition.  My consciousness does not fall
off my body if I clip off a fingernail nor even if I chop off my arm.  But if a
neurosurgeon slices off a piece of my brain, or severs some connections, my
consciousness may radically alter.  If my body is functioning but my brain is
not, I will not have consciousness, whereas if my brain is functioning, my body
can be in very bad shape and I can maintain my consciousness.

So clearly consciousness has something to do with the activity of neurons.  But
consciousness cannot just be an inherent feature of neurons because the
cerebellum contains four or five times as many neurons as the cerebral cortex,
but does not seem to possess any consciousness.  

and any theory of consciousness needs to explain the connection between what is
going on in the brain and qualia.  Beyond that, such a theory needs to explain
why the *rest* of me is apparently *not* conscious.  There is something special
going on in the brain and only the brain (as far as we can tell) that seems to
produce consciousness.

### Consciousness is discrete

The second important property of consciousness that any theory needs to explain
is that consciousness is a single, cohesive experience.  My consciousness is of
my entire self.  It is not of half of myself, nor is it of some superposition
of you and me.  Somehow, whatever is going on in my brain to produce my
consciousness contains my whole brain, not just a subset of it, and that it
doesn't also include anyone else's brain.

Some individuals with severe epilepsy have to have the corpus callosum severed.
The corpus callosum joins the left hemisphere to the right hemisphere.  Once
these individuals have the corpus callosum severed, they seem to exhibit having
*two* consciousnesses rather than one.


The "consciousness is computation" argument essentially fails to account for
this fact.  Since "a computing system" is not well defined in physical space,
it's impossible to say where the computer ends and the rest of the world
begins.  We are fooled by the fact that the computers we are familiar with are
put in neat boxes.  But if our computer is just a bunch of rocks on the sand
the limits of the "computer" are much less clear.  The "consciousness is
computation" argument plays on our intuition that the CPU is like a brain and
the box that the computer is in is like a skull.

### New biology or new physics?

The "hard problem of consciousness" is that there appears to be what Chalmers
has called an "explanatory gap" between a purely physical description of the
universe and the subjective experience of qualia.  How do you go from the
positions and motions of atoms and fields to awareness?  There seem to be no
scientific tools available to us that bridge this gap.  But maybe the answer to
these questions lies in currently undiscovered biological effects or even new
physics.

John Searle is one of the better known proponents of what he calls "naive
realism" and has argued that the only reason that we can't explain
consciousness is that we just don't know enough about the biology of the brain.
In the late 1800s there were heated philosophical debates about whether life
required a mysterious "vital force" or if it could be produced through ordinary
physical interactions.  As biochemists learned more about the chemistry of life
they found that it was the latter and people forgot that this was even a
question that had ever been debated.  Perhaps the same is true of
consciousness.  As we learn more about neurobiology, we will come to see that
consciousness is just generated as a biological process "in the same way that
the stomach produces digestion," in Searle's words.  Then these centuries of
speculation about the "hard problem of consciousness" will be viewed by our
descendents to be as quaint as the debates about vitalism.

I mentioned in the introduction that for any idea, no matter how crazy, you can
always find some philosopher who has propounded it.  In this vein, the
physicist Roger Penrose has argued that an explanation of consciousness does
not merely require new biology, but new physics as well.  I have to confess
that as far-fetched as it seems, I am somewhat partial to the idea.  The
concept of a quantum state has the nice property that, like consciousness, it
is attached to physical objects, but nevertheless extends across space as a
cohesive whole.

Furthermore, this idea has the advantage of providing a connection to one of
the most mysterious features of quantum mechanics --- the collapse of the
wavefunction.  This feature has always sat uncomfortably within the orthodox
Copenhagen interpretation because it is not entirely clear what constitutes an
"observation" that triggers the collapse.  Eugene Wigner among others argued
that it is only a conscious observer who can trigger the collapse of a
wavefunction.  It is an odd idea, but odder things have turned out to be true!

But I will concede that this is nevertheless a far-fetched idea just because the
brain is a warm and noisy environment.  Entanglement, at least in any form that
we know of, is too delicate a state to be maintained in the brain for any
length of time.

I suspect, for the forseeable future, we will be stuck with apophatic
approaches to the hard problem of consciousness.  While we won't be able to say
much about what consciousness *is*, we can at least learn something by saying
what it is *not*.  And we can be confident in saying that computation is among
the long list of things that are not consciousness.

----

## Footnotes

[^1]:
    Strictly speaking, "qualia" refers to individual conscious experiences ---
    the sensation of hearing a bell, for example --- whereas consciousness is
    the unified collection of all qualia that a conscious being experiences. In
    fact this makes the problem of consciousness harder than qualia on its own,
    becaues a theory of consciousness needs to explain not only individual
    perception experiences, but how a collection of these experiences across
    space and time can be unified into single, coherent experience of being.

[^2]:
    The statement that this is true for all algorithms is known as the
    Church-Turing Thesis.  Some algorithms can be exponenitally faster if they
    are run on a quantum computer than if they are run on a Turing machine,
    which is inherently classical.  Nevertheless, for our purposes the
    algorithmic efficiency isn't relevant.  As far as we know, anything that
    can be computed by a quantum computer can also be computed by a Turing
    machine, and it is only the question of computability that matters to us.
    compute the algorithm which is relevant to us.

[^3]:
    This happens more frequently than you might think.  You can actually run an
    app on your smartphone that uses the camera as a cosmic ray detector.

[^5]:
    This is the so-called "systems response" to John Searle's Chinese Room
    argument, though presented in an oblique way.  The argument is that while
    the rocks themselves might not be conscious, the whole *system* of the
    rocks being manipulated *is* conscious.  In Searle's thought experiment the
    computation being performed was an individual in a room manipulating
    symbols according to rules in a book rather than rocks in a desert, but the
    underlying idea is the same.

[^6]:
    The classic argument that qualia exists is due to Frank Jackson in the
    article "What Mary Didn't Know."  I encourage you to read the original
    article (and the Wikipedia article is quite good, too), but in brief, the
    argument proposes a thought experiment: Suppose there is a scientist named
    Mary.  Through extensive study, she has learned all there is to know about
    the physics of color, the physiology of the eye, and the neurology of the
    brain.  Given some stimulus like looking at a red rose, she knows exactly
    how the light impacts the eye, how the image forms on the retina, how this
    produces a signal along the optical nerve, and how the brain processes this
    signal.  However, Mary has lived her entire life within a black and white
    room and has never perceived color herself.  One day, she leaves the room
    and looks at a red rose.  Does she learn anything new from this experience?
    If she does, we are forced to conclude that qualia exists --- that an
    experience is distinct from perfect knowledge of how the brain reacts to
    the stimuli that produced that experience.

[^7]:
    The formal name for this theory is "functionalism", and the basic idea is
    that the physical constituents aren't relevant to a mental state --- all
    that matters is that the system functions appropriately.  In the case of a
    computer program, it doesn't matter what computer you run the program on,
    the important thing is the program itself.
 
[^8]:
    Or at least, if we are to accept that proposition, we are forced into the
    position of panpsychism, in which all matter is conscious and our
    consciousnesses are not bound to anything at all.

[^9]:
    It was for good reason that the authors of Numerical Recipes described
    random number generation as a "perverse" use of a computer.  A machine
    which is designed to be deterministic is not well suited to behaving
    randomly!


[1]: https://annakaharris.com/chalmers/

[2]: http://www.consc.net/notes/lloyd-comments.html

[3]: https://twitter.com/ilyasut/status/1491554478243258368

[4]: https://www.turingtumble.com/

[5]: https://xkcd.com/505/

[6]: https://ia801304.us.archive.org/22/items/FritjofCapraTheTurningPoint/Daniel%20C.%20Dennett%20-%20Quining%20Qualia.pdf

[7]: https://abakcus.com/video/lego-turing-machine/