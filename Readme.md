***4ο Δημοτικό Σχολείο Καλαμαριάς***

**Smart Garbage Monitoring System**

<html>


<body lang=EL link="#0563C1" vlink="#954F72">

<div class=WordSection1>

<p class=MsoTocHeading>Περιεχόμενα</p>

<p class=MsoToc1><span class=MsoHyperlink><a href="#_Toc137899619">Εισαγωγή</a></span></p>

<p class=MsoToc1><span class=MsoHyperlink><a href="#_Toc137899620">Σενάριο
Χρήσης</a></span></p>

<p class=MsoToc1><span class=MsoHyperlink><a href="#_Toc137899621">Στόχος
Εφαρμογής</a></span></p>

<p class=MsoToc1><span class=MsoHyperlink><a href="#_Toc137899622">Προτεινόμενη
Λύση</a></span></p>

<p class=MsoToc1><span class=MsoHyperlink><a href="#_Toc137899623">Σενάριο&nbsp;Δραστηριότητας</a></span></p>

<p class=MsoToc1><span class=MsoHyperlink><a href="#_Toc137899624">Φάση
Προετοιμασίας</a></span></p>

<p class=MsoToc1><span class=MsoHyperlink><a href="#_Toc137899625">Φάση
σχεδιασμού</a></span></p>

<p class=MsoToc1><span class=MsoHyperlink><a href="#_Toc137899626">Δυσκολίες
που αντιμετωπίσαμε</a></span></p>

<p class=MsoToc1><span class=MsoHyperlink><a href="#_Toc137899627">Σε τι μας
βοηθάει</a></span></p>

<p class=MsoToc1><span class=MsoHyperlink><a href="#_Toc137899628">Κώδικας <span
lang=EN-US>Arduino</span><span lang=EN-US> </span><span lang=EN-US>IDE</span></a></span></p>

<p class=MsoToc1><span class=MsoHyperlink><a href="#_Toc137899629">Μελλοντικές
εξελίξεις</a></span></p>

<p class=MsoToc1><span class=MsoHyperlink><a href="#_Toc137899630">Πλατφόρμες
που χρησιμοποιήθηκαν</a></span></p>

<p class=MsoToc1><span class=MsoHyperlink><a href="#_Toc137899631">Υλοποίηση</a></span></p>

<p class=MsoToc1><span class=MsoHyperlink><a href="#_Toc137899632">Φάση Δοκιμών</a></span></p>

<p class=MsoToc1><span class=MsoHyperlink><a href="#_Toc137899633">Συμπεράσματα</a></span></p>

<p class=MsoNormal>&nbsp;</p>

<p class=MsoNormal style='margin-bottom:12.0pt;text-align:justify;text-justify:
inter-ideograph;line-height:normal;background:white'><b><span lang=EN-US
style='font-size:14.0pt;font-family:"Helvetica",sans-serif;color:#24292F'>&nbsp;</span></b></p>

<h1><a name="_Toc137899618">Περιεχόμενα</a></h1>

<p class=MsoListParagraphCxSpFirst style='margin-bottom:12.0pt;text-align:justify;
text-justify:inter-ideograph;text-indent:-18.0pt;line-height:normal;background:
white'><span style='font-size:14.0pt;font-family:Symbol;color:#24292F'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><b><span
style='font-size:14.0pt;font-family:"Comic Sans MS";color:#24292F'>Εισαγωγή</span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-bottom:12.0pt;text-align:
justify;text-justify:inter-ideograph;text-indent:-18.0pt;line-height:normal;
background:white'><span style='font-size:14.0pt;font-family:Symbol;color:#24292F'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><b><span
style='font-size:14.0pt;font-family:"Comic Sans MS";color:#24292F'>Σενάριο
Χρήσης</span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-bottom:12.0pt;text-align:
justify;text-justify:inter-ideograph;text-indent:-18.0pt;line-height:normal;
background:white'><span style='font-size:14.0pt;font-family:Symbol;color:#24292F'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><b><span
style='font-size:14.0pt;font-family:"Comic Sans MS";color:#24292F'>Στόχος
Εφαρμογής</span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-bottom:12.0pt;text-align:
justify;text-justify:inter-ideograph;text-indent:-18.0pt;line-height:normal;
background:white'><span style='font-size:14.0pt;font-family:Symbol;color:#24292F'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><b><span
style='font-size:14.0pt;font-family:"Comic Sans MS";color:#24292F'>Προτεινόμενη
Λύση</span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-bottom:12.0pt;text-align:
justify;text-justify:inter-ideograph;text-indent:-18.0pt;line-height:normal;
background:white'><span style='font-size:14.0pt;font-family:Symbol;color:#24292F'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><b><span
style='font-size:14.0pt;font-family:"Comic Sans MS";color:#24292F'>Σενάριο Δραστηριότητας</span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-bottom:12.0pt;text-align:
justify;text-justify:inter-ideograph;text-indent:-18.0pt;line-height:normal;
background:white'><span style='font-size:14.0pt;font-family:Symbol;color:#24292F'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><b><span
style='font-size:14.0pt;font-family:"Comic Sans MS";color:#1F2328'>Φάση
Προετοιμασίας</span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-bottom:12.0pt;text-align:
justify;text-justify:inter-ideograph;text-indent:-18.0pt;line-height:normal;
background:white'><span style='font-size:14.0pt;font-family:Symbol;color:#24292F'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><b><span
style='font-size:14.0pt;font-family:"Comic Sans MS";color:#1F2328'>Φάση
Σχεδιασμού</span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-bottom:12.0pt;text-align:
justify;text-justify:inter-ideograph;text-indent:-18.0pt;line-height:normal;
background:white'><span style='font-size:14.0pt;font-family:Symbol;color:#24292F'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><b><span
style='font-size:14.0pt;font-family:"Comic Sans MS";color:#1F2328'>Σε τι μας
βοηθάει</span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-bottom:12.0pt;text-align:
justify;text-justify:inter-ideograph;text-indent:-18.0pt;line-height:normal;
background:white'><span style='font-size:14.0pt;font-family:Symbol;color:#24292F'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><b><span
style='font-size:14.0pt;font-family:"Comic Sans MS";color:#1F2328'>Δυσκολίες
που αντιμετωπίσαμε</span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-bottom:12.0pt;text-align:
justify;text-justify:inter-ideograph;text-indent:-18.0pt;line-height:normal;
background:white'><span style='font-size:14.0pt;font-family:Symbol;color:#24292F'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><b><span
style='font-size:14.0pt;font-family:"Comic Sans MS";color:#1F2328'>Μελλοντικές
εξελίξεις</span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-bottom:12.0pt;text-align:
justify;text-justify:inter-ideograph;text-indent:-18.0pt;line-height:normal;
background:white'><span style='font-size:14.0pt;font-family:Symbol;color:#24292F'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><b><span
style='font-size:14.0pt;font-family:"Comic Sans MS";color:#1F2328'>Κώδικας </span></b><b><span
lang=EN-US style='font-size:14.0pt;font-family:"Comic Sans MS";color:#1F2328'>Arduino
IDE</span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-bottom:12.0pt;text-align:
justify;text-justify:inter-ideograph;text-indent:-18.0pt;line-height:normal;
background:white'><span style='font-size:14.0pt;font-family:Symbol;color:#24292F'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><b><span
style='font-size:14.0pt;font-family:"Comic Sans MS";color:#1F2328'>Πλατφόρμες
που χρησιμοποιήθηκαν</span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-bottom:12.0pt;text-align:
justify;text-justify:inter-ideograph;text-indent:-18.0pt;line-height:normal;
background:white'><span style='font-size:14.0pt;font-family:Symbol;color:#24292F'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><b><span
style='font-size:14.0pt;font-family:"Comic Sans MS";color:#24292F'>Υλοποίηση</span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-bottom:12.0pt;text-align:
justify;text-justify:inter-ideograph;text-indent:-18.0pt;line-height:normal;
background:white'><span style='font-size:14.0pt;font-family:Symbol;color:#24292F'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><b><span
style='font-size:14.0pt;font-family:"Comic Sans MS";color:#24292F'>Φάση Δοκιμών</span></b></p>

