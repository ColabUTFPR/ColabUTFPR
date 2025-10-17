

## Projeto Disciplina: Requisitos de Software

[](https://github.com/ColabUTFPR/ColabUTFPR/blob/main/README.md#projeto-disciplina-requisitos-de-software)

Olá! Este repositório faz parte do projeto da disciplina de Requisitos de Software da UTFPR - Campus Cornélio Procópio.

Link do Padlet:  [https://padlet.com/gustavo2006/my-luminous-padlet-6f60ibwd1sbef48g](https://padlet.com/gustavo2006/my-luminous-padlet-6f60ibwd1sbef48g)

## *1. Introdução*

[](https://github.com/ColabUTFPR/ColabUTFPR/blob/main/README.md#1-introdu%C3%A7%C3%A3o)

_**1.1. ColabUTFPR**_

[Gustavo Henrique de Almeida](https://github.com/guhenrih)

[Thiago Dutra da Silva](https://github.com/SimonR556)  

[Eduardo Aguiar](https://github.com/duduaguiaarr-source)

[Nathan Victor de Oliveira Costa](https://github.com/NathanVictorOC)

_**1.2. Nome do Sistema**_

ColabUTFPR

_**1.3. Propósito do Sistema**_

Este documento apresenta os requisitos dos usuários a serem desenvolvidos pela  Colab, fornecendo aos desenvolvedores as informações necessárias para o projeto e implementação, assim como para a realização dos testes e homologação do sistema.

O objetivo do sistema ColabUTFPR  é facilitar a integração entre alunos da UTFPR, principalmente entre calouros e veteranos, tendo a disposição a possibilidade de se criar fóruns com respostas e interações além de mensagens diretas entre os usuários podendo também separar temas em abas

_**1.2. Público Alvo**_

Este documento se destina a toda equipe de desenvolvimento e teste, além de ser público para os  usuários

_**1.3. Descrição dos usuários**_

_<Descrever quais os usuários finais do sistema (quem vai utilizar o sistema). Neste espaço vocês vão traçar um perfil de usuário, bem como as personas e análide de tarefas>_


_**Personas:**_

# Persona 1 

|**Campo**|**Descrição**|
|------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Nome**              | Mariana Silva |
| **Idade**             | 18 anos |
| **História**          | Mariana chegou à UTFPR neste ano; é caloura do curso de Engenharia de Software, vem de uma cidade pequena no interior e mora em república com outras três estudantes. É organizada, um pouco tímida e tem muita vontade de aprender, mas sente-se perdida com a burocracia da universidade (disciplinas, grupos de estudo, onde conseguir material) e com a vida acadêmica em si. |
| **O que motiva?**     | - Entender rapidamente como funciona a faculdade e obter dicas práticas (professores, matérias, bibliografia). <br><br> - Encontrar colegas para formar grupo de estudo. <br><br>- Ganhar visibilidade e confiança ao ajudar com dúvidas simples e receber reconhecimento (pontos/insígnias). <br><br> - Confiabilidade: prefere ambientes seguros e moderados, onde não terá “trolls”. |
| **Dificuldades**      | - Sentir timidez para perguntar em sala ou presencialmente. <br><br> - Não saber onde achar materiais confiáveis ou quem procurar para dúvidas específicas. <br><br> - Falta de experiência com ferramentas acadêmicas online (Moodle, SIGAA etc.). <br><br> - Medo de ser julgada por perguntas consideradas “básicas”. |
| **Relação com TICs**  | - Usa smartphone diariamente (Instagram, WhatsApp, YouTube). <br><br> - Tem habilidades digitais básicas a intermediárias: sabe pesquisar, usar apps e redes sociais, mas se perde em plataformas acadêmicas mais formais. <br><br> - Prefere interfaces simples e com suporte (tutoriais, FAQs). <br><br> - A gamificação (pontuação/insígnias) funciona bem para motivá-la a participar, desde que o sistema seja claro e seguro. |

[foto da persona: Mariana, imagem gerada pela Meta IA](https://drive.google.com/file/d/19ADvT8cVgNNQqc9zWFTyipkkKik3Ar7M/view?usp=drive_link)


# Persona 2

| **Campo**             | **Descrição** |
|------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Nome**              | Lucas Andrade |
| **Idade**             | 24 anos |
| **História**          | Lucas é aluno do 4º semestre, trabalha parte do tempo como estagiário em uma empresa de TI e já participou de monitorias na faculdade. É extrovertido, gosta de ajudar os colegas e tem experiência em desenvolver pequenos projetos. Tem muitos livros e periféricos que pretende vender/trocar entre colegas para ganhar uma renda extra. |
| **O que motiva?**     | - Construir reputação acadêmica e networking (ser reconhecido como alguém que ajuda). <br><br> - Trocar ou vender material didático usado de forma prática e confiável. <br><br> - Aumentar seu score/gamificação para obter privilégios (ex.: destaque no ranking, acesso a canais exclusivos). <br><br> - Encontrar comunidades temáticas (IA, programação, jogos) para trocar conhecimento avançado. |
| **Dificuldades**      | - Pouco tempo livre: precisa de interações rápidas e eficientes. <br><br> - Desconfiança quanto à segurança em transações entre alunos (pagamentos, trocas presenciais). <br><br> - Moderar o próprio tempo para não gastar demais em fóruns sem objetivo. <br><br> - Lidar com conteúdo repetitivo (perguntas básicas que já respondeu várias vezes). |
| **Relação com TICs**  | - Muito confortável: usa laptop e smartphone; domina GitHub, Discord, Telegram e ferramentas de escritório. <br><br> - Alto nível de autossuficiência tecnológica (consegue testar funcionalidades, reportar bugs e propor melhorias). <br><br> - Gosta de integrações (login único via conta da universidade, notificações por push) e prefere recursos avançados (filtros por tags, comunidades fechadas, sistema de reputação transparente). <br><br> - Valoriza um marketplace integrado, com avaliações e mediação pela comunidade/administradores. |

[foto da persona: Lucas, imagem gerada pela Meta IA](https://drive.google.com/file/d/1C7mKB-b_2pxmU1AeiD02wp8_SiJG5dKV/view?usp=drive_link)

_**Análise da situação atual: antes da introdução de sua solução**_

- O que ela faz?
  1.  Ela precisa saber qual professor é melhor para uma disciplina e onde conseguir as notas de aula
  2.  Ela recorre aos grupos informais de WhatsApp da turma e do curso, pois são familiares para ela.
  3.  Ela pergunta no grupo sobre o professor e os materiais.
  
- Quais os artefatos envolvidos?
  1.  Grupos de WhatsApp lotados e com conversas misturadas.
  2.  E-mails burocráticos e o sistema SIGAA/Moodle, que ela acha confuso e intimidador.

- O que ela precisa saber?
  1. Informações confiáveis sobre a dinâmica da faculdade e dicas de veteranos.

_**Análise das tarefas depois: como serão executadas as suas tarefas com sua solução:**_

-  O que ela faz:
  1.  Ela faz o login no aplicativo ColabUTFPR usando seu e-mail institucional.
  2.  Ela acessa a aba de Fóruns/Comunidades e seleciona a categoria "Engenharia de Software" e o tópico "Cálculo I".
  3.  Ela utiliza a função de busca por posts antigos para ver se a pergunta já foi feita. Ela encontra uma discussão mais antiga sobre o professor, que ela reage positivamente.
  4.  Ela decide criar um novo post com o título "Caloura: Grupo de Estudos de Cálculo I" para encontrar colegas, utilizando a aba de criação de publicações.

-  Os Artefatos Envolvidos:
  1.  O aplicativo ColabUTFPR (instalado em seu smartphone).
  2.  Um sistema de ranking e reputação que filtra as informações de usuários experientes.
  3.  Notificações e um chat de mensagens privadas no aplicativo.

-  O que ela precisa saber:
  1.  O melhor professor e um grupo de estudo.
  2.  O sistema precisa ser confiável e seguro contra "trolls".

_**Cenário: Antes**_

Mariana Silva (18 anos, caloura de Engenharia de Software) está em seu primeiro mês na UTFPR. Ela se sente perdida com a rotina acadêmica, a burocracia e onde encontrar materiais de estudo de qualidade. Ela é tímida e prefere não fazer perguntas em sala de aula ou pessoalmente para não ser julgada.

Mariana faz sua pergunta no grupo do curso no WhatsApp. A conversa do grupo está agitada com memes e assuntos aleatórios. Sua pergunta é rapidamente perdida em meio a dezenas de mensagens. 

Lucas Andrade (Veterano) vê a pergunta, mas está no trabalho e acha repetitivo responder pela décima vez, então ele ignora.
Mariana fica frustrada, sente-se com a sua dificuldade não resolvida, e desiste de perguntar, recorrendo à pesquisa no Google, que não lhe dá a resposta específica da UTFPR.

_**Cenário: Depois**_

Mariana Silva (18 anos, caloura de Engenharia de Software) está em seu quarto, acessando o aplicativo ColabUTFPR pelo seu smartphone. O sistema, com sua interface simples, oferece um ambiente seguro e categorizado para suas dúvidas, diferente do caos do WhatsApp.

Mariana Silva (Caloura, busca informações e networking) e Lucas Andrade (Veterano, busca construir reputação e fazer networking de forma eficiente).

Mariana busca encontrar um grupo de estudos e dicas confiáveis sobre a disciplina de Cálculo I. Lucas pretende ajudar de forma rápida e estratégica, aumentando sua pontuação de reputação.

Mariana decide usar o ColabUTFPR porque sabe que o conteúdo é organizado por tópicos e filtrado por usuários da UTFPR, garantindo a confiabilidade das dicas. Lucas planeja responder apenas a perguntas que lhe darão visibilidade e que sejam pertinentes ao seu perfil.

## 2. Documentos gerais no repositório

[](https://github.com/ColabUTFPR/ColabUTFPR/blob/main/README.md#2-documentos-gerais-no-reposit%C3%B3rio)

_**2.1. Requisitos Funcionais**_

|identificador|descrição|prioridade|dependência|MoSCoW
|--|--|--|--|--|
|RF1|Cadastro deve permitir ao usuário o login via e-mail institucional e suporte para recuperação de senha|alta|sem dependências|M|
|RF2|o sistema deve possuir uma verificação de e-mail por confirmação, mandando um e-mail verificando se o e-mail pertece realmente ao usúario, após clicar em um link enviado para o e-mail fornecido, ele é confirmado e a criação de conta no aplicativo é efetivada com as informações fornecidas|alta|RF1|S|
|RF3|o sistema deve permitir que o usuário crie publicações na aba fórum, escolhendo um fórum em especifico|alta|RF1, RF2|S|
|RF4|o sistema deve permitir a anexação de imagens ou documentos em publicações e comendatários|média|RF3|C|
|RF5|o sistema deve permitir comentários dos usuários e reações em tópicos e/ou pubicações|alta|RF3|C|
|RF6|o sistema deve permitir a busca por outros usuários ou publicações com base em datas, categoria ou usuário|média|RF3, RF5|C|
|RF7|o sistema deve permitir a comunicação entre usuários por mensagens privadas com histórico de conversa, opções de bloqueio e denúncia de usuário|alta|RF1|C|
|RF8|o sistema deve permitir a edição do perfil do usuário(como foto de perfil e bio por exemplo)|média|RF1|S|
|RF9|o sistema deve ter uma aba para configurações de usuário, permitindo alterações de contraste, tema claro/escuro, uma aba para gerenciar contas bloqueadas, uma opção para excluir conta, uma aba de privacidade com configurações de quem pode mandar mensagens privadas e se sua conta pode ser exibida em pesquisas no aplicativo, além de uma opção para limpar seu histórico no aplicativo, uma aba com configurações de linguagem e uma para gerenciar as notificações enviadas, classificando com notificações de fóruns do qual o usuário faz parte, notificações de uma comunidade em que participa, e notificações de resposta a algum post, devendo dar a opção do usuário de ativar e desativar essas notificações (todas ou apenas uma das opções citadas anteriormente)|média|RF1|M|
|RF10|o sistema deverá ter um nível de ranking para medir a confiança nos usuários e seus posts com base em tempo de conta e reputação|média|RF3,RF5|C|
|RF11|o sistema deve permitir a denuncia de um post ou mensagens por outros usuários, caso haja um descumprimento das normas da comunidade|alta|RF3,RF5,RF7|M|
|RF12|o sistema deve possibilitar a exclusão de mensagens, contas ou publicações, se necessário, por usuários moderadores/admins|alta|RF1,RF3,RF7|S|
|RF13|o sistema deve categorizar as publicações por comunidades e assuntos|alta|RF3|C|
|RF14|o sistema deve conter uma aba de suporte para cada pagina do aplicativo|média|sem dependências|C|
|RF15|o sistema deve notificar os usuários em situações especificas como quando um post novo é criado em uma comunidade em que o usuário faz parte, quando alguém citar o usuário em algum fórum do qual o usuário faz parte, quando algum post ou comentário criado pelo usuário é respondido |baixa|RF1|C|
|RF16|a pagina de suporte do aplicativo deve conter uma aba para comentários envio de arquivos como prints ou logs e uma classificação de urgência dada pelo usuário |baixa|RF14|C|



_**2.2. Requisitos Não Funcionais**_

|identificador|descrição|categoria|escopo|prioridade|MoSCoW
|--|--|--|--|--|--
|RNF1|o sistema deve ser compatível com IOS, android e web|portabilidade|sistema|alta|M|
|RNF2|notificações com latência de até 5 segundos|eficiência|sistema|média|C|
|RNF3|o sistema deve ter proteções contra as principais falhas de segurança em partes criticas, como banco de dados e login de admin (XSS, SQL Injection, CSRF, DDoS, etc...) além de usar criptografia de ponta como HTTPS com TLS 1.2+|segurança|sistema|alta|S|
|RNF4|o sistema deve ser feito seguindo as práticas da programação orientada a objetos de modo a facilitar a manutenção, além de testes controlados com usuários betatesters permitindo que os mesmos abram feedbacks de versões mais recentes|manutenção/qualidade|sistema|média|S|
|RNF5|o sistema deve fazer um backup por hora, garantindo que caso haja um imprevisto, seja possível restaurar o sistema para sua versão mais recente e mais estável|confiabilidade|sistema|alta|S|
|RNF6|o sistema deve ter uma disponibilidade de no minimo 99,5% do tempo em base anual, equivalente a no máximo 1 dia e 19 horas de inatividade por ano |confiabilidade|sistema|alta|C|
|RNF7|o sistema deve ter um tempo de resposta preciso, de no máximo 3 segundos|eficiência|sistema|alta|C|
|RNF8|o executável em sistemas mobile(APK/IPA) deve ter um espaço de no máximo 300mb|eficiência|sistema|baixa|C|
|RNF9|o sistema deve garantir estabilidade com no mínimo 8000 usuários simultâneos sem perceptíveis perdas de desempenho|escalabilidade|sistema|média|S|
|RNF10|o sistema deve estar em alinhamento com a lei de proteção de dados pessoais dos usuários (LGPD)|legalidade|sistema|alta|M|
|RNF11|o sistema deve ter configurações Customizáveis para acessibilidade segundo os padrões da WCAG|acessibilidade|sistema|média|M|
|RNF12|o sistema deve guardar os logs para registro dos eventos de no mínimo 365 dias e acesso apenas de roots|segurança|sistema|alta|C|


_**2.3. Perguntas**_

[Perguntas - Entrevista ColabUTFPR](https://docs.google.com/document/d/1YW6ly_eckFNQA0txDjnmrfSQ03iJV_cfXsUcahRelWQ/edit?usp=sharing)

_**2.4. Entrevista**_

[entrevista gravada com o veterano Enrique](https://drive.google.com/file/d/19wEtH1sPg7lgcyuqkptIEpW_G3awXGO2/view?usp=sharing)

[transcrição da entrevista com o veterano Enrique](https://docs.google.com/document/d/1qm0872MMC3pkQ7XpTg7XXi7DJ7nCtuCmLC6f87nqBzA/edit?usp=sharing)

[entrevista gravada com o calouro João Miguel](https://drive.google.com/file/d/1bD_bAy79CcdEHa-tUxhTdgS18HIcpMYf/view?usp=sharing)
[transcrição da entrevista com o calouro João Miguel](https://docs.google.com/document/d/1mX9Nn_LTURqIWO_5uYEkzr7BWLMJybvdD-hh6vZ8Kds/edit?usp=sharing)


_**2.5. Histórias do Usuário**_

_<Imagem, arquivo (PDF), link com as Histórias de Usuário.>_

_**2.6. Diagramas de Caso de Uso e Especificações**_

_<Imagem, arquivo (PDF), link com Diagrama de Caso de Uso.>_

_**2.7. Diagramas de Atividades**_

_<Imagem, arquivo (PDF), link com Diagrama de Atividades.>_

_**2.8. Protótipos**_

_<Imagem, arquivo (PDF), link com Protótipo.>_

## Referências

[](https://github.com/ColabUTFPR/ColabUTFPR/blob/main/README.md#refer%C3%AAncias)

_<Esta seção é destinada à descrição das referências utilizadas pelo documento, como por exemplo, URLs e livros. Ver exemplo a seguir:>_

[1] “Glossário da  _USina_”, <_id_doc glossário_>, Versão <_versão_>. Localização: <_localização_>.
