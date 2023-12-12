# PassWord-Generator
###Features:

#####Password generation:

It allows you to specify the character set:
by enabling/disabling character classes:
    @uppercase ASCII letters A-Z
    @lowercase ASCII letters a-z
    @digits 0-9
    @punctuation !"#$%&'()*+,-./:;<=>?@[\]^_`{|}~
    @space  
    @by adding custom characters
    @by blacklisting custom characters
It allows you to specify any desired length of the password.
It allows you to limit the maximum allowed number of occurrences of the same character, but still takes care that the password length can be reached.

Output:
      $ ./pwgen.py 10 -uld -a'-_' -n6
      ***** Password Generator - © 2016 ByteCommander *****
      
      Using this character set (excluding the arrows):
      →-0123456789ABCDEFGHIJKLMNOPQRSTUVWXYZ_abcdefghijklmnopqrstuvwxyz←
      There are no duplicate character limits.
      
      Generating 6 passwords of length 10:
      
      n0j1MWlig5
      KcrVnGIt34
      jTmDSRz9Pj
      MNYKEwcHcf
      Dqp_uRTEya
      5Zw1uA9NtB
