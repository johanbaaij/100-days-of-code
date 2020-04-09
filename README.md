# #100DaysOfCode Challenge

- <https://twitter.com/BaaijJohan/status/1247818554386206720>
- [100daysofcode.com](http://100daysofcode.com/)

## Log

### Day 2: April 9, 2020 - Thursday

#### Progress

- Spend a bit more time configuring and researching automated semantic releases.
- Added a new feature/check to [bpm-counter](https://github.com/johanbaaij/bpm-counter). Verified the auto generated changelog works.
- Improved [bpm-counter](https://github.com/johanbaaij/bpm-counter) docs.

#### Thoughts

- Would like to generate/include some API docs for [bpm-counter](https://github.com/johanbaaij/bpm-counter) but not sure what the best practises are here. If possible I prefer to avoid redundant/noisy comments for every class and method. Some packages to investigate:
  - <https://typedoc.org/>
  - <https://api-extractor.com/>

#### Links

- <https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882>
- <https://moderatemisbehaviour.github.io/clean-code-smells-and-heuristics/>

### Day 1: April 8, 2020 - Wednesday

#### Progress

- Published my first NPM package [bpm-counter](https://github.com/johanbaaij/bpm-counter) using [semantic-release](https://github.com/semantic-release/semantic-release). Releases and versioning are automatically taken care of by this [GitHub action](https://github.com/johanbaaij/bpm-counter/blob/master/.github/workflows/main.yml)
- Initialized this repository

#### Thoughts

- Some benefits of automated semantic-releases:
  - Forces you to treat `master` as if it may only contain deployable code
  - Takes the guesswork out of versioning
  - Sets up your repo for easy contributing and use in the real world
- It never ceases to amaze me how many tools and infrastructure is available for open source software

#### Links

- <https://www.npmjs.com/package/bpm-counter>
- <https://github.com/johanbaaij/bpm-counter>
- <https://github.com/semantic-release/semantic-release>
