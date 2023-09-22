
# Pauta pra reunião

# quais são os problemas

ESSAS SÃO AS PARTES CHATAS, PRECISAMOS RESOLVER ISSO LOGO!

- nossa entrega é em pouco tempo
  - começa HOJE!
  
- não sabemos o que é esse produto / componente ainda

- ninguém sabe o que fazer
  - precisamos esclarecer o que é o produto
  - precisamos definir um trabalho pra cada um HOJE

- não temos divisão de trabalho
  - não temos liderança  - quem faz o que? porque?






- software tem pouco trabalho
  - metade do nosso time é software
  
  - e as soluções que tivemos parecem incoerentes com o resto do projeto


  - 


  - 







- precisamos aumentar escopo de forma esperta

- pode pegar peças por ordem de chegada
  - não pode contar com isso
  - motor de passo
  - antena
  - tem rasp no time

# decidir requisitos

**o dispenser é algum desses dois:** 

scenário: senhora idosa sem idenpendencia, precisa receber medicamentos
-alarme (notificações físicas e virtuais)
-confirmação do remédio

**NÃO TEMOS CERTEZA SE TERA RECONHECIMENTO VISUAL OU NÃO**

### produto para distribuir medicamentos

um produto para distribuir remédios?

nossa proposta é meio fraca
- isso porque ninguém do time demonstra resolução pra explicar o porque estamos fazendo *isso* desse *jeito* 
- não é algo que *eu acho*, e sim algo que *percebemos* 

precisamos ter uma proposta de valor - 'nosso produto faz {ESSA COISA}, e {ESSA COISA} é boa'

**SE O DISPENSER FOR REALMENTE UM DISPENSER**
o publico alvo do nosso produto vai ser famílias?
o publico alvo do nosso produto são pessoas viciadas em remédios?
<!-- o publico alvo do nosso produto vai ser hospitais? -->
<!-- o publico alvo do nosso produto são idosos? -->

vamos impedir 
- controle de acesso

**USUÁRIO 1: TOMADOR** (DO REMÉDIO)
**USUÁRIO 2: GERENCIADOR** (DO USUÁRIO TOMADOR)

quais são as garantias que oferecemos:

*e se tiver um visor que indica ONDE botar* -> 
  - nomear cada uma das caixas?

- saber que os remédios estão acabando?

- 



<!-- - o produto garante que o remédio será tomado em 30 minutos ou alguém sera notificado? -->

<!-- - e se o **TOMADOR** não tomar, e só retirar o produto da embalagem pra calar a boca da máquina? -->

-- e se o **TOMADOR** tentar tirar o remédio à força? -->
<!-- 
- e se o **GERENCIADOR** esquecer?
  - segunda escalação de problema -->

- e se o **GERENCIADOR** botar o remédio errado?
  - identificação


  <!-- IDENTIFICAR REMÉDIO
    - Reconhecimento de imagem?
    - Sensor por caixa?
    - Alguma forma de reconhecimento com caixa aberta
    - POR FOTO?????
      - suporte ou angulo da foto -->

NÃO QUEREMOS IDENTIFICAR REMÉDIOS!

FREQUENCIA DE CONSUMO??

- Qualquer hora (mais complexo)

- 6h / 12h / 24h

ELETRONICA VAI IDENTIFICAR SLOT VAZIO OU NÃO


IDENTIFICAÇÃO DE SLOTS VAZIOS


MODOS DE USO (programável):
1.  radial interno, meio e externo POR FREQUENCIA
2.  **OU** bota onde quiser e qualquer ordem

Fazer um mapa para slots








- tempo de escalar problema é de 30 minutos 
- o usuário tomou SE E APENAS SE a caixa for aberta
- fundo falso pra descartar remédio não tomado


oferece quantas pílulas (máximo)? - 36? 24?
quanta variedade entre itens que podemos fornecer? - qualquer? depende de formatos?


### componente logistico

um sistema para resolver um problema logístico, voltado para o ordenação de pequenos objetos não maiores que 3cm³ 

ISSO É UM PIVOT DA PROPOSTA INCIAL DO PROJETO, UMA COISA COMUM QUE ACONTECE

**SE O DISPENSER FOR UM PRODUTO LOGÍSTICO**

porque não botar reconhecimento visual?
qual tipo de itens ele ordena (exemplo: <10 gramas, <3 cm³)?
porque alguem utilizaria um produto com tão pouca escalabilidade logisticamente?

precisamos de reconhecimento visual?
- sugestão 

### reconhecimento visual

- objetos de formas e cores diferentes

### QUESTÕES GERAIS

quais as garantias:
- cada item precisa ser registrado?
- cada item precisa ir manualmente?
- cada item precisa ir no seu próprio slot? 
- cada item precisa de muito esforço ser inserido corretamente?


mecanismo de notificações:
- e se o **GERENCIADOR** não ver a notificação?
- e se o **GERENCIADOR** não tiver internet?
- 

garantias de segurança:
- em caso de erro interno, fazemos o que?
- como evitar desligamento? como reduzir os efeitos negativos do produto falhar? 
- se o sistema identificar que está prestes a ficar sem bateria, faz o que?
- como vamos testar essa confiabilidade?


o aparelho possui manutenibilidade?
 



# separar tarefas entre grupos

