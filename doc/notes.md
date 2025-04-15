Tue 15 Apr 13:19:22 UTC 2025

Basis of initial investigation:  clangd offers the programmer
a red icon with an X in it and a count, saying there are issues
with the code as written.

It is independently known these issues are not quite as salient
as might otherwise be true - clandg simply is not finding what
it needs to provide the valued feedback it is seen as capable
of providing.

Long winded way to say: clangd is treated as a new tool (just as
zed is, locally) and is apparently misconfigured or underconfigured.

CPATH has been manually set as part of the process of starting zed
(from within a local shell script).  This seems to ameliorate (SP ck)
the issue with clangd - enough so to want to find out what's proper,
and if this is the preferred means to address the issue systemically.

Of note is the use of Arduino IDE and/or platformio (Arduino Framework)
and that the test project used in the investigation


no markup highlight seen without the square and round brace markings:

  [label](https://github.com/neovim/nvim-lspconfig/blob/master/doc/configs.md#clangd)

The above URI starts to give hints about clangd and lsp and idk what. ;)
Just building some cheaply acquired working vocabulary.

The 'tagging' (alike?) feature of github.com is exploited here, for discovery
purposes.  The long spelled out form of LSP was used - language server protocol.

[topics: lsp](https://github.com/topics/language-server-protocol)

like that.

Adding that .. topic? to this repository kicked in that door. ;)

Literally on github is seen:

  Edit repository details
  Topics  language-server-protocol zed clangd zed-editor

So, it's 'topics' on github (not 'tagging').  As reflected in the URI name
cited above (for the language server topic).
