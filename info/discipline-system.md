# The Discipline System

Rugby league isn't only about legs and lungs. Teams crack under pressure: they give away silly penalties, drop easy
balls and lose their heads after a big hit. The Revamp gives every player a **discipline meter** to model that mental
side of the game.

> **In short:** discipline starts at 100% for everyone. Bad moments drain it, good moments and calm spells bring it
> back. A player low on discipline makes more handling and kicking errors, loses more one-on-one contests, and at the
> very bottom gives away foul tackles that get him sin-binned or sent off.

**On this page**

- [Where to see it](#where-to-see-it)
- [What drains discipline](#what-drains-discipline)
- [What makes it worse](#what-makes-it-worse)
- [How players settle back down](#how-players-settle-back-down)
- [What low discipline does](#what-low-discipline-does)
- [The CPU under pressure](#the-cpu-under-pressure)
- [Captains](#captains)
- [Professional fouls after a line break](#professional-fouls-after-a-line-break)
- [Turning it up, down or off](#turning-it-up-down-or-off)
- [Tips](#tips)

---

## Where to see it

Look at the **player plate**, the card that shows the player you control. Discipline is the **thin vertical bar on
the right-hand edge** of the card, filling from the bottom. (Stamina is still the line along the bottom of the card.)

| Bar colour | Meaning |
|---|---|
| Ice blue | Settled, nothing to worry about |
| Yellow | Starting to feel it |
| Orange | Errors are creeping in |
| Red | On the edge: penalties, bins and send-offs are possible |

A red **RATTLED** tag appears while the player is rattled (see below).

## What drains discipline

| What happens | Who pays | Cost |
|---|---|---|
| Gives away a penalty | the offender (and he's rattled) | big |
| Gives away a six again | the offender (and he's rattled) | medium |
| Concedes a try | every defender on the field | medium |
| Concedes a line break | every defender, more for the ones who were beaten | small to medium |
| Gets fended, or has his tackle broken | the tackler (fended = rattled) | small |
| Gets hit by a big hit | the player hit (and he's rattled) | medium |
| Knocks on | the player who dropped it | medium |
| Defends a play-the-ball | every defender, more inside his own 40 m and much more inside his own 20 m | tiny, but it adds up over a long set |
| Golden point starts | everyone on the field, both teams | small |
| His team loses the lead | the team that was ahead, more if they're overtaken and more late in the match | small to medium |

Good moments help: scoring a try lifts the whole team on the field, and making a line break, breaking a tackle,
landing a big hit or fending a defender gives some discipline back to the player who did it.

The **bench doesn't take team hits**. Players sitting on the bench recover quickly.

## What makes it worse

Every cost above is multiplied by the player's situation:

- **Fatigue.** A fresh player (over 70% stamina) takes the normal hit. An exhausted one takes up to **three times**
  as much. Tired players make bad decisions.
- **Siege.** Each team has a pressure level. Penalties, six agains, tries and line breaks against you build it.
  Winning a penalty, scoring or landing a big hit relieves it. A team under siege loses discipline up to **twice as
  fast**.
- **Rattled.** For about two and a half minutes of match time after being penalised, fended or flattened, a player
  loses discipline faster and doesn't recover at all.
- **The scoreboard.** A team chasing a big deficit (18 points or more) gets desperate, especially late. A team well
  in front plays calmer. A tight finish (within 6 points in the last fifth of the match) puts both teams on edge.
- **Age.** Young players (20 and under) are the most volatile: they drain faster but also bounce back faster.
  Veterans (32+) are steady, but fatigue hits them harder.
- **Aggression.** A player's aggression rating (which the stock game doesn't use on the field) makes him drain
  faster and makes a send-off more likely.
- **Captains** drain slower and recover a little faster.

## How players settle back down

- **Calm spells.** While his team isn't under siege, he has over half his stamina and he isn't rattled, a player
  slowly gets his discipline back. It's slow on purpose: a fresh player roughly holds steady, a tired one sinks.
- **The bench.** Players recover much faster on the bench.
- **Referee warnings.** When the referee warns a team (the stock game's warnings for high tackles and ruck
  penalties), the whole team settles a little. A **final warning** settles them more and puts each player **on
  notice** for about 5 minutes, which cuts how much he loses.
- **Repeated penalties.** Three penalties of any kind in a short spell now also get the referee's final warning,
  with the call, the scoreboard banner and commentary. It doesn't bring a sin bin any closer.
- **Half time.** Everyone gets a boost (or is lifted to 60%, whichever is more), and siege, rattled and on notice are
  cleared.
- **The sin bin.** A binned player comes back settled (up to 60%), and his teammates rally a little while he's off.

How much a player gains from these moments depends on him: older heads, captains and calm (low aggression) players
settle better. Players who have cracked gain the most, and nothing lifts anyone above 85%.

## What low discipline does

**Errors (everyone, including you).** Below 50%, a player's passing, offloading, catching, goal kicking and field
goal skills drop, by up to a quarter at 0%. The game's own knock-on, bad-pass and kicking rolls then do the rest.

**Losing contests (everyone).** Below 60%, a player's fend, step, tackle break and tackling fade, so he's easier to
beat and easier to tackle. He's easier to strip and more likely to spill the ball in a big hit. A player who is very
composed (over 85%) gets a little better at all of it.

**Foul tackles (both teams, including you).** Below 35%, a front-on tackle can turn into a real foul: a **spear
tackle** or a **head-high hit**, using the game's own foul animations. It's always a **sin bin**, and below 10% it
can be a **send-off** (more likely for aggressive players and spears). Even a calm player very occasionally loses
it, but that can only ever be a sin bin.

**Straight to the bin (CPU).** A CPU player who gives away a high tackle while below 15% skips the team's warnings
and goes straight to the sin bin. Below 7% it can be a send-off.

The rule throughout: **a sin bin or send-off for foul play always comes from a tackle that looks illegal.** You'll
never be binned for a tackle that looked normal.

## The CPU under pressure

When a CPU team's discipline drops, it plays like a rattled team. It's more likely to:

- go for a **reckless big hit** instead of a safe tackle;
- force an **offload** in the tackle;
- make a **sloppy play-the-ball** (a lost or slow one);
- be **lazy getting back onside**;
- send a **kick chaser early**, and give away a penalty if he plays the ball while still offside.

That's how you get rewarded for pressure: keep a team pinned in its own end and it starts to make mistakes.

## Captains

After a setback (a try or penalty conceded, a line break, a teammate binned), a composed captain steadies his
teammates. A captain who has lost it himself unsettles them. A captain on the bench counts for less, and one in the
sin bin counts for nothing. If a captain is **sent off**, his team drains faster until a new one takes over (the CPU
names one straight away; your team gets a stand-in after 10 minutes or at the next half).

## Professional fouls after a line break

From a line break until the next play-the-ball, holding the tackler down is a **professional foul**: a penalty
anywhere on the field (never a six again) and a **sin bin**, for both teams. You can turn this off (see below).

## Turning it up, down or off

Discipline is **on** for every preset difficulty (Rookie to Legend). Harder difficulties drain **your** team faster
and keep the **CPU** calmer:

| Difficulty | Your team | CPU team |
|---|---|---|
| Rookie | x0.5 | x1.25 |
| Amateur | x0.75 | x1.1 |
| Pro | x1 | x1 |
| Veteran | x1.25 | x0.9 |
| Legend | x1.5 | x0.8 |

To change it, make your own difficulty: **Academy > Custom Difficulties**, edit one, and switch to the **MODDED** tab
(L1 / R1 switch tabs):

| Setting | What it does |
|---|---|
| **Discipline** | On / Off. Off: everyone stays at 100% and none of this happens. |
| **Discipline Strength** | How fast discipline drains, both teams (x0.25 to x3, default x1). |
| **Territory Pressure** | How much being pinned in your own end wears a team down (x0 to x3, default x1). |
| **Discipline Recovery** | How fast players settle (x0 = every mistake sticks, up to x3). |
| **Discipline Contests** | How much discipline decides fends, steps, tackle breaks and strips (x0 = off, up to x2). |

The **LINE BREAKS** tab has **Professional Foul Sin Bin** (on / off).

Settings are saved when you press Back, per custom difficulty name. Renaming a difficulty starts it fresh. Pick your
custom difficulty for a match and its settings apply. You can also share difficulties: press **Square** on the edit
screen to **Export to JSON** or **Import from JSON**.

## Tips

- **Rotate your bench.** Tired players lose discipline up to three times faster, and the bench is where they recover.
- **Get out of your own end.** Long sets defending your own line drain the whole team. A good kick to relieve
  pressure helps their minds as well as the scoreboard.
- **Watch the bar on your playmakers.** A halfback or fullback in the red is more likely to drop the ball or miss a
  kick.
- **Don't panic when you're behind.** Chasing a big deficit late is when teams crack. Scoring a try settles the
  whole team.
- **Squeeze the CPU.** Hold them inside their own 40 m and they start giving away penalties, forcing offloads and
  playing the ball sloppily.

[Back to the info index](README.md)
