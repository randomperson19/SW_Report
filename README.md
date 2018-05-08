# Τίτλος εργασίας: Οπτικοποίηση δεδομένων χορηγιών (UK)

Ονοματεπώνυμο: Ευάγγελος Γεραμάνης

ΑΜ: Π2015107

[Link στο αποθετήριο του κώδικα](https://github.com/randomperson19/D3js-uk-political-donations/tree/master)

[Link στο εκτέλεσιμο](https://randomperson19.github.io/D3js-uk-political-donations/#)

[Link στο branch του κώδικα του τελικού παραδοτέου, που περιλαμβάνει τις αλλαγές όλων των παραδοτέων](https://github.com/randomperson19/D3js-uk-political-donations/tree/%CE%A0%CE%B1%CF%81%CE%B1%CE%B4%CE%BF%CF%84%CE%AD%CE%BF_2)


## Σύνοψη

   Για το μάθημα του ΣΤ' εξαμήνου "Τεχνολογία Λογισμικού" μας δόθηκε η δυνατότητα να ασχοληθούμε με ένα project που είχε άμεση σχέση με το αντικείμενο του μαθήματος. Η οπτικοποίηση δεδομένων χορηγιών για το Ηνωμένο Βασίλειο μου κέντρισε αμέσως το ενδιαφέρον, καθώς οι υπόλοιπες επιλογές απαιτούσαν πιο πολύ χρόνο για την υλοποίηση των παραδοτέων, αλλά και μου φάνηκαν αρκετά πιο δύσκολες. Αν και δεν ασχολήθηκα όσο θα έπρεπε για να φέρω εις πέρας τους στόχους όλων των παραδοτέων, τουλάχιστον νομίζω πως έλαβα κάποιες στοιχειώδεις γνώσεις αναφορικά με τη Javascript, την Html, τη βιβλιοθήκη Data-Driven Documents (ή αλλιώς D3.js), καθώς και εμβάθυνα λίγο ακόμα στο Github και στη φιλοσοφία του "ανοικτού κώδικα".
  
## Εισαγωγή

   Προκειμένου να ανταπεξέλθω στις απαιτήσεις του κάθε παραδοτέου, απαιτούνταν πρωτίστως η κατανόηση της πλατφόρμας του Github. Σε αυτήν την προσπάθεια συνέβαλε θετικά και το εργαστήριο του μαθήματος. Ειδικά για όσους φοιτητές/φοιτήτριες προέρχονταν από την κατεύθυνση των πληροφοριακών συστημάτων, σίγουρα νομίζω πως τους βοήθησε σε μεγάλο βαθμό το εν λόγω εργαστήριο στην εξοικείωσή τους με το Github. Αντίθετα δε, όσοι προερχόμασταν από την άλλη κατεύθυνση -αυτή των Ανθρωπιστικών και Κοινωνικών Επιστημών- νομίζω πως δε δυσκολευτήκαμε ιδιαίτερα όσον αφορά τη χρήση του Github, για τα πλαίσια της εργασίας. Στη συνέχεια προχώρησα στη μελέτη της βιβλιοθήκη D3 της Javascript, καθώς ήταν η βάση για την υλοποίηση σχεδόν κάθε ζητούμενου. 
  
## Επιλογή εργαλείων και σχετικών έργων

   Τα εργαλεία που χρησιμοποίησα ήταν το "ResponsiveVoice" για text-to-speech λειτουργία. Η βιβλιοθήκη D3.js, από όπου άντλησα πληροφορίες από την πληθώρα παραδειγμάτων που υπήρχαν για να υλοποιήσω κάποια στοιχεία από τα παραδοτέα. Τέλος και πιο σημαντικό το Github που η χρήση του βεβαίως ήταν αναπόφευκτη προκειμένου να υλοποιηθεί το project. 
  

## Μέθοδος και τεχνικές ανάπτυξης

   Αρχικά έγινε download τοπικά το αποθετήριο του κώδικα της εργασίας (έπειτα από συμβουλή του κ.Χωριανόπουλου για να εμφανίζονται απευθείας οι αλλαγές που θα εφαρμόζονταν στον κώδικα αποτυπωμένες να "τρέχουν" τοπικά). Για να επιτευχθεί η λειτουργικότητα  σε τοπικό επίπεδο απαιτούνταν η ύπαρξη δύο βιβλιοθηκών ("jquery.min.js" και "d3.v3.min.js"). Σε αυτό το βήμα με βοήθησε πάρα πολύ ο Αστέριος (2015059). Στη συνέχεια εγκαταστάθηκαν όλα τα απαραίτητα εργαλεία (αυτά που αναφέρονται παραπάνω) για να είναι εφικτή η πραγματοποίηση των παραδοτέων. 
  
### Για το παραδοτέο 1 πραγματοποιήθηκαν οι ακόλουθοι στόχοι: 
  
α) Για τα ζητούμενα στα οποία απαιτούνταν αλλαγές στο προσωπικό μας αποθετήριο πραγματοποιήθηκαν τα κάτωθι:

* Ο σύνδεσμος της σελίδας με την εφαρμογή, καθώς και το url της εφαρμογής τροποποιήθηκε ώστε να μην καταλήγει σε 'full-viz.html' και να περιλαμβάνει το αντίστοιχο username. Για να επιτευχθεί αυτό, ενεργοποιήθηκαν τα gh-pages και η ονομασία του αρχείου 'full-viz.html' αλλάχθηκε σε 'index.html'.

* Τα χρώματα των κύκλων με τα δεδομένα των δωρεών και των δωρητών αλλάχθηκαν, καθώς και των 3 πεδίων της ομαδοποίησης 'Split by party'.

* Προστέθηκε ήχος κάθε φορά που γίνεται 'κλικ' σε μία επιλογή ομαδοποίησης των δεδομένων.

* Προστέθηκε η δυνατότητα αναζήτησης στο 'google' με τα στοιχεία του δωρητή, εφόσον γίνει 'κλικ'πάνω σε έναν αντίστοιχο κύκλο.

* Επεκτάθηκε η εφαρμογή, ώστε να ανταποκρίνεται και στις απαιτήσεις των ανθρώπων με περιορισμένη όραση, κάνοντας το ποντίκι να ενεργεί ως μεγεθυντικός φακός όταν περνάει πάνω από τις λέξεις. Επιπροσθέτως εμπλουτίστηκε και με την επιλογή της ακρόασης του ονόματος του δωρητή και του ποσού της δωρεάς όταν ο δείκτης του ποντικιού βρίσκεται πάνω από κάποιο κύκλο δεδομένων για τους ανθρώπους που δεν τους δίνεται η δυνατότητα να τα δουν.

* Τέλος επεκτάθηκε η εφαρμογή με την προσθήκη της ομαδοποίησης των δεδομένων 'Split by the amount of the donation'

β) Για τα ζητούμενα στα οποία απαιτούνταν αλλαγές (pull request) στο κοινό αποθετήριο του κώδικα παρατίθεται ο σχετικός σύνδεσμος από το merged pull-request: [2015107.csv και 5 εικόνες δωρητών](https://github.com/ioniodi/D3js-uk-political-donations/pull/79)


### Αναφορικά με το παραδοτέο 2:

α) Για τα ζητούμενα στα οποία απαιτούνταν αλλαγές στο προσωπικό μας αποθετήριο πραγματοποιήθηκαν τα κάτωθι:

 * Προστέθηκε η δυνατότητα όταν το ποντίκι περνάει μέσα από κάποιο κύκλο του γραφήματος να εμφανίζεται και να επεκτείνεται δυναμικά στο κάτω μέρος της ιστοσελίδας, η σειρά επισκεψιμότητας των εικόνων των δωρητών. 
 
 * Η δημιουργία ενός ακόμα D3 γραφήματος για την απεικόνιση των ίδιων δεδομένων, καθώς και η απεικόνιση διαφορετικών δεδομένων με το διαθέσιμο, δοθέν, D3 γράφημα δεν υλοποιήθηκαν. 
 
 β) Για τα ζητούμενα στα οποία απαιτούνταν αλλαγές (pull request) στο κοινό αποθετήριο του κώδικα παρατίθενται οι σχετικοί σύνδεσμοι από τα merged pull-requests: 
 
 * [index.html, τροποποίηση της #position 009, ώστε το username να έχει ένα animation εμφάνισης](https://github.com/ioniodi/D3js-uk-political-donations/pull/278)
 
 * [2015107.html, οπτικοποίηση των contributors του κεντρικού αποθετηρίου του κώδικα](https://github.com/ioniodi/D3js-uk-political-donations/pull/286)
 
 
 
## Παρακάτω ακολουθούν ενδεικτικές οθόνες και animated gif

* Εδώ παρουσιάζονται οι αλλαγές στα χρώματα των κύκλων με τα δεδομένα, καθώς και των 3 πεδίων ομαδοποίησης του 'split by party'.

![Colour](https://user-images.githubusercontent.com/22643647/39749743-225a644e-52bc-11e8-8b17-3d7c3e5da9a1.png)

* Παρακάτω διαφαίνεται η καινούρια ομαδοποίηση 'split by the amount of the donation' που προστέθηκε.

![Split by the amount of the donation]
({{https://github.com/randomperson19/D3js-uk-political-donations/tree/%CE%A0%CE%B1%CF%81%CE%B1%CE%B4%CE%BF%CF%84%CE%AD%CE%BF_2}}/Screenshots/Colour.png)

* Στη κάτωθι εικόνα είναι ορατή η σειρά επίσκεψης των κύκλων (δωρητών) του γραφήματος μέσα από τις εικόνες που εμφανίζονται

![Donors' images](https://github.com/randomperson19/D3js-uk-political-donations/blob/%CE%A0%CE%B1%CF%81%CE%B1%CE%B4%CE%BF%CF%84%CE%AD%CE%BF_2/Screenshots/Donors'%20images.png)

* Στο παρακάτω animated gif φαίνεται καλύτερα πως επιτυγχάνεται η δυναμική επέκταση των εικόνων των δωρητών

![Donors' images dynamical expansion](https://github.com/randomperson19/D3js-uk-political-donations/blob/%CE%A0%CE%B1%CF%81%CE%B1%CE%B4%CE%BF%CF%84%CE%AD%CE%BF_2/Screenshots/Donors'%20images%20dynamical%20expansion%20.gif)

* Τέλος παρατίθεται η λειτουργία του μεγεθυντικού φακού

![Zoom](https://github.com/randomperson19/D3js-uk-political-donations/blob/%CE%A0%CE%B1%CF%81%CE%B1%CE%B4%CE%BF%CF%84%CE%AD%CE%BF_2/Screenshots/Zoom.gif)


## Συμπεράσματα

   Εν κατακλείδι, πιστεύω ακράδαντα ότι αποκόμισα αρκετά πράγματα από την όλη διαδικασία του Project. Κατ'αρχάς απέκτησα ακόμα μεγαλύτερη οικειότητα με το Github, κάτι το οποίο σίγουρα θα φανεί ωφέλιμο για το μέλλον. Επιπροσθέτως είχα μια ουσιαστική και αρκετά εποικοδομητική επαφή με τη Javascprit και τη βιβλιθήκη D3. Επιπροσθέτως πήρα μια ιδέα αναφορικά με την εξέλιξη μίας διαδικασίας ανάπτυξης/επέκτασης μίας ιστοσελίδας και πως αυτή χτίζεται βήμα - βήμα, έστω και χωρίς να εμβαθύνω ιδιαίτερα. Ωστόσο το πιο καίριο και ουσιώδες κομμάτι της όλης εργασίας για μένα ήταν η κατανόηση της σημαντικότητας του ανοικτού κώδικα για την εξέλιξη των εφαρμογών. Πριν από αυτήν την εργασία, δεν είχα συνειδητοποιήσει σε τι αποσκοπούν ακριβώς τα ανοικτού κώδικα προγράμματα, πέρα ίσως από τη δωρεάν χρήση τους. Αδιαμφισβήτητα λοιπόν, το τελικό "προϊόν" που παρουσιάζω επιδέχεται αμέτρητες αλλαγές και βελτιστοποιήσεις ακόμα.



## Δικτυογραφία που χρησιμοποιήθηκε για την υλοποίηση της εργασίας:

[Χρώματα για τη CSS](https://colorwiki.org/)

[Εργαλείο που χρησιμοποιήθηκε για τη μετατροπή του κειμένου σε φωνή](https://responsivevoice.org/api/)

[Ιστότοπος από όπου 'κατεβάστηκε' ο ήχος που προστέθηκε όταν γίνεται 'κλικ' στις επιλογές ομαδοποίησης των δεδομένων](https://www.soundjay.com/button-sounds-2.html)

[Αίτημα στο API του Github για την αποστολή των δεδομένων των contributors που χρειάστηκε για το 2ο παραδοτέο](https://www.w3schools.com/xml/ajax_xmlhttprequest_create.asp)

Σύνδεσμοι για τους πηγαίους κώδικες που χρησιμοποιήθηκαν για την υλοποίηση του 2ου παραδοτέου για τα ζητούμενα που αφορούσαν αλλαγές στο αποθετήριο του κώδικα με pull-request:
  
[index.html](http://tobiasahlin.com/moving-letters/#) και 

[2015107.html](https://github.com/AsteriosP/D3js-uk-political-donations/blob/Paradoteo2-Meros2o/participants/2015059.html) 


