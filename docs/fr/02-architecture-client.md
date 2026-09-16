# 2. Architecture du client

L’arborescence sépare notamment chain, core, runtime, network, storage, state-sync, neard et les outils associés. Cette séparation permet de relier consensus, état, synchronisation et exposition des API.

Pour une DApp, le point important est le cycle lecture-écriture : soumettre une transaction, attendre son inclusion, puis lire l’état final auprès d’un nœud.

[Chapitre suivant : smart contracts et SDK](03-smart-contracts-sdk.md)
