# Geneva (city): law history in git

The municipal law of the city of Geneva (Ville de Genève, canton of Geneva, Switzerland) as a git history: one file per article, one paragraph per line, so `git blame`, `git log` and `git diff` work line by line.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law). The law of the canton of Geneva is in [lexifina/switzerland-geneva-law](https://github.com/lexifina/switzerland-geneva-law); federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in French, exactly as the city publishes it.

## What this repository holds

51 acts with 51 versions so far: the règlement of the municipal council first, then the city's other règlements, tariffs and similar enactments in force, in the order of the collection, in parts of about 50. Directives, instructions, general conditions and charters are not included.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `21111/` | Règlement du Conseil municipal de la Ville de Genève (21111) | 1 | current text only, as at 28 January 2026 |
| `21121/` | Règlement du Conseil administratif de la Ville de Genève (21121) | 1 | current text only, as at 1 September 2024 |
| `21122/` | Règlement concernant le traitement et la retraite des membres du Conseil administratif (21122) | 1 | current text only, as at 1 June 2020 |
| `21122-1/` | Règlement d'application du règlement concernant le traitement et la retraite des membres du Conseil administratif (21122.1) | 1 | current text only, as at 1 January 2022 |
| `21131/` | Règlement de la salle de consultation des Archives de la Ville de Genève (21131) | 1 | current text only, as at 1 November 2021 |
| `21135/` | Règlement relatif au Comité de direction (CODIR) (21135) | 1 | current text only, as at 16 May 2019 |
| `21136/` | Règlement relatif à l'organisation et à la surveillance des fondations et établissements de droit public communal (21136) | 1 | current text only, as at 6 November 2025 |
| `21152-0/` | Règlement d'application du statut du personnel de la Ville de Genève (REGAP) (21152.0) | 1 | current text only, as at 1 May 2025 |
| `21152-1/` | Règlement relatif aux droits de propriété intellectuelle dans l'administration municipale (21152.1) | 1 | current text only, as at 1 April 2019 |
| `21152-10/` | Règlement de la commission du personnel interne des Musées d'art et d'histoire (21152.10) | 1 | current text only, as at 1 February 2012 |
| `21152-11/` | Règlement de la commission du personnel interne du service de la petite enfance (21152.11) | 1 | current text only, as at 22 June 2026 |
| `21152-15/` | Règlement relatif à la rémunération du personnel assurant la mise à disposition des locaux de vote dans les écoles primaires de la Ville de Genève (21152.15) | 1 | current text only, as at 1 January 2021 |
| `21152-16/` | Règlement sur les frais professionnels des membres du personnel (21152.16) | 1 | current text only, as at 1 October 2026 |
| `21152-18/` | Règlement sur les indemnités et les congés spéciaux du personnel de la Division de la voirie (21152.18) | 1 | current text only, as at 1 January 2023 |
| `21152-21/` | Règlement pour la réalisation de l'égalité entre femmes et hommes au sein de l'administration municipale (21152.21) | 1 | current text only, as at 4 March 2021 |
| `21152-22/` | Règlement sur les inconvénients de service horaires (21152.22) | 1 | current text only, as at 1 January 2023 |
| `21152-35/` | Règlement sur la protection de la santé et la sécurité du travail (21152.35) | 1 | current text only, as at 1 March 2025 |
| `21152-43/` | Règlement sur l'aménagement du temps de travail planifié du service Voirie - Ville propre (21152.43) | 1 | current text only, as at 1 February 2025 |
| `21152-5/` | Règlement relatif aux conditions d'engagement de l'apprenti et l'apprentie (21152.5) | 1 | current text only, as at 1 July 2023 |
| `21152-6/` | Règlement relatif aux conditions d'engagement du ou de la stagiaire (21152.6) | 1 | current text only, as at 20 September 2021 |
| `21152-7/` | Règlement relatif aux conditions d'engagement de l'auxiliaire (21152.7) | 1 | current text only, as at 20 September 2021 |
| `21152-8/` | Règlement sur les allocations pour enfants (21152.8) | 1 | current text only, as at 1 March 2019 |
| `21152-9/` | Règlement de la commission des personnels du Grand Théâtre de Genève (21152.9) | 1 | current text only, as at 21 November 2012 |
| `21153-11/` | Règlement sur la libération de l'obligation de travailler pour les fonctions particulièrement pénibles (21153.11) | 1 | current text only, as at 19 April 2024 |
| `21153-2/` | Règlement d'élection des représentants des assurés de la Ville de Genève au Comité de gestion de la CAP (21153.2) | 1 | current text only, as at 1 April 2019 |
| `21153-3/` | Règlement de la CPI « Ville de Genève et les autres communes genevoises » relatif au financement et à la garantie de la prévoyance (21153.3) | 1 | current text only, as at 1 January 2014 |
| `21153-7/` | Règlement du Fonds pour le versement d'une indemnité au décès (21153.7) | 1 | current text only, as at 1 January 2022 |
| `21154-1/` | Règlement régissant l'attribution des places de stationnement sur le domaine privé de la Ville de Genève (21154.1) | 1 | current text only, as at 1 March 2024 |
| `21154-2/` | Règlement fixant les conditions de location des logements de fonction de la Ville de Genève (21154.2) | 1 | current text only, as at 15 December 2007 |
| `21181/` | Règlement du programme d'encouragement à l'innovation sociétale « G'innove » (21181) | 1 | current text only, as at 1 January 2016 |
| `21191/` | Règlement relatif au service du contrôle financier, à l'audit interne et à la révision des comptes annuels (21191) | 1 | current text only, as at 26 April 2023 |
| `21195/` | Règlement régissant les conditions d'octroi des subventions municipales (21195) | 1 | current text only, as at 1 August 2023 |
| `21214/` | Règlement sur l'aménagement des chemins publics pour piétons sur fonds privés (21214) | 1 | current text only, as at 1 June 2020 |
| `21221/` | Règlement du Fonds de responsabilité solidaire pour les marchés publics de la Ville de Genève (21221) | 1 | current text only, as at 18 March 2016 |
| `21221-1/` | Règlement d'application du Fonds de responsabilité solidaire pour les marchés publics de la Ville de Genève (21221.1) | 1 | current text only, as at 1 June 2020 |
| `21222/` | Règlement relatif à l'indemnisation des commerces de la rue de Carouge impactés par les travaux (21222) | 1 | current text only, as at 1 October 2025 |
| `21252/` | Règlement du Fonds municipal Post Tenebras Lux (21252) | 1 | current text only, as at 1 June 2020 |
| `21253-1/` | Règlement d'application du Fonds municipal d'art contemporain (RA-FMAC) (21253.1) | 1 | current text only, as at 28 April 2022 |
| `21311/` | Règlement concernant les fêtes foraines (21311) | 1 | current text only, as at 1 February 1981 |
| `21314/` | Règlement sur les terrasses d'établissements publics (21314) | 1 | current text only, as at 19 November 2025 |
| `21316-4/` | Règlement de la plage des Eaux-Vives (21316.4) | 1 | current text only, as at 1 November 2022 |
| `21316-5/` | Règlement général des Bains du Jet d'eau (21316.5) | 1 | current text only, as at 27 June 2024 |
| `21331/` | Règlement des espaces verts, préaux et places de jeux de la Ville de Genève (21331) | 1 | current text only, as at 1 June 2020 |
| `21333/` | Règlement du Fonds Thérèse de Francia de la Ville de Genève (21333) | 1 | current text only, as at 19 December 2018 |
| `21351-2/` | Règlement des infrastructures funéraires de la Ville de Genève (21351.2) | 1 | current text only, as at 1 January 2013 |
| `21351-3/` | Règlement relatif à l'exercice d'une industrie dans les cimetières de la Ville de Genève (21351.3) | 1 | current text only, as at 1 January 2013 |
| `21372/` | Règlement relatif à la mise à disposition du matériel de fêtes (21372) | 1 | current text only, as at 1 June 2020 |
| `21374/` | Règlement fixant les conditions d'adjudication des concessions de service public (21374) | 1 | current text only, as at 16 June 2021 |
| `21375/` | Règlement fixant les conditions de location des salles et locaux des musées du département de la culture et de la transition numérique (DCTN) (21375) | 1 | current text only, as at 1 June 2020 |
| `21411/` | Règlement de la police municipale (21411) | 1 | current text only, as at 19 March 2019 |
| `21431/` | Règlement du corps des sapeurs-pompiers volontaires de la Ville de Genève (21431) | 1 | current text only, as at 1 December 2012 |

## Source

The Règlements de la Ville de Genève (LC 21), published by the city at <https://www.geneve.ch/autorites-administration/administration-municipale/reglements-municipaux>: the current text of each act as one PDF, with the date it was adopted, its entry into force and the date the text is current as at ("Etat au").

## Dates

- The collection holds only the current text, so each act has one version: the "oldest version available", dated at **noon, Europe/Zurich**, on the "Etat au" date printed on its PDF (or, without one, the collection's "En vigueur depuis le" date), and credited to the publisher. Earlier wording is not held.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5, `art-005a.md` Art. 5a; `ingress.md` holds the title and date block; `gliederung.md` the headings of titles and chapters; `schluss.md` the closing formula, the signatures and the notes on later modifications the PDF prints after the articles. One paragraph or list item per line.

## How it is checked

- Every act is read back from git (`tools/check_repo.py`) and must match `corpus.json`.
- The letters and digits of every act equal those of a second, independent reader of the same PDF (poppler pdftotext, running footers removed), and every article's text appears in it.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of each act's commit is the publisher (Ville de Genève), because the text is the current consolidation rather than the act as adopted, with an e-mail address that cannot exist. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the city publishes as binding. Only the current wording is held, and only the acts listed above are included.
