# CRIAÇÃO DE WORKFLOW
Este repositório é destinado para o desenvolvimento de atividade 2 da matéria de Sistemas Distribuídos

Aqui vamos explorar algumas funções do GitHub Actions utilizando um modelo simples em JavaScript para conversão de Moedas.

# PIPELINE E ESTÁGIOS

Inicialmente como é um projeto simples que utiliza puramente JavaScript, foram implementados 3 estágios básicos para demostrar como o workflow funciona:

1. Build (Construção)
    Nesta etapa o GitHub Actios cria um ambiente Linux (Ubuntu) para rodar os comandos. Em seguida o código é baixado automaticamente do repositório.
'''yaml
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout Repository
        uses: actions/checkout@v4
'''

2. Test (Teste)
3. Deploy (Implementação)
