# Sproutcore 2.0 Handlebars

Pretty much what it sounds like. The biggest goal being the capability of precompiling templates on the serverside during the build process.

Trying to come up with the best api, so feel free to fork and suggest. Alot of it is just proxied right into the handlebars module from @kpdecker (via @wycats )

## Docs

More or less, this is the same as the `handlebars` module in npm. It has the same interface, this is just a little wrapper around it. So most of your learning would be done here:

https://github.com/kpdecker/handlebars.js

Just sub things that say `handlebars` with `sc-handlebars`

Ugh, ok... Try this:

`npm install sc-handlebars -g`

`sc-handlebars myapp/templates/mytemplate.handlebars`

BOOM

You should see compiled handlebars templates now. There are flags and stuff too, those will show up if you just type `sc-handlebars` after installation. It'll do files or directories and stuff too. woot.

## WTF is this

I have a single wiki/doc on the who, what, and why, if you are interested in WTF this is:

https://github.com/SlexAxton/sc-handlebars/wiki/Everything

## Integration

There's a requirejs plugin for adding this to your require app in the extras folder. It probably requires (no pun intended) some modification since there are no standard ways to include sproutcore into require (at least at this time).

## Version

1.0.2beta  -- This just stays in sync with the last tested version of sproutcore handlebars.

If I were to actually version this, it'd be like -4 or so. probably.