<p class=MsoListParagraphCxSpLast style='margin-bottom:12.0pt;text-align:justify;
text-justify:inter-ideograph;text-indent:-18.0pt;line-height:normal;background:
white'><span style='font-size:14.0pt;font-family:Symbol;color:#24292F'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span></span><b><span
style='font-size:14.0pt;font-family:"Comic Sans MS";color:#24292F'>Συμπεράσματα</span></b></p>

<h1><a name="_Toc137899619">Εισαγωγή</a></h1>

<p class=MsoNormal style='margin-bottom:12.0pt;text-align:justify;text-justify:
inter-ideograph;text-indent:36.0pt;line-height:normal;background:white'><span
style='font-size:12.0pt;font-family:"Comic Sans MS";color:#24292F'>Η διαδικασία
της καθημερινής συλλογής των αστικών οικιακών απορριμμάτων στις μεγάλες κυρίως
πόλεις, μπορεί να «κρύβει» μια σπατάλη ενέργειας που στην σημερινή εποχή της
κλιματικής αλλαγής θα ήταν προτιμότερο να μπορούσαμε να την αποφύγουμε. Πιο
συγκεκριμένα οι υπάλληλοι που χειρίζονται τα μηχανήματα αποκομιδής σκουπιδιών
από τους γνωστούς μας κάδους, έχουν ένα καθημερινό δρομολόγιο μέσα στους
δρόμους μιας μεγαλούπολης, με σκοπό να αδειάσουν τους </span><span
style='font-size:12.0pt;font-family:"Comic Sans MS";color:#7030A0'>«πιθανώς»</span><span
style='font-size:12.0pt;font-family:"Comic Sans MS";color:#24292F'> γεμάτους
κάδους από τα σκουπίδια. Ο σχεδιασμός της αποκομιδής, υποθέτει βάσει της
πρότερης εμπειρίας τους, ότι είναι τόσο γεμάτοι ώστε να μην μπορεί να
παραληφθούν για έστω και μία ημέρα , από τα μηχανήματα αποκομιδής. κατά την
κυκλοφορία τους καθημερινά μέσα στην πόλη.</span></p>

<p class=MsoNormal style='margin-bottom:12.0pt;text-align:justify;text-justify:
inter-ideograph;text-indent:36.0pt;line-height:normal;background:white'><span
style='font-size:12.0pt;font-family:"Comic Sans MS";color:#24292F'>Είναι όμως
ακριβώς έτσι;  Αν για παράδειγμα κάποιοι κάδοι , από τους οποίους περνάνε τα
μηχανήματα είναι μισοάδειοι και θα μπορούσαν να παραμείνουν μέχρι και την
επόμενη ημέρα, για να αδειάσουν , τότε μήπως το μηχάνημα αποκομιδής σπατάλησε
ενέργεια σε καύσιμα, χρόνο, ανθρωποώρες εργασίας από τους υπαλλήλους και
τελικώς επιβάρυνε και την κυκλοφορία της πόλης; Επιπλέον αν κάποιοι κάδοι λόγω
κάπου ειδικού και έκτακτου γεγονότος στην περιοχή, γέμισαν νωρίτερα από το
«προβλεπόμενο» χρόνο, τότε αυτή η «αλάνθαστη» καθημερινή εμπειρία χρήσης δεν
είναι τελικά η ενδεδειγμένη διαδικασία αποκομιδής απορριμμάτων μέσα σε μία
πόλη;</span></p>

<h1><a name="_Toc137899620">Σενάριο Χρήσης</a></h1>