- como vamos lidar quando **alguém não entrega as coisas que deveria fazer**?
- como vai garantir que **todo mundo trabalha**? 
- como vai garantir que **ninguém é injustamente sobrecarregado**?
- como evitar **reuniões inúteis** e garantir que estamos sendo eficientes com nosso tempo? 
- todo mundo tem que fazer coisa técnica

QUAIS GRUPOS?
- proponho:
1. GERENCIAMENTO = PRODUTO + PROJETO
   1. pelo menos 2 pessoas
   2. PRECISA estar em algum área técnica também, com carga reduzida
   3. lidera o projeto como um todo
   4. é onde o coordenador geral fica
   5. interessados em participar do produto / projeto
2. SOFTWARE
   1. 9 pessoas (dividindo com outras áreas conforme necessário)
   2. 4 áreas:
      1. front
      2. back
      3. admin
      4. especializado
   3. faz o software
3. ELETRONICA
   1. 2 ou 3 pessoas (sendo uma importada de outra área)
   2. faz funcionar o hardware 
4. ENERGIA
   1. 2 pessoas
   2. alimenta o sistema
5. MECÂNICA E ESTRUTURA (Aeroespacial e Automotiva)
   1. 4 pessoas
   2. Faz o CAD
   3. Monta a estrutura
   4. Monta partes mecânicas


PRODUTO:
- quais medicamentos podem ser tirados
- procurar produtos comerciais que existem sobre o tópico / similares
- 

ELETRONICA:
- vai ser wireless?
- qual vamos usar (rasp, esp, arduino...)
- quais são as demandas eletrônicas

SOFTWARE:
- base de dados (segura, confiável, sem perda de dados)        
- sistema de autenticação e autorização
- onboard de novo usuário
- front-end do usuário gerenciador
- precisa de back
- precisa de login
- como vai ser comunicacao
- qual dado vamos passar?

ENERGIA:
- qual alimentação
- fonte
- qual é a autonomia de tempo
- precisa de bateria - sim
- quais são as garantias que eletrônica podem esperar?
- quais são as garantias que os aparelhos não irão estragar por alta carga?

AERO e AUTO:
- mecânica
- fazer o CAD
- componentes para mecânica do aparelho

# começar relatório PC1 

- coordenador geral
- coordenadores técnicos (2x)

- precisa entender oq vai entregar no ponto de controle 1

- aeroespacial e automotiva (4 membros) - estruturas

- energia - 
-- mayara - escrever relatorio
-- isabela

-eletronica
- thalles

- software
-- bruno
-- renato
-- lucas











O nosso produto é:


- Um produto de logística, em que organizamos objetos (no contexto de um dispenser de remédio)
  - Usamos poucos remédios
  - 


- OU um produto que organiza remédios 





## Requisitos

1. O sistema comporta <x> remédios
2. O produto identifica o remédio? 
3. O remédio precisa ser identificado?
4. O sistema informa **GERENCIADOR** que falta remédios












4. Entrada dos remédios
   1. Vai organizar automaticamete?
   2. precisa aceitar multiplos simultaneamente?
   3. Vai reconhecer ou precisa ser ativamente identificado quando entra?
5. Saida de remédios
   1. Vai dispensar?
   2. Vai abrir uma caixa e tirar?
   3. Vai 






## Decisões

- NÃO SERA HOSPITAL
- SERÁ UM PRODUTO (E NÃO UM SISTEMA LOGÍSTICO)
- 

## SUGESTOES AUMENTO DE ESCOPO
  - fazer 2 front-ends?
  - fazer painel de admin?
  
  - fazer reconhecimento visual? 
    - se for, como evitar sobrecargar o time de eletrônica?
    - o time de software fica responsável por este hardware?
    - eletronica manja
    - fazer por requisisição
     
  - fazer coleta dados informativos pros remédios?
    - individual?
    - para o médico?
    - quais remédios não podem tomar simultaneamente (exemplo)

  - integração com sistemas (?) de saúde?
    - envia um email avisando
    - instruções novas diretamente do médico

  - multiplas maquinas interconectadas
    - maquinas compartilham dos seus recursos
    - generalização do sistema (cada maquina funciona como módulo)
    - ambientes conectados (todos oferecem a mesma maquina)
    - a maquina tenta prever a demanda de consumo para evitar recargas






## professores 22/9

<questoes de produto>

- validar quantidade
- validar tipo de remédio

- retira identificação?

carla:
- pro cuidador
- objetivo grande: identificar se ta tomando remédio ou não?
- identificar SE o cara tomou? só tira uma foto?
- sensor de pressão pra FILMAR 30 segundos? pra garantir que tomou o remédio?
- evitar falso positivos ou negativos na hora de tomar
- emissores de sinais para avisar o cuidador
- mostra um video pro cuidador?
- SIMPLES SIMPLES SIMPLES SIMPLES SIMPLES SIMPLES SIMPLES 
- frontend pode até ser um chatbot no whatsapp 
- usuarios de baixa maturidade tecnologica
- mais de uma pilula por slot? é ok?
- o sistema instrui como colocar as pilulas
- se resolver bem resolvido, está bom o escopo

outros:
- front pode ser por bot, gerenciar, 
- se o feedback for bom 
- tomar na frente do dispense
- bebedouro?


verificar os horarios se MODO 1




VAMOS TER CAMERA PRA MANDAR VIDEO PRO CARA TOMAR O REMEDIO

relatório não é algo interessante pro projeto

publico alvo é o cuidador

qual é o visual

controle de estqoue?



