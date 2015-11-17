cat instructions
ls
cd mystery
grep -r CLUE

clue # 1
Footage from an ATM security camera is blurry but shows that the perpetrator is a tall male, at least 6'.

Clue # 2
Found a wallet believed to belong ot the killer: no ID, just some loose change and membership cards for AAA, Delta SkyMiles, the local library, and the Museum of Bash History.  the cards are totally untraceable and have no name, for some reason.

clue #3
Questioned the barista at the local coffee shop.  He said a woman left right before they heard the shots.  the name on her latte was Annabel, she had blond spiky hair and a New Zealand accent.

head -n 50 people
grep "Annabel" people
cd Streets
cd ..
head -n 40 streets/Hart_Place | tail -n 1
cd interviews
cat interview-47246024
	useless
cd ..
head -n 173 streets/Buckingham_Place | tail -n 1
	useful - Blue Honda Plate reads 1337...9
grep "Blue" vehicles
grep "Honda" vehicles
cd ..
grep -A 5 "L337" mystery/vehicles
cd mystery
cd memberships
cat AAA Musem_of_Bash_History Terminal_City_Library Delta_SkyMiles | grep "Joe Germuska"
cat AAA Musem_of_Bash_History Terminal_City_Library Delta_SkyMiles | grep "Jeremy Bowers"
cat AAA Museum_of_Bash_History Terminal_City_Library Delta_SkyMiles | grep "Jeremy Bowers"

Jeremy Bowers is the most likely suspect