# Calculateur DESP 2014/68/UE

Outil web de classification des équipements sous pression selon la directive européenne 2014/68/UE.

## Accès direct

** [Utiliser le calculateur](https://mauricemendy.github.io/desp-calculator/)**

---

## À propos

Le calculateur DESP permet de déterminer rapidement et précisément la catégorie réglementaire d'un équipement sous pression (récipient ou tuyauterie) en fonction de :

- **Type d'équipement** : Récipient ou Tuyauterie
- **Type de fluide** : Gaz ou Liquide  
- **Groupe de fluide** : Groupe 1 (dangereux) ou Groupe 2 (non dangereux)
- **Paramètres techniques** : PS (pression), V (volume), DN (dimension nominale)
- **Cas particuliers** : Gaz instables, extincteurs, haute température, etc.

Le résultat indique la catégorie applicable (Article 4§3, Catégorie I, II, III ou IV) et le tableau réglementaire utilisé.

---

## Fonctionnalités

- ✅ **Interface intuitive** : Navigation guidée en 5 étapes
- ✅ **Calcul en temps réel** : PS×V ou PS×DN affiché instantanément
- ✅ **Aperçu permanent** : Panel droit avec résumé de la configuration
- ✅ **Sauvegarde automatique** : Reprise du calcul après fermeture (localStorage)
- ✅ **Export PDF** : Génération d'un rapport complet
- ✅ **Navigation clavier** : Support complet (Enter, Tab)
- ✅ **Validation intelligente** : Alertes pour valeurs inhabituelles
- ✅ **Responsive design** : Adapté mobile, tablette et desktop
- ✅ **Court-circuit** : Détection immédiate des équipements non soumis

---

## Technologies

- **Frontend** : HTML5, CSS3, JavaScript ES6+
- **Typographie** : Inter (Google Fonts)
- **Export** : jsPDF 2.5.1
- **Stockage** : localStorage API
- **Hébergement** : GitHub Pages

---

## Tables réglementaires implémentées

- ✅ **Table 1** : Récipients / Gaz / Groupe 2
- ✅ **Table 2** : Récipients / Gaz / Groupe 1
- ✅ **Table 3** : Récipients / Liquide / Groupe 2
- ✅ **Table 4** : Récipients / Liquide / Groupe 1
- ✅ **Table 6** : Tuyauteries / Gaz / Groupe 2
- ✅ **Table 7** : Tuyauteries / Gaz / Groupe 1
- ✅ **Table 8** : Tuyauteries / Liquide / Groupe 2
- ✅ **Table 9** : Tuyauteries / Liquide / Groupe 1

---

## Utilisation

1. Sélectionnez le **type d'équipement** (Récipient ou Tuyauterie)
2. Choisissez le **type de fluide** (Gaz ou Liquide)
3. Indiquez le **groupe de fluide** (Groupe 1 ou 2)
4. Renseignez les **paramètres techniques** (PS, V ou DN)
5. Cochez les **cas particuliers** éventuels
6. Consultez le **résultat** et exportez en PDF si nécessaire

---

## Conformité réglementaire

Cet outil implémente les règles de classification définies dans :
- **Directive 2014/68/UE** du Parlement européen
- **Annexe II** - Tableaux de classification

**Note** : Cet outil est fourni à titre indicatif. Pour une classification officielle, consultez toujours la directive complète et un organisme notifié.

---

## Liens utiles

- [Blog](https://mauricemendy.com)
- [LinkedIn](https://linkedin.com/in/mauricemendy)
- [Directive DESP 2014/68/UE](https://eur-lex.europa.eu/legal-content/FR/TXT/?uri=CELEX:32014L0068)

---

## Licence

© 2024 Maurice Mendy - Tous droits réservés

---

## Contact

Des questions ou suggestions ? N'hésitez pas à :
- Ouvrir une [issue](https://github.com/mauricemendy/desp-calculator/issues)
- Me contacter via [LinkedIn](https://linkedin.com/in/mauricemendy)
- Consulter mon [blog](https://mauricemendy.com)
