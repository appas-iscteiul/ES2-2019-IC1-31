Grupo31

69225-Afonso Alves(4) 
78038-António César(5)
72863-José Ramalho(2) 
78384-Pedro Nogueira(1) 
78456-Ricardo Nunes(6)

Complemento 1 - Pedro Nogueira
Neste complemento foi criada a estrutura do site, tendo em conta as directrizes dadas pelos professores. Houve dificuldade na colocacao dos ficheioros recebidos dos colegas. E na criacao da imagem para o envio ao professor;

Complemento 2 não foi realizado.

Complemento 4 - Afonso Alves:
Na tabela o campo fileTimestamp, está mesmo em timestamp, após muitas tentativas não foi possível alterar para uma date mais "user-friendly". Existem alguns problemas na transposição da aplicação java para outras máquinas. De resto, 100%funcional, mostra todos os gráficos e tem método para fazer pull de todas as tags que vão sendo adicionadas ao repositório.

Complemento 5 - António César:
As seguintes queries funcionam, e podem ser alteradas com diferentes zon as do país.
cd C:\Users\António César\eclipse-workspace\ES2_ponto5\target
java -jar Maven_quickstar-0.0.1-SNAPSHOT.jar

Site deve ter separador com link para http://localhost:8082/search (Só funciona se o .jar ja tiver sido executado)

Testar Queries:
/RDF/NamedIndividual/@*
//*[contains(@about,'Algarve')]/Testes/text()
//*[contains(@about,'Algarve')]/Infecoes/text()
//*[contains(@about,'Algarve')]/Internamentos/text()

Complemento 6 - Ricardo Nunes:
Em relação a esta aplicação, é retirado as duas noticias mais recentes, para efeitos de comparação, e depois aparece os diferentes valores dos dados de internamentos, infecoes e testes, da região do Alentejo e do Algarve. Para este complemento basta correr a aplicação e será visualizado os dados numa página html, mas devido a problemas com a aplicação .jar só é possivél verificar o resultado no eclipse.

