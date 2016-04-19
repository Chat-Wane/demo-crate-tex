# CRATE: Writing Stories Together with our Browsers

<i>Keywords: Collaborative editor, decentralized, real-time</i>

<i>Authors: Brice Nédelec, Pascal Molli, Achour Mostefaoui</i>


Real-time collaborative editors are common tools to distribute work across
space, time, and organizations. Unfortunately, mainstream editors such as Google
Docs rely on central servers and raises privacy and scalability issues.
[CRATE](https://github.com/Chat-Wane/CRATE) is a real-time decentralized
collaborative editor that runs directly in web browsers thanks to
WebRTC. Compared to state-of-the-art, CRATE is the first real-time editor that
only requires browsers in order to support collaborative editing and to
transparently handle from small to large groups of users. Consequently, CRATE
can also be used in massive online lectures, TV shows or large conferences to
allow users to share their notes. CRATE's properties rely on two scientific
results: (i) a [replicated sequence](https://github.com/Chat-Wane/LSEQTree)
structure with sub-linear upper bound on space complexity; this prevents the
editor from running costly distributed garbage collectors, (ii) an [adaptive
peer sampling protocol](https://github.com/Chat-Wane/spray-wrtc); this prevent
the editor from oversizing routing tables, hence from letting small networks pay
the price of large networks.  This paper describes CRATE, its properties and its
usage.

## Available at

<ul>
  <li>[proceedings](http://www2016.net/proceedings/companion/p231.pdf)</li>
  <li>[ACM](http://dl.acm.org/citation.cfm?id=2890539)</li>
  <li>[HAL](https://hal.archives-ouvertes.fr/hal-01303333)</li>
</ul>

## BibTeX

```
@inproceedings{nedelec2016crate,
  author = {N{\'e}delec, Brice and Molli, Pascal and Mostefaoui, Achour},
  title = {CRATE: Writing Stories Together with Our Browsers},  
  booktitle = {Proceedings of the 25th International Conference Companion on
  World Wide Web},
  series = {WWW '16 Companion},
  year = {2016},
  isbn = {978-1-4503-4144-8},
  location = {Montr{\'e}al, Qu{\'e}bec, Canada},
  pages = {231--234},
  numpages = {4},
  url = {http://dx.doi.org/10.1145/2872518.2890539},
  doi = {10.1145/2872518.2890539},
  acmid = {2890539},
  publisher = {International World Wide Web Conferences Steering Committee},
  address = {Republic and Canton of Geneva, Switzerland},
  keywords = {collaborative editor, decentralized, real-time},
} 
```

## Acknowledgments

This work was partially funded by the French ANR project SocioPlug
([ANR-13-INFR-0003](http://www.agence-nationale-recherche.fr/?Projet=ANR-13-INFR-0003)),
and by the DeSceNt project granted by the Labex CominLabs excellence laboratory
([ANR-10-LABX-07-01](http://www.descent.cominlabs.ueb.eu/fr)).

Experiments presented in this paper were carried out using the Grid'5000
testbed, supported by a scientific interest group hosted by Inria and including
CNRS, RENATER and several Universities as well as other organizations (see
[official website](https://www.grid5000.fr)).