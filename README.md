# Kana Trainer

A web app for drilling Japanese kana character recognition. Built for anyone who wants to learn to read hiragana and katakana.

## What it does

This app does one thing well: it teaches you to **recognize** kana characters. You won't learn vocabulary or grammar, just the ability to look at a character and know how to read it.

## Features

- **Study Mode** — flip through flashcards at your own pace, reveal the romaji when ready
- **Quiz Mode** — characters appear one at a time, you type the romaji, get instant feedback
- **Line selector** — choose which rows to study (A, K, S, T, N, H, M, Y, R, W)
- **Dakuten support** — include voiced consonants (が, ざ, だ, ば, ぱ...)
- **Yoon support** — include combination characters (きゃ, しゃ, ちゃ...)
- **Hiragana and Katakana** — switch between scripts
- **Custom question count** — set how many questions you want per session
- **Mistake tracker** — results screen shows which characters you struggled with

## Why this exists

I was learning Japanese and found that existing apps either taught too much at once or didn't let me drill specific character groups. I originally built a command-line version in Python, then rebuilt it as a web app so anyone could use it.

## How to use

No installation needed. Just open `index.html` in your browser.

1. Select your script (hiragana or katakana)
2. Pick which lines to study
3. Toggle dakuten/yoon if desired
4. Choose study or quiz mode
5. Hit Start

## Tech Stack

- HTML, CSS, JavaScript

## Background

This project started as a Python terminal script and was rebuilt as a fully functional web app. The core logic — character sets, line groupings, dakuten/yoon combinations — was ported directly from the original Python version.