<p class=MsoNormalCxSpFirst style='margin-bottom:0cm;margin-bottom:.0001pt;
text-align:justify;text-justify:inter-ideograph;text-indent:36.0pt;line-height:
normal;background:white'><span style='font-size:12.0pt;font-family:"Comic Sans MS";
color:#1D2228'>Ένας αισθητήρας υπερήχων (<i>ένας αισθητήρας απόστασης)</i> θα
τοποθετηθεί στην εσωτερική πλευρά του καπακιού, αυτή που βλέπει τα στερεά
απόβλητα. Καθώς τα σκουπίδια αυξάνονται, η απόσταση μεταξύ του υπερήχου και των
σκουπιδιών μειώνεται. Αυτά τα ζωντανά δεδομένα θα σταλούν στον μικροελεγκτή
μας.   Στη συνέχεια, ο μικροελεγκτής μας επεξεργάζεται τα δεδομένα και μέσω της
βοήθειας WiFi τα στέλνει σε μια εφαρμογή.</span></p>

<p class=MsoNormalCxSpMiddle style='margin-bottom:0cm;margin-bottom:.0001pt;
text-align:justify;text-justify:inter-ideograph;text-indent:36.0pt;line-height:
normal;background:white'><span style='font-size:12.0pt;font-family:"Comic Sans MS";
color:#1D2228'>Αυτό που κάνει η εφαρμογή αντιπροσωπεύει οπτικά την ποσότητα των
σκουπιδιών στον κάδο με μια μικρή κινούμενη εικόνα.</span></p>

<p class=MsoNormalCxSpMiddle style='margin-bottom:0cm;margin-bottom:.0001pt;
text-align:justify;text-justify:inter-ideograph;text-indent:36.0pt;line-height:
normal;background:white'><span style='font-size:12.0pt;font-family:"Comic Sans MS";
color:#1D2228'>Αυτή η διαδικασία θα υποδείξει όλους τους κάδους που απαιτούν
προσοχή, οδηγώντας τον χρήστη να ακολουθήσει την πιο αποτελεσματική διαδρομή.</span><span
style='font-family:"Comic Sans MS"'> </span></p>

<p class=MsoNormal><span style='font-family:"Comic Sans MS"'>&nbsp;</span></p>

<p class=MsoNormal align=center style='text-align:center'><span
style='font-family:"Comic Sans MS"'><img border=0 width=594 height=251
id="Εικόνα 1"
src="images/1.png"></span></p>

<p class=MsoNormal align=right style='text-align:right'><span lang=EN-US
style='font-family:"Comic Sans MS"'>&nbsp;</span></p>

<p class=MsoNormal align=center style='text-align:center'><span
style='position:absolute;z-index:251660288;left:0px;margin-left:471px;
margin-top:638px;width:136px;height:264px'><img width=109 height=211
src="Arduino_smart_garbadge_monitoring_system_2023_Readme%20-%20Αντιγραφή.files/image002.png"></span><span
style='position:absolute;z-index:251659264;left:0px;margin-left:565px;
margin-top:664px;width:44px;height:216px'><img width=35 height=173
src="Arduino_smart_garbadge_monitoring_system_2023_Readme%20-%20Αντιγραφή.files/image003.png"></span><span
style='font-family:"Comic Sans MS"'><img border=0 width=631 height=239
id="Εικόνα 2"
src="Arduino_smart_garbadge_monitoring_system_2023_Readme%20-%20Αντιγραφή.files/image004.jpg"></span></p>

<p class=MsoNormal style='margin-right:11.3pt;text-align:justify;text-justify:
inter-ideograph;text-indent:36.0pt'><span style='font-size:12.0pt;line-height:
107%;font-family:"Comic Sans MS"'>Σε κάθε κάδο υπάρχει ένας <span
style='color:red'>αισθητήρας </span></span><span style='font-size:12.0pt;
line-height:107%;font-family:"Comic Sans MS";color:black'>, </span><span
style='font-size:12.0pt;line-height:107%;font-family:"Comic Sans MS";
color:black'>ο οποίος βλέπει πόσο γεμάτος είναι ο κάδος. Όταν ο κάδος είναι
γεμάτος τότε το </span><span style='font-size:12.0pt;line-height:107%;
font-family:"Comic Sans MS";color:#002060'>τσιπάκι </span><span
style='font-size:12.0pt;line-height:107%;font-family:"Comic Sans MS";
color:black'>στέλνει μήνυμα μέσω </span><span lang=EN-GB style='font-size:12.0pt;
line-height:107%;font-family:"Comic Sans MS";color:black'>Wi</span><span
style='font-size:12.0pt;line-height:107%;font-family:"Comic Sans MS";
color:black'>-</span><span lang=EN-GB style='font-size:12.0pt;line-height:107%;
font-family:"Comic Sans MS";color:black'>Fi</span><span style='font-size:12.0pt;
line-height:107%;font-family:"Comic Sans MS";color:black'> στην εφαρμογή.</span></p>

<p class=MsoNormal style='margin-right:11.3pt;text-align:justify;text-justify:
inter-ideograph;text-indent:36.0pt'><span style='font-size:12.0pt;line-height:
107%;font-family:"Comic Sans MS";color:black'>Υλικά</span></p>

