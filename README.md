## Design system

Estruturar ambiente organizado para usuario, componentes, modulos, interface e dados. 

## Etapas

1. Levantar requisitos
   - [] entender o sistema que vai desenhar
   - [] Requisitos funcionais
     - tempo de resposta
     - observabilidade
   - [] Requisitos nao funcionais

2. Casos de uso:
    - [] como usuario ira interagir
3. Desenhando solucao / diagrama de sequencia

## Tradeoffs

1. Escalabilidade x Complexidade.

2. Consistencia x Disponibilidade (Teorema CAP):
    sistema bancarios tem que ter disponibilidade, mas um numero de curtidas precisa ser constante mesmo vendo um valor antigo.
3. Latencia x Throughput:
    Menor latencia ou lhe dar com mais requisicoes.
4. Seguranca e Usabilidade:
5. Armazenamento em memori x armazenamento em disco:
    dados em cache para ser rapido, limitado e geralmente caro. Em disco barato mas tem tempos de acesso mais lento.
  nmn 

## Etapas ( FACEBOOK )

#### Funcionais:
   * O usuario poder visualizar o feed, posts recentes.
   * Scrool com posts recentes
   * Interacao curtir, comentar, compartilhar.

#### Nao funcionais:
   * Tempo de resposta do feed, minimo 200ms -> precisa de cache
   * Sistema deve suportr grande quantidade de usuario e posts simultaneo -> escalabilidade 
   * Feed deve ser atualizado em tempo real ou minima latencia.
  
#### Definir use cases:
   * Visualisar Feed
   * Rolar Feed
   * Interagir com Posts




   
Diagrama da solucao:

<img width="1567" alt="-product-sales-" src="https://github.com/Guilhermefonseca2021/modelagem_dados/assets/92196697/d2e28c8d-7674-4e3c-9c3d-2b239f1e5100" alt="Modelo de Dados" >
