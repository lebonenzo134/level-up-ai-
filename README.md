# Level Up AI — test de validation (7 jours)

Deux landing pages en anglais pour comparer l'intérêt pour deux piliers avant d'écrire le produit :

- `style.html` : coach IA pour les tenues.
- `dating.html` : coach IA pour les messages de dating (18+).
- `privacy.html` : notice de confidentialité de la liste d'attente.
- `index.html` : page de liaison (non indexée).

Les pages sont statiques. Aucune IA n'est appelée ; la démonstration des tons sur la page Dating est un exemple écrit à la main.

## Valeurs à remplacer avant publication

| Placeholder | Fichiers | Où l'obtenir |
|---|---|---|
| `TALLY_FORM_ID_STYLE` | style.html | ID du formulaire Tally « Style » (ex. `w4ByZ1`) |
| `TALLY_FORM_ID_DATING` | dating.html | ID du formulaire Tally « Dating » |
| `GOATCOUNTER_CODE` | style.html, dating.html | Code choisi à l'inscription GoatCounter |
| `CONTROLLER_NAME`, `CONTACT_EMAIL`, `CHANGE_DATE` | privacy.html | Toi |

## Formulaires Tally (un par page)

Champs :
1. Email (obligatoire).
2. « What would you use it for first? » (texte court, facultatif).
3. « Would you pay $7.99/month for unlimited use? » (Yes / Maybe / No).
4. Dating uniquement : case obligatoire « I confirm I am 18 or older ».
5. Case obligatoire : « I agree to receive one email when early access opens. See our privacy notice. » avec le lien vers `privacy.html`.

## Publication (GitHub Pages)

Settings → Pages → Source : « Deploy from a branch », branche `main`, dossier `/ (root)`.

## Mesure

- Visiteurs uniques par page : GoatCounter.
- Inscriptions : nombre de réponses dans chaque formulaire Tally.
- Taux d'inscription = inscriptions / visiteurs uniques, par page.