<table class=MsoTableGrid border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none'>
 <tr style='height:16.5pt'>
  <td width=193 valign=top style='width:144.75pt;border:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span style='font-size:12.0pt;font-family:
  "Comic Sans MS";color:black'>Είδος</span></p>
  </td>
  <td width=101 valign=top style='width:75.95pt;border:solid windowtext 1.0pt;
  border-left:none;padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span style='font-size:12.0pt;font-family:
  "Comic Sans MS";color:black'>Ποσότητα</span></p>
  </td>
 </tr>
 <tr style='height:16.5pt'>
  <td width=193 valign=top style='width:144.75pt;border:solid windowtext 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span lang=EN-US style='font-size:12.0pt;
  font-family:"Comic Sans MS";color:black'>Arduino UNO R3 SMD</span></p>
  </td>
  <td width=101 valign=top style='width:75.95pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span style='font-size:12.0pt;font-family:
  "Comic Sans MS";color:black'>5</span></p>
  </td>
 </tr>
 <tr style='height:16.5pt'>
  <td width=193 valign=top style='width:144.75pt;border:solid windowtext 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span lang=EN-US style='font-size:12.0pt;
  font-family:"Comic Sans MS";color:black'>Ultrasonic distance sensor</span></p>
  </td>
  <td width=101 valign=top style='width:75.95pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span lang=EN-US style='font-size:12.0pt;
  font-family:"Comic Sans MS";color:black'>5</span></p>
  </td>
 </tr>
 <tr style='height:16.5pt'>
  <td width=193 valign=top style='width:144.75pt;border:solid windowtext 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span lang=EN-US style='font-size:12.0pt;
  font-family:"Comic Sans MS";color:black'>9v Battery</span></p>
  </td>
  <td width=101 valign=top style='width:75.95pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span lang=EN-US style='font-size:12.0pt;
  font-family:"Comic Sans MS";color:black'>5</span></p>
  </td>
 </tr>
 <tr style='height:16.5pt'>
  <td width=193 valign=top style='width:144.75pt;border:solid windowtext 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span lang=EN-US style='font-size:12.0pt;
  font-family:"Comic Sans MS";color:black'>Jumper wires 40pcs</span></p>
  </td>
  <td width=101 valign=top style='width:75.95pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span lang=EN-US style='font-size:12.0pt;
  font-family:"Comic Sans MS";color:black'>5</span></p>
  </td>
 </tr>
 <tr style='height:16.5pt'>
  <td width=193 valign=top style='width:144.75pt;border:solid windowtext 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span lang=EN-US style='font-size:12.0pt;
  font-family:"Comic Sans MS";color:black'>LEDs </span></p>
  </td>
  <td width=101 valign=top style='width:75.95pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span lang=EN-US style='font-size:12.0pt;
  font-family:"Comic Sans MS";color:black'>5</span></p>
  </td>
 </tr>
 <tr style='height:16.5pt'>
  <td width=193 valign=top style='width:144.75pt;border:solid windowtext 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span lang=EN-US style='font-size:12.0pt;
  font-family:"Comic Sans MS";color:black'>Breadboard</span></p>
  </td>
  <td width=101 valign=top style='width:75.95pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span lang=EN-US style='font-size:12.0pt;
  font-family:"Comic Sans MS";color:black'>5</span></p>
  </td>
 </tr>
</table>

<p class=MsoNormal style='margin-right:11.3pt;text-align:justify;text-justify:
inter-ideograph;text-indent:36.0pt'><span style='font-size:12.0pt;line-height:
107%;font-family:"Comic Sans MS";color:black'>&nbsp;</span></p>

<h1><a name="_Toc137899621"><span style='font-size:18.0pt;line-height:107%'>Στόχος
</span></a>Εφαρμογής</h1>

<p class=MsoNormal style='margin-right:-19.15pt;text-indent:36.0pt'><span
style='font-size:12.0pt;line-height:107%;font-family:"Comic Sans MS";
color:black'>Ο Στόχος αυτής της εφαρμογής είναι να διευκολύνει τους ανθρώπους
που μαζεύουν τα σκουπίδια ή ακόμα και τους ανθρώπους για να πετάξουν τα σκουπίδια
τους.</span></p>

<h1><a name="_Toc137899622">Προτεινόμενη Λύση</a></h1>

<p class=MsoNormal style='margin-right:-19.15pt;text-align:justify;text-justify:
inter-ideograph;text-indent:36.0pt'><span style='font-size:12.0pt;line-height:
107%;font-family:"Comic Sans MS";color:black'>Η πιλοτική εφαρμογή που
προτείνουμε να δημιουργήσαμε αποτελεί μια ιδέα που μπορεί να εξοικονομήσει
ενέργεια κατά τη αποκομιδή και διαχείριση των οικιακών αποβλήτων αλλά και να
δημιουργήσει ένα πιο φιλικό αστικό και βιώσιμο αστικό περιβάλλον, μειώνοντας
την σπατάλη ενέργειας, τον θόρυβο, την επιβάρυνση του κυκλοφοριακού φόρτου της
πόλης από την άσκοπη μετακίνηση μηχανημάτων αποκομιδής, όταν αυτό μπορεί να
προβλεφθεί και να αποφευχθεί.</span></p>

<p class=MsoNormal style='margin-right:-19.15pt;text-align:justify;text-justify:
inter-ideograph'><span style='font-size:12.0pt;line-height:107%;font-family:
"Comic Sans MS";color:black'>Αρχικά θα πρέπει πρώτα να εισάγουμε (ορίσουμε) το
ύψος του κάδου απορριμμάτων. Αυτό θα μας βοηθήσει να υπολογίσουμε το ποσοστό
των απορριμμάτων μέσα στον κάδο απορριμμάτων. Στη συνέχεια, έχουμε δύο κριτήρια
που πρέπει να πληρούνται για να δείξουμε ότι ο συγκεκριμένος κάδος πρέπει να
αδειάσει:</span></p>

<p class=MsoNormal style='margin-right:-19.15pt'><span style='font-size:12.0pt;
line-height:107%;font-family:"Comic Sans MS";color:black'>&nbsp;</span></p>

<p class=MsoListParagraph style='margin-top:0cm;margin-right:-19.15pt;
margin-bottom:8.0pt;margin-left:14.2pt;text-align:justify;text-justify:inter-ideograph;
text-indent:-14.2pt'><span lang=EN-US style='font-size:12.0pt;line-height:107%;
font-family:"Comic Sans MS";color:black'>1.<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;
</span></span><span style='font-size:12.0pt;line-height:107%;font-family:"Comic Sans MS";
color:black'>Ας πούμε ότι εάν ο κάδος σας είναι μισογεμάτος, δεν χρειάζεται
πραγματικά να τον αδειάσετε. Το σημείο πλήρωσης του κάδου, ή η μέγιστη ποσότητα
απορριμμάτων που επιτρέπουμε, είναι το 75% του κάδου. </span><span lang=EN-US
style='font-size:12.0pt;line-height:107%;font-family:"Comic Sans MS";
color:black'>(Μπορείτε να οριστεί ανάλογα με τις επιλογές του χρήστη.)</span></p>

