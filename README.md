# Academic project (Data Structures)

StringDoubleEndedQueue

H διεπαφή StringDoubleEndedQueue δηλώνει τις βασικές μεθόδους για μια ουρά, η οποία χειρίζεται
στοιχεία τύπου String, και στην οποία μπορεί να γίνεται εισαγωγή και διαγραφή στοιχείων και
από τα 2 άκρα της. 

PostfixToInfix

Πρόγραμμα-πελάτη το οποίο θα διαβάζει μία αριθμητική
παράσταση σε μεταθεματική (postfix) μορφή και θα τυπώνει την αντίστοιχη ενθεματική (infix)
μορφή. Για απλότητα, θεωρούμε ότι οι αριθμητικές παραστάσεις περιέχουν μονοψήφιους
ακεραίους αριθμούς και χρησιμοποιούν τους τελεστές +, -, *, /. Κατά τη μετατροπή στην
ενθεματική παράσταση περιλαμβάνονται και οι παρενθέσεις όπου χρειάζεται.
Επιπλέον τυπώνετε κάποιο μήνυμα λάθους αν η παράσταση δεν είναι σε έγκυρη μεταθεματική
μορφή (π.χ. αν περιέχει και άλλα σύμβολα εκτός των αριθμών και των τελεστών, ή αν δεν
τερματίζει με τελεστή).

DNAPalindrome

Πρόγραμμα-πελάτη που λύνει το παρακάτω πρόβλημα
χρησιμοποιώντας την προηγούμενη υλοποίηση.
Μία ακολουθία DNA είναι ένα αλφαριθμητικό (String) που αποτελείται από τα γράμματα A, T,
C, G. Τα γράμματα αυτά αντιστοιχούν στα νουκλεοτίδια Αδενίνη, Θυμίνη, Κυτοσίνη, Γουανίνη.
Τα νουκλεοτίδια Α και Τ είναι συμπληρωματικά μεταξύ τους και θα λέμε ότι το Α είναι το
συμπλήρωμα του Τ και αντιστρόφως. Ομοίως το C είναι το συμπλήρωμα του G και το G το
συμπλήρωμα του C. Μία ακολουθία DNA είναι Watson-Crick complemented palindrome
(συμπληρωματικά παλίνδρομη) αν, όταν αντικαταστήσουμε κάθε νουκλεοτίδιο με το
συμπλήρωμά του και μετά αντιστρέψουμε την σειρά, τότε παίρνουμε την ίδια ακολουθία με την
αρχική. Για παράδειγμα το string AAAACGTTTT είναι συμπληρωματικά παλίνδρομο.
Αντιθέτως το ATAATA δεν είναι (προσέξτε ότι η έννοια αυτή είναι διαφορετική από το να είναι
απλά παλίνδρομη μια ακολουθία χαρακτήρων). Οι ακολουθίες DNA με αυτή την ιδιότητα έχουν
σημαντικούς βιολογικούς ρόλους. Για παράδειγμα τα καρκινικά κύτταρα συχνά μεγαλώνουν τα
γονίδιά τους δημιουργώντας τέτοιου είδους συμπληρωματικά παλίνδρομα DNA.
Το πρόγραμμα διαβάζει μια ακολουθία χαρακτήρων που αναπαριστά DNA
ακολουθία και αποφασίζει αν είναι Watson-Crick complemented palindrome. Η main μας διαβάζει 
την ακολουθία DNA από το standard input, να ελέγχει αν είναι έγκυρη (π.χ.
δεν περιέχει κενά ενδιάμεσα ή μη αποδεκτούς χαρακτήρες, μη κεφαλαία γράμματα), και στο
τέλος να εκτυπώνει το σχετικό αποτέλεσμα.
Παραδείγματα από Watson-Crick παλινδρόμηση
Ναι: "ATATATAT", και "" (το κενό string ικανοποιεί την ιδιότητα).
Όχι: "AAAA", "AAAAGTTTT", "ATAATA", "ZZZZ" και "AaTT".
