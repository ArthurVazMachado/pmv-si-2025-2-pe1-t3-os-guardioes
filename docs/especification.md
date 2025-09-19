# Especificações do Projeto

Esta seção tem como objetivo detalhar as especificações gerais do projeto de uma plataforma digital voltada à segurança comunitária em bairros de Belo Horizonte com alta vulnerabilidade à criminalidade.

Para isso, utilizamos as seguintes técnicas e ferramentas:

- Mapa de Personas: representação de usuários típicos com base em entrevistas, dados e comportamento esperado.

- Histórias de Usuário: definição dos desejos, necessidades e funcionalidades esperadas da plataforma, a partir da perspectiva das personas.

- Requisitos Funcionais e Não Funcionais: definição técnica do escopo do sistema.

- Levantamento de Restrições: identificação de limitações impostas ao projeto.

- Planejamento estratégico: atraves do miro.

Caso deseje atribuir uma imagem a sua persona, utilize o site https://thispersondoesnotexist.com/

## Personas

Érica tem 39 anos, é esteticista e mora no bairro Guarani, em Belo Horizonte.
Conhecida pelos vizinhos por ser comunicativa e prestativa, Érica gosta de ir à praça para conversar, caminhar e cuidar da saúde. Usa bastante o WhatsApp e redes sociais para manter contato com amigos e clientes. Apesar de gostar da convivência com a comunidade, já teve o celular roubado, o que a deixou mais preocupada com a segurança do bairro. Seu sonho é abrir o próprio negócio, mas acredita que precisa de um ambiente mais seguro para isso. Ela procura uma solução que a ajude a se manter informada sobre o que acontece na região e que facilite o diálogo com outros moradores.

Breno Monteiro tem 23 anos, é apaixonado por motos e vive uma vida tranquila, mas cheia de sonhos. Nos momentos de folga, ele gosta de pilotar pela cidade. Apesar do jeito calmo, Breno é determinado: quer vencer na vida e conquistar estabilidade financeira para ter mais independência e poder ajudar a família. Como motociclista, ele já passou por situações de risco nas ruas e se preocupa com a segurança, principalmente durante a noite. Breno busca uma forma de se manter informado sobre alertas de segurança e ocorrências em tempo real, além de querer fazer parte de uma rede de apoio que possa proteger quem, como ele, está sempre nas ruas. Ele acredita que, com mais informação e união, é possível transformar o lugar onde vive em um ambiente mais seguro para todos.

Mateus tem 23 anos, é tranquilo, criativo e sonha em ser um criador de conteúdos reconhecido. Ele passa boa parte do seu tempo gravando vídeos, editando cenas e estudando como crescer nas redes sociais. Mora em um bairro onde a insegurança é constante, o que o faz pensar duas vezes antes de sair com equipamentos caros ou gravar vídeos em ambientes externos. Apesar disso, ele não quer deixar o medo limitar seus sonhos. Mateus procura uma solução que o ajude a se manter informado sobre os riscos ao redor e que permita se conectar com outras pessoas da comunidade para criar uma rede de proteção. Ele acredita que, com mais segurança e apoio entre os vizinhos, será possível produzir com mais liberdade e seguir firme no seu sonho de viver da criação de conteúdo.

O Sargento Lucas tem 35 anos, é policial militar, pai de família e leva a disciplina como valor de vida. Pratica esportes regularmente e faz questão de passar tempo com a esposa e os filhos sempre que possível. No trabalho, é conhecido por sua paciência, firmeza e lealdade. Seu maior objetivo é crescer ainda mais na carreira e formar novos soldados comprometidos com a missão de proteger a população. Lucas também se preocupa com o bem-estar da comunidade onde vive e trabalha — ele sabe que a segurança não depende apenas da polícia, mas também da participação ativa dos moradores. Por isso, busca ferramentas que aproximem a população das forças de segurança e que incentivem o companheirismo e a responsabilidade coletiva. Para ele, uma comunidade bem-informada, conectada e unida é uma comunidade mais forte e segura — e é exatamente isso que ele quer deixar como legado para sua família e para os colegas de farda.

Seu Antônio tem 62 anos e é dono de um bar tradicional no bairro Guarani, em Belo Horizonte. Mora na região há décadas e conhece bem a vizinhança. Ultimamente, tem se preocupado com a segurança, especialmente à noite, quando o movimento diminui por medo de assaltos. Seu sonho é manter o bar funcionando com tranquilidade e ver o bairro mais seguro. Procura uma forma simples de se manter informado sobre ocorrências e de se conectar com outros comerciantes e moradores para fortalecer a segurança local.

----------------------------------------------------------------------------------------------------

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Morador | Registrar uma atividade suspeita           | Para ajudar a proteger meu bairro             |
|Comerciante | Registrar situações de risco          | Para ajudar a proteger os negócios e meus clientes            |
|Policial       | Gerar mapa de calor do bairro                 | Intensificar o patrulhamento |
|Empresa de Vigilância | Criar estratégias comerciais  | Vender soluções personalizadas |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |
|Moderador       | Investigar possíveis denúncias falsas            | Aumentar confiabilidade da ferramenta |

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito                                                                                          | Prioridade | 
|------|-----------------------------------------------------------------------------------------------------------------|------------| 
|RF-001| A aplicação deve permitir o cadastro de usuários.                                                               | ALTA  |  
|RF-002| A aplicação deve permitir login.                                                                                | ALTA  | 
|RF-003| A aplicação deve permitir o registro de ocorrências.                                                            | ALTA  | 
|RF-004| A aplicação deve permitir o registro de descrição, data, hora e localização na ocorrência.                      | ALTA  | 
|RF-005| A aplicação deve permitir a consulta de ocorrências em lista.                                                   | ALTA  | 
|RF-006| A aplicação deve permitir a filtragem da lista de ocorrências.                                                  | ALTA  | 
|RF-007| A aplicação deve permitir a consulta de ocorrências registradas em mapa.                                        | BAIXA | 
|RF-008| A aplicação deve permitir a notificação de reuniões comunitárias (mutirões, encontros com polícia, palestras).  | ALTA  | 
|RF-009| A aplicação deve permitir o feedback comunitário para avaliar a confiabilidade das informações postadas.        | ALTA  | 


### Requisitos não Funcionais

|ID     | Descrição do Requisito                                                                             |Prioridade |
|-------|----------------------------------------------------------------------------------------------------|-----------|
|RNF-001| A aplicação deve ser responsiva, adaptando-se a dispositivos móveis e desktop.                     | MÉDIA  | 
|RNF-002| A aplicação deve processar requisições do usuário em no máximo 3 segundos.                         |  BAIXA | 
|RNF-002| O sistema deve ter disponibilidade mínima de 95%, exceto em manutenções programadas.               |  MÉDIA | 
|RNF-002| A aplicação deve garantir a segurança de dados utilizando criptografia (HTTPS, hash de senha).     |  ALTA  | 
|RNF-002| O sistema deve ser intuitivo e de fácil uso, mesmo para usuários sem experiência tecnológica.      |  MÉDIA | 
|RNF-002| O sistema deve ser compatível com navegadores modernos (Chrome, Edge, Firefox).                    |  MÉDIA | 

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |

