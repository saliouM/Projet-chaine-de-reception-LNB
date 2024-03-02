# Projet d'Étude et Simulation d'une Chaîne de Réception LNB sous Advanced Design System (ADS)

Bienvenue dans notre projet dédié à l'étude et à la simulation d'une chaîne de réception de LNB (Low Noise Block) sous Advanced Design System (ADS), un logiciel de conception électronique avancé développé par Keysight Technologies.

## À propos de ADS :
ADS est une plateforme complète et intégrée conçue pour la conception, la simulation et la vérification de circuits électroniques analogiques et radiofréquences. C'est l'outil privilégié des ingénieurs et des concepteurs de circuits électroniques pour sa puissance et ses fonctionnalités avancées.

## Partie Étude : La Chaîne de Réception Typique (LNB)

Le convertisseur de bloc à faible bruit (LNB) a été inventé par deux technologues chinois en microélectronique, KUO TIEN CHANG et JIA LUN CHEN. Les différents modes de réalisation de cette invention comprennent un oscillateur local, un mélangeur, un amplificateur FI, et un régulateur. Ces composants travaillent ensemble pour amplifier et traiter les signaux reçus en bande haute, assurant une transmission de qualité.

Pour plus de détails sur l'étude, veuillez consulter le rapport complet dans ce repository.

## Partie Simulation

### Composants Utilisés sous ADS :
- P_1Tone (Power Source, Single Frequency)
- Filtre BPF_Butterworth (Butterworth Bandpass Filter)
- Amplificateur LNA (Low Noise Amplifier)
- Mixer
- Oscillateur V_1Tone
- Résistance Term
- Simulateur S-Parameters
- Filtre LPF_Bessel (situé à la sortie du mélangeur)

### Simulation 1 : Simulation des Paramètres d'Impédance et Gain

Cette simulation vise à caractériser le comportement des composants à travers leurs paramètres S (paramètres de diffusion) à différentes fréquences. L'analyse du coefficient de réflexion S22 et du coefficient de transmission S21 permet d'optimiser le transfert de puissance et de minimiser les pertes de signal.

### Simulation 2 : Simulation du Niveau de Bruit dans la LNB

Cette simulation évalue le niveau de bruit à l'entrée et à la sortie du bloc LNB, prenant en compte les conditions de bruit dans le bloc. La réponse en fréquence obtenue montre le rôle crucial du LNB dans la minimisation du bruit pour assurer une transmission de qualité.

Pour des détails approfondis sur les simulations, veuillez vous référer au rapport complet dans ce repository.

**Note :** Pour plus de détails sur l'étude et la simulation de ce projet, vous pouvez consulter le rapport complet ci-dessus dans ce repository.
