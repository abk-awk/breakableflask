name: Automatisation des tests DevSecOps
on: push
jobs:
  Dependances:
    runs-on: ubuntu-latest
    steps:
      - name: Dependances
        run: |
          echo "ecrire ici le scrypt de contrôle des dépendances"
  Dockerfile:
    runs-on: ubuntu-latest
    needs: Dependances
    steps:
      - name: Test Dockerfile
        run: |
          echo "ecrire ici le scrypt de contrôle du Dockerfile"
  Deploy:
    runs-on: ubuntu-latest
    needs: Dockerfile
    steps:
      - name: Deploy
        run: |
          echo "Rien à faire ici. Votre application est prête à être déployée"
