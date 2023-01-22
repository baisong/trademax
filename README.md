# trademax

Work-in-progress: A generic library for determining maximal item exchanges among a group of people based on ranked want lists.

## Work-in-progress

This will take a little time!

## Thank you

### The story of this code

Some people love board games. Some of those people have met up to share their games via BoardGameGeek/BGG.

Around 2007, Chris Okasaki implemented a [700-line Trade Maximizer in the Java language](https://github.com/chrisokasaki/TradeMaximizer/blob/master/src/tm/TradeMaximizer.java), and it was used to maximize the number of trades based on what games/items people have, and which of those items people want.

Around 2018, Jeff Michaud translated that Java library into a [1600-line Javascript version](https://bgg.activityclub.org/olwlg/trademax.js).

This package is an NPM module version for generic use in web applications, such as for neighbors sharing common items (see [nextjs-potluck by Kevin Nguyen](https://github.com/lightandluck/nextjs-potluck)).

### Built and packaged using `create-svelte`

This project was started by typing [`npm create svelte@latest`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte) using the "Skeleton Library" project preset, and built into an npm package by running [`svelte-package`](https://kit.svelte.dev/docs/packaging).