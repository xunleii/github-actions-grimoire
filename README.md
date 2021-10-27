# Github Actions - :closed_book: Grimoire
> A grimoire (/ɡrɪmˈwɑːr/ grim-WAHR) (also known as a "book of spells") is a textbook of magic, typically including instructions on how to create magical objects like talismans and amulets, how to perform magical spells, charms and divination, and how to summon or invoke supernatural entities such as angels, spirits, deities and demons.
> *[Wikipedia](https://en.wikipedia.org/wiki/Grimoire)*

So, after having read the Github blog post about [keeping our Github Actions DRY](https://github.blog/changelog/2021-10-05-github-actions-dry-your-github-actions-configuration-by-reusing-workflows/), I wanted to share with you my common used Github Actions.

## List of shared Github Actions
### Security
- [Security hardening for Github Actions](.github/workflows/security.workflows.yaml) ([see usage](.github/workflows/run.security.workflows.yaml))<br>
  [![Security hardening (Github Actions workflows)](https://github.com/xunleii/github-actions-grimoire/actions/workflows/run.security.workflows.yaml/badge.svg)](https://github.com/xunleii/github-actions-grimoire/actions/workflows/run.security.workflows.yaml)
  - Checks if you all of yours Github Actions uses pinned Actions
  - Checks javascript syntax with CodeQL

## Can I contribute to this "book" ?
Of course, and I really appreciate any contribution on this repo to get a sort of shared workflow collection that everyone could use.
