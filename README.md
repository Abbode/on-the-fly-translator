# on-the-fly-translator

this is a translator script designed to work on any GNU/Linux
computer using bash shell and some other tools.

to translate a word or sentence one have to open translator program
and write the word one want to translate (with exception of KDE global search
and a GNOME-shell-extension that doesn't work since GNOME 40).

this script solves that, and one can translate any word from any where
without having to leave his workflow/document using mouse selection
and a shortcut to run the script.

to have this script work one will need:
1) translate-shell
2) xsel
3) a simple text editor(to view the trnslation)
4) an internet connection


editing script before usage:
1) make the translation fit your needs (ex: translation from language x to language y,
    any option you want to apply to the translation , etc...). for more informations
    type <code>man trans</code> in your terminal, for languages list type <code>trans -T</code> (default: from English to Arabic)
2) use the text editor that is installed on your machine, default is xed (ex: gedit, kate, kwrite, etc...)
3) if you want the output file to go to some other directory than the default edit it's path(optional).
4) make the text editor read the new output file in changed(optional).

How to use:
1) you put the script in a directory inside your home direcry if you want to use it
    alone or in /usr/bin if you want other users to use it as well.
2) you make it excutable for yourself or others if it's for all users to use.
3) you assign a keyboard short cut to run it.
4) voila , you can select any text and run the command and it will translate it.

