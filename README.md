# Project-CP-class
Password requirements verification (with realistic requirements)

This code program is designed to :
1. Ask the user to enter a password of his/her choice,
2. To verify if the password correspond to the standard requirements.

Password requirements : 
- at least 1 alpha char (controlled by the boolean pAlphaMet)
- at least 1 special char (pSpecialMet)
- at least 8 chars long (pLengthMet)
- no spaces (pSpaceMet)
- and can't start with "!" or "?" (pStartsQuestExcMet : for question and exclamation marks)

I use also the boolean pEquals (to check if password1 == password2) and pCharOccMet (to check that no character is repeaded more than two times)

I added some comments in the code to make some things a bit clearer