<p class=MsoNormal style='margin-right:-19.15pt;text-align:justify;text-justify:
inter-ideograph'><span lang=EN-US style='font-size:12.0pt;line-height:107%;
font-family:"Comic Sans MS";color:black'>&nbsp;</span></p>

<p class=MsoListParagraphCxSpFirst style='margin-top:0cm;margin-right:-19.15pt;
margin-bottom:8.0pt;margin-left:14.2pt;text-align:justify;text-justify:inter-ideograph;
text-indent:-14.2pt'><span style='font-size:12.0pt;line-height:107%;font-family:
"Comic Sans MS";color:black'>2.<span style='font:7.0pt "Times New Roman"'>&nbsp;
</span></span><span style='font-size:12.0pt;line-height:107%;font-family:"Comic Sans MS";
color:black'>Αν υποθέσουμε ότι ένας συγκεκριμένος κάδος απορριμμάτων γεμίζει
20% και μετά για μια εβδομάδα δεν αλλάζει, μπαίνει στο δεύτερο κριτήριό μας, ο
χρόνος. Με τον καιρό, ακόμη και η μικρή ποσότητα θα αρχίσει να σαπίζει,
οδηγώντας σε ένα δύσοσμο περιβάλλον. Για να αποφύγουμε το επίπεδο ανοχής μας να
είναι 2 ημέρες, επομένως εάν ένας κάδος απορριμμάτων είναι μικρότερος από 75%
αλλά είναι δύο ημερών, τότε θα πρέπει επίσης να αδειάσει.</span></p>

<p class=MsoListParagraphCxSpMiddle><span style='font-size:12.0pt;line-height:
107%;font-family:"Comic Sans MS";color:black'>&nbsp;</span></p>

<p class=MsoListParagraphCxSpMiddle><span style='font-size:12.0pt;line-height:
107%;font-family:"Comic Sans MS";color:black'>&nbsp;</span></p>

<p class=MsoListParagraphCxSpMiddle><span style='font-size:12.0pt;line-height:
107%;font-family:"Comic Sans MS";color:black'>&nbsp;</span></p>

<p class=MsoListParagraphCxSpMiddle><span style='font-size:12.0pt;line-height:
107%;font-family:"Comic Sans MS";color:black'>&nbsp;</span></p>

<p class=MsoListParagraphCxSpMiddle><span style='font-size:12.0pt;line-height:
107%;font-family:"Comic Sans MS";color:black'>&nbsp;</span></p>

<p class=MsoListParagraphCxSpLast><span style='font-size:12.0pt;line-height:
107%;font-family:"Comic Sans MS";color:black'>&nbsp;</span></p>

<h1><a name="_Toc137899623">Σενάριο&nbsp;Δραστηριότητας</a></h1>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><b><span style='font-family:"Comic Sans MS";color:#1F2328'>&nbsp;</span></b></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";color:#1F2328'>Αριθμός
μαθητών: 7</span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";color:#1F2328'>Αριθμός
ομάδων: 1</span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";color:#1F2328'>Αριθμός
Ατόμων ανά ομάδα: 7</span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
7.1pt;text-indent:-7.1pt;background:white'><span style='font-family:"Comic Sans MS";
color:#1F2328'>Είδος Δραστηριότητας:&nbsp;Ομαδοσυνεργατική</span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";color:#1F2328'>Ρόλοι:
Δεν υπάρχουν διακριτοί ρόλοι στην ομάδα</span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";color:#1F2328'>Ηλικιακή
Ομάδα: 11-12</span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";color:#1F2328'>&nbsp;</span></p>

<h1><a name="_Toc137899624">Φάση Προετοιμασίας</a></h1>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";color:#1F2328'>Οι
μαθητές:</span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
36.0pt;text-indent:-18.0pt;background:white'><span style='font-family:Symbol;
color:#1F2328'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span style='font-family:"Comic Sans MS";color:#1F2328'>Βρήκαμε&nbsp;την&nbsp;ιδέα</span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
36.0pt;text-indent:-18.0pt;background:white'><span style='font-family:Symbol;
color:#1F2328'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span style='font-family:"Comic Sans MS";color:#1F2328'>Ορίσαμε&nbsp;τις&nbsp;προδιαγραφές&nbsp;της&nbsp;εφαρμογής</span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
36.0pt;text-indent:-18.0pt;background:white'><span style='font-family:Symbol;
color:#1F2328'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span style='font-family:"Comic Sans MS";color:#1F2328'>Σκεφτήκαμε&nbsp;τις&nbsp;λειτουργίες&nbsp;της&nbsp;εφαρμογής</span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
36.0pt;text-indent:-18.0pt;background:white'><span style='font-family:Symbol;
color:#1F2328'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span style='font-family:"Comic Sans MS";color:#1F2328'>Καταγράψαμε&nbsp;τις&nbsp;ανάγκες&nbsp;για&nbsp;υλικά</span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
36.0pt;text-indent:-18.0pt;background:white'><span style='font-family:Symbol;
color:#1F2328'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span style='font-family:"Comic Sans MS";color:#1F2328'>Παραγγείλαμε
τα&nbsp;υλικά</span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
36.0pt;text-indent:-18.0pt;background:white'><span style='font-family:Symbol;
color:#1F2328'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span style='font-family:"Comic Sans MS";color:#1F2328'>Προετοιμάσαμε
και αποστείλαμε την περίληψη για την συμμετοχή μας στον διαγωνισμό</span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";color:#1F2328'>&nbsp;</span></p>

