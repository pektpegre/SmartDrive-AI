# SmartDrive-AI - Τηλεκατευθυνόμενο όχημα με τεχνητή νοημοσύνη

**Όνομα Ομάδας**
- SmartDrive AI

**Διοργανωτής**

Πόλος Εκπαιδευτικής Καινοτομίας Τεχνολογίας Πληροφορίας και Επικοινωνιών Γρεβενών (Π.Ε.Κ.Τ.Π.Ε. Γρεβενών)

**Εκπαιδευτικοί**
- Λιάμπα Θεοδούλα (ΠΕ86 Πληροφορικής)
- Μωϋσιάδης Βασίλης (ΠΕ86 Πληροφορικής)

**Μαθητές Δημοτικού**
- Δεμερτζίδης Παύλος
- Ζάχος Σπύρος
- Καραμέτσιου Αικατερίνη
- Κυρατζής Στέργιος 
- Ντρόγκουντας Γεώργιος
- Ντούνας Γεώργιος

**Βίντεο με παρουσίαση της κατασκευής.**

https://youtu.be/DsiuslH4l6Y


**Αναλυτική περιγραφή έργου**

Στόχος του έργου μας ήταν η κατασκευή δύο αυτοκινήτων, η κίνηση των οποίων γίνεται με τη χρήση της τεχνητής νοημοσύνης. Τα δύο αυτοκίνητα διαθέτουν κάμερα τεχνητής νοημοσύνης και συγκεκριμένα την HuskyLens της DFRobot. Η συγκεκριμένη κάμερα δίνει τη δυνατότητα στο κάθε όχημα να αναγνωρίζει την εντολή κίνησης που δίνεται ως είσοδος για να κινείται στην αντίστοιχη κατεύθυνση.

Το πρώτο αυτοκίνητο καθοδηγείται με εντολές που αντιστοιχούν σε εκτυπωμένες ετικέτες (tags). Αυτές αναγνωρίζονται από την κάμερα και μπορεί να μετακινείται μπροστά, πίσω, δεξιά, αριστερά και να σταματάει. Η κάμερα για να μπορέσει να αναγνωρίσει τις ετικέτες, έχει προηγουμένως εκπαιδευτεί με απλές ρυθμίσεις μέσω του μενού που διαθέτει.

Το δεύτερο αυτοκίνητο αναγνωρίζει τις κινήσεις που κάνει το πρώτο όχημα και το ακολουθεί, χρησιμοποιώντας επίσης τις δυνατότητες τεχνητής νοημοσύνης της κάμερας HuskyLens.

Η κατασκευή βασίζεται στον μικροελεγκτή micro:bit. Αφενός γιατί οι εντολές σε μορφή block του περιβάλλοντος προγραμματισμού (Makecode) ήταν πιο οικείες για τους μαθητές. Αφετέρου γιατί το περιβάλλον προγραμματισμού επιτρέπει την εύκολη σύνδεση και επικοινωνία της AI κάμερας HuskyLens με το micro:bit με ένα πλήθος εντολών και χωρίς δυσλειτουργίες. Επίσης, κάθε αυτοκίνητο εκτός από τον μικροελεγκτή micro:bit, και την κάμερα HuskyLens, διαθέτει μία κατάλληλη πλακέτα επέκτασης, δύο κινητήρες και μία μπαταρία για να είναι αυτόνομο και να κινείται ελεύθερα. Οι ρόδες και το πλαίσιο των οχημάτων σχεδιάστηκαν στο Tinker CAD και εκτυπώθηκαν σε 3D εκτυπωτή.

Τα υλικά που χρησιμοποιήθηκαν είναι τα εξής :
- 2 x BBC micro:bit (40 ευρώ)\
    https://microbit.org/ 
- 2 x πλακέτες επέκτασης για κινητήρες (50 ευρώ)\
    WaveShare - Motor Driver for micro:bit\
    https://www.waveshare.com/wiki/Motor_Driver_for_micro:bit
- 4 x κινητήρες DC (52 ευρώ)\
    Waveshare - DC motor with encoder\
    https://www.waveshare.com/dcgm-3865-12v-en-240rpm.htm
- 2 x Κάμερες με δυνατότητες τεχνητής νοημοσύνης (140 ευρώ)\
    HuskyLens DFRobot\
    https://www.dfrobot.com/product-1922.html
- 12 x Επαναφορτιζόμενες μπαταρίες (ΑΑ) (36 ευρώ)
- 1 x Νήμα εκτύπωσης PLA (20 ευρώ)
- Αναλώσιμα (καλώδια, διακόπτες, κ.α.) (22 ευρώ)

Συνολικό κόστος : 360 ευρώ


**Στάδια Κατασκευής και προγραμματισμού**

