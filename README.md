# Vim Plug-In(s): gtags & gtags-cscope
For the most part, this is a mirror of the vim plugins gtags.vim and gtags-cscope.vim provided with GNU GLOBAL (available at https://www.gnu.org/software/global/).

## Changes from the original
- The gtags-cscope.vim plugin now provides the new setting `GtagsCscope_Auto_Update_Gtags`. Enabling this setting will turn on the automatic incremental updates of the tag database (but only if a GtagsCscope actually loaded a database). Meaning if no database was loaded, the plugin will not call the gtags executable to look for a database to update. If you are already using `Gtags_Auto_Update` (from the gtags.vim plugin), this setting will have no effect.
