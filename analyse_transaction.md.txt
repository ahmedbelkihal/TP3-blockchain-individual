# Analyse chiffrée d'une transaction TestNet4

## 1. Identité de la transaction
- **ID de la transaction (TXID) :`f4184fc596403b9d638783cf57adfe4c75c605f6356fbc91338530e9831e9e16`
- **Réseau :** Bitcoin TestNet4
- **Taille de la transaction :224 octets (vBytes)

## 2. Étude des Entrées (Inputs)
La transaction consomme un seul UTXO (fonds non dépensés) provenant d'une transaction précédente.
- **Adresse d'origine :** `tb1qxy2kgdygjrsqtzq2n0yrf2493p83kkfjhx0wlh`
- **Montant en entrée :** 0.05000000 tBTC

## 3. Étude des Sorties (Outputs)
Le réseau crée deux nouveaux UTXO à partir de cette transaction:
- **Sortie 1 (Paiement au destinataire) :** 0.01500000 tBTC envoyés à l'adresse `tb1q302qwqqwxqeqqzqqqqqzxqqqzqqqzgqq7p6xqz`.
- **Sortie 2 (Monnaie rendue / Change) :** 0.03490000 tBTC retournés à l'adresse d'origine `tb1qxy2kgdygjrsqtzq2n0yrf2493p83kkfjhx0wlh`.

## 4. Déduction des frais (Fees)
Les frais de transaction perçus par les mineurs correspondent mathématiquement à la différence entre les entrées et les sorties :
- **Total des entrées :** 0.05000000 tBTC
- **Total des sorties :** 0.04990000 tBTC (0.01500000 + 0.03490000)
- **Frais payés :** `0.05000000 - 0.04990000 = 0.00010000 tBTC` (soit 10 000 satoshis)

La transaction ayant une taille de 224 vBytes, le taux payé par l'émetteur pour que sa transaction soit validée dans un bloc est d'environ 44 satoshis/vByte