# Climate-risk-modeliling-ORSA
Modèle ORSA climatique complet sous Solvabilité II : SCR Marché, Non-Vie, Vie, Contrepartie, Monte-Carlo, scénarios IPCC (SSP). Interface VBA, moteur actuariel, documentation scientifique (EIOPA + AR6).

📘 Projet ORSA Climatique — Modèle Actuariel sous Solvabilité II

Ce dépôt contient une application complète permettant de modéliser l’impact du changement climatique sur la solvabilité d’un assureur non-vie, selon les lignes directrices de l’EIOPA et les scénarios scientifiques du GIEC (IPCC AR6).

Le projet inclut :

🧮 Un modèle VBA/Excel entièrement fonctionnel

🎛 Une interface utilisateur (UserForm) pour saisir les données

📊 Le calcul du SCR détaillé par module (marché, non-vie, vie, contrepartie, opérationnel)

🌍 Trois scénarios climatiques (Modéré, Sévère, Extrême)

🔁 Un module Monte-Carlo climatique (2000 simulations)

📈 Des graphiques comparatifs

📄 Un export automatique en PDF

📚 Une documentation scientifique complète (LaTeX + PDF)

🔧 Fonctionnalités principales
1. Calcul du SCR Marché

Taux (stress EIOPA)

Spread (migration de notation AA→A)

Actions (stress proportionnel)

Immobilier (dévalorisation)

2. Calcul du SCR Non-Vie

Loi Gamma pour modéliser sinistres historiques

Projection climatique (+3 %, +5 %, +8 %)

Catastrophes naturelles (inondation, sécheresse, tempête, autres)

Agrégation quadratique

3. Agrégation Solvabilité II

Matrice de corrélation EIOPA

Calcul du BSCR

Ratio de solvabilité

4. Simulation Monte-Carlo climatique

Variabilité : croissance sinistres, taux, spread, actions

2000 simulations

Intervalle de confiance

Bande d’incertitude

5. Export PDF

Résultats

Graphiques

Commentaires actuariaux

Explication méthodologique
