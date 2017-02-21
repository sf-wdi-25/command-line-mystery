cd mystery
ls mystery

HINT 1 RESULTS
head -n 20 people
***************
To go to the street someone lives on, use the file
for that street name in the 'streets' subdirectory.
To knock on their door and investigate, read the line number
they live on from the file.  If a line looks like gibberish, you're at the wrong house.
***************

NAME	GENDER	AGE	ADDRESS
Alicia Fuentes	F	48	Walton Street, line 433
Jo-Ting Losev	F	46	Hemenway Street, line 390
Elena Edmonds	F	58	Elmwood Avenue, line 123
Naydene Cabral	F	46	Winthrop Street, line 454
Dato Rosengren	M	22	Mystic Street, line 477
Fernanda Serrano	F	37	Redlands Road, line 392
Emiliano Wenk	M	90	Paulding Street, line 490
Larry Lapin	M	71	Atwill Road, line 298
Jakub Gondos	M	61	Mitchell Street, line 187
Derek Kazanin	M	55	Tennis Road, line 440
Jens Tuimalealiifano	M	83	Rockwood Street, line 205
Nikola Kadhi	M	75	Glenville Avenue, line 226


HINT 2 results
grep "CLUE" crimescene
CLUE: Footage from an ATM security camera is blurry but shows that the perpetrator is a tall male, at least 6'.
CLUE: Found a wallet believed to belong to the killer: no ID, just loose change, and membership cards for AAA, Delta SkyMiles, the local library, and the Museum of Bash History. The cards are totally untraceable and have no name, for some reason.
CLUE: Questioned the barista at the local coffee shop. He said a woman left right before they heard the shots. The name on her latte was Annabel, she had blond spiky hair and a New Zealand accent.

HINT 4 results
grep "Annabel" people
Annabel Sun	F	26	Hart Place, line 40
Oluwasegun Annabel	M	37	Mattapan Street, line 173
Annabel Church	F	38	Buckingham Place, line 179
Annabel Fuglsang	M	40	Haley Street, line 176

hint 5 results
SEE INTERVIEW #9437737
Doesn't appear to be the witness from the cafe, who is female

SEE INTERVIEW #47246024
Ms. Sun has brown hair and is not from New Zealand.  Not the witness from the cafe.

SEE INTERVIEW #699607
Interviewed Ms. Church at 2:04 pm.  Witness stated that she did not see anyone she could identify as the shooter, that she ran away as soon as the shots were fired.

However, she reports seeing the car that fled the scene.  Describes it as a blue Honda, with a license plate that starts with "L337" and ends with "9"

SEE INTERVIEW #871877
Mr. Fuglsang is male and has brown hair.  Not the witness from the cafe


suspects
License Plate L337WR9
Make: Honda
Color: Blue
Owner: Jacqui Maher
Height: 6'2"
Weight: 130 lbs

License Plate L3375A9
Make: Honda
Color: Blue
Owner: Jeremy Bowers
Height: 6'1"
Weight: 204 lbs

License Plate L337DV9
Make: Honda
Color: Blue
Owner: Joe Germuska
Height: 6'2"
Weight: 164 lbs

cat AAA Delta_SkyMiles Museum_of_Bash_History Terminal_City_Library | grep "Jeremy Bowers" | wc -l
4

whodunit: Jeremy Bowers
