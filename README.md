# Acheulean Lab Scripts

Collection of scripts used in [Acheulean Lab](https://www.acheuleanlab.com) 

--- 

## Stochastic Blur Text

A minimalist js animation to periodically blurs text at random. Built to animate a manifesto on web header: invites readers to look twice.

### Description

- Targets `.headertext` containers
- Chooses a random `<span>` child every 850ms
- Temporarily applies a **blur + opacity** filter
- Restores the span after 1.2s with a fade

---

## IPA Phonetic 

Tooltip Hover Animation for Pronnunceation Guide. Helps readers pronounce unfamiliar or scholarly terms (like “Acheulean”).

### Description

- Targets `.ipa-symbol` spans within an `.IPA` container  
- On hover, displays a tooltip showing the IPA character's phonetic value  
