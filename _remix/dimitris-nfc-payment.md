---
layout: single
title: NFC Payment
header: no
categories:
  - remix
  - easy
tags:
  - NFC
  - payment
  - proximity
  - HCI
---

Διαδραστικό παράδειγμα για **proximity interaction** τύπου tap-to-pay. Το παράδειγμα προσομοιώνει μια απλή ροή πληρωμής με NFC, όπου ο χρήστης εισάγει βασικά στοιχεία, πατά **Tap to Pay** και βλέπει καθαρό feedback **Approved** ή **Failed**. Στόχος της άσκησης είναι να φανεί γιατί σε τέτοιες αλληλεπιδράσεις είναι κρίσιμο το σαφές feedback και η δυνατότητα επανάληψης της ενέργειας.

<iframe
  height="500"
  style="width: 100%;"
  scrolling="no"
  title="NFC Payment Demo"
  src="/assets/demos/dimitris-nfc-payment-demo.html"
  frameborder="no"
  loading="lazy"
  allowfullscreen="true">
</iframe>

**Άσκηση:**  
Επεκτείνετε το παράδειγμα ώστε:
1. να προστεθεί και κατάσταση **Processing...** πριν από το τελικό αποτέλεσμα,
2. να καταγράφεται πόσες φορές χρειάστηκε **Try Again**,
3. να προστεθεί ένα ακόμη μήνυμα βοήθειας που να εξηγεί γιατί η σαφής ανάδραση είναι κρίσιμη στις πληρωμές με NFC.
