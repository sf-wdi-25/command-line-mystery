// Search crimescene 
 $ grep "CLUE" crimescene 

// Researched Annabel
 $ grep "Annabel" people

// Researched Ms. Sun
 $ grep -r "Annabel Sun" *

// Researched Ms. Church
 $ grep -r "Annabel Church" *

// Visited Ms. Church
 $ less +179 streets/Buckingham_Place 

// Interviewed Ms. Church
 $ less interviews/interview-699607 
// Car: blue Honda, license plate "L337..9"

// cross refferenced blue honda w/ license plate.
 $ less vehicles
 /L337..9
// L337DV9, Blue Honda, Joe Germuska, 6'2", 164 lbs? Possibly
// L3375A9, Blue Honda, Jeremy Bowers, 6'1", 204 lbs? Possibly
// L337WR9, Blue Honda, Jacqui Maher, 6'2", 130 lbs? Possibly

// Research possible suspects.
$ grep -r "Joe Germuska" *
// memberships/Terminal_City_Library:Joe Germuska
// memberships/AAA:Joe Germuska
// people:Joe Germuska	M	65	Plainfield Street, line 275
// vehicles:Owner: Joe Germuska

$ grep -r "Jeremy Bowers" *
//memberships/Museum_of_Bash_History:Jeremy Bowers
//memberships/Terminal_City_Library:Jeremy Bowers
//memberships/AAA:Jeremy Bowers
//memberships/Delta_SkyMiles:Jeremy Bowers
//people:Jeremy Bowers	M	34	Dunstable Road, line 284
//vehicles:Owner: Jeremy Bowers

$ grep -r "Jacqui Maher" *
//memberships/Museum_of_Bash_History:Jacqui Maher
//memberships/Terminal_City_Library:Jacqui Maher
//memberships/AAA:Jacqui Maher
//memberships/Delta_SkyMiles:Jacqui Maher
//people:Jacqui Maher	F	40	Andover Road, line 224
//vehicles:Owner: Jacqui Maher

// 2 suspects: Jacqui Maher and Jeremy Bowers
$ less +284 streets/Dunstable_Road 
// SEE INTERVIEW #9620713

$ less interviews/interview-9620713
// Not home, fled? guilty?

$ less +224 streets/Andover_Road
// SEE INTERVIEW #904020

$ less interviews/interview-904020
// Suspect eliminated

// Don't believe he's our guy but better safe than sorry.
$ less +275 streets/Plainfield_Street
// SEE INTERVIEW #29741223

$ less interviews/interview-29741223
// suspect eliminated

|| CULPRIT: Jeremy Bowers ||