10-21-2014-HW
=============
1a)
>>> s1="spam"
>>> s2="ni!"
>>> "The Knights who say, " + s2
'The Knights who say, ni!'

1b) 
>>> 3*s1+2*s2
'spamspamspamni!ni!'

1c)
>>> s1[1]
'p'

1d)
>>> s1[1:3]
'pa'

1e)
>>> s1[2]+s2[:2]
'ani'

1f)
>>> s1+s2[-1]
'spam!'

1g)
>>> s1.upper()
'SPAM'

1h)
>>> s2.upper().ljust(4)*3
'NI! NI! NI! '

2a)
s2.upper()

2b)
s2+s1+s2

2c)
(s1.ljust(5)+s2.ljust(5))*3

2d)
s1

2e)
s1[:2],s1[-1]

2f)
s1[:2]+s1[-1]
