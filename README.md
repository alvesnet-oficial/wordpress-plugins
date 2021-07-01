# wordpress-plugins

# Plugins importantes

1. Astra Widgets
2. Companhion Auto Update 
3. Editor Classico
4. EWW image Optimizer
5. Google Analycs for WordPress by Monsterinsights
6. Microthemer
7. Rank Math SEO
8. Realy Simple SSL (Algumas situações especificas)
9. Starter Templates
10. Tradução (LOCO)
11. Ultimate Addons for Gutenberg
12. WP Cerber Security, Antispam & Malware Scan
13. WP Mail SMTP
14. WP Super Cache
15. WPForms Lite
16. WPS Hide Login
17. Woocommerce
18. Brazilian Market on WooCommerce (Por Claudio Sanches)
19. PagSeguro for WooCommerce (Por Claudio Sanches)
20. SumUp Payment Gateway For WooCommerce (Por SumUp)
21. Gutentor – Gutenberg Blocks – Page Builder for Gutenberg Editor

# Plugins

1. Astra Widgets

2. Companhion Auto Update 
- Atualizações de Segurança

3. Editor Classico
- Caso tenha dififuldade em usar as ferramentas mais atuais.
- As vezes as pessoas que gerencia o Blogs fica mais facil para ela editar de forma mais facil e pratico.

4. EWW image Optimizer
- Otimiza as imagens do site para um determinado tamanho para que ele fique mais rapido.

5. Google Analycs for WordPress by Monsterinsights
- Integra-se ao modulo SEO

6. Microthemer
- Nos ajuda a personalizar e modificaçoes o site até 5 CSS .

7. Rank Math SEO
- Integra-se ao modulo SEO

8. Realy Simple SSL
- Ajuda na migracao de um provedor que não tem HTTPS. Mas é um processamento a cada chamada que gera um desempenho a mais no servidor. So é bom usa mesmo durante a migracao.

9. Starter Templates
- Auxiliar na instalação do modelo do Layout que vai ser utilizado.

10. Tradução (LOCO)
- Tradução de idioma.

11. Gutenberg Blocks - Ultimate Addons for Gutenberg **
- Ajuda com funções para customizar 

12. WP Cerber Security, Antispam & Malware Scan
- Segurança e proteção do Website

13. WP Mail SMTP
- Para envio de e-mail.

14. WP Super Cache
- Ativar somente no final do projeto.

15. WPForms Lite
- Axiliar na criação de formularios.

16. WPS Hide Login
- Oculta a pagina defaul do wp-admin por questão de segurança

17. Woocommerce

18. Brazilian Market on WooCommerce

19....

20...

21. Gutentor – Gutenberg Blocks – Page Builder for Gutenberg Editor

* Criação de Blocos de Slides

Os 5 maiores players utilizam o maior banner do topo da pagina.
'width':1500 e 'height':600 

e o menor banner os tamanhos das imagens
'width':970 e 'height':250

Sugestões: Nos vamos utilizar 1200x400 tamanho medio entre os grandes players. Os banner não precisam ser na maior resolução possível, os jpeg salve em 72% e 82% para um melhor otimização.

* CDN (Rede de Servidores para Distribuição de Conteudo Statico). O Conteudo vem do servidor mais proximo de voce. Hoje é possivel ter CND em alguns provedores de hospedagem.

https://br.freepik.com/ : Logo e Banner personalizando de acordo com sua necessidade.

# Corrigir algumas configurações importante:

** Alerta!:
O Ultimate Addons for Gutenberg requer o Editor de blocos . Você pode alterar as definições do seu editor para Editor de blocos 
. O plugin NÃO ESTÁ funcionando no momento.

Resolução:
- Entrar nas configurações do Edito Classico e alterar a configuração da mesma forma como está abaixo:

1. Editor padrão para todos os usuários:

  Classic editor ( )

  Block editor (x)
 
2. Permitir que os usuários alternem entre editore:

  Sim (x)
  
  Não ( )
  
# Starter Templates

No painel do WordPress clique em 'Aparencia / Starter Templates', escolha a opção Gutenberg. 


# WooCommerce / Produtos:

1. Comportamento da ação de adicionar produto ao carrinho:

  Redirecionar ao carrinho após uma adição bem-sucedida (x)

  Ativar botão para comprar utilizando AJAX nas páginas de arquivo (x)
  
2. Imagem substituta:

  (id) insira o 'id' de uma imagen personalizada com sua logo-marca se assim desejar.
  
3. Medidas:

  Unidade de peso (g = gramas)
  Unidades de medida (cm = centimentros)

4. Avaliações:

  Ativar avaliações	Ativar avaliações Ativar avaliações de produto (x)  
  Exibir "comprador verificado" nas avaliações de clientes (x)  
  Avaliações podem ser feitas apenas com "compradores verificados" (x)
  
5. Avaliações de produto:
  
  Ativar classificação com estrelas em avaliações (x)
  
  Classificação com estrela deve ser obrigatório, não opcional (x) 

