name:  Propozycja funkcjonalności
about: Zgłoś pomysł na nową funkcjonalność
title: "[Feature Request]: "
labels: enhancement
assignees: ''

body:
  - type: markdown
    attributes:
      value: |
        Dziękujemy za zgłoszenie propozycji! Prosimy wypełnij poniższy formularz możliwie dokładnie.

  - type: input
    id: summary
    attributes:
      label: Krótkie podsumowanie
      description: Jednozdaniowy opis funkcjonalności
      placeholder: Np. "Dodanie trybu ciemnego do interfejsu użytkownika"
    validations:
      required: true

  - type: textarea
    id: description
    attributes:
      label: Opis funkcjonalności
      description: Opisz szczegółowo, czego dotyczy propozycja i dlaczego jest istotna.
    validations:
      required: true

  - type: textarea
    id: solution
    attributes:
      label: Proponowane rozwiązanie
      description: Jeśli masz pomysł na implementację, opisz go tutaj.
    validations:
      required: false

  - type: textarea
    id: alternatives
    attributes:
      label: Alternatywy
      description: Czy rozważałeś inne sposoby rozwiązania problemu?
    validations:
      required: false

  - type: textarea
    id: additional-context
    attributes:
      label: Dodatkowe informacje
      description: Dodaj tu zrzuty ekranu, diagramy lub inne pomocne materiały.
    validations:
      required: false