Αρχικά οι μαθητές έπρεπε να κατανοήσουν τι είναι η τεχνητή νοημοσύνη. Παρουσιάσεις, βίντεο, διαδικτυακές εφαρμογές (Chat GPT, Copilot, GenCraft, Microsoft Designer κλπ) χρησιμοποιήθηκαν στην εκπαιδευτική διαδικασία προκειμένου να κατανοήσουν την έννοια αλλά και τη χρήση της.  Χρησιμοποιήθηκε επίσης και το Teachable Machine προκειμένου να δημιουργήσουν οι μαθητές τα δικά τους μοντέλα μηχανικής μάθησης και να προβληματιστούν εποικοδομητικά ως προς πλήθος και το είδος των δεδομένων που εισάγονται στο μοντέλο, αξιολογώντας τον αντίκτυπο που έχουν αυτοί οι δύο παράγοντες στο αποτέλεσμα της πρόβλεψης.

<p align="center">
    <img src="https://github.com/pektpegre/SmartDrive-AI/assets/99668439/c70d9a79-82e2-4942-9e4f-72656664a0ad" width="600">
</p>

Για την υλοποίηση της κατασκευής μας χρησιμοποιήσαμε την AI κάμερα HuskyLens, η οποία είναι εύκολη στη χρήση και διαθέτει δυνατότητες τεχνητής νοημοσύνης κατάλληλη για την ηλικιακή κατηγορία των μαθητών. Είναι εξοπλισμένη με πολλές λειτουργίες, όπως αναγνώριση προσώπου, παρακολούθηση αντικειμένων, αναγνώριση αντικειμένων, παρακολούθηση γραμμής, αναγνώριση χρώματος και αναγνώριση ετικέτας. Έχει τη δυνατότητα να συνδεθεί με δημοφιλείς πλακέτες ελέγχου όπως Arduino, micro: bit, Raspberry Pi και LattePanda και δίνει τη δυνατότητα να  αναπτυχθούν πολύ δημιουργικά έργα χωρίς την ανάπτυξη πολύπλοκων αλγορίθμων. Διαθέτει την ενσωματωμένη τεχνολογία μηχανικής εκμάθησης που της επιτρέπει να αναγνωρίζει πρόσωπα και αντικείμενα και να μπορεί να μαθαίνει συνεχώς νέα πράγματα ακόμα και από διαφορετικές οπτικές γωνίες. Μετά είναι σε θέση να τα αναγνωρίσει. Επιπλέον διαθέτει οθόνη IPS 2,0 ιντσών και δεν χρειάζεται η χρήση υπολογιστή για τη ρύθμιση των παραμέτρων. 

Οι μαθητές κατανόησαν αρχικά τη λειτουργία της κάμερας HuskyLens και έμαθαν πώς μπορούν να την εκπαιδεύουν, ώστε να αναγνωρίζει χρώματα, αντικείμενα και ετικέτες ή να ακολουθεί ένα συγκεκριμένο αντικείμενο. Εξοικειώθηκαν με την οθόνη και το μενού λειτουργίας της και έκαναν πολλές δοκιμές προκειμένου να μάθουν να την χειρίζονται και να την εκπαιδεύουν.

<p align="center">
    <img src="https://github.com/pektpegre/SmartDrive-AI/assets/99668439/0f44e8aa-c8df-4564-b3f6-f08311a11d55" width="800">
</p>

Στο επόμενο στάδιο έπρεπε η κάμερα να συνδεθεί με το micro:bit και να εξοικειωθούν οι μαθητές με το προγραμματιστικό περιβάλλον και τον έλεγχο της κάμερας μέσω του μικροελεγκτή. Ο προγραμματισμός έγινε με χρήση της διαδικτυακής εφαρμογής Makecode που είναι ελεύθερη προς χρήση.

Ιδιαίτερα απαιτητική για τους μαθητές ήταν η σύνδεση των κινητήρων και της μπαταρίας, δεδομένου ότι το πλήθος των καλωδίων αυξήθηκε και οι συνδεσμολογίες τους δυσχέραιναν τη διαχείριση της όλης κατασκευής. Οι μαθητές ξεκίνησαν να δοκιμάζουν τον κώδικα και να πειραματίζονται με τον τρόπο επικοινωνίας, ελέγχου και προγραμματισμού της κατασκευής, και ιδιαίτερα των κινητήρων. Αν και αρχικά δοκιμάστηκαν κινητήρες servo, στην τελική κατασκευή χρησιμοποιήθηκαν οι κινητήρες DC. Η συνδεσμολογία για την κάμερα και τους κινητήρες με με την πλακέτα επέκτασης του micro:bit υπάρχουν αναλυτικά στον φάκελο hardware.

<p align="center">
    <img src="https://github.com/pektpegre/SmartDrive-AI/assets/99668439/dc02688d-4cb4-4da4-b2e6-b50579040158" width="800">
</p>

