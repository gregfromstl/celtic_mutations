# celtic_mutations
This challenge involves predicting a grammatical phenomenon that occurs in the Celtic languages (Links to an external site.) known as initial mutations. These are changes to the spelling and pronunciation of words depending on the grammatical or semantic context. For example, in Irish, the word for “woman” is “bean”, but  “the woman” is “an bhean”, where the preceding definite article causes the letter h to be inserted as the second letter.  We will work with Irish language (Links to an external site.) data in this challenge, where there are four different mutations which we tag as S, U, H, and T (and we introduce a fifth label N for words that are not mutated like “an” above). The challenge is then to take a text where the mutations have been removed (e.g. bhean → bean) and predict the correct mutation labels:  an bean → an/N bean/S
