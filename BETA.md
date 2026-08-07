# For beta testers

You are here early. The game is playable start to finish, it is not finished, and what you
say about it changes it — usually within a day, sometimes within an hour.

**You will already have the link.** It is not published here, and the beta is not open to
the public yet. If you were sent here without one, ask whoever pointed you at this page.

No account, no install, nothing to sign up for.

---

## What you can do

**Play it however you like and tell us what happened.** That is the entire job. You are not
running a test plan and there is nothing to tick off.

Three kinds of thing are all worth sending, and the reporter takes them all:

* **Something is broken.** It froze, it did the wrong thing, you got killed by something
  that should not have been able to kill you.
* **Something is annoying.** Not a defect — just worse than it should be. A sound that
  grates, a screen that does not explain itself, a menu that takes too many presses.
* **Something is missing, or you just want something.** "Can the projectiles not wrap
  around the edge?" was a suggestion, and it is a setting now.

The last two are the ones people talk themselves out of sending. Don't. Two of the first
handful of reports were suggestions, and both shipped.

## How to send it

Press <kbd>B</kbd> while you are playing. Type. Send.

That is all of it. You do not need to describe your setup, what level you were on, what
settings you had, or what your browser is — **a snapshot rides along automatically**: the
build, the screen you were on, the level, the seed, your settings, and a summary of the run
so far.

### The one thing that actually helps

**Say which thing you mean, by name.** There is no reply channel. Nobody can write back and
ask you what you meant, so an ambiguous report is one nobody can act on.

A real example, still unresolved because of exactly this:

> *"I DON'T LIKE THE SOUNDS FROM THE THRUSTER THAT LOOKS LIKE A DUST SWARM"*

Fair enough — but three of the nineteen thrusters could be described that way, and there
is no way to ask which one. Press <kbd>T</kbd> until you see the name in the corner and
put that name in the report, and it is a fixable thing instead of a guess.

Same for everything else: which screen, which power-up, which boss, which sound.

---

## What happens to it

1. **A human reads it.** Every report, before anything is published.
2. **It becomes an [Issue](../../issues) here**, quoted exactly as you wrote it, with the
   useful half of your snapshot attached.
3. **It gets checked against the actual code**, not taken at face value — twice now the
   real defect turned out to be worse than what was visible from the cockpit.
4. **If it gets fixed, the Issue is closed naming the build it went live in.** Deploys take
   about two minutes, so you can go and look.

You are not filing into a void, and you are not going to be told your report is a duplicate
of an internal ticket you cannot see.

---

## Worth knowing before you start

**Your save lives in your browser.** Nine slots, all local. Clearing site data for the
domain clears your runs — there is no cloud save and no account to restore from.

**The game redeploys constantly.** There is no version you are "on" for the evening; a fix
can land mid-session. If something looked broken an hour ago, reload before reporting it —
though a report on a stale build is still useful, and the snapshot tells us which one you
had.

**Some things are deliberately hidden.** Most gameplay settings are locked until you find
THE CONTROL ROOM, which is a place in the game rather than a menu. That is not a bug. What
is *never* locked: accessibility settings, and anything that ships switched on.

**Difficulty is not tuned.** It is a first pass. "This is too hard" and "this is too easy"
are both real reports, and neither will offend anyone.

---

## Not in this beta yet

So you know what is out of scope rather than reporting it as broken:

* **Online play.** You will see a **MULTIPLAYER** entry on the main menu and it does
  something. It is half-built, it is not what this beta is for, and it is not being tested
  yet — so please spend your time on the single-player game. You are not missing anything
  by ignoring it, and a report about it is not wasted so much as early.
* **A release, on any platform.** There is no date, no store page and no launcher.
* **Anything with an account attached** — no logins, no profiles, no cloud saves, no
  leaderboards.

---

## If it will not run at all

The game is 2D canvas with no shader path, so it does not ask much of a machine, but if it
will not start there is nowhere to press <kbd>B</kbd>. Open an
[Issue](../../issues/new) here directly and say what browser you are on.

---

*Thank you. Genuinely — the ghost laser that kept killing people after its owner was
already smashed was found by a beta tester who could have just assumed they were bad at the
game.*
