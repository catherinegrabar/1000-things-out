# 1,000 Things Out

A decluttering tracker I built with Claude. The goal: get 1,000 things out of the house by a set date, and log each one as donated, trashed or sold.

I wrote about it in my "Things I've built with Claude" series on LinkedIn (part 3: a decluttering app that made me declutter less).

## What it does

- Counts every item toward the goal, with one dot per item
- Three buttons for logging: Donate, Trash, Sell
- A sale list for things you've listed but not sold yet
- A countdown with a daily pace to stay on track
- Optional photos: take a picture and Claude fills in the category, count and description
- A photo wall of everything that left

## How to use it

The whole app is one file, `index.html`. It was built as a Claude artifact and uses Claude's artifact features to save your data, store photos and read them.

To get your own copy:

1. Download `index.html`.
2. Start a chat with Claude, attach the file, and ask it to publish the file as an artifact with storage and photo support.
3. Open the artifact on your phone and start logging.

If you open the file directly in a browser, the layout loads but nothing is saved and the photo features are off. I haven't tested it anywhere except as a Claude artifact.

## A warning from experience

The photo step is fun, and it's also what made me stop logging things in the moment. If you want to keep your pace up, use the plain buttons day to day and save the photos for big cleanouts.

No personal data is in this file. Your items and photos live in your own artifact's storage.
