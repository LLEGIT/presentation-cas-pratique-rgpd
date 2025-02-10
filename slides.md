---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://www.usinenouvelle.com/mediatheque/0/2/0/000167020_896x598_c.JPG
# some information about your slides (markdown enabled)
title: Présentation RGPD
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
---

<div class="flex flex-col items-top justify-top">
  <h1>Cas pratique RGPD</h1>
  <h2>Candidature au poste de développeur logiciel et DPO</h2>
</div>

<p class="absolute bottom-2 right-2">
  Dorian Jaguenaud, Théo Gillet
</p>


---
transition: fade-out
level: 1
---

# Rappel du contexte

<div class="grid grid-cols-2 gap-4">
  <ul>
    <h4>✓ Contexte entreprise :</h4>
    <ul>
      <li>15 salariés</li>
      <li>Gestion de paie</li>
      <li>Vidéosurveillance</li>
      <li>Prospection LinkedIn</li>
    </ul>
  </ul>

  <ul>
    <h4>✓ Données à protéger :</h4>
    <ul>
      <li>Données des employés</li>
      <li>Données clients</li>
      <li>Données de paie</li>
      <li>Images vidéosurveillance</li>
      <li>Données professionnelles LinkedIn</li>
    </ul>
  </ul>

  <ul>
    <h4>✓ Poste à pourvoir :</h4>
    <ul>
      <li>Développeur logiciel paie</li>
      <li>DPO</li>
      <li>Maintenance</li>
    </ul>
  </ul>

  <ul>
    <h4>✓ Mission principale :</h4>
    <ul>
      <li>Mise en conformité RGPD</li>
      <li>Protection des données</li>
      <li>Prévention des sanctions</li>
    </ul>
  </ul>
</div>

---
transition: fade-out
level: 2
---

# Qui sommes nous ?

<img width=500 height=500 src="https://www.numerama.com/wp-content/uploads/2025/01/Video-Pierre.webp">

- Pierre chabrier, 30 ans
- 🧑‍💻 **Développeur backend** - orienté C++ depuis plus de 10 ans
- 🛠 **Skills** - Mise en place d'architecture logiciel, base de données. Dispense des formations aux entreprises sur les bonnes pratiques RGPD 

<!--
Here is another comment.
-->

---
transition: slide-up
level: 2
---

# Que pouvons nous apporter à l'entreprise ?

- Contribuer efficacement à la maintenance du logiciel de paie.  
- Définir une stratégie robuste de protection des Données à Caractère Personnel (DCP), particulièrement cruciales dans le contexte d'un système de paie.
## Apporter une vision holistique, combinant :
- La compréhension approfondie des enjeux techniques du développement logiciel
- La maîtrise des exigences réglementaires du RGPD
- La capacité à traduire les obligations légales en solutions techniques concrètes
- L'expérience dans la sensibilisation et la formation des équipes

---
transition: fade-out
level: 3
---

# Définition des données à protéger

<img width=300 height=300 src="https://planonsoftware.com/upload_mm/2/3/9/4719_fullimage_20210309-image-dataanalytics-magnifieroverview-high-3000x1987_360x250_1447x1132_progr.jpg">

- Données des clients : Identité des salariés, bulletins de salaire, contrats de travail, fin de contrat, paiement URSSAF.
- Données des employés de la société DUPONT : Informations personnelles, contrats, paie.
- Données issues de la vidéosurveillance : Images des employés et visiteurs.
- Données marketing : Informations collectées via LinkedIn et autres réseaux sociaux.

---
transition: slide-up
level: 4
---

# Rappel des principes clés du RGPD

<img width=200 height=200 src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSuXLGlIm1dCrGcET1I9SewZizkd-u-VXOe1g&s">

- Licéité, loyauté et transparence 
- Limitation des finalités
- Minimisation des données
- Exactitude des données
- Conservation limitée
- Sécurité et intégrité
- Responsabilisation (Accountability)

---
transition: slide-down
level: 5
---

# Risques et sanctions en cas de non conformité

<img width=400 src="https://img.lemde.fr/2024/10/28/0/0/6240/4160/664/0/75/0/010b6d4_1730111490482-rev-1-jr2-06412r-1-high-res-jpeg.jpeg">

- Sanctions financières pouvant aller jusqu'à 4% du chiffre d'affaires annuel.
- Atteinte à la réputation de l'entreprise.
- Risques juridiques en cas de plainte d'un employé ou d'un client.
- Perte de confiance des clients et partenaires.

---
transition: fade-out
level: 6
---

# Constat

<img width=500 height=300 src="https://www.deshoulieres-avocats.com/wp-content/uploads/2022/12/AdobeStock_204894616.jpg">

L'entreprise Dupont doit recruter un DPO en raison du traitement de données sensibles (paie, données collaborateurs et clients). Une mise en conformité est nécessaire, particulièrement au niveau de l'infrastructure réseau, avec le déploiement d'éléments de sécurité comme des pare-feu nouvelle génération, connexions SSH, segmentation réseau, VPN et surveillance du trafic.

---
transition: fade-out
level: 7
---

# Applicatif et développement 

<div class="flex justify-center">
  <img class="rounded-lg" width=300 src="https://www.apixit.fr/wp-content/uploads/2022/02/APIXIT-cybersecurite-SASE-SSE-1024x585.jpg">
</div>

- Chiffrement systématique des données sensibles en base de données
- Utilisation d'un gestionnaire de secrets sécurisé (comme HashiCorp Vault) pour la gestion des informations sensibles
- Mise en place d'une politique de gestion des droits d'accès stricte
- Audit régulier du code et des configurations de sécurité
- Journalisation des accès aux données sensibles

---
transition: fade-out
level: 8
---

# Organisationnel et humain

<div class="flex items-center p-3 gap-x-2">
  <ul>
    <li>Élaboration d'un programme de formation continue à la cybersécurité</li>
    <li>Sensibilisation aux bonnes pratiques quotidiennes </li>
    <li>Verrouillage systématique des postes de travail lors des absences</li>
    <li>Vigilance accrue face aux tentatives de phishing</li>
    <li>Identification des outils et services en ligne autorisés</li>
    <li>Signature d'une décharge autorisant l'enregistrement de vidéo surveillance</li>
    <li>Mise en place de procédures d'incident et de gestion de crise</li>
  </ul>
  <img width=400 height=200 src="https://www.petite-entreprise.net/wp-content/uploads/2021/11/structure-entreprise-12-768x512.png">
</div>

---
transition: slide-left
level: 9
---

# Bilan

✓ Attention aux usages quotidiens à risque (ex: convertisseurs de fichiers en ligne non validés)

✓ Nécessité de fournir des outils sécurisés approuvés par l'IT

✓ Le DPO assurera :
- La conformité réglementaire 
- Le développement d'une culture de protection des données

✓ Objectifs : 
- Renforcer la confiance client
- Protéger les actifs informationnels
