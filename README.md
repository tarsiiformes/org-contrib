This repository contains add-ons to Org.

You can use them by installing the `org-contrib` NonGNU ELPA package
from <https://elpa.nongnu.org/nongnu/>.


# Please help maintaining these add-ons

Files in this repository used to live in the Org repository but have
been filtered out of the Org 9.5 release.  The `contrib/` directory used
to contain a `scripts/` directory that now lives on [the Worg repository](https://code.orgmode.org/bzg/worg/src/master/code).

**Files in this repository receive little if no maintainance and there
is no guaranty that they are compatible with the Org stable version.**

For files a `Maintainer` header and a `Homepage` pointing outside of this
repository are in transition: they are maintained and will be removed
from the next release of this repository.  As a user, please carefully
track the new URL where the add-on is now maintained.

If you want to maintain some of these add-ons, please send me an email
at `bzg@gnu.org` once you set up a separate repository for them.


# License

All files in this repository are licensed under the GNU General Public
License, either version 3 of the License, or (at your option) any
later version.  See [COPYING](COPYING).


# Files to remove from the next release

These files are maintained in a separate repository, which you can
find after the "Homepage:" keyword in the files themselves:

-   **ob-arduino.el:** Org-mode Babel support for Arduino
-   **ob-clojure-literate.el:** Clojure's Org-mode Literate Programming
-   **ob-mathematica.el:** org-babel functions for Mathematica evaluation
-   **ob-php.el:** Execute PHP within org-mode blocks
-   **ob-redis.el:** Execute Redis queries within org-mode blocks
-   **ob-sclang.el:** SCLang support for Org-mode Babel
-   **ob-smiles.el:** Org-mode Babel support for SMILES
-   **ob-spice.el:** org-babel functions for spice evaluation
-   **ol-notmuch.el:** Links to notmuch messages
-   **org-attach-embedded-images.el:** Transmute images to attachments
-   **org-link-edit.el:** Slurp and barf with Org links
-   **org-mac-link.el:** Insert org-mode links to items selected in various Mac apps
-   **org-notify.el:** Notifications for Org-mode
-   **org-passwords.el:** org derived mode for managing passwords
-   **org-velocity.el:** something like Notational Velocity for Org
-   **ox-rss.el:** RSS 2.0 Back-End for Org Export Engine


# Other files


## Org utils

-   **org-annotate-file.el:** Annotate a file with org syntax
-   **org-attach-embedded-images.el:** Transmute images to attachments
-   **org-bibtex-extras.el:** Extras for working with org-bibtex entries
-   **org-checklist.el:** org functions for checklist handling
-   **org-choose.el:** Use TODO keywords to mark decision states
-   **org-collector.el:** Collect properties into tables
-   **org-contacts.el:** Contacts management
-   **org-contribdir.el:** Dummy file to mark the org contrib Lisp directory
-   **org-depend.el:** TODO dependencies for Org-mode
-   **org-effectiveness.el:** Measuring your personal effectiveness
-   **org-eldoc.el:** Eldoc documentation for SRC blocks
-   **org-eval.el:** The <lisp> tag, adapted from Muse
-   **org-eval-light.el:** Evaluate in-buffer code on demand
-   **org-expiry.el:** Expiry mechanism for Org entries
-   **org-git-link.el:** Provide org links to specific file version
-   **org-interactive-query.el:** Interactive modification of tags query
-   **org-invoice.el:** Help manage client invoices in OrgMode
-   **org-learn.el:** SuperMemo's incremental learning algorithm
-   **org-license.el:** Insert free licenses to your org documents
-   **org-link-edit.el:** Slurp and barf with Org links
-   **org-mac-iCal.el:** Imports events from iCal.app to the Emacs diary
-   **org-mac-link.el:** Grab links and URLs from various Mac applications
-   **org-mairix.el:** Hook mairix search into Org for different MUAs
-   **org-notify.el:** Notifications for Org-mode
-   **org-panel.el:** Simple routines for us with bad memory
-   **org-passwords.el:** Org derived mode for managing passwords
-   **org-registry.el:** A registry for Org links
-   **org-screen.el:** Visit screen sessions through Org-mode links
-   **org-screenshot.el:** Take and manage screenshots in Org-mode files
-   **org-secretary.el:** Team management with org-mode
-   **org-static-mathjax.el:** Muse-like tags in Org-mode
-   **org-sudoku.el:** Create and solve SUDOKU puzzles in Org tables
-   **org-toc.el:** Table of contents for Org-mode buffer
-   **org-track.el:** Keep up with Org development
-   **org-velocity.el:** something like Notational Velocity for Org
-   **org-wikinodes.el:** CamelCase wiki-like links for Org


## Org exporters

-   **ox-bibtex.el:** Export bibtex fragments
-   **ox-confluence.el:** Confluence Wiki exporter
-   **ox-deck.el:** deck.js presentations exporter
-   **ox-extra.el:** Convenience functions for org export
-   **ox-freemind.el:** Freemind exporter
-   **ox-groff.el:** Groff exporter
-   **ox-rss.el:** RSS 2.0 exporter
-   **ox-s5.el:** S5 presentations exporter
-   **ox-taskjuggler.el:** TaskJuggler exporter


## Org link

-   **ol-bookmark.el:** Links to bookmarks
-   **ol-elisp-symbol.el:** Links to Emacs-lisp symbols
-   **ol-git-link.el:** Links to specific file version
-   **ol-mew.el:** Links to Mew messages
-   **ol-notmuch.el:** Links to notmuch messages
-   **ol-vm.el:** Support for links to VM messages
-   **ol-wl.el:** Support for links to Wanderlust messages


## Org Babel languages

-   **ob-abc.el:** Org-mode Babel Functions for ABC
-   **ob-arduino.el:** Org-mode Babel Functions for Arduino
-   **ob-asymptote.el:** Org-mode Babel Functions for Asymptote
-   **ob-clojure-literate.el:** Clojure's Org-mode Literate Programming
-   **ob-coq.el:** Org-mode Babel Functions for Coq
-   **ob-csharp.el:** Org-mode Babel Functions for csharp evaluation
-   **ob-ebnf.el:** Org-mode Babel Functions for EBNF
-   **ob-eukleides.el:** Org-mode Babel Functions for eukleides evaluation
-   **ob-fomus.el:** Org-mode Babel Functions for fomus evaluation
-   **ob-hledger.el:** Org-mode Babel Functions for hledger
-   **ob-io.el:** Org-mode Babel Functions for Io
-   **ob-J.el:** Org-mode Babel Functions for J
-   **ob-ledger.el:** Org-mode Babel Functions for Ledger
-   **ob-mathematica.el:** Org-mode Babel Functions for Mathematica evaluation
-   **ob-mathomatic.el:** Org-mode Babel Functions for mathomatic evaluation
-   **ob-mscgen.el:** Org-mode Babel Functions for Mscgen
-   **ob-oz.el:** Org-mode Babel Functions for Oz evaluation
-   **ob-php.el:** Execute PHP within org-mode blocks
-   **ob-picolisp.el:** Org-mode Babel Functions for Picolisp
-   **ob-redis.el:** Execute Redis queries within org-mode blocks
-   **ob-sclang.el:** SCLang support for Org-mode Babel
-   **ob-shen.el:** Org-mode Babel Functions for Shen
-   **ob-smiles.el:** Org-mode Babel support for SMILES
-   **ob-spice.el:** Org-mode Babel Functions for spice evaluation
-   **ob-stan.el:** Babel Functions for Stan
-   **ob-stata.el:** Org-mode Babel Functions for Stata evaluation
-   **ob-tcl.el:** Org-mode Babel Functions for tcl evaluation
-   **ob-vala.el:** Org-mode Babel Functions for Vala
-   **ob-vbnet.el:** Org-mode Babel Functions for VB.Net evaluation

