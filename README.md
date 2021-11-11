# DigitalHomework
Ανάπτυξη Διαδικτυακής Εφαρμογής - ακαδημαϊκό έτος 2021-22


Στόχος εργασίας
Στόχος της εργασίας είναι η ανάπτυξη μιας εφαρμογής ιστού για ανάρτηση ανακοινώσεων για τα μαθήματα του τμήματος Ψηφιακών Συστημάτων.


To Αρχικό template που χρησιμοποιήιηκε είναι το classimax ενα template βασισμένο στο bootstrap.
Μπορούμε να το βρούμε εδώ και είναι δωρεάν https://themefisher.com/products/classimax-bootstrap-classified-responsive-theme/

Το Project έχει ανέβει ήδη και τρέχει σε προσωπικό μου server μηχάνημα ubuntu 21.04.
Μπορείτε να το επισκεφτείτε στην διεύθυνση www.digitalhomework.ddns.net

Η εφαρμογή είναι API based. Το backend να αναπτυχθεί ανεξάρτητα από το frontend. Το backend απαντάει στα http request στέλνοντας δεδομένα σε json. Αντίστοιχα, το frontend  
να κάνει http request μέσω ajax calls. ΟΧΙ μεθοδολογία “Spaghetti” 

Οι τεχνολογίες που Χρησιμοποιούνται - διδάσκονται/ αναφέρονται στο μάθημα Είναι : HTML, CSS, PHP, Javascript, MySQL/MariaDB, json, ajax, Bootstrap.


Προδιαγραφές για ατομική εργασία
Η εφαρμογή θα έχει δύο βασικά μέρη. Το πρώτο μέρος θα αφορά τους καθηγητές του τμήματος, οι οποίοι, αφου κάνουν login στην εφαρμογή θα μπορούν να αναρτούν  ανακοινώσεις. Δεν είναι απαραίτητο να δημιουργηθεί registration form. 
Τα usernames και τα passwords μέσω των οποίων θα μπορούν να κάνουν login οι καθηγητές, θα προϋπάρχουν στον πίνακα users της Βάσης Δεδομένων. Για κάθε ανακοίνωση που αποθηκεύεται στη βάση δεδομένων, θα αποθηκεύεται και η 
πληροφορία για το ποιος καθηγητής δημιούργησε την ανακοίνωση.
Στο δεύτερο μέρος της εφαρμογής, οι φοιτητές και οι φοιτητριες (δεν απαιτείται login) θα μπορούν να βλέπουν τις ανακοινώσεις που έχουν ανεβάσει οι καθηγητές. Αρχικά, όλες οι ανακοινώσεις θα εμφανίζονται στην οθόνη. 
Η παρουσίαση της κάθε ανακοίνωσης θα πρέπει να συνοδεύεται από τον συντάκτη της (δηλαδή το επίθετο του καθηγητή που την δημιούργησε). Οι φοιτητές και οι φοιτήτριες, θα έχουν στη διάθεση τους ένα φιλτρο μέσω του οποίου 
θα μπορούν να δουν τις ανακοινώσεις ενός συγκεκριμένου καθηγητή. Συνεπώς, η εφαρμογή θα προσφέρει ένα dropdown list (<select>) όπου θα φορτώνονται δυναμικά από τη Βάση Δεδομένων τα επίθετα των καθηγητών. Όταν ο χρήστης 
επιλέγει το επίθετο κάποιου καθηγητή, τότε θα εμφανίζονται μόνο οι ανακοινώσεις του συγκεκριμένου καθηγητή.

Προδιαγραφές για εργασία δύο ατόμων
Στις προδιαγραφές συμπεριλαμβάνονται οι προδιαγραφές για ατομική εργασία αλλά στην περίπτωση εργασίας δύο ατόμων οι χρήστες, είτε καθηγητές είτε φοιτητές και φοιτήτριες, για να αποκτήσουν πρόσβαση στη διαδικτυακή ε
φαρμογή, θα πρέπει να κάνουν εγγραφή στην εφαρμογή. Έτσι, θα πρέπει να υπάρχει ένα registration form όπου οι χρήστες θα μπορούν να επιλέξουν την ιδιότητα τους (φοιτητής/φοιτήτρια ή καθηγητής), το επιθυμητό username κ
αι password, το όνομα τους, το επίθετο τους κτλ. Τα στοιχεία αυτά θα αποθηκεύονται στη Βάση Δεδομένων. Όταν κάποιος φοιτητής ή φοιτήτρια κάνει login (αφού πρώτα δημιουργήσει λογαριασμό) θα εμφανίζεται το δεύτερο 
μέρος της εφαρμογής. Φυσικά, οι φοιτητές και οι φοιτήτριες δεν θα μπορούν να αναρτούν ανακοινώσεις. Δικαίωμα ανάρτησης ανακοίνωσης θα έχουν μόνο οι καθηγητές, δηλαδή αυτοί που κατα την εγγραφή τους δήλωσαν ότι 
είναι καθηγητές. Συνεπώς, όταν ένας καθηγητής κάνει login, αυτός θα μπορεί να δει τις ανακοινώσεις ενώ θα μπορεί ακολουθήσει έναν σύνδεσμο που θα τον οδηγεί στην ιστοσελίδα από όπου θα μπορεί να καταχωρεί ανακοινώσεις. 
Αν κάποιος φοιτητής επιχειρήσει να ανοίξει την ιστοσελίδα καταχώρησης ανακοίνωσης, η εφαρμογή θα πρέπει να εμφανίζει μήνυμα για το ότι δεν έχει τα απαραίτητα δικαιώματα.
Σε πραγματικές εφαρμογές, τα password αποθηκεύονται κωδικοποιημένα στη βάση δεδομένων (βλέπε password_hash της PHP) και στέλνεται email όπου ο χρήστης πρέπει να ακολουθήσει έναν σύνδεσμο για την ενεργοποίηση του 
λογαριασμού. Θα εκτιμηθεί αν θα τα κάνετε. Ωστόσο, δεν είναι απαραίτητο να υλοποιήσετε αυτά τα χαρακτηριστικά.

