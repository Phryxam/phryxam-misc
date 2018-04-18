# Problem 5:
## Substitute Teacher (25 points)

```
Mr. Michael S. “Mike” Rogers is the substitute teacher
for the day, but he is having trouble deciphering the
secret message that was left for him by the teacher.
Mr. Rogers knows the note is in English, but that’s
about all. Can you help him? ENCRYPTED.txt
```

ENCRYPTED.txt contains the message:
```
Xq ohvckbmhicyv, i jlsjkxklkxbq oxcyrh xj i nrkybg ba rqobgxqm sv tyxoy lqxkj ba
cdixqkruk ihr hrcdiorg txky oxcyrhkruk, ioobhgxqm kb i axurg jvjkrn; kyr
"lqxkj" niv sr drkkrhj (kyr nbjk obnnbq), cixhj ba drkkrhj,
khxcdrkj ba drkkrhj, nxuklhrj ba kyr isbpr, iqg jb abhky. Kyr
hrorxprh groxcyrhj kyr kruk sv crhabhnxqm kyr xqprhjr
jlsjkxklkxbq. (Txfxcrgxi.bhm, "Jlsjkxklkxbq ovcyrh") Kyxj xj, abh vblh jifr, i
obncdrkrdv qbhnid Rqmdxjy kruk. Tr trhr jb qxor, tr groxgrg kb dripr oicxkidxzikxbq
xq kyr rqohvckrg kruk... & clqoklikxbq! Ihrq'k tr qxor. Kyrhr xj i hrdikxprdv
qbhnid drkkrh gxjkhxslkxbq xq kyxj kruk, jb xk jybldgq'k yipr srrq kbb gxaaxoldk
kb jbdpr. Iqvtiv, obqmhikldikxbqj! Yrhr xj vblh adim:
bqdv_jdxmykdv_srkkrh_kyiq_oirjih
```

This is a substitution cipher, as evidenced by the name of the problem, and the large quantity of text. A substitution cipher works by each letter representing something else. By looking at the frequency of the letters that appear in the message, and the letters that most frequently appear in English, we can figure out what letters replace what.

However, because we're allowed to use tools the website http://quipqiup.com/ will automate this process for us.
This will give us a result of:
```
In crypto?raphy, a substitution cipher is a method o? encodin? by which units o?
plainte?t are replaced with cipherte?t, accordin? to a ?i?ed system; the "units" may be
letters (the most common), pairs o? letters, triplets o? letters, mi?tures o? the above,
and so ?orth. The receiver deciphers the te?t by per?ormin? the inverse substitution.
(Wikipedia.or?, "Substitution cypher") This is, ?or your sake, a completely normal
En?lish te?t. We were so nice, we decided to leave capitalization in the encrypted
te?t... & punctuation! Aren't we nice. There is a relatively normal letter distribution
in this te?t, so it shouldn't have been too di??icult to solve. Anyway, con?ratulations!
Here is your ?la?: only_sli?htly_better_than_caesar
```
From this, we should be able to determine that the flag is `only_slightly_better_than_caesar`