<h1><a name="_Toc137899625">Φάση σχεδιασμού</a></h1>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";color:#1F2328'>Η
συσκευή που θέλουμε να φτιάξουμε θα είναι φτιαγμένη από έναν αισθητήρα απόστασης
(</span><span lang=EN-GB style='font-family:"Comic Sans MS";color:#1F2328'>ultrasonic</span><span
lang=EN-GB style='font-family:"Comic Sans MS";color:#1F2328'> </span><span
lang=EN-GB style='font-family:"Comic Sans MS";color:#1F2328'>sensor</span><span
style='font-family:"Comic Sans MS";color:#1F2328'>) ο οποίος θα τοποθετηθεί στο
καπάκι του κάδου και θα μετράει την ποσότητα των σκουπιδιών στον κάδο. Το
μηχάνημα θα ελέγχετε από το </span><span lang=EN-GB style='font-family:"Comic Sans MS";
color:#1F2328'>Arduino</span><span lang=EN-GB style='font-family:"Comic Sans MS";
color:#1F2328'> </span><span lang=EN-GB style='font-family:"Comic Sans MS";
color:#1F2328'>Uno</span><span lang=EN-GB style='font-family:"Comic Sans MS";
color:#1F2328'> </span><span lang=EN-GB style='font-family:"Comic Sans MS";
color:#1F2328'>R</span><span style='font-family:"Comic Sans MS";color:#1F2328'>3.</span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";color:#1F2328'>&nbsp;</span></p>

<h1><a name="_Toc137899626">Δυσκολίες που αντιμετωπίσαμε</a></h1>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";color:#1F2328'>Ήταν
αρκετά δύσκολο να δούμε πως συνδέεται το κάθε καλώδιο και το πως να το
συνδέσουμε με το </span><span lang=EN-GB style='font-family:"Comic Sans MS";
color:#1F2328'>Arduino</span><span lang=EN-GB style='font-family:"Comic Sans MS";
color:#1F2328'> </span><span style='font-family:"Comic Sans MS";color:#1F2328'>UNO.
Επίσης ήταν αρκετά δύσκολο να προσαρμόσουμε τον κώδικα για να ταιριάζει στα
δικά μας δεδομένα.</span></p>

<h1><a name="_Toc137899627">Σε τι μας βοηθάει</a></h1>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";color:#1F2328'>Η
βοήθειά του είναι μεγάλη διότι όποιος θέλει να αδειάσει τον κάδο θα μπορεί
απλώς να μπει στην εφαρμογή και να δει αν ο κάδος είναι γεμάτος ή άδειος τότε
θα τους διευκολύνει. Η εφαρμογή βοηθάει τους αυτούς τους φορείς, </span><span
style='font-family:"Comic Sans MS";color:#1F2328'>Όπως ο Δήμος, η περιφέρεια
και η γειτονιά.</span><span style='font-family:"Comic Sans MS";color:#1F2328'> </span><span
style='font-family:DengXian;color:#1F2328'>Γ</span><span style='font-family:
"Comic Sans MS";color:#1F2328'>λυτώνει πολύ χρόνο.</span></p>

<h1><img width=609 height=280
src="Arduino_smart_garbadge_monitoring_system_2023_Readme%20-%20Αντιγραφή.files/image005.png"
align=right hspace=12 vspace=5
alt="#include &lt;Software Serial.h&gt;   &#13;&#10;#include &lt;ESP8266WiFi.h&gt;&#13;&#10;#include &lt;ESP8266HTTPClient.h&gt;&#13;&#10;&#13;&#10;#define trigger D5&#13;&#10;#define echo D6     &#13;&#10;float times=0;&#13;&#10;int distance=0;&#13;&#10;// Replace with your network credentials&#13;&#10;const char* ssid     = &quot;muthu&quot;;&#13;&#10;const char* password = &quot;muthumuthu001&quot;;&#13;&#10;&#13;&#10;&#13;&#10;void setup() {&#13;&#10;  Serial.begin(115200);&#13;&#10;  Serial.print(&quot;Connecting to &quot;);&#13;&#10;  Serial.println(ssid);&#13;&#10;  pinMode(trigger,OUTPUT);&#13;&#10;  pinMode(echo,INPUT);&#13;&#10;  WiFi.begin(ssid, password);&#13;&#10;  while (WiFi.status() != WL_CONNECTED) {&#13;&#10;    delay(500);&#13;&#10;    Serial.print(&quot;.&quot;);&#13;&#10;  }&#13;&#10;  Serial.println(&quot;&quot;);&#13;&#10;  Serial.println(&quot;WiFi connected.&quot;);&#13;&#10;  Serial.println(&quot;IP address: &quot;);&#13;&#10;  Serial.println(WiFi.localIP());&#13;&#10;&#13;&#10;}&#13;&#10;&#13;&#10;&#13;&#10;void loop() {&#13;&#10;&#13;&#10;  digitalWrite(trigger,LOW);&#13;&#10; delayMicroseconds(2);&#13;&#10; digitalWrite(trigger,HIGH);&#13;&#10; delayMicroseconds(10);&#13;&#10; digitalWrite(trigger,LOW);&#13;&#10; delayMicroseconds(2);&#13;&#10; times=pulseIn(echo,HIGH);&#13;&#10; int distance=times*340/20000;&#13;&#10;&#13;&#10; //Serial.println(&quot;Distance:&quot;);&#13;&#10; Serial.println(distance);&#13;&#10; //Serial.println(&quot; cm&quot;);&#13;&#10;  if (WiFi.status() == WL_CONNECTED) { //Check WiFi connection status&#13;&#10; &#13;&#10;    HTTPClient http;  //Declare an object of class HTTPClient&#13;&#10;  &#13;&#10;    http.begin(&quot;http://192.168.43.204/ultrasonic/data.php?cm=&quot;+String(distance));  //Specify request destination&#13;&#10;    &#13;&#10;    int httpCode = http.GET();                                  //Send the request&#13;&#10;  &#13;&#10;    if (httpCode &gt; 0) { //Check the returning code&#13;&#10; &#13;&#10;      String payload = http.getString();   //Get the request response payload&#13;&#10;      Serial.println(payload);             //Print the response payload&#13;&#10; &#13;&#10;    }&#13;&#10; &#13;&#10;    http.end();   //Close connection&#13;&#10; &#13;&#10;  }&#13;&#10; &#13;&#10;  delay(1000);    //Send a request every 30 seconds&#13;&#10;}&#13;&#10;"><a
name="_Toc137899628">Κώδικας </a><span lang=EN-US>Arduino</span><span
lang=EN-US> </span><span lang=EN-US>IDE</span>   </h1>