Προδιαγραφές για εργασία τριών ατόμων
Στις προδιαγραφές συμπεριλαμβάνονται οι προδιαγραφές για εργασία δύο ατόμων. Επιπρόσθετα, ο κάθε καθηγητής, θα μπορεί να αναρτήσει ανακοίνωση που θα αφορά συγκεκριμένο μάθημα. Με άλλα λόγια, όταν ένας καθηγητής 
θα καταχωρεί μια ανακοίνωση, θα επιλέγει από ένα drop down list (<select>) και το μάθημα που θα αφορά η συγκεκριμένη ανακοίνωση. Όλοι οι καθηγητές θα μπορούν να ανεβάζουν ανακοινώσεις για οποιοδήποτε μάθημα. 
Οι φοιτητές και οι φοιτήτριες αφου κάνουν login, θα βλέπουν όλες τις ανακοινώσεις. Ωστόσο, θα έχουν στη διάθεση τους δύο φίλτρα. Το ένα θα αφορά τον καθηγητή και το άλλο το μάθημα. Για παράδειγμα, αν ο χρήστης 
επιλέξει από το ένα φίλτρο το όνομα τον καθηγητή “Ουγιάρογλου” και από το άλλο φίλτρο το μάθημα “Ανάπτυξη Διαδικτυακών Εφαρμογών”, η εφαρμογή θα εμφανίζει τις ανακοινώσεις που έχουν γίνει από τον καθηγητή 
“Ουγιάρογλου” και αφορούν το μάθημα “Ανάπτυξη Διαδικτυακών Εφαρμογών”. Αντίστοιχα, αν ο χρήστης επιλέξει κάτι μόνο από το ένα φίλτρο, το άλλο φιλτρο θα αγνοηθεί. Για παράδειγμα, αν ο χρήστης επιλέξει από 
το φίλτρο του μαθήματος το μάθημα “Ανάπτυξη Διαδικτυακών Εφαρμογών”, θα εμφανίζονται όλες οι ανακοινώσεις για το συγκεκριμένο μάθημα που έχουν δημιουργηθεί από όλους τους καθηγητές. 
Φυσικά, τα ονόματα των μαθημάτων, θα φορτώνονται δυναμικά από τη βάση δεδομένων. Για παράδειγμα αν ο πίνακας της βάσης δεδομένων που αφορά τα μαθήματα περιλαμβάνει πέντε μαθήματα, μόνο πέντε μαθήματα θα 
εμφανίζονται τόσο στο φίλτρο που αφορά την σελίδα που παρουσιάζονται οι ανακοινώσεις όσο στο στο drop down list της σελίδας που αφορά την καταχώρηση νέας ανακοίνωσης. Τα μαθήματα θα προϋπάρχουν στη βάση 
δεδομένων. Δεν είναι απαραίτητο να αναπτύξετε λειτουργία για την καταχώρηση μαθημάτων μέσω της εφαρμογής.

Προδιαγραφές για εργασία τεσσάρων ατόμων
Στις προδιαγραφές συμπεριλαμβάνονται οι προδιαγραφές για εργασία τριών ατόμων. Επιπρόσθετα, οι καθηγητές θα μπορούν να διαγράψουν ανακοινώσεις. Άρα, οι καθηγητές, θα μπορούν να δουν ανακοινώσεις, να 
εισάγουν νέες ανακοινώσεις αλλά και να διαγράψουν ανακοινώσεις μέσα από την εφαρμογή. Φυσικά, θα απαγορεύεται στους φοιτητές και τις φοιτήτριες να εισάγουν και να διαγράψουν μια ανακοίνωση.

