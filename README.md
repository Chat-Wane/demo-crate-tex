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

## Available at (TODO)

<ul>
  <li>[HAL]</li>
</ul>

## BibTeX (TODO)

## Acknowledgments

This work was partially funded by the French ANR project SocioPlug
([ANR-13-INFR-0003](http://www.agence-nationale-recherche.fr/?Projet=ANR-13-INFR-0003)),
and by the DeSceNt project granted by the Labex CominLabs excellence laboratory
([ANR-10-LABX-07-01](http://www.descent.cominlabs.ueb.eu/fr)).

Experiments presented in this paper were carried out using the Grid'5000
testbed, supported by a scientific interest group hosted by Inria and including
CNRS, RENATER and several Universities as well as other organizations (see
[official website](https://www.grid5000.fr)).