<p class=MsoNormal><span style='font-size:12.0pt;line-height:107%'>&nbsp;</span></p>

<h1><a name="_Toc137899629">Μελλοντικές εξελίξεις</a> </h1>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";color:#1F2328'>Θα
θέλαμε πολύ το Project μας να δημοσιευτεί στον Δήμο Καλαμαριάς και σε άλλους
Δήμους φυσικά για να διευκολύνει όλους τους εργάτες που δουλεύουν στα
απορριμματοφόρα.</span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";color:#1F2328'>&nbsp;</span></p>

<h1><a name="_Toc137899630">Πλατφόρμες που χρησιμοποιήθηκαν</a></h1>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
36.0pt;text-indent:-18.0pt;background:white'><span style='font-family:Symbol;
color:#1F2328'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span lang=EN-US style='font-family:"Comic Sans MS";color:#1F2328'>Tinkerc</span><span
lang=EN-GB style='font-family:"Comic Sans MS";color:#1F2328'>ad</span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
36.0pt;text-indent:-18.0pt;background:white'><span style='font-family:Symbol;
color:#1F2328'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span lang=EN-US style='font-family:"Comic Sans MS";color:#1F2328'>Arduino
IDE</span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
36.0pt;text-indent:-18.0pt;background:white'><span style='font-family:Symbol;
color:#1F2328'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span lang=EN-US style='font-family:"Comic Sans MS";color:#1F2328'>Prezi</span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
36.0pt;text-indent:-18.0pt;background:white'><span style='font-family:Symbol;
color:#1F2328'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span lang=EN-US style='font-family:"Comic Sans MS";color:#1F2328'>Appinventor</span></p>

<h1><a name="_Toc137899631">Υλοποίηση</a></h1>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";color:#1F2328'>Η
συσκευή φτιάχτηκε συνδέοντας το </span><span lang=EN-US style='font-family:
"Comic Sans MS";color:#1F2328'>Arduino</span><span lang=EN-US style='font-family:
"Comic Sans MS";color:#1F2328'> </span><span style='font-family:"Comic Sans MS";
color:#1F2328'>με τον Αισθητήρα  </span><span lang=EN-US style='font-family:
"Comic Sans MS";color:#1F2328'>Ultrasonic</span><span lang=EN-US
style='font-family:"Comic Sans MS";color:#1F2328'> </span><span lang=EN-US
style='font-family:"Comic Sans MS";color:#1F2328'>sensor</span><span
lang=EN-US style='font-family:"Comic Sans MS";color:#1F2328'> </span><span
style='font-family:"Comic Sans MS";color:#1F2328'>και τα </span><span
lang=EN-US style='font-family:"Comic Sans MS";color:#1F2328'>LEDs</span><span
style='font-family:"Comic Sans MS";color:#1F2328'>. Στη συνέχεια τα βάλαμε όλα μέσα
στο κουτί και τα τοποθετήσαμε στον κάδο.</span></p>

<h1><a name="_Toc137899632">Φάση Δοκιμών</a></h1>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";color:#1F2328'>Όταν
το κύκλωμα ήταν έτοιμο έπρεπε να δούμε αν δούλευε. Όταν κάναμε τις δύο τρείς
πρώτες δοκιμές δεν ήμασταν και τόσο ευχαριστημένοι. Όμως αργότερα όταν έγιναν
κάποιες από αυτές είμασταν περισσότερο ευχαριστημένοι. Κάποια από τα λαμπάκια
μερικές φορές άναβαν ενώ κάποιες άλλες όχι. Όταν πήγαινες πολύ κοντά το
αντικείμενο, στον αισθητήρα,  τότε άναβε το κόκκινο λαμπάκι, αν το πήγαινες
λίγο πιο μακριά άναβε το μπλε, αν ήταν μακριά στο ένα μέτρο άναβε το πράσινο
και αν ήταν μακριά από ένα μέτρο τότε δεν άναβε κανένα λαμπάκι. </span></p>

<h1><a name="_Toc137899633">Συμπεράσματα</a> </h1>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";color:#1F2328'>Καταλάβαμε
πόσο δύσκολο ήταν να αναλαμβάνεις κάτι τόσο μεγάλο γιατί είμαστε ακόμα πολύ
μικροί για να το καταλάβουμε και δεν μπορούμε να φτιάξουμε ολόσωστα αυτό το </span><span
lang=EN-US style='font-family:"Comic Sans MS";color:#1F2328'>Project</span><span
style='font-family:"Comic Sans MS";color:#1F2328'>.</span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";color:#1F2328'>&nbsp;</span></p>

</div>

</body>

</html>

**ΕΙΣΑΓΩΓΗ**

Η διαδικασία της καθημερινής συλλογής των αστικών οικιακών απορριμμάτων στις μεγάλες κυρίως πόλεις, μπορεί να «κρύβει» μια σπατάλη ενέργειας που στην σημερινή εποχή της κλιματικής αλλαγής θα ήταν προτιμότερο να μπορούσαμε να την αποφύγουμε. Πιο συγκεκριμένα οι υπάλληλοι που χειρίζονται τα μηχανήματα αποκομιδής σκουπιδιών από τους γνωστούς μας κάδους, έχουν ένα καθημερινό δρομολόγιο μέσα στους δρόμους μιας μεγαλούπολης, με σκοπό να αδειάσουν τους «πιθανώς» γεμάτους κάδους από τα σκουπίδια. Ο σχεδιασμός της αποκομιδής, υποθέτει βάσει της πρότερης εμπειρίας τους, ότι είναι τόσο γεμάτοι ώστε να μην μπορεί να παραληφθούν για έστω και μία ημέρα , από τα μηχανήματα αποκομιδής. κατά την κυκλοφορία τους καθημερινά μέσα στην πόλη.

