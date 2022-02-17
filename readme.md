# Codeless Language Modules for BBEdit

Codeless Language Modules (CLM) provide syntax coloring, function navigation, and text completion for the editor BBEdit.  

## Custom keyword files

Keyword files go in `~/Library/Application Support/BBEdit/Custom Keywords/` and must have the extension defined in the CLM.  Multiple files for each language are acceptable.   See the BBEdit manual Chapter 2, page 36 (for version 14.1).

## Recutils

[Recutils][] is a plain text database.  The CLM provides coloring for all keys, and some of the predefined types.  Since keys are user definable, I find it useful to creat a dedicated keyword file for databases you use a lot to enable keyword completion.   Extension for the keyword files is `.rec`.

[Recutils]: https://www.gnu.org/software/recutils/


## BibTeX

BibTeX is the reference management software for LaTeX.  THe CLM provides highlighting, function navigation for entries, and completion for common keys and entry types.

## Ledger

[Ledger][] is a command line accounting tool.  Forked from [mixio][], whom I think forked it from [lifepillar][].  I have added some of my commonly used stock symbols; feel free to edit or modify.  While the accounts should be syntax colored, they will not autocomplete as they are defined in the CLM.  For that, I put commonly used accounts in a custom keyword file.  One could also put commonly used stock symbols in that file.

[ledger]: http://ledger-cli.org/
[mixio]: https://gist.github.com/mixio/4f233eb409c287101277502505e6b644
[lifepillar]: https://gist.github.com/lifepillar/1597432