7. Inventário
  
  Gerenciar estoque Ativar gestão de estoque
  Manter estoque (minutos): 60
  
  Observação: Se for trabalhar tambem com pagamentos por boletos 60 minutos pode ser muito pouco, é importante verificar com a empresa que vai gerenciar o Gateway de Pagamento por quanto tempo voce pode deixar caso o cliente não paga!. Se o cliente não pagar o boleto precisar ficar 1 ate 2 dias para verificar com cliente se ele vai pagar o produto ou não. Se for cartão de credito 60 minuto está otimo.

  *Manter estoque (para pedidos não pagos) por x minutos. Quando esse limite é atingido, o pedido pendente será cancelado. Deixe em branco para desabilitar.

  Notificações:
  Ativar notificações de baixo estoque (x)
  Ativar notificações de item em falta no estoque (x)
  
  Destinatários da notificação: cliente@dominio.x.x  (É o email do responsavel pelo estoque designado pelo cliente)
  
  Limiar de estoque baixo: 2  (Se voce vende muito pouco produto 2 pode ser o suficiente, se voce vender muito pode ser que tenha que aumentar para 10 ou mais...)
  
  Limiar de fora de estoque: 0 (Leve em consideração que se voce trabalhar com boletos talves tenha clientes que esteja na eminencia de pagar ou não o boleto, e voce precise deixar algumas peças)
  
  Visibilidade dos produtos fora de estoque:
  
  Ocultar os produtos fora de estoque do catálogo ( )  # Se voce ativar essa função aquele produto 'some' , se é um produto que eu posso ficar sem estoque mas eu não quero que eles some continue aparecendo la com um botão de 'avise-me quando chegar!' por que eu vou comprar mais então você não oculta!. Quando você oculta as vezes voce pode perder indexação pelo Google daquela pagina do produto. Tome cuidado se é um produto que vai acabar e não vou vender mais então oculta. Mas se é um produto que vende depois compro mais e continua ele pode ficar mostrando que está fora de estoque mais tem o o botão 'avise-me quando chegar!'. Importante decidir isso com o cliente.
  
  Formato de exibição do estoque: Sempre mostra a quantidade restante em estoque, por exemplo "12 em estoque"
  
# Contas e Privacidade

Finalização de compra como visitante:

  Permitir que seus clientes efetuem pedidos sem uma conta ( )
  
  Permitir que seus clientes façam login em uma conta existente durante a finalização da compra (x)
  
Criação de conta:

  Criação de conta Permitir que seus clientes criem uma conta durante a finalização da compra (x)
  
  Permitir que seus clientes criem uma conta na página "Minha Conta" (x)
  
  Ao criar uma conta, gere automaticamente um nome de usuário da conta para o cliente com base em seu nome, sobrenome ou e-mail (x)
  
  Quando uma conta for criada, gerar automaticamente uma senha para a conta ( )
 
 Solicitações de remoção de contas:
  
   Remover dados pessoais dos pedidos sob demanda ( )

*Quando lidando com uma solicitação de remoção de conta, devem ser mantidos ou removidos os dados pessoais dentro de pedidos? 

  Remover o acesso aos downloads sob demanda ( )

*Quando lidando com uma solicitação de remoção de conta, os acessos aos arquivos baixáveis devem ser revogados e os registros de downloads apagados?

Remoção de dados pessoais:
  
  Permitir que os dados pessoais sejam removidos dos pedidos em massa ( )

*Adiciona uma opção à listagem de pedidos para remover dados pessoais em massa. Observe que a remoção de dados pessoais não pode ser revertida.

# Integração:

MaxMind Geolocation

Uma integração para a utilização do MaxMind para realizar pesquisas de localização geográfica. Observe que essa integração fará apenas pesquisas de países.

Chave de licença do MaxMind: ???

  *A chave que será usada ao lidar com os serviços de geolocalização do MaxMind. Você pode ler como gerar um na documentação da integração com a geolocalização do MaxMind.

Caminho do arquivo de banco de dados: Ex: /home/'dominio'/public_html/'site'/wp-content/uploads/woocommerce_uploads/SOIwRfuKPP2ILQJQTbVK66KwUuRpmSLd-GeoLite2-Country.mmdb

  *O local em que o banco de dados do MaxMind deve ser armazenado. Por padrão, a integração salvará automaticamente o banco de dados aqui.

Tabela do histórico de rastreamento: (Contrato com os Correios)

  *Exibe uma tabela com informações da entrega na página Minha conta > Ver pedido. Nome de usuário e senha são obrigatórios para o funcionamento e podem ser obtidos com a área comercial dos Correios.

Habilitar/Desabilitar 
  Ativar a tabela de histórico de rastreamento (x)
  
  Código administrativo: ???
  
  Senha administrativa: ???

Log de depuração:

  Ativar log para histórico de rastreamento ( )

*Registra os eventos do(a) Tabela do histórico de rastreamento, como requisições no WebService. Ver logs.

Autopreenchimento de endereços:

Exibe uma tabela com informações da entrega na página Minha conta > Ver pedido.

Habilitar/Desabilitar
  
  Ativar autopreenchimento de endereços (x)
  
Validade dos CEPs: '12 meses'

*Define por quanto tempo um CEP ficará salvo no banco de dados antes de uma nova consulta.

Forçar autopreenchimento:

  Ativar opção de forçar o autopreenchimento (x)

*Quanto ativado irá autopreencher todos os endereços depois que o usuário terminar de digitar o CEP, até mesmo quando o endereço já foi preenchido antes.

Limpar banco de dados: 'Limpar banco de dados'

*Deletar todos os CEPs salvos do banco de dados, utilize esta opção caso você tenha problemas com CEPs desatualizados.

Log de depuração:

Ativar log para o autopreenchimento de endereços (x)

*Registra os eventos do(a) Autopreenchimento de endereços, como requisições no WebService. Ver logs.

# Entrega

Dica: 

Validar Faixa de CEP por região
http://cep.la/

Inserir da seguinte forma no Woocommerce sem os caracteres:

Ex: Rio de Janeiro

20000000...28999999

A regra de negocio na configuração dos cep sempre comece configurando do mais especifico para o mais generico:

Segue está ordem:

1º. Bairro
2º. Rio de Janeiro
3º. Capital
4º. Estado

Ex: 

1. Rio de Janeiro: 20000000...28999999
2. Brasil





