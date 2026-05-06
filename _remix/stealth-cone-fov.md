---
layout: single
title: Stealth Cone & Field of View
header: no
categories:
  - visualization
  - tools
tags:
  - visualization
  - geometry
  - trigonometry
  - games
  - education
  - HCI
---

Το διαδραστικό αυτό εργαλείο οπτικοποιεί τον κώνο όρασης ενός εχθρού σε παιχνίδι stealth, όπως συμβαίνει σε δημοφιλή παιχνίδια τύπου Metal Gear Solid ή Assassin's Creed. Μετακινώντας το ποντίκι μέσα στο πεδίο, μετακινείτε τον παίκτη και παρατηρείτε αν είναι ορατός από τον εχθρό. Με τους sliders μπορείτε να μεταβάλλετε τη γωνία του κώνου όρασης (FOV), την απόσταση όρασης και την κατεύθυνση που κοιτάζει ο εχθρός. Ο εχθρός γίνεται κόκκινος όταν εντοπίζει τον παίκτη και πράσινος όταν ο παίκτης είναι κρυμμένος. Είναι ένας ψηφιακός τρόπος να κατανοήσετε ότι το stealth στα παιχνίδια δεν είναι μαγεία αλλά καθαρή γεωμετρία: ο εχθρός σε βλέπει μόνο όταν ο παίκτης βρίσκεται μέσα στον κυκλικό τομέα που ορίζει η γωνία και η ακτίνα της όρασής του, κάνοντας τη θεωρία πράξη σε πραγματικό χρόνο.

<p class="codepen" data-height="400" data-pen-title="Stealth Cone & Field of View" data-default-tab="result" data-slug-hash="RNoWdNN" data-user="SiaDalan" style="height: 400px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
<span>See the Pen <a href="https://codepen.io/SiaDalan/pen/RNoWdNN">
  Stealth Cone & Field of View</a> by Aspasia Dalanika (<a href="https://codepen.io/SiaDalan">@SiaDalan</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

Χρησιμοποίησε το ποντίκι για να μετακινήσεις τον παίκτη και τους sliders για να αλλάξεις τα χαρακτηριστικά της όρασης του εχθρού. Στόχος είναι να καταλάβεις πότε ο παίκτης είναι ορατός και πότε όχι.
1. Κράτησε σταθερή την απόσταση όρασης r = 200 px και τη γωνία FOV = 60°. Κούνησε τον παίκτη γύρω από τον εχθρό. Σε ποια απόσταση και υπό ποια γωνία ο εχθρός σε εντοπίζει; Επαλήθευσε ότι ο εχθρός σε βλέπει μόνο όταν η γωνία μεταξύ του διανύσματος "εχθρός→παίκτης" και της κατεύθυνσης του εχθρού είναι μικρότερη από FOV/2.
2. Δοκίμασε ακραίες τιμές: γωνία FOV = 360° (ο εχθρός βλέπει παντού) και FOV = 10° (ο εχθρός βλέπει μόνο μπροστά). Πώς αλλάζει η δυσκολία του παιχνιδιού; Σκέψου: αν ένας game designer ήθελε ένα "εύκολο" επίπεδο stealth, ποιες τιμές θα έβαζε για το FOV και την ακτίνα όρασης r;