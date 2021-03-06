# Culture
1. To scale a dev team, you need to establish a culture
    - Common way of evaluating designs, making tradeoffs, etc.
    - Common way of developing code and reacting to problems (build breaks, critical bugs, etc.)
    - Common way of establishing ownership of problems
1. Goal setting can be the foundation for the culture
1. Keeping culture alive as a team grows is a huge challenge

https://danluu.com/microsoft-culture/

# On-boarding
Read: https://about.sourcegraph.com/go/go-reliability-and-durability-at-dropbox-tammy-butow

> Every Dropbox engineer goes through the same rigorous Go onboarding process, consisting of:
>
> - Readings on infrastructure topology, Go style guide, and the Protobuf style guide
> - Strict but friendly code reviews
> - Building a toy application (an app store) in Go
> - Learning Bazel for building and testing Go code
> - This onboarding process takes about a week for experienced engineers.

If there are frequent new staff coming in to do Go programming, we may need to setup an onboarding process like Dropbox for new engineers. This allows them to easily get up to speed as well as reducing the chances of the code review becoming as basic as `use go fmt`.

## Good Reads
1. [Why Go is my favorite programming language](https://michael.stapelberg.de/Artikel/golang_favorite)
1. [Go best practices](https://peter.bourgon.org/go-best-practices-2016/)
1. [Rob Pike - 'Concurrency Is Not Parallelism'](https://youtu.be/cN_DpYBzKso)
1. [dotGo 2015 - Rob Pike - Simplicity is Complicated](https://youtu.be/rFejpH_tAHM)

## Git Commits
1. [How to Write a Git Commit Message](http://chris.beams.io/posts/git-commit/)
1. [5 Useful Tips for a better commit message](https://robots.thoughtbot.com/5-useful-tips-for-a-better-commit-message)
    * Related: [Sample Git Message from ThoughtBot](https://github.com/thoughtbot/dotfiles/blob/master/gitmessage)
1. For people who don't use vim, [No Newline at End of File](https://robots.thoughtbot.com/no-newline-at-end-of-file)

## Code Review
1. [Implementing a code-review culture](https://youtu.be/PJjmw9TRB7s)
