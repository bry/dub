dub
==============

dub is du with -h human readable output sorted by size. Compare:

### du:

    > du -h -d 1 
      0B	./Colloquy Transcripts
     14G	./Library
     23G	./Personal
    673M	./Work
     37G	.


### dub:

    > dub -h -d 1
          37.0G .
          23.0G ./Personal
          14.0G ./Library
         673.0M ./Work
           0.0B ./Colloquy Transcripts

## SCRIPT COMPATIBILITY
  - Mac OS X
  - Ruby 1.8.7

## DEPLOY
  0. Ensure /usr/local/bin is in your PATH variable
    
    `> echo $PATH`
  
  1. Copy 'dub' to /usr/local/bin

    `> sudo cp dub /usr/local/bin`

## SYNOPSIS
     du [-H | -L | -P] [-a | -s | -d depth] [-c] [-h | -k | -m | -g] [-x]
        [-I mask] [file ...] -G 

## DESCRIPTION

    -G Enable colorized output.

'man du' for details
