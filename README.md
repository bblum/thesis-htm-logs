# thesis-htm-logs

This is a collection of the state space estimation logs from the experiments in
chapter 6 of my thesis.

I have not really gone out of my way to make this repository super user-
friendly, because I don't really expect anybody to ever actually use it, but if
you're here to prove me wrong, I am really flattered and honored. This brief
readme is for you, then, and should you find it insufficient, feel free to get
in touch with questions.

The ls-id-options files capture the command-line arguments that I issued when I
ran each test. These include the test name (-p) and the reduction and/or
transactional semantics options (-X, -A, -S, -M), but (regrettably) not the K,N
parameters. (Those I configured by hand as #defines in the test programs
themselves.) You can match these ls-id-options files up to the corresponding
quicksand log by taking the timestamp (the number starting with 2018), and
finding the ls-id-log file that matches it. You can then disambiguate which log
corresponds to which K,N configuration of each test by comparing the number of
interleavings explored (printed at the end, of course) with the numbers in
Tables 6.1, 6.2, and 6.4. I have made an effort to remove extraneous logs that
do not correspond to the results in those tables, but I may have let a few slip
by; my apologies if so.

If you end up drawing any useful conclusions with these logs, I should be
interested to hear about them.

There are no easter eggs in this repository.
