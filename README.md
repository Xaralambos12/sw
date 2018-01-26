# Δημιουργία Pacman

   ## Ονοματεπώνυμο: Xαζάπης Ιωάννης*
   ## Αριθμός Μητρώου: Π2013114*
   ## Προσωπικό αποθετήριο κώδικα https://github.com/GiChazap/pacman*
   ## Εκτελέσιμο https://gichazap.github.io/pacman/

## Σύνοψη

**Η παρούσα τελική αναφορά δημιουργήθηκε από τον Ιωάννη Χαζάπη με αριθμό μητρώου Π2013114 για το μάθημα Τεχνολογία Λογισμικού του ΣΤ' εξαμήνου στο ακαδημαϊκό έτος 2017-2018.

Στόχος της εργασίας είναι η δημιουργία μίας παραλλαγής του παιχνιδιού Pacman σε HTML5, με χρήση της βιβλιοθήκης Phaser.

Αρχικά, έγινε αλλαγή του **βασικού χαρακτήρα του Pacman**, σχεδιάστηκε μία **νέα πίστα** και αντικαταστάθηκαν τα **dots**.

Στη συνέχεια, έγινε προσθήκη **ήχων**, **score**, **ήχων **, **ζωών** και **bonus πόντων**. 

Τέλος, πρόσθεσα και μία **εικόνα background**. 


**Aρχικός σχεδιασμός εφαρμογής**
Προτεινόμενες αλλαγές:

Αρχικές αλλαγές
    Αντί για τον Pacman χρησιμοποίησε έναν άλλο χαρακτήρα για πρωταγωνιστή του παιχνιδιού.
    Αντί ο πρωταγωνιστής να μαζεύει μόνο dots θα μπορούσε να μαζεύει διάφορα αντικείμενα (κέρματα, λουλούδια, φρούτα κτλ).
    Δημιούργησε μια νέα πίστα για το παιχνίδι χρησιμοποιώντας το Tiled.

Υλοποίηση:
    Aρχικά, αντικατέστησα τον χαρακτήρα του Pacman με ένα χαρακτήρα που να ταιριάζει στο θέμα του pacman που επέλεξα και αυτός ήταν ένας boxer.
    Η αλλαγή που έκανα στα dots είναι να τα αντικαταστήσω με μετάλλια καθώς δεν είναι λογικό ένας boxer να ενδιαφέρεται για dots.
    Τέλος δημιούργησα μία νέα πίστα αυτήν που υπήρχε στον φάκελο Assets η οποία να μοιάζει περισσότερο με ring αλλάζοντας τα χρώματα σε μπλε άσπρο και κόκκινο. [Πίστα](http://prntscr.com/i62fxq)
    
    
**Τελικό προσχέδιο και βελτιώσεις**
    
Στην συνέχεια πρόσθεσα [μουσική background](https://www.youtube.com/watch?v=cWQluSY36FQ) αλλά και αντικατέστησα την ήxo που υπήρχε όποτε ο boxer pacman έπαιρνε ένα μετάλλιο με τον ήχο από καμπανάκι.
Ο ήχος από το καμπανάκι πάρθηκε από το youtube [ήχος](https://www.youtube.com/watch?v=TvvTacquttk). 
Πρόσθεσα μία background εικόνα που ενσωματόθηκε στην οθόνη του χρήστη ([Φωτογραφία background](https://wallpapercave.com/wp/01Syr5o.jpg) καθώς και πόντους,bonus πόνοτυς αλλά και ζωές. [πόντοι και ζωές](http://prntscr.com/i62ezx) 
Ο κάθε παίκτης έχει 3 ζωές.

[Τελική εικόνα χρήστη](http://prntscr.com/i62jrj)
    
