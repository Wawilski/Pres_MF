# Intro


- NuXmv comes from nuSMV
- Uses and examples
    - Used only by the society 
    - School and non commercial goals only
- Own language
- CLI not GUI
- Mainly interactive


# Language

\not me

# Model Checking

## FINITE STATE 
- BDD : Convertis formule LTL ou CTL en BDD (passant par µ-calculus)
  - exaustif
  - de base from Nusmv
  - check_ltlspec,check_ctlspec

- SAT : 
    - BMC : 
        - Cherche contradiction avec profondeur plus ou moins élevée
        - Profondeur automatique pour nuXmv mais peut choisir une profondeur
        nous meme
        - check_ltlspec_bmc

    - K-Liveness : 
        - Prouve par induction la véracité de la formule
        - check_ltlspec_ic3

## INFINITE STATE

