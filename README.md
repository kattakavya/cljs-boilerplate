# cljs-boilerplate

Example boilerplate project for cljs. Uses fighweel main and reagent.

## How To

    lein new figwheel-main %project_name% -- --reagent

There is a small bug in the template which I need to correct. In core.cljs, there is a hiccup element with a h3 tag ... the second slash always comes as backward for some reason ... this causes the repl to crash. Correct this before trying to run the repl.

Run the repl with

    M-x cider-jack-in-cljs

Then wait for the popup that asks you to choose your cider repl of choice.
Choose figwheel-main.

When asked which production build to use type

    :dev
    
## Issues

When we had originally configured emacs, because of discrepancy with spacemacs, lein version, cider version etc ... we had disabled some nrepl packages ... if the repl does not work, we will need to disable them, and make sure all our versions are up to date.

## License

Copyright © 2018 FIXME

Distributed under the Eclipse Public License either version 1.0 or (at your option) any later version.
