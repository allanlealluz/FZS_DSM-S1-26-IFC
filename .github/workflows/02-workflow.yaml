name: Pipeline Experimental

on: push

jobs: 
  ci-continuous-integracion:
    name: Teste de CI
    runs-on: ubuntu-22.04

    steps:
      - name: Mensagem simples
        run: echo "Ola Mundo"
        continue-on-error: true

      - name: Fazendo clone e checkout no meu repositorio nessa maquina virtual
        uses: actions/checkout@v4

      - name: Zippar os arquivos
        run: zip -r arquivo.zip .
