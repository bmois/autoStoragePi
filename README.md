# autoStoragePi
Automatic storage machine based on Raspberry Pi

Αυτόματο σύστημα αποθήκευσης βασισμένο σε Raspberry Pi

Με την βοήθεια τριών Raspberry Pi και τον απαραίτητων αισθητήρων και κινητήρων θα δημιουργηθεί ένα αυτόματο σύστημα αποθήκευσης με τα εξής χαρακτηριστικά. Θα υλοποιηθού οι εξής αυτόματοι μηχανισμοί :
- Μηχανισμός Α οποίος θα μεταφέρει τα επόμενα αντικείμενα προς τοποθέτηση σε μία κυλιόμενη ράγα.
- Μηχανισμός Β ο οποίο θα παιρνει το αντικείμενο από την ράγα και θα το τοποθετεί σε ένα κενό ράφι. Ο ίδιος μηχανισμός θα παίρνει το αντικείμενο που ζητείται από το ράφι και θα το τοποθετεί στην κυλιόμενη μπάρα εξόδου.
- Μηχανισμός Γ με κυλιόμενη μπάρα ο οποίος θα παραλαμβάνει το αντικείμενο από τον μηχανισμό μεταφοράς. Επίσης θα δημιουργηθεί εφαρμογή για κινητό τηλέφωνο με την οποία θα γίνεται χειρισμός του συστήματος δηλαδή, εκκίνηση, τερματισμός και επιλογή αντικειμένου προς ανάκτηση.

Ένα παράδειγμα του μηχανισμού Β φαίνεται στο επόμενο βίντεο του Youtube. Στην υλοποίηση μας η κατασκευή θα γίνει σε μικροκλίμακα.
https://www.youtube.com/watch?v=QetS5n2ZE5k&t=109s

Η υλοποίηση του προγραμματιστικού μέρους όσον αφορά τα Raspberry Pi θα γίνει σε γλώσσα Python η οποία είναι και πανελλαδικώς εξεταζόμενη στον Τομέα Πληροφορικής του ΕΠΑΛ. Η υλοποίηση του προγραμματιστικού μέρους για το κινητό τηλέφωνο θα γίνει σε AppInventor. Έχει επιλεγεί συνεργασία τριών Raspberry Pi για να πειραματιστούν οι μαθητές με την επικοινωνία και τον συγχρονισμό των συσκευών καθώς και με την δημιουργία μίας απλής βάσης δεδομένων όπου θα αποθηκευέται κάθε χρονική στιγμή η κατάσταση του αποθηκευτικού χώρου.

Απαιτούμενος εξοπλισμός είναι ο εξής :

<table>
  <tr>
    <td>Α/Α</td>
    <td>Ονομασία</td>
    <td>Ποσότητα</td>
    <td>Τιμή Τεμαχίου</td>
    <td>Σύνολο Τιμής</td>
  </tr>
  <tr>
    <td>1</td>
    <td>
      Raspberry Pi 3 - Model B+</br>
      https://grobotronics.com/raspberry-pi-3-model-b-el.html
    </td>
    <td>1</td>
    <td>41,90 €</td>
    <td>41,90 €</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Κάρτα μνήμης microSDHC 16GB Class 10</br>
    https://grobotronics.com/microsdhc-16gb-class-10-sandisk-ultra-sdsquar-sdsquar-016g-gn6ma.html
    </td>
    <td>1</td>
    <td>8,90 €</td>
    <td>8,90 €</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Pimoroni Raspberry Pi Zero W Starter Kit</br>
    https://grobotronics.com/pimoroni-raspberry-pi-zero-w-starter-kit.html
    </td>
    <td>2</td>
    <td>42,90 €</td>
    <td>85,80 €</td>
  </tr>
  <tr>
    <td>Α/Α</td>
    <td>Ονομασία</td>
    <td>Ποσότητα</td>
    <td>Τιμή €</td>
    <td>Σύνο €</td>
  </tr>
  <tr>
    <td>Α/Α</td>
    <td>Ονομασία</td>
    <td>Ποσότητα</td>
    <td>Τιμή €</td>
    <td>Σύνο €</td>
  </tr>
  <tr>
    <td>Α/Α</td>
    <td>Ονομασία</td>
    <td>Ποσότητα</td>
    <td>Τιμή €</td>
    <td>Σύνο €</td>
  </tr>
  <tr>
    <td>Α/Α</td>
    <td>Ονομασία</td>
    <td>Ποσότητα</td>
    <td>Τιμή €</td>
    <td>Σύνο €</td>
  </tr>
  <tr>
    <td>Α/Α</td>
    <td>Ονομασία</td>
    <td>Ποσότητα</td>
    <td>Τιμή €</td>
    <td>Σύνο €</td>
  </tr>
</table>
Μηχανισμός Α
- Ένα Raspberry Zero W
- Ένα Step Motor
- Module οδήγησης Servo Motor
- Αισθητήρας απόστασης
- Επαναφορτιζόμενη μπαταρία
- Παρελκόμενα (Καλώδια, πυκνωτές, αντιστάσεις, SD Card, Θήκη Raspberry)

Εκτιμώμενο Κόστος (80 ευρώ)

Μηχανισμός Β
- Ένα Raspberry Pi 3
- Τρία Step Motor
- Module οδήγησης Step Motor
- Επαναφορτιζόμενη μπαταρία
- Αισθητήρας απόστασης
- 2 Αισθητήρες χρώματος
- Παρελκόμενα (Καλώδια, πυκνωτές, αντιστάσεις, SD Card, Θήκη Raspberry)

Εκτιμώμενο Κόστος (150 ευρώ)

Μηχανισμός Γ
- Ένα Raspberry Zero W
- Ένα Step Motor
- Module οδήγησης Servo Motor
- Αισθητήρας απόστασης
- Επαναφορτιζόμενη μπαταρία
- Παρελκόμενα (Καλώδια, πυκνωτές, αντιστάσεις, SD Card, Θήκη Raspberry)

Εκτιμώμενο Κόστος (80 ευρώ)


Υλικά που θα απαιτηθούν για την κατασκευή :
Αυτήν την στιγμή το σχολείο μας δεν διαθέτει 3D εκτυπωτή, αλλά πιθανόν να προμηθευτεί στο μέλλον. Στην περίπτωση που δεν χρησιμοποιηθεί 3D εκτυπωτής θα χρησιμοποιηθούν άλλα μεταλικά υλικά.
- PLA για 3D εκτυπωτή.
- Αγορά μηχανικών μερών (μεταλλικοί άξονες, μπουλόνια, τροχαλίες)

Εκτιμώμενο Κόστος (150 ευρώ)


Επιπλέον απαιτούμενα υλικά εργαλεία
- Πιστόλι σιλικόνης
- Stick σιλικόνης
- Tire up
- Υλικά για ηλεκτρολογική κόλληση

Εκτιμώμενο Κόστος (70 ευρώ)

Συνολικό εκτιμώμενο κόστος (450 ευρώ)
Θα γινει προσπάθεια χρήσης ανακυκλώσιμων υλικών (πχ παλιούς εκτυπωτές, cd-rom) οπότε είναι πιθανόν να κατέβει το κόστος.
