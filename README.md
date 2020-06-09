# vi-editor---newbie-to-pro---search-and-replace
vi / vim editor - beginner to advanced - options - search and replace


Search whole file, replace globally (all occurrence/repetitions will be replaced)
:%s/FindMe/ReplaceMe/g

Search current line only, replace globally on that line only.
:s/FindMe/ReplaceMe/g

Search whole file, replace only first match
:%s/FindMe/ReplaceMe/

Search current line only, replace first match only.
:s/FindMe/ReplaceMe/

Search whole file, replace globally, with confirmation(c).
:%s/FindMe/ReplaceMe/gc

Search whole file, replace globally, with confirmation(c), Case Sensitive(I) search.
:%s/FindMe/ReplaceMe/gcI

Search whole file, replace globally, with confirmation(c), Case insensitive(i) search.
:%s/FindMe/ReplaceMe/gci
