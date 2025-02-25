# CRIAÇÃO DE WORKFLOW
Este repositório é destinado para o desenvolvimento de atividade 2 da matéria de Sistemas Distribuídos

Aqui vamos explorar algumas funções do GitHub Actions utilizando um modelo simples em JavaScript para conversão de Moedas.

# PIPELINE E ESTÁGIOS

Inicialmente como é um projeto simples que utiliza puramente JavaScript, foram implementados 3 estágios básicos para demostrar como o workflow funciona:

1. Build (Construção)

2. Test (Teste)

3. Deploy (Implementação)

Cada etapada só vai rodar se o estágio anterior for executado com sucesso.

# NOVOS ESTÁGIOS

Depois de executar as 3 etapas mais básicas, foi aplicado mais 2 estágios nesse projeto (Lint e Performance Test). Como o projeto utiliza o JavaScript puro e de forma bem simples, não faz sentido tentar utilizar aplicações muito complexas.

- Lint: Faz uma analise do código sem precisar instalar pacotes.

- Performance Test: Mede a eficiencia e velocidade do programa, garantindo que não há gargalos.

# AUTOR

GUSTAVO HERDT