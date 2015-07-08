Given two dates, `dateseq` prints out all the dates between those dates (including the start date, but excluding the end date).

Install
===

**Requirements**

- Python

---

**Installation**

Assumes you have `~/bin` set up as a directory on your PATH.

    wget -O $HOME/bin/dateseq https://github.com/wcauchois/dateseq/raw/master/dateseq
    chmod +x $HOME/bin/dateseq

Use
===

    $ dateseq 2015-01-01 2015-01-05
    2015-01-01
    2015-01-02
    2015-01-03
    2015-01-04

---

    $ for d in $(dateseq 2015-06-12 2015-06-15); do echo "something with $d"; done
    something with 2015-06-12
    something with 2015-06-13
    something with 2015-06-14



