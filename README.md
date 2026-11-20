# Mon Journal de veille

[google](https.//google.com)
[mdn](https://mdn.com)

## 30/10/2026 - Sécurité de l'Authentifiaction (Site de l'ANSSI)

- **source** : Site gouvernemental de l'ANSSI : https://messervices.cyber.gouv.fr/guides/recommandations-relatives-lauthentification-multifacteur-et-aux-mots-de-passe

**Ce que j'ai appris** :
    **Quels buts** :
        - Analyser les risques lors de la mise en place de l'authentification
        - Privilégier les authentificatitions multifacteurs (double authentifiaction)
        - Privilégier les moyens d'authenfication possédés (e-mail, numéro de téléphones)
        - Adapter la robustesse des mots de passes
        - AVoir un coffre-fort pour stocker les mots de passes
    **Ce qu'il faut faire** :
        - Mémoriser le mot de passe
        - utiliser des mots de passe long (au moins 15 caractère pour un mot de passe fort)
        - Mélanger lettres minuscules, majuscules, chiffres et caractères spéciaux
        - changer régulièrement de mot de passe (tous les 3 à 6 mois)
            - Le changement de mot de passe est à imposer au comptes sensibles
              qui ont des accès à des données ou des fonctionnalités (administrateurs).

**Pourquoi c'est utile en tant que développeur web ?** :
        - La sécurité d'un site, de ses utilisateurs et de son infrastructure, et il faut
          prendre le moins de risques possibles cela passe par des systèmes
          d'authentification robustes.

**Ce que je vais faire et vérifier** : 
        - Garder les mots de passes soit dans ma tête, soit dans un coffre-fort
        - Essayer de modifier régulièrement les mots de passe de mes comptes
        - Suivre les recommandations et créer des mots de passes long et robustes

## 13/11/2026 - Widely available et Newly available : quelle différence ?

**Source: https://developer.mozilla.org/en-US/docs/Glossary/Baseline/Compatibility**

**Ce que j'ai appris**
- Les fonctionnalités répertoriées comme étant largement disponibles bénéficient d'un historique de prise en charge constant dans chacun des navigateurs de référence depuis au moins deux ans et demi.
- Newly avaliable est basée sur la dernière version stable il est possible que cela ne fonctionne pas sur les appareils plus anciens

**Ce qu'il faut faire**

-Vérifier si la fonctionnalité est disponible depuis longtemps sur le navigateur
- Sinon vérifier si la fonctionnalité fonctionne sur l'appareil (à sa dernière version stable)
- Dégager si déprécié

**Pourquoi est-ce utile en tant que développeur**

C'est important de se renseigner sur l'évolution des fonctionnalités (à jour, déprécié etc...)

**Ce que je vais faire et vérifier**

Je doit continuer à vérifier l'évolution des fonctionnalités si accessible ou pas.

# 20/11/2026 : toSorted() sur le site de TC39

**Ce que j'ai appris**

nom : Change Array by Copy

Dans la liste des proposition toSorted() à été accepté dans le but de copier un tableau sans le copier
en même temps que toReverse() et toSplice()

Accepté en 2023

le TC39 est le comité technique d’Ecma International qui fait évoluer ECMAScript ; une proposition passe par des étapes (stages) de 0 à 4 ; au stage 4, elle est terminée et entre dans la norme de l’année.

**Ce qu'il faut faire**

Vérifier l'évolution du code, des fonctions qui peuvent être ajoutées comme toSorted() de faire de la logique métier et de simplifier le code (au lieu de faire cinq lignes de code n'avoir qu'une fonction oare exemple)

**Pourquoi est-ce utile en tant que développeur**

Il faut se renseigner car le code évolue en permanence, des functions peuvent devenir obsolète et être remplacées par de nouvelles function ou déclaration comme var en JS qui n'est plus utilisé on utilise let pour des variables modifiables ou const pour des variables permanentes

**Ce que je vais faire et vérifier**

Regarder sur les sites de W3C ou de TC39 l'évolution des languages de programmation que j'utilise.