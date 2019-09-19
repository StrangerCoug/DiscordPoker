# Contributing guidelines
Before contributing, please read the following:
* If you have a bug or a feature request, first search the issues tab to make sure somebody hasn't already opened an issue describing your bug or feature request. If it's not there, then open up an issue and fill out the template as appropriate to your issue. Please do not open an issue simply to ask a question; I'm generally available via Discord or e-mail.
* If your feature request is for a new poker variant, we generally need a clear description of how the game is played from a third party. (A good source that I recommend is [The Wizard of Odds](https://wizardofodds.com/) or John McLeod's [Card Game Rules](https://www.pagat.com/).) This is to ensure that the variant is sufficiently well-known to warrant inclusion in the game. As an open-source project, we cannot accept proprietary poker variants.

## Style conventions
In general, code should closely follow Oracle's style guide for both [Java](https://www.oracle.com/technetwork/java/javase/documentation/codeconvtoc-136057.html) and [JavaDoc](https://www.oracle.com/technetwork/java/javase/documentation/index-137868.html). They were written to ensure consistency, legibility, and maintainability. Deviating from the letter of Oracle's guides is fine, but the general principles behind them apply to this project.

We slightly differ from Oracle's indentation convention in that we follow the "tabs for indentation, spaces for alignment" principle in this project. The tab character counts _once_ toward the 80-character limit per line just like everything else. For continuation indents, use two hard tabs.

## Versioning scheme
We use (https://semver.org/)[Semantic Versioning 2.0.0] when assigning release numbers in this project.
