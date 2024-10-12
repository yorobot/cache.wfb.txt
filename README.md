# cache worldfootball (wfb) datsets in Football.TXT




## tips & tricks


### step 1 - tokens/tokenizer

to double check on syntax and more try:

    $ fbtok . -q        #  use -q/--quiet

resulting in:

    OK   no parse errors found in 281 datafile(s)

### step 2 - parse tree/parser

    $ fbt .

resulting in:

    OK - no parse errors in 281 datafile(s)


### step 3 - name (error) checks and more

only check leagues (turn off name check for teams)

    $ fbchk . --no-teams

the full monty

    $ fbchk .


and so on.



