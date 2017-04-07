# Vim

the error because use vim like emacs and when i go exit is break
with message:

` ^X mode (^]^D^E^F^I^K^L^N^O^Ps^U^V^Y) `

to resolve:

```  Try typing ^Q.

^S and ^Q are the default "stop" and "start" characters in the tty settings.

(vim should be manipulating the tty settings so control-S doesn't stop output, but I've seen systems where it doesn't. Yes, it's annoying.)
```

by [this link in StackOverflow](http://stackoverflow.com/questions/14737703/vim-unresponsive-after-a-c-x-c-s-sequence)