Είναι όμως ακριβώς έτσι; Αν για παράδειγμα κάποιοι κάδοι , από τους οποίους περνάνε τα μηχανήματα είναι μισοάδειοι και θα μπορούσαν να παραμείνουν μέχρι και την επόμενη ημέρα, για να αδειάσουν , τότε μήπως το μηχάνημα αποκομιδής σπατάλησε ενέργεια σε καύσιμα, χρόνο, ανθρωποώρες εργασίας από τους υπαλλήλους και τελικώς επιβάρυνε και την κυκλοφορία της πόλης; Επιπλέον αν κάποιοι κάδοι λόγω κάπου ειδικού και έκτακτου γεγονότος στην περιοχή, γέμισαν νωρίτερα από το «προβλεπόμενο» χρόνο, τότε αυτή η «αλάνθαστη» καθημερινή εμπειρία χρήσης δεν είναι τελικά η ενδεδειγμένη διαδικασία αποκομιδής απορριμμάτων μέσα σε μία πόλη;

**ΠΡΟΤΕΙΝΟΜΕΝΗ ΛΥΣΗ**

Η πιλοτική εφαρμογή που προτείνουμε να δημιουργήσαμε αποτελεί μια ιδέα που μπορεί να εξοικονομήσει ενέργεια κατά τη αποκομιδή και διαχείριση των οικιακών αποβλήτων αλλά και να δημιουργήσει ένα πιο φιλικό αστικό και βιώσιμο αστικό περιβάλλον, μειώνοντας την σπατάλη ενέργειας, τον θόρυβο, την επιβάρυνση του κυκλοφοριακού φόρτου της πόλης από την άσκοπη μετακίνηση μηχανημάτων αποκομιδής, όταν αυτό μπορεί να προβλεφθεί και να αποφευχθεί.

Αρχικά θα πρέπει πρώτα να εισάγουμε (ορίσουμε) το ύψος του κάδου απορριμμάτων. Αυτό θα μας βοηθήσει να υπολογίσουμε το ποσοστό των απορριμμάτων μέσα στον κάδο απορριμμάτων. Στη συνέχεια, έχουμε δύο κριτήρια που πρέπει να πληρούνται για να δείξουμε ότι ο συγκεκριμένος κάδος πρέπει να αδειάσει:

1.  Ας πούμε ότι εάν ο κάδος σας είναι μισογεμάτος, δεν χρειάζεται πραγματικά να τον αδειάσετε. Το σημείο πλήρωσης του κάδου, ή η μέγιστη ποσότητα απορριμμάτων που επιτρέπουμε, είναι το 75% του κάδου. (Μπορείτε να οριστεί ανάλογα με τις επιλογές του χρήστη.)
2.  Αν υποθέσουμε ότι ένας συγκεκριμένος κάδος απορριμμάτων γεμίζει 20% και μετά για μια εβδομάδα δεν αλλάζει, μπαίνει στο δεύτερο κριτήριό μας, ο χρόνος. Με τον καιρό, ακόμη και η μικρή ποσότητα θα αρχίσει να σαπίζει, οδηγώντας σε ένα δύσοσμο περιβάλλον. Για να αποφύγουμε το επίπεδο ανοχής μας να είναι 2 ημέρες, επομένως εάν ένας κάδος απορριμμάτων είναι μικρότερος από 75% αλλά είναι δύο ημερών, τότε θα πρέπει επίσης να αδειάσει.

**ΣΕΝΑΡΙΟ ΧΡΗΣΗΣ**

Ένας αισθητήρας υπερήχων (A.K.A ένας αισθητήρας απόστασης) θα τοποθετηθεί στην εσωτερική πλευρά του καπακιού, αυτή που βλέπει τα στερεά απόβλητα. Καθώς τα σκουπίδια αυξάνονται, η απόσταση μεταξύ του υπερήχου και του σκουπιδιού μειώνεται. Αυτά τα ζωντανά δεδομένα θα σταλούν στον μικροελεγκτή μας.

Στη συνέχεια, ο μικροελεγκτής μας επεξεργάζεται τα δεδομένα και μέσω της βοήθειας WiFi τα στέλνει σε μια εφαρμογή.

Αυτό που κάνει η εφαρμογή εμφανίζει οπτικά την ποσότητα των σκουπιδιών στον κάδο με μια μικρή κινούμενη εικόνα.

Αυτή η διαδικασία θα υποδείξει όλους τους κάδους που απαιτούν προσοχή, οδηγώντας τον χρήστη να ακολουθήσει την πιο αποτελεσματική διαδρομή.

 <img src="images/1.png" width="400"/>

 <img src="images/2.png" width="400"/>
 

Σε κάθε κάδο υπάρχει ένας αισθητήρας Ultrasonic Distance Sensor, ο οποίος βλέπει γεμάτος είναι ο κάδος. Ανάλογα με το πόσο γεμάτος είναι (%) ο μικροελεγκτής Arduino στέλνει αντίστοιχο μήνυμα μέσω Wi-Fi στην εφαρμογή.

**ΥΛΙΚΑ**

|  **ΕΊΔΟΣ**                    | **ΠΟΣΟΤΗΤΑ**|
|-------------------------------|-------------| 
| Arduino UNO R3 SMD            |     5       |
| Base Shield V2                |     5       |
| Ultrasonic Distance Sensor    |     5       |
| Arduino MKR1000               |     5       |
| 9V Battery Clip (With On/Off) |     5       |
| Jumper Wires 40pcs            |     5       |
| Slide Switch (X2)             |     5       |
