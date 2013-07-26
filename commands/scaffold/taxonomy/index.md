---
layout: default
title: 'wp scaffold taxonomy'
---

`wp scaffold taxonomy` - Generate PHP code for registering a custom taxonomy.

### OPTIONS

	--post_types=<post_types>
			Post types to register for use with the taxonomy.

	--label=<label>
			The text used to translate the update messages

	--textdomain=<textdomain>
			The textdomain to use for the labels.

	--theme
			Create a file in the current theme directory, instead of sending to
STDOUT.

	--plugin=<plugin>
			Create a file in the given plugin's directory, instead of sending to
STDOUT.

	--raw
			Just generate the `register_taxonomy()` call and nothing else.

### EXAMPLES

	wp scaffold taxonomy venue --post_types=event,presentation

