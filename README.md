# aneuraz.github.io

Sert `.well-known/apple-app-site-association` pour l'association de domaine
Apple (WebAuthn / passkeys).

Le fichier autorise l'application `com.aneuraz.prfprobe` — une sonde jetable
qui mesure si l'extension PRF rend des octets déterministes, dans le cadre du
choix d'architecture des applications clientes du projet `rdv`.

Deux pages de test du mode hébergé de `rdv`, sans donnée réelle, à retirer
après mesure :

- `rdv-prf-probe/` : l'extension PRF dans un navigateur ;
- `rdv-wasm-spike/` : le cœur patient compilé en WASM (aléa, pseudonyme,
  HPKE, débit du PoW).
