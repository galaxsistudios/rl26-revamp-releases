# FAQ

Quick answers to the questions players ask most.

**Installing and updating**

- [What do I need?](#what-do-i-need)
- [Why does the first install take so long?](#why-does-the-first-install-take-so-long)
- [Windows SmartScreen warned me about the launcher. Is it safe?](#windows-smartscreen-warned-me-about-the-launcher-is-it-safe)
- [The install stopped part way. What now?](#the-install-stopped-part-way-what-now)
- [How do I update?](#how-do-i-update)
- [Steam updated the game. What do I do?](#steam-updated-the-game-what-do-i-do)
- [How do I go back to the stock game?](#how-do-i-go-back-to-the-stock-game)

**Saves**

- [Are my saves safe?](#are-my-saves-safe)
- [Will my old careers still work?](#will-my-old-careers-still-work)
- [How do I restore a backup?](#how-do-i-restore-a-backup)

**Playing**

- [Can I play online?](#can-i-play-online)
- [Where are the Revamp's settings?](#where-are-the-revamps-settings)
- [How do I skip the intro?](#how-do-i-skip-the-intro)
- [How do I get PlayStation button prompts?](#how-do-i-get-playstation-button-prompts)
- [The game feels too hard (or too easy) since installing. Why?](#the-game-feels-too-hard-or-too-easy-since-installing-why)
- [What's the bar on the right of my player's card?](#whats-the-bar-on-the-right-of-my-players-card)
- [I'm streaming. Is the music safe?](#im-streaming-is-the-music-safe)

**Other mods and games**

- [Can I use Blobset Tools mods with the Revamp?](#can-i-use-blobset-tools-mods-with-the-revamp)
- [What's the Rugby 25 Expansion?](#whats-the-rugby-25-expansion)
- [Do I need Rugby League Live 4 for the old kits?](#do-i-need-rugby-league-live-4-for-the-old-kits)

**Problems**

- [How do I report a bug?](#how-do-i-report-a-bug)
- [The game crashed. Where are the crash reports?](#the-game-crashed-where-are-the-crash-reports)

---

## Installing and updating

### What do I need?

- Rugby League 26 on Steam (PC), fully updated
- Windows 10 or 11
- About 12 GB of free disk space
- 30 to 45 minutes for the first install

Download **RL26-Revamp-Launcher.exe** from the
[latest release](https://github.com/galaxsistudios/rl26-revamp-releases/releases/latest), run it and click **Install**.

### Why does the first install take so long?

The Revamp is **built on your PC from your own copy of the game**, so no game files are handed around. The launcher
downloads about 1.1 GB, then rebuilds textures, kits, crowds, coaches and menus from your game files. Updates are
much quicker: usually a few minutes.

### Windows SmartScreen warned me about the launcher. Is it safe?

SmartScreen warns about any new program that few people have downloaded yet. Choose **More info**, then **Run
anyway**. If Windows **Controlled folder access** is on, allow the launcher through it as well, or it can't write to
the game folder.

### The install stopped part way. What now?

Open the launcher again. It offers **Resume install**, which carries on from where it stopped. If a newer release is
out, take the update first, then resume. If it keeps stopping at the same place, send a [bug report](#how-do-i-report-a-bug).

### How do I update?

Open the launcher. When a new release is out it offers an **Update**: it downloads only the changed files, re-runs
the steps they affect and backs up your saves first. The launcher checks for releases when it opens, so reopen it to
see a new one.

### Steam updated the game. What do I do?

A game update can replace files the Revamp changed. The launcher warns you when the game has been updated since the
release was built. Wait for a Revamp release that supports the new game version, then update through the launcher.
If things look wrong in the meantime, **Repair** downloads the package again and does a full reinstall.

### How do I go back to the stock game?

Click **Revert to vanilla** in the launcher. It undoes every change and puts the game back exactly as it was, after
backing up your saves. You can install the Revamp again later.

## Saves

### Are my saves safe?

Yes. Before every install, update and revert, the launcher copies your whole `Saved Games\Rugby League 26` folder:
careers, competitions, your Academy players, clubs and kits, and your settings. The newest 10 automatic backups are
kept. **Saves & Academy > Back up now** makes one whenever you like, and those are kept until you delete them.

### Will my old careers still work?

Revamp careers and competitions save **separately** from stock ones. While the Revamp is installed you'll only see
Revamp saves, and stock saves come back when you revert. Nothing is moved or deleted.

The new career features need a **new career**. When a Revamp update changes the career save format, loading an older
career shows a warning that lists what changed. Starting a new career is the safe choice.

### How do I restore a backup?

In the launcher, open **Saves & Academy > Restore...**, pick a backup, then choose:

- **Everything:** careers, competitions, the Academy and settings; or
- **Only the Academy:** your custom and edited players, clubs and kits (careers stay as they are).

Your current saves are backed up first, so a restore can be undone. If Steam Cloud is on, Steam may offer its own
copy next time you play: choose the **local** files to keep the restore.

## Playing

### Can I play online?

No. Online play is switched off in the Revamp. A modded game behaves differently from everyone else's, and playing
online with mods risks your account. You can still browse and download Academy content. Before you upload anything,
the Revamp warns you that it may contain kits, logos or players other people don't have.

To play online, use **Revert to vanilla** first.

### Where are the Revamp's settings?

| What | Where |
|---|---|
| Gameplay (discipline, kicking, passing, AI, referees, HIAs, scrums...) | **Academy > Custom Difficulties**: edit a custom difficulty, then the stock tabs plus **MODDED**, **KICKING** and **LINE BREAKS** |
| Graphics and Revamp Lighting | **Settings > Graphics** |
| Music, team songs and menu playlists | **Settings > Audio > Manage Music** |
| Match options (referees, kick-off, ball, markings, crowd) | **Play Now > Match Settings** |
| Training drills | **Play > Training Mode** |
| Button icons and skipping the intro | The launcher's settings |

Custom difficulty settings only apply when you **play on that custom difficulty**. The preset difficulties use the
Revamp defaults. See [Turning it up, down or off](discipline-system.md#turning-it-up-down-or-off).

### How do I skip the intro?

Tick **Skip the boot splash screens** in the launcher and click **Apply settings**. You can also press Accept during
the intro to skip it.

### How do I get PlayStation button prompts?

Plug your PlayStation controller in **before** you press Play and the Revamp shows PS5 or PS4 prompts automatically.
To force a style (Xbox, PS4, PS5 or Switch), pick it in the launcher's settings and click **Apply settings**. If you
swap controllers, restart the game.

### The game feels too hard (or too easy) since installing. Why?

The Revamp changes a lot on the field: the CPU kicks better and uses its bench, passes can go wrong, and the
[discipline meter](discipline-system.md) makes tired, pressured teams crack. On harder difficulties your team's
discipline drains faster and the CPU stays calmer.

Make a custom difficulty (**Academy > Custom Difficulties**) to tune it: for example, lower **Discipline Strength**,
**Passing Errors** or **Kick Skill Effect**, or switch **Discipline** off.

### What's the bar on the right of my player's card?

That's his **discipline**. Blue is settled, red means he's close to giving away penalties or getting binned. See
[The Discipline System](discipline-system.md).

### I'm streaming. Is the music safe?

The menu music defaults to the **Non-Copyrighted (Stream Safe)** playlist. The **Copyrighted** playlist and the club
run-out, winning and try songs are real songs. Switch off any you don't want in **Settings > Audio > Manage Music**.

## Other mods and games

### Can I use Blobset Tools mods with the Revamp?

Yes, but only in Blobset Tools' **Mod Loader mode**. Don't use its other modes with the Revamp installed.

### What's the Rugby 25 Expansion?

An optional add-on for players who also own **Rugby 25** on Steam. It adds Rugby 25's tackles, celebrations, tunnel
walks and referee moments, converted on your PC from your own copy. The launcher shows **Add the expansion** when
Rugby 25 is installed, and **Remove** takes it out again. See
[What the Revamp Changes](whats-changed.md#the-optional-rugby-25-expansion).

### Do I need Rugby League Live 4 for the old kits?

No. The older kits come with the Revamp and are in each club's **KIT LIBRARY** (Academy club > Uniforms).

## Problems

### How do I report a bug?

1. Go to **Settings > Graphics > Revamp Diagnostics** and set **Debug Logging** to **On**.
2. Make the problem happen again, then quit the game.
3. In the launcher, click **Bug report**. It saves a zip of your logs to your **Desktop**, with your Windows user name
   removed.
4. Send the zip along with what you did and what went wrong.

Turn Debug Logging back **Off** afterwards. It writes a lot of files.

### The game crashed. Where are the crash reports?

In the `revamp_crashes` folder inside the game folder. You don't need to dig them out: the **Bug report** button
includes the newest ones.

[Back to the info index](README.md)
