1- Pra esse teste, todas as endpoints do documento swagger foram testadas.  São todas do verbo GET.
2- A API Key, bem como as ULRs, foram armazenadas em variáveis para melhor gerenciamento, caso elas sejam alteradas.
3- Os testes foram escritos direto na coleção, assim cobrindo todos os request, com excessão de um teste de body response, que
valida se o body response contem a palavra "timezone", presente somente para quatro request, nesse caso foi feito um  ifelse 
pra esse teste rodas somente nesses requests.
4- Teste para verificar se a resposta chegou em menos de 5 segundos.