Αφού ολοκληρώθηκε ο προγραμματισμός των κινητήρων, η κατασκευή έπρεπε να μετατραπεί σε όχημα για να δοκιμαστεί και η κίνηση. Με τη βοήθεια της ομάδας του γυμνασίου, σχεδιάστηκε στο τρισδιάστατο πρόγραμμα σχεδίασης TinkerCAD, ένα τρισδιάστατο μοντέλο αυτοκινήτου. Φυσικά χρειάστηκαν αρκετές δοκιμές και εκτυπώσεις προκειμένου να μπορέσουν να τοποθετηθούν όλα τα μηχανικά μέρη του (micro:bit, HuskyLens, πλακέτα επέκτασης, κινητήρες, ρόδες, μπαταρίa, σασί, καλώδια) στις σωστές λειτουργικές θέσεις και να κινείται σωστά το όχημα. Οι μαθητές συναρμολογησαν όλα τα μέρη του οχήματος, βιδώνοντας όπου χρειαζόταν κατάλληλες βίδες για να επιτευχθεί η στατικότητα και ταυτόχρονα η ευελιξία της κατασκευής. Το τελικό τρισδιάστατο σχέδιο βρίσκεται στον φάκελο 3D-model.


<p align="center">
    <img src="https://github.com/pektpegre/SmartDrive-AI/assets/99668439/6bacfa9e-22a9-4021-8835-f56218ef5acf" width="600">
</p>


<p align="center">
    <img src="https://github.com/pektpegre/SmartDrive-AI/assets/99668439/ea0a579b-7825-4a47-8e81-787b522ee0bd" width="600">
</p>



<p align="center">
    <img src="https://github.com/pektpegre/SmartDrive-AI/assets/99668439/cf755dea-adfd-4b3b-97da-fa3e26113c4d" width="600">
</p>


<p align="center">
    <img src="https://github.com/pektpegre/SmartDrive-AI/assets/99668439/3de80b51-7dcc-4668-a21c-6b153c0694cf" width="600">
</p>



<p align="center">
    <img src="https://github.com/pektpegre/SmartDrive-AI/assets/99668439/db0efa95-73f3-43aa-8539-1599a4a9b7a1" width="600">
</p>



<p align="center">
    <img src="https://github.com/pektpegre/SmartDrive-AI/assets/99668439/14198b97-b674-4e2c-821b-cc20ba9e1039" width="400">
</p>


<p align="center">
    <img src="https://github.com/pektpegre/SmartDrive-AI/assets/99668439/74cb4025-e37d-4d14-8843-7386d96ef897" width="400">
</p>



Όταν τα οχήματα ήταν έτοιμα οι μαθητές δοκίμασαν τον έλεγχο της κίνησής τους. Μετά από δοκιμές, αποδείχθηκε ότι το αυτοκίνητο ελέγχεται καλύτερα με τη χρήση ετικετών, διότι στην αναγνώριση χρωμάτων η κίνηση επηρεαζόταν από τα χρώματα του περιβάλλοντος χώρου. Για τον έλεγχο του οχήματος με ετικέτες, σχεδιάστηκε τελικά στο TinkerCAD μία κατασκευή σε μορφή κύβου που διαθέτει στις πέντε πλευρές του πέντε διαφορετικές ετικέτες. Έτσι, όταν η κάμερα βλέπει την αντίστοιχη ετικέτα κινείται προς τα μπροστά, πίσω, δεξιά, αριστερά ή σταματάει. Το τρισδιάστατο σχέδιο του κύβου και των ετικετών βρίσκεται στον φάκελο 3D-model.

<p align="center">
    <img src="https://github.com/pektpegre/SmartDrive-AI/assets/99668439/02eb6d7d-bb41-442d-879e-327eb96ffa32" width="600">
</p>


<p align="center">
    <img src="https://github.com/pektpegre/SmartDrive-AI/assets/99668439/676871cc-40a9-45ae-a523-b5701e16503d" width="600">
</p>


<p align="center">
    <img src="https://github.com/pektpegre/SmartDrive-AI/assets/99668439/b14eb66c-d29b-492f-8fad-7643b40b1daa" width="600">
</p>



Το δεύτερο όχημα προγραμματίστηκε έτσι ώστε να ακολουθεί το πρώτο. Για αυτόν τον σκοπό η κάμερα του εκπαιδεύτηκε να εντοπίζει και να ακολουθεί στην οθόνη το πρώτο όχημα. Έτσι με την βοήθεια των συντεταγμένων που το εντοπίζει πάνω στην οθόνη αποφασίζει και πως θα κινηθεί. Ο τελικός κώδικας που δημιουργήθηκε και για τα δύο οχήματα βρίσκεται στον φάκελο code.

<p align="center">
    <img src="https://github.com/pektpegre/SmartDrive-AI/assets/99668439/c7df1d43-3653-4e69-b5ed-e416065e058d" width="800">
</p>




