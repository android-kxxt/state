- `hardware/qcom-caf/thermal-legacy-um`: thermal: Reset msmnile configs to LA.UM.9.1.r1<br>
  2025-07-24T04:49:44Z by [Nick Reuter](mailto:nreuter85@gmail.com) [45aa40ea41ae](https://github.com/LineageOS/android_hardware_qcom_thermal/commit/45aa40ea41ae)  [Review](https://review.lineageos.org/q/Idfda2efa435f4e5e24d8cbbc2776c116dab0395b)
- `build/make`: envsetup: Build OOT kernel during lunch if needed<br>
  2025-10-23T08:53:35Z by [Michael Bestas](mailto:mkbestas@lineageos.org) [4e5717d88102](https://github.com/LineageOS/android_build/commit/4e5717d88102)  [Review](https://review.lineageos.org/q/Ie61ebb571dc758d1331d4fdec1f1456fd5bc5b32)
- `lineage/charter`: device-support-requirements: Allow prebuilt GKI<br>
  2025-10-26T23:13:26Z by [Nolen Johnson](mailto:johnsonnolen@gmail.com) [873eada46943](https://github.com/LineageOS/charter/commit/873eada46943)  [Review](https://review.lineageos.org/q/I3da17e891a4c168a283a7abd61b8909db0506ed1)
- `external/nano`: Merge tag &#x27;v8.6&#x27; of git://git.git.savannah.gnu.org/nano into lineage-23.0  <details>
    <summary>Merge Details</summary>

      * tag 'v8.6' of git://git.git.savannah.gnu.org/nano:
        po: update translations and regenerate POT file and PO files
        bump version numbers and add a news item for the 8.6 release
        gnulib: update to its current upstream state
        completion: don't stop looking for candidates one byte too early
        rcfile: accept also {}} in a string bind, for symmetry with {{}
        tweaks: swap two symbolic menu names, for giggles
        browser: let a refresh also reread the file list, like it used to
        browser: redo the layout only when an actual resize occurred
        browser: redo the layout when the window _might_ have resized
        display: when resizing, redraw the bottom bars also when in file browser
        syntax: po: colorize also the %b and %B format specifiers
        tweaks: put two related checks together, like they are elsewhere
        tweaks: reshuffle some lines, to group things better
        tweaks: use a direct parameter instead of an intermediary boolean
        tweaks: rename a parameter, and invert its logic
        tweaks: normalize the indentation after the previous change
        tweaks: split the goto function into an interactive and command-line one
        tweaks: reshuffle a condition to a better place, like it is elsewhere
        tweaks: reshuffle a few lines, for density and to elide an 'else'
        history: do not forget anchors when line number is given on command line
        docs: document the ++/-- prefix feature for the `gotoline` function
        new feature: interpret a line number prefixed with ++ or -- as relative
        tweaks: remove a check for a symbol that never gets defined


    </details>

  2025-10-27T20:27:57Z by [Thomas Turner](mailto:thomas_turner@talktalk.net) [b83fc23d564c](https://github.com/LineageOS/android_external_nano/commit/b83fc23d564c)  [Review](https://review.lineageos.org/q/I61b21eafc537c9fd6ad2e140abdb909305e9b343)
- `external/unrar`: Merge https://github.com/pmachapman/unrar into lineage-23.0  <details>
    <summary>Merge Details</summary>

      * https://github.com/pmachapman/unrar:
        Updated to 7.1.10
        Updated to 7.1.9
        Updated to 7.1.8


    </details>

  2025-10-27T22:04:13Z by [Thomas Turner](mailto:thomas_turner@talktalk.net) [140cfb9e8fc9](https://github.com/LineageOS/android_external_unrar/commit/140cfb9e8fc9)  [Review](https://review.lineageos.org/q/I8fb87fd44f4530f3f4590c2d8d19679763bfd50f)
- `external/vim`: Merge tag &#x27;v9.1.1882&#x27; of https://github.com/vim/vim into lineage-23.0  <details>
    <summary>Merge Details</summary>

      v9.1.1882
      
      * tag 'v9.1.1882' of https://github.com/vim/vim:
        patch 9.1.1882: Vim9: Not able to use a lambda with :defer
        runtime(netrw): fix misaligned comment after #18611
        patch 9.1.1881: tests: test_popupwin fails after c8eeda9b
        runtime(doc): regenerate help tags file after eba51337
        runtime(rust): Do not use rustfmt as 'formatprg' by default
        patch 9.1.1880: Allocation error with complete_info()
        patch 9.1.1879: Crash when using a lambda funcref with :defer
        patch 9.1.1878: filetype: Soy files are not recognized
        runtime(doc): update the :split help tags.
        patch 9.1.1877: cindent: wrong indentation after an array declaration
        runtime(doc): Improve header formatting
        runtime(doc): mention that 'incsearch' ignores addresses and offset
        runtime(doc): Normalise heredoc end marker label at :help const
        patch 9.1.1876: pre-inserted text not exposed in cmdcomplete_info()
        patch 9.1.1875: username parsing bug in netrw plugin
        patch 9.1.1874: short-description
        runtime(vim): Update base syntax, improve :@ highlighting
        patch 9.1.1873: Clipboard provider feature broke clipboard support
        patch 9.1.1872: Cmdline history not updated when mapping <Up> and <CR>
        runtime(colors): Add PmenuBorder/PmenuShadow
        runtime(debversions): Add resolute (26.04) as Ubuntu release name
        CI: Include a job index in names of collected artifacts
        runtime(make): Prevent makeTargetinDefine matching extra line
        runtime(doc): Improve highlighting of the +feature-list table
        patch 9.1.1871: Wrong 'showcmd' in the cmdwin
        runtime(unison): update syntax from upstream repository
        runtime(doc): Fix option markup at :help 'pumborder'
        patch 9.1.1870: :Tutor may not work as expected
        runtime(tutor): Update German translation for the tutor
        patch 9.1.1869: tests: test failures with Python 3.14 and test_python3
        patch 9.1.1868: v:register is wrong in v_: command
        patch 9.1.1867: HAVE_STDARG_H still defined
        patch 9.1.1866: HAVE_STRCSPN define is unused
        patch 9.1.1865: tests: do not notice lines containing only a tab
        Fix incorrect spelling of Vim script and Vim9 script
        patch 9.1.1864: tests: Clipboard provider feature test failure
        runtime(vimcomplete): do not complete 'shellcmd' on WSL and Windows
        patch 9.1.1863: Cannot test for working "+" register
        patch 9.1.1862: wrong ifdefs for clipboard provider
        runtime(odin): fix indent for mis-identified case statements
        patch 9.1.1861: Amiga: Locating runtime dir and rc files can be simplified
        patch 9.1.1860: clipboard register "+" enabled with cplipboard provider feature
        patch 9.1.1859: completion: whitespace not cleared with 'ai'
        patch 9.1.1858: v:register not reset after Visual mode command
        patch 9.1.1857: Missing clipboard provider support
        patch 9.1.1856: cannot style popup window (border, shadow, etc)
        patch 9.1.1855: Makefile: using non-portable syntax
        runtime(doc): Miscellaneous documentation fixes
        runtime(doc): Fix example highlighting at :help prop_list()
        runtime(doc): Normalise formatting of builtin function descriptions
        runtime(doc): Remove accidental option name highlighting from :help channel.txt
        patch 9.1.1854: unnecessary code in optionstr.c
        patch 9.1.1853: Ctrl-F and Ctrl-B at more prompt not working with key protocol
        CI: Bump github/codeql-action from 3 to 4
        runtime(vimcomplete): do not complete on empty line
        runtime(doc): fix inconsistent alignment
        runtime(bitbake): fix multiline Python function parameter syntax
        runtime(rst): Preserve indentation of directives
        runtime(rst): Update b:undo_ftplugin variable
        runtime(rst): Style update
        runtime(rst): Enable spell checking for more syntax constructs
        runtime(rst): Inline literal escape support
        runtime(rst): Recognise numeric footnotes [1] correctly
        runtime(rst): Correctly end nested comments
        runtime(rst): Fix highlights nested in directive body
        runtime(rst): Add support for rst_minlines
        runtime(rst): Fix doctest block syntax
        runtime(doc): Whitespace updates
        runtime(make): syntax highlighting update for makeDefine
        runtime(vim): Update syntax, add missing commands to generator exclusion list
        patch 9.1.1852: vim9class: memory leak in parse_member()
        patch 9.1.1851: memory leak in heredoc_get()
        patch 9.1.1850: completion: not triggered after i_Ctrl-W/i_Ctrl-U
        patch 9.1.1849: CTRL-F and CTRL-B don't work in more prompt
        runtime(doc): Replace rotted URL links
        patch 9.1.1848: A few typos in the code
        patch 9.1.1847: No cmdline completion for :echoconsole and :echowindow
        runtime(cangjie): Fixes and improvements for syntax script
        runtime(doc): Add missing optional tail command-name specs
        runtime(doc): Update documentation style in gui_w32.txt
        runtime(doc): update credit section for Girish Palya
        patch 9.1.1846: Build failure when building without wayland
        patch 9.1.1845: Makefile: Missing dependency on osdef.h
        runtime(doc): Tweak documentation in develop.txt
        patch 9.1.1844: Makefile: dependencies not updated
        runtime(filetype): Improve filetype loading time
        patch 9.1.1843: tests: Test_search_stat_option() may fail on slow systems
        runtime(doc): Add reference to 'wildoptions' in fuzzy-matching docs
        patch 9.1.1842: MS-Windows: build failure when mzscheme is included
        runtime(doc,vim): Update base syntax, match full :syntime command
        runtime(vim): fix indentation after `:registers +`
        patch 9.1.1841: patch 9.1.1840 adds python build dependency
        patch 9.1.1840: Generating prototype files does not work on all platforms
        runtime(vim): Update base syntax, allow legacy script comments after :eval
        runtime(termdebug): Add remote debugging capabilities
        runtime(java): Fold adjacent "import" declarations
        runtime(colors): Update colorscheme and add TitleBar/TitleBarNC
        patch 9.1.1839: Window may have wrong height if resized from another tabpage
        patch 9.1.1838: proto files out of sync
        runtime(doc): Normalise ellipsis dots in syntax.txt
        patch 9.1.1837: tests: Test_plugin_evaluate_in_popup() fails on 32bit
        patch 9.1.1836: 'culopt' "screenline" not redrawn with line("w0") and :retab
        patch 9.1.1835: completion: not possible to style popup borders globally
        patch 9.1.1834: MS-Windows: not possible to highlight the title bar
        runtime(doc): Fix typos in syntax.txt
        translation(ru): updated Vim manpages
        translation(ru): Updated message file
        translation(it): Update Italian translation
        runtime(tex): link some tex highlight groups to new standard ones
        translation: regenerate po/vim.pot after a644b7924d
        patch 9.1.1833: completion: fuzzy candidates are not sorted
        runtime(doc): Update sections 5 to 8 in vim9.txt
        patch 9.1.1832: if_perl: contains references to legacy if_perlsfio
        runtime(zip): add *.pkpass to list of zip extensions
        runtime(kerml): update KerML comments to handle more cases
        runtime(doc): fix typo in :h credits section
        patch 9.1.1831: stray vseps in right-most 'winfixwidth' window
        patch 9.1.1830: MS-Windows: Dark mode titlebar is not configurable
        patch 9.1.1829: filetype: KerML and SysML files are not recognized
        patch 9.1.1828: local variables shadowed by import names
        patch 9.1.1827: completion: v9.1.1797 broke Ctrl-Y behaviour
        runtime(doc): Use the optional tail command-name spec at :help :sign
        patch 9.1.1826: Patch v9.1.1230 causes confusion about Ctrl-C behaviour
        runtime(doc): update if_perl after v9.1.1822)
        patch 9.1.1825: completion: flicker when LSP server is slow
        runtime(doc): update credits section
        patch 9.1.1824: tests: no test for displaying 'foldcolumn' with Unicode "foldinner"
        patch 9.1.1823: diff: w_topline may be invalidated
        runtime(doc): Add explanation for Vim's IME
        runtime(java): Make changes for JDK 25
        runtime(help): Update syntax
        patch 9.1.1822: Makefile still supports Perl < 5.005
        nsis: Getting the Vim version number via makensis
        nsis: Duplicate files in the icons.zip archive have been removed
        nsis: delete README.txt from the icons directory
        Filelist: include nsis/icons/README.txt again
        patch 9.1.1821: filetype: Not all PKL files are recognized
        patch 9.1.1820: completion: some issues with 'acl'
        patch 9.1.1819: Cannot configure the inner foldlevel indicator
        runtime(doc): fix typo after commit cfcf1a57cbef
        CI: stop using macos-13 runner
        runtime: Update a few icons
        nsis: added a note about installer icons in README.txt
        runtime(log): remove domain highlight
        runtime(new-tutor): fix mismatched line numbers in vim-02-beginner
        patch 9.1.1818: possible crash when calculating topline in diff.c
        Filelist: include nsis/icons/README.txt
        runtime(doc): Clarify use of "noselect" in 'completeopt'
        runtime(vim): Update base syntax, contain user command replacement text
        runtime(optwin): Update formatting of option descriptions
        patch 9.1.1817: popup: there are some position logic bugs
        nsis: Rework icons, update icons archive, add copyright notice
        rutnime(new-tutor): Updated English new tutor
        runtime(doc): Tweak documentation style
        patch 9.1.1816: existing icon files are dated
        runtime(netrw): MS-Windows: fix netrw not being able to navigate to parent folder
        runtime(doc): make :h virtcol() more accurate
        runtime(help): Update syntax, match legacy header at :help vim9-mix
        patch 9.1.1815: file mode changes in os_amiga.pro
        patch 9.1.1814: Patch v9.1.1812 causes crashes
        patch 9.1.1813: MS-Windows: title bar is always white
        patch 9.1.1812: completion: flicker with slow LSPs
        runtime(doc): Update os-support section for Amiga OS
        patch 9.1.1811: Amiga: Initialization of random buffer can be improved
        patch 9.1.1810: completion: "longest" doesn't work for manual completion with 'ac'
        patch 9.1.1809: winclip.pro included in PRO_AUTO
        runtime(doc): Tweak documentation style
        nsis: Load correct readme at the end, refactor gvim.nsi slightly
        nsis: Reorder code blocks
        nsis: Split gvim.nsi and factor out auxiliary code into auxiliary.nsh
        nsis: Fix indentation and alignment issues in gvim.nsi
        runtime(tex): add amsmath support to tex syntax script
        patch 9.1.1808: Option insecure flags not copied when splitting window
        patch 9.1.1807: :set doesn't clear local insecure flag like :setlocal does
        runtime(doc): update list of modifiers at :h expand()
        patch 9.1.1806: Missing PROTO defines
        runtime(help): Update syntax, add vim9 example language
        runtime(vim): Update base syntax, improve line-continuation skip patterns
        runtime(doc): Fix :help complete() example
        patch 9.1.1805: Amiga: Missing build date in version string
        runtime(vim): Update base syntax, allow Vim9 :echo tail comments
        patch 9.1.1804: Wrong indentation of nested ifdefs in findfile.c
        patch 9.1.1803: Amiga: build errors
        runtime(java): Recognise _module_ import declarations
        patch 9.1.1802: 'nowrap' in a modeline may hide malicious code
        patch 9.1.1801: Vim9: misleading error when extending dictionary
        patch 9.1.1800: completion: strange behaviour with 'ac' completeopt=longest,preinsert
        patch 9.1.1799: completion: crash with autcompletion
        patch 9.1.1798: Wrong display with 'sms' and long wrapped virt text at EOL
        runtime(doc): improve preinserted() doc
        patch 9.1.1797: completion: autocompletion can be improved
        patch 9.1.1796: Wrong cursor position with wrapped "after" virtual text and 'sbr'
        runtime(doc): update getwininfo() documentation about popups
        patch 9.1.1795: Vim9: popup_show() may return void
        runtime(vim): Update base syntax, match null_tuple literal
        patch 9.1.1794: configure: terminfo test does not work with musl
        patch 9.1.1793: Link error when build without channel feature
        patch 9.1.1792: List of changes not protected from changes
        runtime(doc): make order of verbs match order of operators
        runtime(doc): MS-Windows: Improve documentation about VTP support
        patch 9.1.1791: type(void) throws an internal error
        runtime(python): fix 'type' syntax highlighting
        patch 9.1.1790: completion: Enter does not insert match with "noinsert"
        patch 9.1.1789: MS-Windows: using wrong check for bold font
        runtime(doc): fix inconsistent indent in cmdline.txt
        runtime(doc): Improve documentation of the ..= assignment operator
        runtime(javascript): Add "using" keyword to JavaScript syntax highlighting
        patch 9.1.1788: Vim9: can declare a void variable
        runtime(doc): mention improved rendering with 'termguicolors'
        runtime(swayconfig): support new config options in syntax script
        patch 9.1.1787: filetype: not all Sway config files are recognized
        runtime(doc): update Vim policy
        translation(sr): Update Serbian messages translation
        runtime(doc): update live-grep and fuzzy-file-picker examples
        runtime(sh): refactored sh.vim syntax script
        runtime(vim): Update base syntax, match :terminal command
        runtime(vim): Update base syntax, match :wincmd
        translation(sr): Update vim-02-beginner.tutor translation
        translation(sr): Update vim-01-beginner.tutor translation
        patch 9.1.1786: Compile error with clipboard
        runtime(netrw): 'equalalways' is not always respected
        patch 9.1.1785: typo in comment in change.c
        runtime(doc): fix typo, reorder, mention zip plugin at :h changed-9.2
        runtime(doc): clarify 'fileignorecase' option setting
        patch 9.1.1784: Wayland code can be improved
        runtime(zip): support PowerShell Core
        patch 9.1.1783: ins_compl_leader() too far away from ins_compl_leader_len()
        patch 9.1.1782: buffer-listener callbacks may not match buffer content
        patch 9.1.1781: some functions could be defined static
        runtime(vimgoto): recognize 'silent' prefixes
        patch 9.1.1780: mbyte contains overlapping list of utf_classes table
        runtime(unicode): update check for netrw
        patch 9.1.1779: completion: 'autocomplete' cannot be enabled per buffer
        patch 9.1.1778: sha256() treats empty blob and null blob differently
        runtime(lf): update syntax to support lf version r38
        patch 9.1.1777: Mouse click to open fold doesn't work with utf-8 "foldclose" chars
        patch 9.1.1776: completion: "adding" expansion doesn't work with cfc=keyword
        Remove dlejay from maintainer list
        patch 9.1.1775: filetype: Mamba configuration files are not recognized
        patch 9.1.1774: cannot calculate sha256 of a Blob
        runtime(config): fix inconsistent group name
        patch 9.1.1773: Crash in BufLeave after BufUnload closes other windows
        patch 9.1.1772: completion: inconsistent selection of first item with 'autocomplete'
        patch 9.1.1771: complete: some redraw issues with 'autocomplete'
        patch 9.1.1770: Vim9: wrong behaviour with trailing comments in command blocks
        runtime(log): highlight Java Errors
        patch 9.1.1769: completion: "preinsert" insert wrong word with 'smartcase' and 'autocomplete'
        runtime(vim): Update base syntax, fix indented Vim9 :redir highlighting
        runtime(netrw): update regex to handle remote archives
        patch 9.1.1768: Makefile does not uninstall global plugins
        patch 9.1.1767: Patch v9.1.1765 was wrong
        runtime(kitty): Fix typo in syntax file for kitty
        patch 9.1.1766: Vim9: some functions do not handle null_string correctly
        runtime(doc): Tweak doc style in syntax.txt
        runtime(doc): mention generic log highlighter
        runtime(doc): fix doc style from commit 5c9b71d63c1
        runtime(kitty): fix typo in syntax script
        runtime(doc): remove trailing whitespace from example in builtin.txt
        runtime(doc): clarify how to call complete() funcs
        runtime(m4): Improve parameters highlighting in syntax script
        patch 9.1.1765: f_isnan() and f_isinf() do not correctly initialize rettv type
        runtime(termdebug): drop outdated comment from termdebug.vim
        runtime(colors): update colorschemes:
        runtime(doc): Fix typos in eval.txt
        Fix some typos in documentation, C code and test files
        patch 9.1.1764: filetype: CODEOWNERS file not recognized
        patch 9.1.1763: filetype: kitty config files are not recognized
        patch 9.1.1762: completion: selected item not cleared on <BS> with 'ac'
        Problem:  'ruler' is set in defaults.vim
        runtime(doc): Improve doc for cmdline-ranges in cmdline.txt
        runtime(doc): Improve the doc for :syn-containedin
        runtime(doc): typo in recent doc style tweaks in options.txt
        patch 9.1.1760: wrong proto file for insexpand.pro
        patch 9.1.1759: filetype: generic log detection is too disturbing
        runtime(doc): Tweak documentation style more in options and ft_hare
        patch 9.1.1758: Diff mode crashes when adding text property in autocommand
        runtime(config): mark unportable += as an error
        runtime(html): guard against an existing b:undo_ftplugin var
        patch 9.1.1757: The colorresp plugin causes additional redraws
        patch 9.1.1756: termdebug: Need a few more user commands
        runtime(doc): update Markdown syntax documentation and mention Pandoc
        runtime(doc): tweak documentation style a bit more in options.txt
        patch 9.1.1755: filetype: generic log files are not recognized
        runtime(doc): tweak documentation style
        runtime(doc): Add :defe[r] shortname spec and tag
        patch 9.1.1754: :helptags doesn't skip examples with syntax
        runtime(doc): improve 'complete' option description
        runtime(netrw): only keep cursor position in tree listing mode
        runtime(doc): use a single pattern in :h 'incsearch' example
        patch 9.1.1753: defaults: 'diffopt' option value can be improved
        runtime(vim): Update indent script for line continuation with lambda
        runtime(python): Update syntax, fix pythonEllipsis pattern
        runtime(doc): Update autocmd examples for command line autocompletion
        runtime(doc): improve docs related to 'autocomplete'
        patch 9.1.1752: tests: need another test for v9.1.1750 behaviour
        patch 9.1.1751: potential buffer-overflow in find_pattern_in_path()
        patch 9.1.1750: completion: preinserted text highlighed using ComplMatchIns
        patch 9.1.1749: leaking memory in cs_find_common()
        patch 9.1.1748: macOS: Default scheduler priority too low
        patch 9.1.1747: completion: redo (.) broken with preinsert and autocompletion
        runtime(doc): mention 'findfunc' at :h :find
        patch 9.1.1746: Missing Null ptr check in cs_find_common()
        runtime(doc): mention hl-PreInsert in version9.txt
        patch 9.1.1745: tabpanel: not properly redraw after wildmenu
        runtime(python): highlight ellipsis literals
        runtime(doc): Improve doc for cmdline-autocompletion
        patch 9.1.1744: tests: Test_skip_wildtrigger_hist_navigation() may fail
        CI: Bump actions/labeler from 5 to 6
        patch 9.1.1743: Haiku: no full-screen support
        runtime(hare): update for Hare 0.25.2
        runtime(python): Update syntax file, fix f-string float highlighting
        patch 9.1.1742: complete: preinsert does not work well with preinsert
        patch 9.1.1741: Regression with kitty protocol and trailing byte "u"
        patch 9.1.1740: Memory leak with wildmode=longest,full and wildoptions=pum
        runtime(m4): Remove m4Type and leftover m4Function in syntax script
        runtime(doc): Tweak spacing in develop.txt
        patch 9.1.1739: Matches may be listed twice with wildmode=longest,list
        patch 9.1.1738: cmdline-autocompletion breaks history navigation
        patch 9.1.1737: Patch v9.1.1714 introduce a regression for wildmenu
        runtime(nu): Add new Nushell runtime files
        runtime(m4): Remove m4Function
        patch 9.1.1736: Cannot detect <F3> using kitty protocol
        patch 9.1.1735: Cygwin Makefile still checks for Win XP version
        runtime(colorresp): use correct load guard pattern
        runtime(ada): mark as unmaintained, fix a few issues with the ftplugin
        runtime(hamster): do not globally set ignorecase
        runtime(m4): Improve comments, distinguish them from #-lines
        patch 9.1.1734: Memory leak when allocating match fails
        patch 9.1.1733: tests: failure when remote_server() fails
        runtime(python): Do not match contained identifiers as pythonType
        runtime(netrw): Ensure netrw#fs#Dirname() always returns a trailing slash
        runtime(python): add syntax support inside f-strings
        patch 9.1.1732: filetype: .inc file detection can be improved
        patch 9.1.1731: Not using const qualifier for opchars
        runtime(doc): Add a Development policy
        runtime(doc): Tweak documentation in vi_diff.txt
        runtime(m4): update syntax script
        CI: increase timeout parameter to 60s for the link-check
        runtime(doc): Remove dead link from todo.txt
        runtime(doc): quote partial urls with a backtick
        runtime(vimgoto): Implement jumping to autoloaded functions
        patch 9.1.1730: filetype: vivado journal/log files are not recognized
        runtime(doc): remove documentation for t_Ms terminal code
        runtime(keymap): Add transliteration (buckwalter) arabic keymap
        patch 9.1.1729: CI is not run with clang 21
        patch 9.1.1728: termdebug: cannot evaluate visual selected expression
        patch 9.1.1727: Nextstep support still included
        patch 9.1.1726: Patch v9.1.1725 causes problems
        runtime(doc): document use of proto files in develop.txt
        patch 9.1.1725: Wayland code can be improved
        runtime(doc): add missing da1 value to TermResponseAll doc
        patch 9.1.1724: Compiler warning about ununitialized variable in ex_docmd.
        patch 9.1.1723: Missing ifdefs
        patch 9.1.1722: compiler may optimize away clearing of crypt key
        patch 9.1.1721: Defining a global gettimeofday() function
        patch 9.1.1720: using gettimeofday() for parsing OSC responses
        patch 9.1.1719: socket server code can be improved
        patch 9.1.1718: filetype: kubectl config file is not recognized
        patch 9.1.1717: filetype: AWS cli alias file is not recognized
        runtime(java): Dismiss "g:markdown_fenced_languages" for Java buffers
        runtime(vim): Update base syntax, fix Vim9 :for loop variable highlighting
        patch 9.1.1716: wrong indent in win_line()
        patch 9.1.1715: Some functions need to be re-ordered
        patch 9.1.1714: completion: wildmode=longest:full selects wrong item
        patch 9.1.1713: filetype: fvwm2m4 files are no longer detected
        patch 9.1.1712: Screen not redrawn properly on t_RB response
        patch 9.1.1711: Missing type cast in clipboard.c
        runtime(doc): Add [range] spec to :help :tcl and :help :tclfile
        runtime(doc): Tweak documentation style
        patch 9.1.1710: Compile warnings in clipboard.c
        patch 9.1.1709: filetype: kyaml files are not recognized
        runtime(vim): Update base syntax, match :defer command argument
        patch 9.1.1708: tests: various tests can be improved
        runtime(astro): catch json_decode() error when parsing tsconfig.json
        patch 9.1.1707: diff.pro contains #ifdefs
        patch 9.1.1706: MS-Windows: Compile error when building with if_ruby
        README.md: Fix the Warp link
        README.md: Make the Vim logo visible again.
        README.md: Add sponsor banner
        patch 9.1.1705: time.h include is available on all platforms
        runtime(tutor): Add a section on text objects and special registers to Chapter 2
        patch 9.1.1704: Cannot determine non-X11/Wayland clipmethods
        patch 9.1.1703: Cannot react to terminal OSC responses
        runtime(vim): update vim syntax generator for patch v9.1.1692
        patch 9.1.1702: tests: test_edit still fails on CI
        patch 9.1.1701: tests: failure on CI with GUI and ASAN in test_edit.res
        patch 9.1.1700: Multiline ignorecase specific pattern does not match with 'ignorecase'
        patch 9.1.1699: Fuzzy completion disabled for 'findfunc' and customlist
        runtime(debversions): Move bullseye, focal, and oracular to "unsupported"
        patch 9.1.1698: Some error numbers are not documented
        runtime(vimcomplete): Try catch completion of `pack_jobs->add({`
        patch 9.1.1697: tests: no test for aclocal.m4
        runtime(indent-tests): Use silent write of resulting files
        translation: Remove outdated rule for nl.po
        patch 9.1.1696: tabnr from getwininfo() for popup windows is always 0
        runtime(tutor): remove duplicate tutor1.zh
        runtime(tutor): fix language selection for zh
        patch 9.1.1695: Need more Vim script specific tests
        patch 9.1.1694: filetype: Buck eXtension Lang files are not recognized
        patch 9.1.1693: tests: test_filetype fails in shadow dir
        patch 9.1.1692: global_functions are not constant
        patch 9.1.1691: over-allocation in ga_concat_strings()
        patch 9.1.1690: Missing recursion guard in dos/unix_expandpath()
        patch 9.1.1689: CmdlineChanged not triggered by <Del>
        patch 9.1.1688: potential buffer overrun in bufwrite.c
        patch 9.1.1687: filetype: autoconf filetype not always correct
        runtime(lf): update syntax to support lf version r37
        patch 9.1.1686: if_ruby: unknown pragma when not using gcc
        patch 9.1.1685: Missing changes from PR 18068
        patch 9.1.1684: min()/max() does not handle float data types
        patch 9.1.1683: xxd: Avoid null dereference in autoskip colorless
        runtime(python): support 'type's soft keyword form
        patch 9.1.1682: tests: Test_wildtrigger_update_screen() creates unused mapping
        patch 9.1.1681: tests: no test for actually moving cursor with 'acl'
        runtime(termdebug): Remove load guard
        runtime(doc): update termguicolors default description
        patch 9.1.1680: MS-Windows: possible buffer-under run in if_cscope
        patch 9.1.1679: unclear what key causes CmdlineLeave autocommand
        runtime(netrw): fix :Explore command in terminal
        patch 9.1.1678: Amiga: cannot handle large undo files
        patch 9.1.1677: wrong ifdef in message.c
        patch 9.1.1676: completion: long line shown twice
        runtime(sh): add syntax highlighting support for ${ cmd;} and ${|cmd;}
        patch 9.1.1675: MS-Windows: Makefiles can be refactored
        patch 9.1.1674: Patch v9.1.1666 causes problems on kitty
        patch 9.1.1673: if_python: still support for Python 1
        patch 9.1.1672: completion: cannot add timeouts for 'cpt' sources
        runtime(fstab): Added mtab support to fstab syntax.
        patch 9.1.1671: configure: missing comment about AC_CONFIG_SRCDIR
        patch 9.1.1670: completion: autocomplete breaks second completion
        patch 9.1.1669: Vim script: no support for URI de-/encoding
        patch 9.1.1668: items() does not work for Blobs
        patch 9.1.1667: Another outdated comment in eval.c
        patch 9.1.1666: no support for terminal primary device attributes
        patch 9.1.1665: Outdated comment in eval.c
        runtime(doc): Fix missing heading in remote.txt
        patch 9.1.1664: configure: can use any autoconf
        runtime(doc): Tweak documentation style
        runtime(colors): Update colorschemes
        patch 9.1.1663: xxd: 9.1.0023 introduced additional dependency
        runtime(systemverilog): Add syntax highlighting for 1800-2023 block strings
        patch 9.1.1662: Issues with proto files: missing or inconsistent prototypes.
        patch 9.1.1661: Coverity finds a few issues in clientserver.c
        patch 9.1.1660: popups without decoration are positioned wrong at bottom of screen
        patch 9.1.1659: configure: uses AC_INIT without args
        patch 9.1.1658: Missing includes for Wayland headers
        patch 9.1.1657: Autocompletion adds delay
        runtime(doc): correct another problem in :h items()
        patch 9.1.1656: MS-Windows: Patch v9.1.1652 breaks clipboard
        patch 9.1.1655: Build-failure in do_mouse()
        patch 9.1.1654: build failure when FEAT_DIFF is not defined
        patch 9.1.1653: Coverity complains about Null pointer dereference
        translation(it): Update Italian translation
        translation(it): update Italian manpage
        patch 9.1.1652: cannot determine non-X11/Wayland clipmethods
        patch 9.1.1651: Cannot use clientserver over socket
        patch 9.1.1650: popup: window may not properly resize
        patch 9.1.1649: attrs allocation and fuzzy growarray could leak
        runtime(python): optimize pythonSync pattern
        CI: Bump actions/checkout from 4 to 5
        patch 9.1.1648: MS-Windows: some style issues with patch v9.1.1646
        runtime(doc): fix style and clarify items() function for String type
        patch 9.1.1647: filetype: Cangjie files are not recognized
        patch 9.1.1646: MS-Windows: completion cannot handle implicit drive letters
        patch 9.1.1645: fuzzy.c can be further improved
        patch 9.1.1644: configure: doesn't separate CPPFLAGS and CFLAGS
        runtime(doc): Update help for the items() function
        patch 9.1.1643: tabpanel: mouse code too complicated
        patch 9.1.1642: configure: wrong C99 feature test
        patch 9.1.1641: a few compiler warnings are output
        patch 9.1.1640: Unicode has deprecated some code-points
        patch 9.1.1639: completion: popup may be misplaced
        patch 9.1.1638: completion: not possible to delay the autcompletion
        runtime(vim): set 'comments' based on script type (legacy/Vim9)
        runtime(vim9): Disable shellslash for shellescape() in Open()
        patch 9.1.1637: FEAT_DIFF used in diff.pro
        translation(sr): Update Serbian messages translation
        runtime(diff): fix mixed translations in zh_CN
        patch 9.1.1636: style issues
        patch 9.1.1635: tabpanel: cannot drag inactive tabs
        patch 9.1.1634: Clipboard code can be improved
        patch 9.1.1633: Search pattern shown incorrectly with negative offset
        patch 9.1.1632: memory leak in fuzzy.c
        patch 9.1.1631: proto files are outdated
        patch 9.1.1630: tests: fuzzy bufname completion test doesn't match successfully
        patch 9.1.1629: Vim9: Not able to use more than 10 type arguments in a generic function
        runtime(python): highlight "self" and "cls" in syntax script
        runtime(vimgoto): make gf extract packadd/colo name more flexible
        patch 9.1.1628: fuzzy.c has a few issues
        runtime(doc): Adapt fuzzy doc to reflect 'fzy' algorithm
        patch 9.1.1627: fuzzy matching can be improved
        patch 9.1.1626: cindent: does not handle compound literals
        patch 9.1.1625: Autocompletion slow with include- and tag-completion
        runetime(vim): gf maybe hang and fail
        runtime(vim): cannot jump to :colorscheme files
        patch 9.1.1624: Cscope not enabled on MacOS
        runtime(doc): allow more C99 features
        runtime(python): Also sync syntax at 'async def'
        runtime(doc): update :call with a range and remove space
        runtime(doc): Fix 2 minor issues after 32d6bd6df
        runtime(python): Highlight f-string replacement fields in Python
        runtime(python): Highlight classes as structures
        CI: Add Lychee CI test to check for broken links
        runtime(doc): remove dead links
        patch 9.1.1623: Buffer menu does not handle unicode names correctly
        patch 9.1.1622: Patch v9.1.1432 causes performance regressions
        patch 9.1.1621: flicker in popup menu during cmdline autocompletion
        patch 9.1.1620: filetype: composer.lock and symfony.lock files not recognized
        patch 9.1.1619: Incorrect E535 error message
        runtime(doc): Fix style and typos in builtin.txt and usr_41.txt
        patch 9.1.1618: completion: incorrect selected index returned from complete_info()
        patch 9.1.1617: Vim9: some error messages can be improved
        runtime(doc): Tweak documentation style
        patch 9.1.1616: xxd: possible buffer overflow with bitwise output
        patch 9.1.1615: diff format erroneously detected
        patch 9.1.1614: Vim9: possible variable type change
        patch 9.1.1613: tests: test_search leaves a few swapfiles behind
        patch 9.1.1612: Ctrl-G/Ctrl-T do not ignore the end search delimiter
        patch 9.1.1611: possible undefined behaviour in mb_decompose()
        runtime(vim): Update ftplugin, fix option variable 'keywordprg' matching
        runtime(racket): update Racket runtime files
        translation: Generate year for MS Windows differently
        patch 9.1.1610: completion: hang or E684 when 'tagfunc' calls complete()
        runtime(doc): Update CONTRIBUTING and clarify use of Vim9 script
        patch 9.1.1609: complete: Heap-buffer overflow with complete function
        runtime(c): set omnifunc only for Vim, since it is Vim9 Script
        runtime(vim): add simple vimscript complete function
        runtime(script): Update Last Change Header
        patch 9.1.1608: No command-line completion for :unsilent {command}
        patch 9.1.1607: :apple command detected as :append
        patch 9.1.1606: filetype: a few more files are not recognized
        patch 9.1.1605: cannot specify scope for chdir()
        runtime(doc): Improve doc for cmdline-autocomplete
        runtime(doc): update develop assumptions
        patch 9.1.1604: completion: incsearch highlight might be lost
        runtime(optwin): Fix E94 when searching for the option-window
        patch 9.1.1603: completion: cannot use autoloaded funcs in 'complete' F{func}
        runtime(java): Manage byte limits for variable-width lookbehind assertions
        runtime(help): Unset `'comments'` and `'cms'` options
        runtime(netrw): netrw#BrowseX() needs to distinguish local and remote file
        runtime(typescript): Add syntax support for defer and arbitrary module identifiers
        translation: Auto-generate headers for the vim.pot file
        patch 9.1.1602: filetype: requirements-*.txt files are not recognized
        patch 9.1.1601: Patch v8.1.0425 was wrong
        runtime(netrw): Use correct "=~#" for the netrw_sizestyle='H' option
        runtime(openscad): add a filetype plugin
        patch 9.1.1600: using diff anchors with hidden buffers fails silently
        runtime(javascript): add "as" as a reserved keyword to syntax script
        patch 9.1.1599: :bnext doesn't go to unlisted help buffers
        runtime(doc): Update ft-vim-syntax documentation
        patch 9.1.1598: filetype: waybar config file is not recognized
        patch 9.1.1597: CI reports leaks in libgtk3 library
        patch 9.1.1596: tests: Test_search_wildmenu_iminsert() depends on help file
        runtime(doc): remove mentioning of netrwSettings.vim
        runtime(doc): fix typo at :h cmdline-autocompletion
        patch 9.1.1595: Wayland: non-portable use of select()
        patch 9.1.1594: completion: search completion throws errors
        runtime(doc): tweak option name notation further
        runtime(doc): add back bars for the '' mark
        runtime(vim): add gf support for import and packadd in ftplugin
        runtime(helptoc): add s keymap to split and jump to selected entry
        runtime(syntax-tests): Break up non-ASCII over-75-byte-long lines
        runtime(doc): fix mismatch between 'backspace' and |i_backspacing|
        runtime(doc): Use correct option-name tags
        CI: Update labeler.yml with correct netrw path
        runtime(doc): Tweak documentation style
        translation(uk): Fix wrong Ukrainian message translation
        check.vim: Further improve po message checks
        translation(it): Update Italian translation
        patch 9.1.1593: Confusing error when compiling incomplete try block
        runtime(misc): removing saccarosium from maintainer list
        patch 9.1.1592: Vim9: crash with classes and garbage collection
        runtime(vim): Update base syntax, match Neovim builtin functions
        runtime(vim): Update base syntax, fix :map termination in :command RHS
        CI: Manage multibyte characters in syntax tests
        CI: Remove the file filters for syntax tests
        CI(screendump): Support iterative filtering for screendump comparison
        CI(screendump): Move an early-return test out of the loop
        CI: Include provenance in names of collected artifacts
        runtime(vim): Cleanup syntax tests
        patch 9.1.1591: VMS support can be improved
        patch 9.1.1590: cannot perform autocompletion
        runtime(ccomplete): return partial results on complete_check()
        patch 9.1.1589: Cannot disable cscope interface using configure
        patch 9.1.1588: Vim9: cannot split dict inside command block
        runtime(netrw): upstream snapshot v184
        runtime(vim): fix various indentation issues
        runtime(doc): use correct possessive form
        patch 9.1.1587: Wayland: timeout not updated before select()
        patch 9.1.1586: Vim9: can define an enum/interface in a function
        runtime(vim): Update base syntax, match enum constructor type args
        runtime(vim): Update base syntax, match generic functions
        runtime(ccomplete): use complete_check() in ccomplete plugin
        runtime(editorconfig): drop mkzip.sh
        patch 9.1.1585: Wayland: gvim still needs GVIM_ENABLE_WAYLAND
        runtime(misc): use :hor :term to ensure new term window is split horizontally
        CI: increase test timeout to 30 minutes
        patch 9.1.1584: using ints as boolean type
        check.vim: Improve po message checks
        translation(it): Update Italian translation
        runtime(doc): Tweak documentation style in usr_90.txt
        patch 9.1.1583: gvim window lost its icons
        patch 9.1.1582: style issue in vim9type.c and vim9generics.c
        runtime(doc): remove mention of ftp.vim.org
        runtime(doc): Tweak documentation style
        runtime(doc): Fix typo in :help help-summary
        patch 9.1.1581: possible memory leak in vim9generics.c
        patch 9.1.1580: possible memory leak in vim9type.c
        patch 9.1.1579: Coverity complains about unchecked return value
        patch 9.1.1578: configure: comment still mentions autoconf 2.71
        patch 9.1.1577: Vim9: no generic support yet
        patch 9.1.1576: cannot easily trigger wildcard expansion
        runtime(doc): clarify C99 constraints and portability assumptions
        patch 9.1.1575: tabpanel not drawn correctly with wrapped lines
        patch 9.1.1574: Dead code in mbyte.c
        runtime(doc): mention the "pipefail" shell option
        patch 9.1.1573: Memory leak when pressing Ctrl-D in cmdline mode
        translation: mark vim.pot as binary
        translation: do not add message location as comments into vim.pot
        patch 9.1.1572: expanding $var does not escape whitespace for 'path'
        patch 9.1.1571: CmdlineChanged triggered to often
        runtime(rust): improve loading time
        runtime(doc): Update help syntax, match :autocmd options
        patch 9.1.1570: Copilot suggested some improvements in cmdexpand.c
        translation(de): Update German translations
        translation(it): Update Italian translations
        patch 9.1.1569: tests: Vim9 tests can be improved
        runtime(doc): Tweak documentation about tab pages
        runtime(uc): include uc filetype plugin
        translation: comment out deletion of *.pot file in Makefiles
        patch 9.1.1568: need a few more default highlight groups
        patch 9.1.1567: crash when using inline diff mode
        patch 9.1.1566: self-referenced enum may not get freed
        patch 9.1.1565: configure: does not consider tiny version for wayland
        runtime(lf): update syntax to support lf version r36
        runtime(sh): properly delete shell commands in syntax file
        Update editorconfig and the documented C-style for sign.c/sound.c
        runtime(vim): Update base syntax and generator, improve command/function distinction
        patch 9.1.1564: crash when opening popup to closing buffer
        translation: mark vim.pot as linguist-generated, ignore msg locations in vim.pot
        patch 9.1.1563: completion: ruler may disappear
        patch 9.1.1562: close button always visible in the 'tabline'
        runtime(python): Highlight f-strings in Python
        runtime(vim): Update base syntax, match "any" type distinctly
        patch 9.1.1561: configure: wayland test can be improved
        patch 9.1.1560: configure: uses $PKG_CONFIG before it is defined
        patch 9.1.1559: tests: Test_popup_complete_info_01() fails when run alone
        runtime(doc): fix claim that 'CTRL-W CTRL-C' and 'CTRL-W c' are the same
        runtime(doc): handle newlines in base64 string encode example
        runtime(vim): Update base syntax, fix incorrect function error
        runtime(compiler): Add PHPStan compiler
        translation: regenerate vim.pot, ignore version.c changes
        patch 9.1.1558: str2blob() treats NULL string and empty string differently
        patch 9.1.1557: not possible to anchor specific lines in difff mode
        patch 9.1.1556: string handling in cmdexpand.c can be improved
        patch 9.1.1555: completion: repeated insertion of leader
        patch 9.1.1554: crash when omni-completion opens command-line window
        patch 9.1.1553: Vim9: crash when accessing a variable in if condition
        runtime(tar): update minimum Vim version required for tar.vim
        patch 9.1.1552: [security]: path traversal issue in tar.vim
        patch 9.1.1551: [security]: path traversal issue in zip.vim
        patch 9.1.1550: defaults: 'showcmd' is not enabled in non-compatible mode on Unix
        patch 9.1.1549: filetype: pkl files are not recognized
        patch 9.1.1548: filetype: OpenFGA files are not recognized
        runtime(swig): add 'comments', 'commentstring' in filetype plugin
        runtime(twig): include twig filetype plugin
        patch 9.1.1547: Wayland: missing ifdef
        translation: ignore vim.pot creation date, regenerate it, rm allfiles
        patch 9.1.1546: Vim9: error with has() and short circuit evaluation
        runtime(python2): Highlight b-strings in Python 2.7
        runtime(doc): Tweak documentation
        patch 9.1.1545: typo in os_unix.c
        runtime(python): highlight bytes in python
        runtime(python2): highlight unicode strings in python2
        patch 9.1.1544: :retab cannot be limited to indentation only
        runtime(erlang): Add support for triple-quoted strings and docstrings
        patch 9.1.1543: Wayland: clipboard appears to not be working
        patch 9.1.1542: Coverity complains about uninitialized variable
        patch 9.1.1541: Vim9: error when last enum value ends with a comma
        runtime(vim): Update help syntax file, improve highlighting of included Vim examples
        patch 9.1.1540: completion: menu state wrong on interruption
        patch 9.1.1539: completion: messages don't respect 'shm' setting
        runtime(vim): Update base syntax, improve :match highlighting
        translation(it): update Italian message translations
        translation: include vim.pot in the repository
        runtime(python): update rendering of Unicode named literals in syntax script
        translation(ru): Update messages translation
        tests: string options in gen_opt_test.vim not fully sorted
        check.vim: detect trailing whitespace
        runtime(help_ru): Update help_ru syntax script
        runtime(vim): Update base syntax, improve function call highlighting
        patch 9.1.1537: helptoc: still some issues when markdown code blocks
        patch 9.1.1536: tests: test_plugin_comment uses wrong :Check command
        patch 9.1.1535: the maximum search count uses hard-coded value 99
        patch 9.1.1534: unnecessary code in tabpanel.c
        patch 9.1.1533: helptoc: does not handle code sections in markdown well
        runtime(doc): clarify how ex ranges are adjusted when acting on folds
        translation(ru): update vim-ru according to patch 9.1.1485
        translation(ru): update vimtutor-ru man according to commit 5bbdd0b
        translation(ru): Update main readme.ru.txt according to commit 2bfd1ee
        runtime(filetype): fix incorrect pattern and break early
        Revert "runtime(haskell): Add single quote to `iskeyword` in ftplugin (#8191)"
        patch 9.1.1532: termdebug: not enough ways to configure breakpoints
        patch 9.1.1531: confusing error with nested legacy function
        patch 9.1.1530: Missing version change in v9.1.1529
        patch 9.1.1529: Win32: the toolbar in the GUI is old and dated
        patch 9.1.1528: completion: crash with getcompletion()
        patch 9.1.1527: Vim9: Crash with string compound assignment
        runtime(filetype): improve asm heuristics and move into FTasmsyntax()
        patch 9.1.1526: completion: search completion match may differ in case
        runtime(netrw): restore blank line cleanup after file listing
        patch 9.1.1525: tests: testdir/ is a bit messy
        patch 9.1.1524: tests: too many imports in the test suite
        patch 9.1.1523: tests: test_clipmethod fails in non X11 environment
        patch 9.1.1522: tests: still some ANSI escape sequences in test output
        patch 9.1.1521: completion: pum does not reset scroll pos on reopen with 'noselect'
        patch 9.1.1520: completion: search completion doesn't handle 'smartcase' well
        patch 9.1.1519: tests: Test_termdebug_decimal_breakpoints() may fail
        runtime(doc): Add documentation style
        patch 9.1.1518: getcompletiontype() may crash
        runtime(optwin): add missing values for tabpanel option
        translation(tr): Update Turkish translations
        runtime(doc): fix a few typos introduced in 0ae9e19540dda5d
        runtime(autopkgtest): add ftplugin file for autopkgtest
        runtime(autopkgtest): add syntax file for autopkgtest
        runtime(debcontrol): move kernel/architecture definitions to shared/debarchitectures.vim
        patch 9.1.1517: filetype: autopkgtest files are not recognized
        patch 9.1.1516: tests: no test that 'incsearch' is updated after search completion
        patch 9.1.1515: Coverity complains about potential unterminated strings
        patch 9.1.1514: Coverity complains about the use of tmpfile()
        patch 9.1.1513: resizing Vim window causes unexpected internal window width
        runtime(doc): add a section for options influencing search
        tests: fix typo in comment (after v9.1.1511)
        runtime(vim): Update base-syntax, match :filetype in functions
        patch 9.1.1512: completion: can only complete from keyword characters
        patch 9.1.1511: tests: two edit tests change v:testing from 1 to 0
        patch 9.1.1510: Search completion may use invalid memory
        patch 9.1.1509: patch 9.1.1505 was not good
        runtime(vim): Update base-syntax, match escape sequences in :command blocks
        runtime(go): fix `b:undo_ftplugin`
        patch 9.1.1508: string manipulation can be improved in cmdexpand.c
        runtime(vim): Update base-syntax and generator, match all default highlight groups
        runtime(vim): Update base-syntax and generator, generate command modifiers
        patch 9.1.1507: symlinks are resolved on :cd commands
        runtime(postscr): Correct some standard font names in syntax
        runtime(optwin): show 'guiligatures' option also on MS-Windows builds
        patch 9.1.1506: tests: missing cleanup in Test_search_cmdline_incsearch_highlight()
        patch 9.1.1505: not possible to return completion type for :ex command
        patch 9.1.1504: filetype: numbat files are not recognized
        patch 9.1.1503: filetype: haxe files are not recognized
        patch 9.1.1502: filetype: quickbms files are not recognized
        patch 9.1.1501: filetype: flix files are not recognized
        runtime(go): add section movement mappings to ftplugin
        runtime(doc): Tweak documentation style
        patch 9.1.1500: if_python: typo in python error variable
        patch 9.1.1499: MS-Windows: no indication of ARM64 architecture
        runtime(tutor): regenerate utf-8 version of French vimtutor manpage
        runtime(netrw): upstream snapshot of v183
        runtime(vim): Update base-syntax, improve :syn-sync line defaults
        patch 9.1.1498: completion: 'complete' funcs behave different to 'omnifunc'
        patch 9.1.1497: Link error with shm_open()
        patch 9.1.1496: terminal: still not highlighting empty cells correctly
        README: mention POSIX vi as a goal of this project
        patch 9.1.1495: Wayland: uses $XDG_SEAT to determine seat
        ci: Use tmate for debugging Github Actions CI
        ci: disable installing netbeans on Windows runners
        patch 9.1.1494: runtime(tutor): no French translation for Chapter 2
        runtime(tutor): apply fixes to runtime/tutor/tutor2
        translation(it): updated Italian manpage
        patch 9.1.1493: manually comparing positions on buffer
        nsis: copy tutor directory recursively
        patch 9.1.1492: tests: failure when Wayland compositor fails to start
        patch 9.1.1491: missing out-of-memory checks in cmdexpand.c
        runtime(vim): re-generate vim syntax script after v9.1.1487
        patch 9.1.1490: 'wildchar' does not work in search contexts
        runtime(doc): fix :vmap example to avoid unwanted spaces with JJ
        patch 9.1.1489: terminal: no visual highlight of empty cols with empty 'listchars'
        patch 9.1.1488: configure: using obsolete macro AC_PROG_GCC_TRADITIONAL
        runtime(doc): Fix modeline in wayland.txt
        patch 9.1.1487: :cl doesn't invoke :clist
        patch 9.1.1486: documentation issues with Wayland
        Maintainers: Update MAINTAINERS file
        patch 9.1.1485: missing Wayland clipboard support
        runtime(pandoc): sync syntax script with upstream
        runtime(netrw): upstream snapshot of v182
        patch 9.1.1484: tests: Turkish locale tests fails on Mac
        patch 9.1.1483: not possible to translation position in buffer
        patch 9.1.1482: scrolling with 'splitkeep' and line()
        runtime(doc): mismatch between the :uniq document's description and examples
        runtime(diff): fix regex for matching no-eol match
        runtime(netrw): remove the fun from netrw :)
        runtime(doc): update description of :uniq command
        runtime(vim): Update base-syntax, match unamed register alias
        patch 9.1.1481: gcc complains about uninitialized variable
        runtime(doc): improve documentation style in editing.txt
        patch 9.1.1480: Turkish translation outdated
        patch 9.1.1479: regression when displaying localized percentage position
        translation(it): update Italian manpage for vimtutor
        runtime(vim): Update base-syntax, match :uniq command
        patch 9.1.1478: Unused assignment in ex_uniq()
        runtime(vim): Update base-syntax, match OR operator in :echo and :execute
        patch 9.1.1476: no easy way to deduplicate text
        runtime(java): Complement the recognition of type parameter sections
        patch 9.1.1476: missing out-of-memory checks in cmdexpand.c
        runtime(doc): vimtutor starts Vim in nocompatible mode
        runtime(doc): remove wrong documentation of the :digraph command


    </details>

  2025-10-27T22:13:50Z by [Thomas Turner](mailto:thomas_turner@talktalk.net) [cb78fe1a1d15](https://github.com/LineageOS/android_external_vim/commit/cb78fe1a1d15)  [Review](https://review.lineageos.org/q/I478980c6d0eebbc5fdc30dea9591fcf7ed208f9b)
- `build/soong`: Revert &quot;Clear as much of cc.Module as possible after GenerateBuildActions&quot;<br>
  2025-10-27T22:57:34Z by [Colin Cross](mailto:ccross@android.com) [cff28f536f96](https://github.com/LineageOS/android_build_soong/commit/cff28f536f96)  [Review](https://review.lineageos.org/q/If8b6862d43bb3328045a7625471742420b540d69)
- `device/qcom/sepolicy_vndr/sm8550`: NFC: ST: Add the AIDL HAL service<br>
  2025-10-29T00:29:44Z by [Devendar Gali](mailto:quic_dgali@quicinc.com) [2894ee51cb2a](https://github.com/LineageOS/android_device_qcom_sepolicy_vndr/commit/2894ee51cb2a)  [Review](https://review.lineageos.org/q/I2f6620951014fd176361b6b9cc114278004a494c)
- `device/qcom/sepolicy_vndr/sm8450`: NFC: FR74324, Add the new STM NFC HAL service<br>
  2025-10-29T00:30:15Z by [Devendar Gali](mailto:quic_dgali@quicinc.com) [e39b56b1cc7b](https://github.com/LineageOS/android_device_qcom_sepolicy_vndr/commit/e39b56b1cc7b)  [Review](https://review.lineageos.org/q/I83b2053b0fe8a0db9827765d14d7945e041b7233)
- `device/qcom/sepolicy_vndr/sm8450`: NFC: ST: Add the AIDL HAL service<br>
  2025-10-29T00:30:44Z by [Devendar Gali](mailto:quic_dgali@quicinc.com) [43f9c104140b](https://github.com/LineageOS/android_device_qcom_sepolicy_vndr/commit/43f9c104140b)  [Review](https://review.lineageos.org/q/I2f6620951014fd176361b6b9cc114278004a494c)
- `hardware/qcom-caf/thermal-legacy-um`: thermal-hal: Revert &quot;Add tsens,bcl configuration for kona&quot;<br>
  2025-10-29T13:31:46Z by [armdebug](mailto:armdebug@protonmail.com) [08781377d20a](https://github.com/LineageOS/android_hardware_qcom_thermal/commit/08781377d20a)  [Review](https://review.lineageos.org/q/I406f20699a375e4fe1c726961b26caebcf9d4450)
- `hardware/qcom-caf/thermal-legacy-um`: thermal-hal: Update skin temperature threshold for kona<br>
  2025-10-30T00:50:21Z by [Edwin Moquete](mailto:edwinmmoquete@gmail.com) [03845e453f08](https://github.com/LineageOS/android_hardware_qcom_thermal/commit/03845e453f08)  [Review](https://review.lineageos.org/q/I24a8cefd6751580091e69487190c91ac00c516ce)
- `external/vim`: vim: Update srcs\[\]<br>
  2025-10-30T15:09:39Z by [Thomas Turner](mailto:thomas_turner@talktalk.net) [5f10e711add3](https://github.com/LineageOS/android_external_vim/commit/5f10e711add3)  [Review](https://review.lineageos.org/q/Ia40e8e12a31b8a9e0891595cc015db55afe28275)
- `device/xiaomi/sm8250-common`: sm8250-common: Add clang-format<br>
  2025-10-30T22:16:31Z by [Sebastiano Barezzi](mailto:seba@sebaubuntu.dev) [0e514b939d84](https://github.com/LineageOS/android_device_xiaomi_sm8250-common/commit/0e514b939d84)  [Review](https://review.lineageos.org/q/I5619199d6048299796c783b408f05408f518a5e1)
- `device/xiaomi/sm8250-common`: sm8250-common: libinit: Apply clang-format<br>
  2025-10-30T22:16:31Z by [Sebastiano Barezzi](mailto:seba@sebaubuntu.dev) [28789fa86325](https://github.com/LineageOS/android_device_xiaomi_sm8250-common/commit/28789fa86325)  [Review](https://review.lineageos.org/q/Ia66f8cffb06e65d24fc3d357831364d2db47a4ea)
- `device/xiaomi/sm8250-common`: sm8250-common: libinit: Fix headers inclusion order<br>
  2025-10-30T22:16:31Z by [Sebastiano Barezzi](mailto:seba@sebaubuntu.dev) [20322d050a52](https://github.com/LineageOS/android_device_xiaomi_sm8250-common/commit/20322d050a52)  [Review](https://review.lineageos.org/q/Iabae5a63577cf462e171dee5eac796c345962801)
- `device/xiaomi/sm8250-common`: sm8250-common: libinit: Move &#x60;dalvik_heap_info&#x60; outside the header<br>
  2025-10-30T22:16:31Z by [Sebastiano Barezzi](mailto:seba@sebaubuntu.dev) [2611da542055](https://github.com/LineageOS/android_device_xiaomi_sm8250-common/commit/2611da542055)  [Review](https://review.lineageos.org/q/I6dea4a5e669a211c9fbf44d0ca3dc0c530bbdd6f)
- `device/xiaomi/sm8250-common`: sm8250-common: libinit: Use #pragma once<br>
  2025-10-30T22:16:31Z by [Sebastiano Barezzi](mailto:seba@sebaubuntu.dev) [cb13832dc57b](https://github.com/LineageOS/android_device_xiaomi_sm8250-common/commit/cb13832dc57b)  [Review](https://review.lineageos.org/q/I33db772ba211e7c124cd3d381e226e1331269218)
- `device/xiaomi/sm8250-common`: sm8250-common: libinit: &#x60;typedef&#x60; is not needed with C++<br>
  2025-10-30T22:16:31Z by [Sebastiano Barezzi](mailto:seba@sebaubuntu.dev) [8b16c8418675](https://github.com/LineageOS/android_device_xiaomi_sm8250-common/commit/8b16c8418675)  [Review](https://review.lineageos.org/q/Ie412cb5483b065b2d470d0d5dbb4c81c1aec1aa0)
- `device/xiaomi/sm8250-common`: sm8250-common: Set vendor init lib via soong config<br>
  2025-10-30T22:17:09Z by [Bruno Martins](mailto:bgcngm@gmail.com) [a1064afd5bbd](https://github.com/LineageOS/android_device_xiaomi_sm8250-common/commit/a1064afd5bbd)  [Review](https://review.lineageos.org/q/I8f7e6b987bee58dbf09ca9ad7cfd5a7e99e19c3b)
- `device/xiaomi/sm8250-common`: sm8250-common: libinit: Add brackets<br>
  2025-10-30T22:17:09Z by [Sebastiano Barezzi](mailto:seba@sebaubuntu.dev) [1c3aecb6a893](https://github.com/LineageOS/android_device_xiaomi_sm8250-common/commit/1c3aecb6a893)  [Review](https://review.lineageos.org/q/I1d70aeaf0972726d832c144f729067f96b2cb0c6)
- `device/xiaomi/sm8250-common`: sm8250-common: libinit: Fix &#x60;const&#x60; and &#x60;static&#x60; usages<br>
  2025-10-30T22:17:09Z by [Sebastiano Barezzi](mailto:seba@sebaubuntu.dev) [da9315c19682](https://github.com/LineageOS/android_device_xiaomi_sm8250-common/commit/da9315c19682)  [Review](https://review.lineageos.org/q/I39738685bca884a5c9303d877b699d0beab9eacc)
- `device/xiaomi/sm8250-common`: sm8250-common: libinit: Introduce libvariant and related Soong select<br>
  2025-10-30T22:17:09Z by [Sebastiano Barezzi](mailto:seba@sebaubuntu.dev) [04c17fe6d863](https://github.com/LineageOS/android_device_xiaomi_sm8250-common/commit/04c17fe6d863)  [Review](https://review.lineageos.org/q/I1aa99abc47d483cba2a0552e497667212919358c)
- `device/xiaomi/sm8250-common`: sm8250-common: libinit: Move to local header path<br>
  2025-10-30T22:17:09Z by [Sebastiano Barezzi](mailto:seba@sebaubuntu.dev) [2b5c24b54064](https://github.com/LineageOS/android_device_xiaomi_sm8250-common/commit/2b5c24b54064)  [Review](https://review.lineageos.org/q/I66174d5f732f8d04e4a5d10fa2b54563bd5aeeb2)
- `device/xiaomi/sm8250-common`: sm8250-common: libinit: Stop copying objects around functions<br>
  2025-10-30T22:17:09Z by [Sebastiano Barezzi](mailto:seba@sebaubuntu.dev) [f4c506422de8](https://github.com/LineageOS/android_device_xiaomi_sm8250-common/commit/f4c506422de8)  [Review](https://review.lineageos.org/q/Ic226030f4dac212d3ed545e6b3cc41e8a53e29f7)
- `device/xiaomi/sm8250-common`: sm8250-common: libinit: Use early return<br>
  2025-10-30T22:17:09Z by [Sebastiano Barezzi](mailto:seba@sebaubuntu.dev) [54fa815b6a5d](https://github.com/LineageOS/android_device_xiaomi_sm8250-common/commit/54fa815b6a5d)  [Review](https://review.lineageos.org/q/I860c3ec6eb736381021e545e5a73ac232eb0c8cc)
- `state`: Save state of mondrian-2025-10-31-03-10-47-release<br>
  2025-10-31T03:37:01Z by [kxxt](mailto:rsworktech@outlook.com) [3a51e4068a26](https://github.com/android-kxxt/state/commit/3a51e4068a26) 
- `state`: Generate changelog for mondrian-2025-10-31-03-10-47-release<br>
  2025-10-31T03:37:31Z by [kxxt](mailto:rsworktech@outlook.com) [75d6aacd7dac](https://github.com/android-kxxt/state/commit/75d6aacd7dac) 
- `ota`: Update OTA metadata for mondrian (UNOFFICIAL, Release)<br>
  2025-10-31T03:44:00Z by [kxxt](mailto:rsworktech@outlook.com) [32fc9fc5cd85](https://github.com/android-kxxt/ota/commit/32fc9fc5cd85) 
- `state`: Generate changelog for mondrian-2025-10-31-03-10-47-release<br>
  2025-10-31T04:31:07Z by [kxxt](mailto:rsworktech@outlook.com) [17d30b9d10dd](https://github.com/android-kxxt/state/commit/17d30b9d10dd) 
- `state`: fixup<br>
  2025-10-31T04:39:12Z by [Levi Zim](mailto:rsworktech@outlook.com) [1c5953d80c19](https://github.com/android-kxxt/state/commit/1c5953d80c19) 
- `cicd`: changelog-generator: skip non-existent checkouts<br>
  2025-10-31T13:14:23Z by [Levi Zim](mailto:rsworktech@outlook.com) [857ab646166f](https://github.com/android-kxxt/cicd/commit/857ab646166f) 
- `lineage/hudson`: Regenerate device dependency mappings<br>
  2025-10-31T23:30:44Z by [LineageOS Infra](mailto:infra@lineageos.org) [5bdec50a756b](https://github.com/LineageOS/hudson/commit/5bdec50a756b)  [Review](https://review.lineageos.org/q/Ic6588f6c4047001d4cbbbbc50a9780ad35291951)
- `tools/extract-utils`: extract_utils: sort-blobs-list.py: Fix lint warning<br>
  2025-11-01T12:01:18Z by [Sebastiano Barezzi](mailto:seba@sebaubuntu.dev) [4afac1ddc075](https://github.com/LineageOS/android_tools_extract-utils/commit/4afac1ddc075)  [Review](https://review.lineageos.org/q/Ibb44d7816e8db242c652a96e1377fc0c7190879a)
- `tools/extract-utils`: extract_utils: sort-blobs-list.py: Handle sha1sum argument<br>
  2025-11-01T12:01:18Z by [Sebastiano Barezzi](mailto:seba@sebaubuntu.dev) [ceaf57360989](https://github.com/LineageOS/android_tools_extract-utils/commit/ceaf57360989)  [Review](https://review.lineageos.org/q/I469932c488a035770654af54e6a2b6d6b1f4490d)
- `tools/extract-utils`: extract_utils: sort-blobs-list.py: Use a single regex to get source name<br>
  2025-11-01T12:01:18Z by [Sebastiano Barezzi](mailto:seba@sebaubuntu.dev) [4e62c3413bff](https://github.com/LineageOS/android_tools_extract-utils/commit/4e62c3413bff)  [Review](https://review.lineageos.org/q/I9bc378874490630f907d47dd4f5e10e5b51d0d1c)
- `lineage-sdk`: Automatic translation import<br>
  2025-11-01T19:48:36Z by [LineageOS Infra](mailto:infra@lineageos.org) [d518e8d4a390](https://github.com/LineageOS/android_lineage-sdk/commit/d518e8d4a390)  [Review](https://review.lineageos.org/q/I45fc4be884f33e834b44b808183c0f1e6e1a27b4)
- `packages/apps/Aperture`: Automatic translation import<br>
  2025-11-01T19:48:36Z by [LineageOS Infra](mailto:infra@lineageos.org) [998f355aed97](https://github.com/LineageOS/android_packages_apps_Aperture/commit/998f355aed97)  [Review](https://review.lineageos.org/q/I009fa8787930b2ffa2934486f36554837c7ee0ac)
- `packages/apps/Glimpse`: Automatic translation import<br>
  2025-11-01T19:48:38Z by [LineageOS Infra](mailto:infra@lineageos.org) [6a365d196ea0](https://github.com/LineageOS/android_packages_apps_Glimpse/commit/6a365d196ea0)  [Review](https://review.lineageos.org/q/Ie912eda60a7557b41198f2a92c24c52c5068ab50)
- `packages/apps/Twelve`: Automatic translation import<br>
  2025-11-01T19:48:39Z by [LineageOS Infra](mailto:infra@lineageos.org) [516d1f420110](https://github.com/LineageOS/android_packages_apps_Twelve/commit/516d1f420110)  [Review](https://review.lineageos.org/q/I368e8493fc25f1ed273a3b5b159e7e61b1427881)
- `packages/inputmethods/LatinIME`: Automatic translation import<br>
  2025-11-01T19:48:40Z by [LineageOS Infra](mailto:infra@lineageos.org) [5253c60f1078](https://github.com/LineageOS/android_packages_inputmethods_LatinIME/commit/5253c60f1078)  [Review](https://review.lineageos.org/q/I1836b7b8b32c1ecfbb10ab71c9d68b704ba0f8fe)
- `packages/resources/devicesettings`: Automatic translation import<br>
  2025-11-01T19:48:41Z by [LineageOS Infra](mailto:infra@lineageos.org) [28a3378d2e7f](https://github.com/LineageOS/android_packages_resources_devicesettings/commit/28a3378d2e7f)  [Review](https://review.lineageos.org/q/I4e092547c30d44a058407c0939c07437d6e83f38)
- `vendor/crowdin`: Automatic translation import<br>
  2025-11-01T19:48:48Z by [LineageOS Infra](mailto:infra@lineageos.org) [208c135c86f7](https://github.com/LineageOS/android_vendor_crowdin/commit/208c135c86f7)  [Review](https://review.lineageos.org/q/I57979661924c67fbfa1bdcd5f8384f22b32761c5)
- `lineage/wiki`: wiki: Fix bluejay&#x27;s screen refresh rate<br>
  2025-11-01T21:39:42Z by [LuK1337](mailto:priv.luk@gmail.com) [cee05e65bcf0](https://github.com/LineageOS/lineage_wiki/commit/cee05e65bcf0)  [Review](https://review.lineageos.org/q/I2e1c72f501a5772f5b15814034702bee0e6d0c4f)
- `lineage/hudson`: dodge joins the 23.0 race<br>
  2025-11-02T10:20:14Z by [chandu078](mailto:chandudyavanapelli03@gmail.com) [a902755918b9](https://github.com/LineageOS/hudson/commit/a902755918b9)  [Review](https://review.lineageos.org/q/I9ddd5fba7999cef438d5c92e6e415c72055d30e7)
- `lineage/wiki`: wiki: Add OnePlus 13<br>
  2025-11-02T10:22:33Z by [chandu078](mailto:chandudyavanapelli03@gmail.com) [e2e2162d55db](https://github.com/LineageOS/lineage_wiki/commit/e2e2162d55db)  [Review](https://review.lineageos.org/q/Ib8a259a2925eb1e9d7ececb7bab19a2f46938ebd)
- `lineage/wiki`: salami/waffle/dodge: Add eSIM quirk<br>
  2025-11-02T11:00:07Z by [Bruno Martins](mailto:bgcngm@gmail.com) [054183537e9f](https://github.com/LineageOS/lineage_wiki/commit/054183537e9f)  [Review](https://review.lineageos.org/q/I5747ad98c6e18d5bab224687d2c542497c167f14)
- `lineage/wiki`: wiki: Fix indentation in install guide<br>
  2025-11-02T12:12:53Z by [Inhishonor](mailto:inhishonor@protonmail.com) [ff9f210c9d65](https://github.com/LineageOS/lineage_wiki/commit/ff9f210c9d65)  [Review](https://review.lineageos.org/q/I3ad8cb2f1dd3c414d5acb29561b478cbae83bcb3)
- `lineage/wiki`: wiki: Add a note about signature verification<br>
  2025-11-02T12:26:45Z by [Inhishonor](mailto:inhishonor@protonmail.com) [36cd9b4a012d](https://github.com/LineageOS/lineage_wiki/commit/36cd9b4a012d)  [Review](https://review.lineageos.org/q/I9b5b4496ebffaf16887e837bf17968f3c2b8768e)
- `lineage/hudson`: bump gauguin to 23.0<br>
  2025-11-02T13:05:33Z by [Hridaya Prajapati](mailto:info.hridayaprajapati@gmail.com) [89aa3883ee7b](https://github.com/LineageOS/hudson/commit/89aa3883ee7b)  [Review](https://review.lineageos.org/q/I5ea529aeebb74fbece0d8e46fb181b71e3fbb5f8)
- `lineage/wiki`: wiki: Promote gauguin to 23.0<br>
  2025-11-02T13:06:04Z by [Hridaya Prajapati](mailto:info.hridayaprajapati@gmail.com) [01428583a855](https://github.com/LineageOS/lineage_wiki/commit/01428583a855)  [Review](https://review.lineageos.org/q/I9b7dd84359b0c344f1087a6fa737d80138c54f7c)
- `device/qcom/sepolicy_vndr/legacy-um`: legacy: hal_soter -&gt; vendor_hal_soter<br>
  2025-11-02T13:29:44Z by [LuK1337](mailto:priv.luk@gmail.com) [98784484c6df](https://github.com/LineageOS/android_device_qcom_sepolicy_vndr/commit/98784484c6df)  [Review](https://review.lineageos.org/q/I610abc2de664d48c32e320384b57397cae93b1b6)
- `device/qcom/sepolicy-legacy-um`: sepolicy: Move hal_soter attribute to public<br>
  2025-11-02T13:30:17Z by [LuK1337](mailto:priv.luk@gmail.com) [c5a86cf7e400](https://github.com/LineageOS/android_device_qcom_sepolicy/commit/c5a86cf7e400)  [Review](https://review.lineageos.org/q/I035d643aac4f7aa67400864131342b53282fb804)
- `device/lineage/sepolicy`: qcom: Allow platform_app to use Soter HAL<br>
  2025-11-02T13:36:36Z by [dianlujitao](mailto:dianlujitao@lineageos.org) [8b89a12acc8d](https://github.com/LineageOS/android_device_lineage_sepolicy/commit/8b89a12acc8d)  [Review](https://review.lineageos.org/q/Id5c9e3c7ee6a6fe445f42bdcd3db7c376528e8c7)
- `device/lineage/sepolicy`: qcom: hal_soter -&gt; vendor_hal_soter<br>
  2025-11-02T13:36:44Z by [LuK1337](mailto:priv.luk@gmail.com) [c0a6ee1e8aff](https://github.com/LineageOS/android_device_lineage_sepolicy/commit/c0a6ee1e8aff)  [Review](https://review.lineageos.org/q/If169e5f05b19e81300059e4f62e867101f648f08)
- `lineage/wiki`: aston: Add eSIM quirk<br>
  2025-11-02T14:12:21Z by [Bruno Martins](mailto:bgcngm@gmail.com) [dff52d193508](https://github.com/LineageOS/lineage_wiki/commit/dff52d193508)  [Review](https://review.lineageos.org/q/I3e0395c6ce0cbf258eba11c9d6ebeeb4c39c44f0)
- `device/qcom/sepolicy-legacy-um`: legacy: hal_soter -&gt; vendor_hal_soter<br>
  2025-11-02T15:12:10Z by [LuK1337](mailto:priv.luk@gmail.com) [57d39afa87cb](https://github.com/LineageOS/android_device_qcom_sepolicy/commit/57d39afa87cb)  [Review](https://review.lineageos.org/q/I610abc2de664d48c32e320384b57397cae93b1b6)
- `device/qcom/sepolicy-legacy-um`: fixup! legacy: hal_soter -&gt; vendor_hal_soter<br>
  2025-11-02T16:32:19Z by [LuK1337](mailto:priv.luk@gmail.com) [e6959abb7e78](https://github.com/LineageOS/android_device_qcom_sepolicy/commit/e6959abb7e78)  [Review](https://review.lineageos.org/q/I65d488c2e10f43740fc5a028d3e25a3f98dcd8ea)
- `vendor/lineage`: envsetup: Add build_kernel function for Pixel OOT kernel build<br>
  2025-11-02T23:19:00Z by [Michael Bestas](mailto:mkbestas@lineageos.org) [751459e70cce](https://github.com/LineageOS/android_vendor_lineage/commit/751459e70cce)  [Review](https://review.lineageos.org/q/Ib2840cb2bf236a6d25906b60256ef521dd6a2c8a)
- `hardware/qcom-caf/common`: fcm: Add entry for version 2 of ASR AIDL interface<br>
  2025-11-03T12:33:59Z by [Ankit Mishra](mailto:quic_ankmis@quicinc.com) [95c5d93690cd](https://github.com/LineageOS/android_hardware_qcom-caf_common/commit/95c5d93690cd)  [Review](https://review.lineageos.org/q/Ie7f74bb09d477cfa25aa0dc5f80fa52b19dd818b)
- `lineage/hudson`: A wild lizard appears<br>
  2025-11-03T14:32:19Z by [Michael Bestas](mailto:mkbestas@lineageos.org) [48a9559151b7](https://github.com/LineageOS/hudson/commit/48a9559151b7)  [Review](https://review.lineageos.org/q/I70c7db2de819631316cede24c2131dced1a7760c)
- `lineage/hudson`: No source?<br>
  2025-11-03T14:32:19Z by [Michael Bestas](mailto:mkbestas@lineageos.org) [7c9f62180748](https://github.com/LineageOS/hudson/commit/7c9f62180748)  [Review](https://review.lineageos.org/q/Ica79c9fecb305e014b6ded341e50124a2dd59f85)
- `lineage/hudson`: Use tegu for exp 23<br>
  2025-11-03T14:32:40Z by [LuK1337](mailto:priv.luk@gmail.com) [583128d37dd1](https://github.com/LineageOS/hudson/commit/583128d37dd1)  [Review](https://review.lineageos.org/q/Ibda1b93d50ec4c50755145156c58bfa544fd824d)
- `lineage/wiki`: wiki: Add Pixel 9a<br>
  2025-11-03T14:33:24Z by [Michael Bestas](mailto:mkbestas@lineageos.org) [299347f90e46](https://github.com/LineageOS/lineage_wiki/commit/299347f90e46)  [Review](https://review.lineageos.org/q/I0aa45fb520f11be4ba15627636489688786c5c0a)
- `lineage/wiki`: wiki: Link to kernel source manifest for tensor Pixels<br>
  2025-11-03T14:33:24Z by [Michael Bestas](mailto:mkbestas@lineageos.org) [2ec5ede346ee](https://github.com/LineageOS/lineage_wiki/commit/2ec5ede346ee)  [Review](https://review.lineageos.org/q/Ifc8c673638820224e140d90d1a86a53f4871130a)
- `lineage/wiki`: wiki: Promote tensor Pixels to 23.0<br>
  2025-11-03T14:33:24Z by [Michael Bestas](mailto:mkbestas@lineageos.org) [538c85e0c0c0](https://github.com/LineageOS/lineage_wiki/commit/538c85e0c0c0)  [Review](https://review.lineageos.org/q/I4e7aafab99ad01964287224fcf1a851c56e077f0)
- `lineage/hudson`: hudson: Promote Galaxy A71 to 23.0<br>
  2025-11-03T15:04:01Z by [Haky86](mailto:hakamelassouad@gmail.com) [8cf57ebf1bbb](https://github.com/LineageOS/hudson/commit/8cf57ebf1bbb)  [Review](https://review.lineageos.org/q/Ie65187f4a5edbe0884082f6bf8b0ce0f24bb8342)
- `lineage/wiki`: wiki: Promote Galaxy A71 to 23.0<br>
  2025-11-03T15:13:57Z by [Haky86](mailto:hakamelassouad@gmail.com) [cf4c291ef1a8](https://github.com/LineageOS/lineage_wiki/commit/cf4c291ef1a8)  [Review](https://review.lineageos.org/q/Id8790c74fe7965cb78c5463d0a27353a9a652a0d)
- `vendor/lineage`: kernel: Satisfy Rust bindgen for v6.12<br>
  2025-11-03T16:21:01Z by [Sebastiano Barezzi](mailto:seba@sebaubuntu.dev) [2426bf9c8800](https://github.com/LineageOS/android_vendor_lineage/commit/2426bf9c8800)  [Review](https://review.lineageos.org/q/I793e2426f5b697c3c33c6d43729721ac1109abcd)
- `vendor/lineage`: apns: Add APN for Netgsm<br>
  2025-11-03T23:25:24Z by [Doğancan yılmazer](mailto:dogancanyilmazer46@gmail.com) [45094fbaa3ee](https://github.com/LineageOS/android_vendor_lineage/commit/45094fbaa3ee)  [Review](https://review.lineageos.org/q/If7080da334da33c76f741195add206d817f6224a)
- `lineage/wiki`: wiki: Add faq&#x27;s for gapps questions<br>
  2025-11-03T23:25:56Z by [Inhishonor](mailto:inhishonor@protonmail.com) [eea58c659263](https://github.com/LineageOS/lineage_wiki/commit/eea58c659263)  [Review](https://review.lineageos.org/q/Ib1459f3f8b311e9bb4b655ed7195711469531c0b)
- `lineage/wiki`: wiki: Add a faq about fixing frp<br>
  2025-11-03T23:27:19Z by [Inhishonor](mailto:inhishonor@protonmail.com) [bc27c3aacb0f](https://github.com/LineageOS/lineage_wiki/commit/bc27c3aacb0f)  [Review](https://review.lineageos.org/q/Ica9103ade9d303f2f67e13f4000b7bde951d5c39)
- `packages/apps/LineageParts`: Regenerate contributors cloud (2025-11-02)<br>
  2025-11-04T02:49:58Z by [Kevin F. Haggerty](mailto:haggertk@lineageos.org) [ce809c39a139](https://github.com/LineageOS/android_packages_apps_LineageParts/commit/ce809c39a139)  [Review](https://review.lineageos.org/q/Ic49670493cff66484f1fed0453d913c2f307d25a)
- `lineage/wiki`: fixup! wiki: Add a faq about fixing frp<br>
  2025-11-04T03:29:43Z by [Tuan Anh](mailto:tuan73176@gmail.com) [9c17c895431a](https://github.com/LineageOS/lineage_wiki/commit/9c17c895431a)  [Review](https://review.lineageos.org/q/I8a09bf803a0956b7dcb0396d8613763774c1d37a)
- `hardware/qcom-caf/thermal-legacy-um`: thermal-hal: Update skin temperature threshold for msmnile<br>
  2025-11-04T06:23:56Z by [Nick Reuter](mailto:nreuter85@gmail.com) [542969876f48](https://github.com/LineageOS/android_hardware_qcom_thermal/commit/542969876f48)  [Review](https://review.lineageos.org/q/Id69e1f4ce6e5ad3cc895638d898f36965cd8180a)
- `lineage/wiki`: wiki: Fix wipe-frp/reboot commands<br>
  2025-11-04T09:02:28Z by [LuK1337](mailto:priv.luk@gmail.com) [718fb6c84dca](https://github.com/LineageOS/lineage_wiki/commit/718fb6c84dca)  [Review](https://review.lineageos.org/q/Id9595932892d0a1fb59da36a722cd60f0d7fe2e8)
- `vendor/lineage`: wipe-frp: Allow overriding FRP_BLOCK<br>
  2025-11-04T11:24:20Z by [LuK1337](mailto:priv.luk@gmail.com) [d18624129c27](https://github.com/LineageOS/android_vendor_lineage/commit/d18624129c27)  [Review](https://review.lineageos.org/q/I2fed7f088541667fc53d75d841a8af1903edff3d)
- `lineage/scripts`: scripts: Add collect-kernel-module-deps.py<br>
  2025-11-04T22:02:54Z by [Yumi Yukimura](mailto:me.cafebabe@gmail.com) [953b0b19508f](https://github.com/LineageOS/scripts/commit/953b0b19508f)  [Review](https://review.lineageos.org/q/I172e6070d997d868a650d76170b4127b23f9716d)
- `lineage/wiki`: wiki: Sync upgrade with download instructions<br>
  2025-11-05T20:56:16Z by [LuK1337](mailto:priv.luk@gmail.com) [e56f46d582ea](https://github.com/LineageOS/lineage_wiki/commit/e56f46d582ea)  [Review](https://review.lineageos.org/q/I388c2a70e0096235503bca77c5ecaabdcc4de6ae)
- `lineage/wiki`: wiki: Update maintainer list for dre<br>
  2025-11-05T23:55:00Z by [Nick Reuter](mailto:nreuter85@gmail.com) [fb603bedc0d0](https://github.com/LineageOS/lineage_wiki/commit/fb603bedc0d0)  [Review](https://review.lineageos.org/q/I894880e9915c7cc8fe237bf7debd304425f357be)
- `lineage/wiki`: wiki: Update maintainer list for guacamole<br>
  2025-11-06T00:19:04Z by [Nick Reuter](mailto:nreuter85@gmail.com) [13276f2b4c93](https://github.com/LineageOS/lineage_wiki/commit/13276f2b4c93)  [Review](https://review.lineageos.org/q/I5c23516368aa3df341795d30e990d215c80c3de5)
- `packages/apps/Launcher3`: Launcher3: Add resource to enable rotation by default<br>
  2025-11-06T06:05:27Z by [AnierinB](mailto:anierin@evolution-x.org) [47681de972c1](https://github.com/LineageOS/android_packages_apps_Launcher3/commit/47681de972c1)  [Review](https://review.lineageos.org/q/If9642292c58978cd6071f39ceaf3066234eb2d1e)
- `lineage/wiki`: salami/dodge: Remove eSIM quirk<br>
  2025-11-06T15:09:27Z by [Bruno Martins](mailto:bgcngm@gmail.com) [49347c5d91fd](https://github.com/LineageOS/lineage_wiki/commit/49347c5d91fd)  [Review](https://review.lineageos.org/q/I374f3ea3f891a93726e27fb05a26545dc8a83b60)
- `vendor/lineage`: overlay: Don&#x27;t allow toggling camera<br>
  2025-11-06T15:54:54Z by [Hridaya Prajapati](mailto:info.hridayaprajapati@gmail.com) [4339301f251b](https://github.com/LineageOS/android_vendor_lineage/commit/4339301f251b)  [Review](https://review.lineageos.org/q/Iece2b092d0fdcbb94c41c7727de799a0b7baa700)
- `external/vim`: Merge tag &#x27;v9.1.1896&#x27; of https://github.com/vim/vim into lineage-23.0  <details>
    <summary>Merge Details</summary>

      v9.1.1896
      
      * tag 'v9.1.1896' of https://github.com/vim/vim:
        patch 9.1.1896: tests: patch v9.1.1895 breaks CI
        runtime(doc): clarify W11 warning and possible options
        patch 9.1.1895: OSC terminal response hard to detect
        patch 9.1.1894: global_runtime_dir appends /after directory when using XDG
        patch 9.1.1893: ICCF charity will dissolve
        patch 9.1.1892: Not possible to know once Vim is done with sourcing vimrc
        runtime(netrw): NetrwChgPerm for files not in cwd
        runtime(log): syntax file update
        runtime(doc): Fix a few typos
        patch 9.1.1891: g<End> does not move to last non-blank in visual mode
        translation: regenerate po/vim.pot after 73a0de4a04b48cca
        patch 9.1.1890: %P in 'statusline' doesn't behave as documented
        patch 9.1.1889: filetype: not all AppleScript files are recognized
        Drop superfluous execute permissions for readable files
        runtime: regenerate helptags, update last-change header in tombi compiler
        patch 9.1.1888: Wrong display with cpo+=$, matchparen and wrapped line
        runtime(compiler): Fix escaping in Windows shell command for tombi
        patch 9.1.1887: string handling in strings.c can be improved
        runtime(compiler): Fix invalid expression in tombi compiler after d659fafcc
        runtime(compiler): add tombi compiler to lint TOML files
        runtime(vim): Update base syntax, match Vim9 lambda arg to :defer
        patch 9.1.1886: filetype: Android aconfig files are not recognized
        patch 9.1.1885: Wrong restored cursor pos when re-entering buffer after changes
        runtime(doc): Highlight [expr] arg in :help :return description
        patch 9.1.1884: :defer an empty lambda causes a crash
        runtime(doc): revert wrong 'incsearch' description
        patch 9.1.1883: Wrong display with 'smoothscroll' with -diff


    </details>

  2025-11-06T16:56:36Z by [Thomas Turner](mailto:thomas_turner@talktalk.net) [129616c3a262](https://github.com/LineageOS/android_external_vim/commit/129616c3a262)  [Review](https://review.lineageos.org/q/I8e61171472745bf03c966f209e2fbe7c77a8e5d0)
- `lineage/crowdin`: config: Add OplusEsimSwitcher<br>
  2025-11-06T21:01:53Z by [Bruno Martins](mailto:bgcngm@gmail.com) [70783f1bed1b](https://github.com/LineageOS/cm_crowdin/commit/70783f1bed1b)  [Review](https://review.lineageos.org/q/I97a9f21bb1c9d5ba60a8a5bdd0a0e4035aab0504)
