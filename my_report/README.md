# Lesson: Digital & Serious Games

### First and Last Name: Spyros Chomatas
### University Registration Number: dpsd15127
### GitHub Personal Profile: https://github.com/spyroschom
### Digital & Serious Games Personal Repository: https://github.com/spyroschom/Role-Playing-Game

# Introduction
Μέσω του Unity και με την βοήθεια του tutorial δημιούργησα το συγκεκριμένο 2D παιχνίδι. Τα Assets που χρησημοποιείησα είναι έτοιμα απο το internet.


# Summary
Το παιχνίδι είναι ένα απλο 2D RPG εμπνευσμένο απο διαφορα στοιχεία medeival fantasy. Σκοπεύω να έχει 2 επίπεδα με απλούς εχθρούς και κανα NPC στο καθένα.

# 1st Deliverable
Για προταγωνιστή χρησημοποίησα ένα asset υπότη που βρήκα στο διαδίκτυο.

![Idle](https://user-images.githubusercontent.com/117836464/207453533-feaa4012-2181-49f8-a359-556e8dba36f9.png)

Μέσω του κόδικα έκανα τον χαρακτήρα να κουνιέτε πανω, κάτω, δεξιά και αριστερά με την χρήση των πλήκτρων WASD. Όρισα την ταχύτητα που θα κινίτε ο χαρακτήρας και του πέρα το script.



Επίσης βρήκα και tiles τα οποία να είναι κοντα στην θεμάτική του παιχνιδιού. Ακολύθησα το tutorial και εφτιαξα palletes ώστε να μπορέσω να φτιάξω την πίστα.



![TX Tileset Grass](https://user-images.githubusercontent.com/117836464/207453964-69c2e64d-1074-43d6-a457-7bb5aa9a3a99.png)
![TX Tileset Stone Ground](https://user-images.githubusercontent.com/117836464/207453966-afd6795f-40b1-47d6-b393-62f06a46a741.png)
![TX Tileset Wall](https://user-images.githubusercontent.com/117836464/207453969-67cc131b-187d-408d-a2b1-188b53eb6a89.png)
![TX Plant](https://user-images.githubusercontent.com/117836464/207453972-ad0dd905-3904-4a45-8e39-4e9de9e156ac.png)
![TX Props](https://user-images.githubusercontent.com/117836464/207453978-07e5b0c5-9902-4437-925d-b1bc125aaf6f.png)
![TX Struct](https://user-images.githubusercontent.com/117836464/207453979-513f2f61-d4c8-4c57-9c6b-4c0b2f280866.png)


Έτσι χρησημοποιόντας όλα αυτα τα assets έφτιαξα ενα αρχικό κομάτι της 1ης πίστας. 
Θα υπάρξουν αλλαγές στα επόμενα παραδοτέα. Το πλάνο είναι να μεγαλώσω την πίστα και να την διακοσμήσω καλύτερα.

![πιστα 1](https://user-images.githubusercontent.com/117836464/207580607-a3ca1ece-7fc9-4a80-81b2-eaf529e5a327.png)


# 2nd Deliverable!

Ξεκίνησα με το να κάνω ένα rigid body 2d στον προταγονιστή και αφού εφτιαξα τα physics έπειτα άρχησα να δημιουργώ colliders στα αντικείμενα του περιβάλοντος.
Τέλος, εφτιαξα τα colliders στο μέγεθος που με βόλευε και έκανα μερικές ρυθμίσεις στο χαρακτήρα για να μην κάνει jittering και rotate όταν πέφτει πάνω σε κάπιο αντικείμενο.

![colliders](https://user-images.githubusercontent.com/117836464/207569044-e8245025-f25c-4229-9544-456cd471aebb.png)


Στην συνέχεια ακολουθόντας το tutorial εφτιαξα ενα αρχικό health και max health για τον χαρακτήρα. Μετά βρήκα ένα asset pack με διάφορα potions assets και έβαλα ένα στην πίστα. Έκανα τον box collider του potion σε is  trigger και εφτιαξα το ανάλογο script ώστε ο χαρακτήρας αμα πηγαίνει πάνω στο potion με χαμηλή ζωή να παίρνει +1 health και το potion να εξαφανίζετε.


![small Potions](https://user-images.githubusercontent.com/117836464/207570576-7e76704c-f19f-4346-b01d-0013630880bf.png)




![ποτιον](https://user-images.githubusercontent.com/117836464/207570511-424a8624-6f2c-4791-90c0-8ffe41f8f68d.png)


Στο επόμενο βήμα έβαλα στην πίστα εχθρούς να κουνιούνται δεξιά-αριστερά και να κάνουν ζημιά στον χαρακτήρα όταν συγκρούονται. Χρησημοποίησα ενα απλό asset σκελετού.



![Idle](https://user-images.githubusercontent.com/117836464/207572290-38461634-c136-41bc-abd3-7935c192ac50.png)


Έπειτα έπρεπε να δημιούργήσω animations και δυστηχώς το αρχικό asset του ιππότη που χρησημοποίησα δεν είχε. Οπότε άλλαξα χαρακτήρα σε στυλ pixel.



![Idle](https://user-images.githubusercontent.com/117836464/207573117-f036dfd6-6627-42a7-9c65-6e12de2ebeb9.png)


Έτσι ακολουθόντας το tutorial άρχησα να δουλέυω στα animations. Δυστηχώς,το συγκεκριμένο asset pack δεν είχε animation για όταν ο χαρακτήρας κουνιέτε προς τα πάνω και προς τα κάτω, είχε μόνο για δεξια και αριστερά. Έφτιαξα τα animations βάζοντας τα frames από το asset pack και με την βοήθεια του tutorial έκανα τις απαρέτητες ρυθμίσεις. Έπειτα έφτιαξα το blend tree και ανάλογα απο πια κατευθηνση κινείται ο χαρακτήρας θα παίζει και το ανάλογο animation (άμα πηγαίνει προς δεξιά να φαίνετε προς τρέχει προς τα δεξιά και όχι προς τα αριστερά).

![ανιματορ](https://user-images.githubusercontent.com/117836464/207575891-2201e17f-5507-4491-a5b7-280484e4a423.png)


Αφού έφτιαξα και τα animations για τους σκελετούς, είμουν έτοιμος να προχορήσω.


Για το projectile αποφάσησα να χρησημοποιήσω ένα σπαθί καθώς ταιρίαζει πιο πολύ με τον χαρακτήρα.



![evo_bundle8](https://user-images.githubusercontent.com/117836464/207577140-a9eccd32-a936-47ce-bee9-b38cf4edcbcb.png)


Ακολουθόντας το tutorial έφτιαξα το projectile prefab, έκανα της απαράιτητες ρυθμίσεις στο rigid body και έγραψα το κατάλληλο script ώστε το σπαθι να εμφανίζετε εκεί που βρίσκετε ο χαρακτήρας και να εκτοξέβεται προς την κατεύθηνση που κοιτάει όταν ο χρήστη πατάει το αριστερό κλικ στο ποντίκι του. Τέλος, όλα αυτά τα ακολούθεί και ένα attack animation. Το σπαθί εξαφανίζετε καθε φορά που πέφτει πάνω σε κάπιο αντικείμενο ή εχθρο. Το πλάνο είναι όταν πέφτει πάνω σε έχθρο τότε να εξαφανίζετε και ο εχθρός.


Έπειτα, δημιούργησα την CM vcam μέσω του Cinemachine, έκανα τις απαρέτητες ρυθμίσεις ώστε να ακολουθεί τον χαρακτήρα και τα ανάλογα camera bounds ώστε να σταματάει στο τέλος του map. Τέλος, μεγάλωσα την αρχική πίστα, έβαλα και άλλα props και εχθρούς και την διακόσμησα καλύτερα.



![πιστα 1_final](https://user-images.githubusercontent.com/117836464/207580449-868ac2b5-a4e4-4a2c-a2bb-6d3ef9daafc2.png)




# 3rd Deliverable 


# Conclusions


# Sources

