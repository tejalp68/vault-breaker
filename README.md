# ⚡ Vault Breaker

So basically i made this small python game where you're a hacker breaking into a vault. every level you collect energy, boost it, blast through walls etc using different operators like `+`, `-`, `*`, `/`, `//` and `%` its not a big project just something i built to actually understand how operators work instead of just reading about them

## what it does

you go through 7 levels, each one is basically a mission and each one teaches a different operator:

- **level 1** — collect energy (`+`)
- **level 2** — boost your power (`*`)
- **level 3** — blast through a laser wall (`-`)
- **level 4** — split energy between your team (`/`)
- **level 5** — figure out how many hackers you can fully power (`//`)
- **level 6** — leftover energy after that (`%`)
- **level 7** — final vault power (`**`)

at the end it shows a little summary of everything you did kinda like a mission report

## how to run it

just need python installed, then:

```bash
python energy_vault.py
```

and follow whatever it asks you in the terminal

## example run

check out output.md for a full sample run.

## what i actually learned making this

- arithmetic operators (`+ - * / // % **`) and how they behave differently
- `int(input())` to get numbers from the user
- f-strings to print stuff nicely
- how one level's output feeds into the next one
