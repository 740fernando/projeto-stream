# Stream
- É uma sequencia de elementos advinda de uma fonte de dados que 
oferece suporte a "operações agregadas".
- Fonte de dados: coleção, array, função de iteração, recurso de E/S
- Sugestão de leitura:
http://www.oracle.com/technetwork/pt/articles/java/streams-api-java-8-3410098-ptb.htm

# Características
- Stream é uma solução para processar sequências de dados de forma: • Declarativa (iteração interna: escondida do programador)
- Parallel-friendly (imutável -> thread safe)
- Sem efeitos colaterais
- Sob demanda (lazy evaluation)
- Acesso sequencial (não há índices)
- Single-use: só pode ser "usada" uma vez

# Criar uma stream
- Basta chamar o método stream() ou parallelStream() a partir 
de qualquer objeto Collection.
https://docs.oracle.com/javase/10/docs/api/java/util/Collection.html
- Outras formas de se criar uma stream incluem:
- Stream.of
- Stream.ofNullable
- Stream.iterate
