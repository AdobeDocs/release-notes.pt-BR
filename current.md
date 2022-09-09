---
title: Notas de versão mais recentes
description: Leia as notas de versão mais recentes do Adobe [!DNL Experience Cloud] produtos e serviços. Saiba mais sobre os eventos futuros e a nova documentação no Experience League. Descubra os tutoriais e cursos mais recentes para [!DNL Experience Cloud] aplicativos.
doc-type: release notes
last-update: September 2022
author: mfrei
mini-toc-levels: 2
exl-id: 091f0168-21b0-4f48-a02b-d70e96b84e27
source-git-commit: 7c5a6c8ca64bef6ae2421b24a51ab4d0237d186d
workflow-type: tm+mt
source-wordcount: '5431'
ht-degree: 42%

---

# REVISÃO INTERNA - Notas de versão da Adobe Experience Cloud - setembro de 2022

![Banner](assets/experience-cloud-banner-3.png)

Como um criador de experiências, o seu caminho para o sucesso começa com a [Experience League](https://experienceleague.adobe.com/?lang=pt-BR#home). Encontre uma biblioteca ampla de documentação de instruções, tutoriais autoguiados, vídeos de instruções e cursos para todos os níveis e funções, uma comunidade online de usuários e suporte especializado quando precisar.

>[!NOTE]
>
>Para receber uma notificação por email mensal sobre atualizações nessa página, assine a [Atualização Prioritária de Produto da Adobe](https://www.adobe.com/subscription/priority-product-update.html). Verifique com frequência para ficar por dentro do que está acontecendo na Experience League.

Última atualização: **9 de setembro de 2022**

* [[!DNL Experience League] events](#events) (atualizado **Setembro 7**)
* [[!DNL Adobe System Status]](#status)
* [Experience Cloud — componentes e administração da interface central](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cja)
* [[!DNL Streaming Media Analytics]](#sma)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Experience Manager Guides]](#xml-doc)
* [[!DNL Adobe Commerce]](#commerce)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)
* [Blueprints de experiência digital - tutoriais](#blueprints)

Precisa de ajuda? Visite a [Experience League](https://experienceleague.adobe.com/?lang=pt-BR#home) para encontrar documentação técnica e de produtos, cursos com curadoria da Adobe, tutoriais em vídeo, respostas rápidas, insights da comunidade e treinamento ministrado por instrutores.

## ![Ícone](/assets/experience-league.png) Eventos da [!DNL Experience League] {#events}

Os eventos da Experience League são um excelente local para aprender, interagir e obter respostas de especialistas sobre produtos da Adobe. Consulte os [Eventos](https://experienceleague.adobe.com/events/?lang=pt-BR) de julho de 2022 na Experience League para continuar atualizado.

Atualizado **8 de setembro de 2022**

| Nome do produto / evento | Tipo | Descrição |
| -----------|---------- | ----|
| **[!DNL Adobe Analytics]** | Webinário | _Experience Manager - O Skill Exchange_ - Junte-se a nós para o nosso Adobe [!DNL Analytics] edição, onde especialistas lhe dão o furo interno no Adobe [!DNL Analytics]. <p>**Data:** 8 de setembro às 9:00 PT - [Detalhes e registro](https://events.bizzabo.com/411737?promo=ExperienceLeague&amp;tr=true) |
| **[!DNL Adobe Workfront]** | Workshop | Procurando uma oportunidade de se conectar com outros clientes e discutir [!DNL Workfront] recursos? Associe-se à nossa série CS Connections! Uma oportunidade mensal de se conectar com outros clientes para discutir os tópicos principais de sua organização.<p>**Data:** 12 de setembro às 7:00 MT [Detalhes e registro](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,mjTFCSLTbkuVKavNdopApA,dndSyq-qPkqd5A929WkXkw,frxd5xOTA0WDD-QNQbG9Ww,N0rLVNiX1EKbZDmYfMbfKg,mwypq4e8M0qTYr1PjHWlgg?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |
| **[!DNL Experience Cloud]** | Webinário | _Experience Manager Live_ - Um evento gratuito com chaves de Sara Blakely, Peyton Manning e Eli Manning.<p>**Data:** 13 e 14 de setembro - [Detalhes e inscrição](https://business.adobe.com/events/experience-makers-live.html?lang=pt-BR) |
| **[!DNL Adobe Workfront]** | Workshop | Fluxos de trabalho de diagramação - Junte-se à equipe de sucesso do cliente para obter uma discussão ao vivo e uma apresentação dos fluxos de trabalho de diagramação - da entrada até a conclusão - e entenda como definir uma base sólida para práticas eficazes de gerenciamento de trabalho. <p>**Data:** 20 e de setembro - [Detalhes e inscrição](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,hKbbhANIJ0GUZ80-hyYRPQ,eHZZsesEKEW-f54PGw4z9w,8IgA8CD5yEyKFei9pwlDJA,iACjdG_hK0m1uoTTaMinZA,TEaHrWBF3USQb49XCqymTg?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |
| **[!DNL Adobe Campaign]** (Classic e Standard) | Webinário | A temporada de férias, uma temporada de pico e a época mais movimentada do ano para profissionais de marketing entre canais, está ao virar da esquina. O planejamento deve estar bem em andamento. Essa [!DNL Adobe Campaign] A sessão do Insider aborda tópicos que ajudam na capacidade de fornecimento de email, [!DNL Adobe Campaign] ajuste de desempenho e práticas recomendadas de fluxo de trabalho e delivery para garantir que sua instância esteja em forma para pico de atividade.<p>**Data:** 15 de setembro às 8:00 PT [Detalhes e registro](https://adobe-campaign-insider.dxfieldmarketing.adobeevents.com/) |
| **[!DNL Adobe Workfront]** | Webinário | _Princípios básicos de administração de sistema: Introdução ao gerenciamento de recursos_ - Usando o Adobe [!DNL Workfront] para gerenciar seus recursos, é o DREAM - conhecer o trabalho que precisa ser feito, quais recursos você pode acessar e atribuí-los com base em sua disponibilidade. Junte-se a nós para saber como.<p>**Data:** 21 de setembro às 8:00 Reino Unido [Detalhes e registro](https://webinars.on24.com/adobe_workfront/AdminEssentialsRM?partnerref=exl) |
| **[!DNL Adobe Workfront]** | Workshop | _Série Value Realization: Justificar modelos de projeto_ - Junte-se a nós para o nosso debate sobre [!UICONTROL Modelos de projeto] e as diferentes maneiras que agregam valor e criam eficiência para as organizações. Abordaremos diferentes abordagens para estruturar modelos para apoiar seus projetos - por campanha, por deliverable e assim por diante. Vamos demonstrar alguns favoritos, assim como percorrer nossos últimos blueprints. <p>**Data:** 21 de setembro às 12:30 MT [Detalhes e registro](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,mjTFCSLTbkuVKavNdopApA,dndSyq-qPkqd5A929WkXkw,fir0yEdzREq77VYkVxk2kw,W3nJ9w4q-U69PVqUTk7D6Q,zs6GtWtgRkyikfMUMzBEmw?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |
| **[!DNL Adobe Workfront]** | Workshop | _10 Dicas de comunicação para manter você e seus usuários no controle_ - A comunicação eficaz é parte integral de você, de seus usuários e, por fim, do sucesso da empresa. Este workshop fornece dez dicas - dentro e fora de [!DNL Workfront] - contribuir para promover o desempenho, a produtividade e reduzir o risco de problemas desnecessários. <p>**Data:** 22 de setembro às 19:00 MT [Detalhes e registro](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,PiX3iDTmREqs2eOICcUIoA,5KJVGb6S_Uiiki7ErNALgw,Jcg3aU0zf0uG9pB-_vmCUg,pdnZcB-mqk2_nMKUQEQnsA,xYRXQWa6OU6_tvNTp_vuFQ?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |
| **[!DNL Adobe Campaign Classic]** e **[!DNL Adobe Campaign Standard]** | Workshop | _Quebra de Café da Comunidade em Perguntas e Respostas_ - Junte-se a Tamara Wulf e Earl Ross para conversar sobre as suas questões relacionadas com os tópicos [!DNL Adobe Campaign] Webinar do Insider em _Lista de verificação do sucesso durante os feriados e períodos de pico_. <p>**Data:** 22 de setembro às 20:00 MT [Detalhes e registro](https://adobe.ly/3KHrGpl) |
| **[!DNL Adobe Workfront]** | Workshop | _Condução da adoção com painéis: Planejadores_ - Associe-se à equipe de Sucesso do Cliente à medida que continuamos a nova série de painéis com base no [!DNL Adobe Workfront] persona. Essa sessão se concentra nos seus Planejadores, que geralmente funcionam na função de gerenciamento de projetos ou iniciativas. Saiba como criar um espaço pró-ativo e orientado para a equipe para conscientização da atividade e responsabilidade. <p>**Data:** 27 de setembro às 9:00 MT [Detalhes e registro](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,hKbbhANIJ0GUZ80-hyYRPQ,eHZZsesEKEW-f54PGw4z9w,Y1He1usOwUaIvlln-RiUCw,PbQY6cwRBkiHr0Uxk8YBow,2QMMEWx0e0C65kbQ1d4cIA?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |
| **[!DNL Adobe Workfront]** | Workshop | _Série Value Realization: Roteiro da Jornada do Workfront_ - O que vem a seguir na sua Jornada do Workfront?  Junte-se a nós para conversar sobre como criar seu próprio roteiro para o Adobe Workfront em sua organização. Compartilharemos algumas ideias sobre nossos marcos favoritos para adicionar ao seu roteiro, bem como nossas experiências como ex-Administradores do sistema.<p>**Data:** 14 de outubro às 12:30 MT [Detalhes e registro](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,mjTFCSLTbkuVKavNdopApA,dndSyq-qPkqd5A929WkXkw,Bx3LyyABjkC6f0LfiHlHgw,F_Tenijn5UulPjqprok8eg,7lni6LpvlEWagR1OIDfosA?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |
| **[!DNL Adobe Workfront]** | Workshop | _Conexões CS: Compartilhamento de práticas recomendadas estratégicas_ - Procurando uma oportunidade de se conectar com outros clientes e discutir os recursos do Workfront? Associe-se à nossa série CS Connections!  Uma oportunidade mensal de se conectar com outros clientes para discutir os tópicos principais de sua organização. Faremos um brainstorm junto com Sys Admins para resolver desafios, compartilhar ideias e discutir práticas recomendadas. <p>**Data:** 10 de outubro às 7:00 MT [Detalhes e registro](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,mjTFCSLTbkuVKavNdopApA,dndSyq-qPkqd5A929WkXkw,gw8sK1IYp0qugO85lvn9HA,1hAkk731fE2cuzI1JCe2Aw,Lox5X4bDSUC_HaF3SDUy7A?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |
| **[!DNL Adobe Workfront]** | Workshop | _Promover a adoção com o gerenciamento de usuários_ - Você está começando a usar o Workfront e quer se familiarizar com as funções de configuração relacionadas aos usuários finais? Junte-se à equipe de Sucesso do Cliente enquanto revisamos exemplos práticos de relatórios e painéis para definir uma base para o gerenciamento bem-sucedido do usuário e criar uma experiência útil e informativa do usuário final.<p>**Data:** 18 de outubro às 9:00 MT [Detalhes e registro](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,hKbbhANIJ0GUZ80-hyYRPQ,eHZZsesEKEW-f54PGw4z9w,lJV3sMGDTE2CpLxcuzZQXg,KGHthDBZ80q9JJ-wzHyqBQ,mY-6BCClJkmc_bRvqGebtQ?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |
| **[!DNL Adobe Workfront]** | Workshop | _Séries de adoção: Diversão do Workfront (front)!_ Precisa de ideias de adoção? Nós os temos! Nossa equipe tem passado pelos altos e baixos da adoção do usuário e focar na diversão é a chave para o sucesso. Vamos conversar com alguns itens que funcionaram para nós e fornecer tempo suficiente para uma discussão aberta compartilhar ideias com outros clientes.<p>**Data:** 20 de outubro às 12:30 MT [Detalhes e registro](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,mjTFCSLTbkuVKavNdopApA,dndSyq-qPkqd5A929WkXkw,0qiSuEYEcUSxTibSYXD-jA,8QGOKlkyJE25EiBggDF6Ng,WmVegsyV2E6ZDPSMCifdVw?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |

{style=&quot;table-layout:auto&quot;}

Consulte [Eventos](https://experienceleague.adobe.com/events/?lang=en) na Experience League para manter-se atualizado sobre eventos futuros e episódios anteriores.

## ![Ícone](/assets/system-status.png) [!DNL Adobe System Status] {#status}

O [!DNL Adobe System Status] fornece informações detalhadas, atualizações de status e notificações por email sobre eventos de interrupção e manutenção de produtos e serviços da Adobe. Confira em [status.adobe.com](https://status.adobe.com/pt-BR).

Para obter as informações mais recentes da versão, consulte as [notas de versão](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=pt-BR#status) do Status do sistema da Adobe.

## ![Ícone](/assets/ec_appicon_24.png) Experience Cloud — componentes e administração da interface central {#ecloud}

Os [componentes da interface central](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=pt-BR) da Experience Cloud incluem recursos disponíveis na página inicial e no cabeçalho persistente do produto. Esses recursos incluem configurações de perfil do usuário, preferências e pesquisa. Você também encontra ajuda para o gerenciamento de usuários e produtos, atributos do cliente e públicos-alvo da Experience Cloud.

### Atualização de provisionamento

>[!IMPORTANT]
>
>Administradores, não percam esse [aviso importante](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=pt-BR#julho---2022) sobre o provisionamento da Experience Cloud (publicado em julho de 2022).

## ![ícone](/assets/experience_platform_appicon_24.png) Adobe [!DNL Experience Platform] {#platform}

Informações da última versão e nova documentação para a [!DNL Experience Platform] e o [!UICONTROL SDK móvel]:

Versão planejada: **28 de setembro de 2022**

* [Notas de versão do Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=pt-BR) - (24 de agosto de 2022)

### [!DNL Adobe Mobile] SDK

Atualizado: **1 de setembro de 2022** - Consulte [Notas de versão e logs de alterações](https://aep-sdks.gitbook.io/docs/release-notes) para os SDKs do Adobe Experience Platform Mobile.

## ![Ícone](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Próxima versão: **14 de setembro de 2022**

Última atualização: **6 de setembro de 2022**

* [Notas de versão](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=pt-BR) do Adobe Analytics 
* [Documentação de produto e tutoriais](https://experienceleague.adobe.com/docs/analytics.html?lang=pt-BR) do Adobe Analytics

### AppMeasurement {#appm}

Versão de lançamento: **2.22.4**

* [AppMeasurement para notas de versão do JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=pt-BR)

### Novos tutoriais e cursos da [!DNL Analytics] {#tutorials-analytics}

Novos tutoriais em vídeo, artigos e cursos publicados para o Adobe Analytics.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Setembro de 2022 | [Criar uma visualização de fluxo](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analyzing-customer-journeys/flow-visualization.html?lang=en) | Vídeo | Saiba como usar visualizações de Fluxo para explorar as jornadas exatas que os clientes têm com sua marca. |

{style=&quot;table-layout:auto&quot;}

## ![Ícone](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

Última atualização: **6 de setembro de 2022**

* [Notas de versão](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=pt-BR) do Customer Journey Analytics 
* [Documentação de produto e tutoriais](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=pt-BR) do Customer Journey Analytics

### Novos tutoriais e cursos do Customer Journey Analytics {#tutorials-cja}

Novos vídeos, tutoriais ou cursos publicados para o CJA.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Setembro de 2022 | [Publicação de público alvo para o Customer Journey Analytics](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/components/audiences/audience-publishing-for-cja.html) | Vídeo | Saiba como usar o Customer Journey Analytics para publicar públicos-alvo descobertos de sua análise no Perfil do cliente em tempo real da Adobe Experience Platform para ativação de segmentos, usando Adobe Real-time Customer Data Platform ou Adobe Journey Optimizer. |

{style=&quot;table-layout:auto&quot;}

## ![Ícone](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

Última atualização: **23 de março de 2022**

* [Notas de versão](https://experienceleague.adobe.com/docs/media-analytics/using/additional-resources/release-notes.html?lang=pt-BR) do [!DNL Streaming Media Analytics]
* [Documentação do produto e tutoriais](https://experienceleague.adobe.com/docs/media-analytics/using/media-overview.html?lang=pt-BR) do [!DNL Streaming Media Analytics]

## ![Ícone](/assets/audience-manager.png) Audience Manager {#aam}

Não atualizado

Para obter recursos de autoajuda, consulte a [Documentação e tutoriais do Audience Manager](https://experienceleague.adobe.com/docs/audience-manager.html?lang=pt-BR) na Experience League.

## ![Ícone](/assets/aem.png) Adobe Experience Manager {#aem}

Novos recursos, correções e atualizações no Experience Manager. A Adobe recomenda que os clientes com implantações no local implantem os patches mais recentes de forma a assegurar maior estabilidade, segurança e desempenho.

Consulte [Notas de versão atuais do Adobe Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/release-notes/release-notes-current.html?lang=en)

A Adobe recomenda visitar a página de [Roteiros e atualizações de versão do Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=pt-BR) para se manter atualizado sobre as informações de lançamento.

### Vídeos de atualização do produto

Observe a [Vídeo Visão geral da versão de agosto](https://experienceleague.adobe.com/docs/experience-manager-release-overview-events/aemcsupdates/2022/2022-8-0.html?lang=pt-BR) para obter um resumo dos recursos adicionados na versão 2022.8.0 (agosto de 2022). <!-- Beginning with the video this month, Adobe has enabled localized closed captioning in French (FR), German (DE) and Japanese (JP). -->

* [Vídeo Visão geral da versão de julho de 2022](https://video.tv.adobe.com/v/345409/?quality=12)
* [Vídeo de visão geral da versão de junho de 2022](https://video.tv.adobe.com/v/344308/?quality=12)
* [Vídeo de visão geral da versão de maio de 2022](https://video.tv.adobe.com/v/343321/?quality=12)
* [Vídeo de visão geral da versão de abril de 2022](https://video.tv.adobe.com/v/342612?quality=12)
* [Vídeo de visão geral da versão de março de 2022](https://video.tv.adobe.com/v/341465)
* [Vídeo de visão geral da versão de janeiro de 2022](https://video.tv.adobe.com/v/340120)
* [Vídeo de visão geral da versão de dezembro de 2021](https://video.tv.adobe.com/v/339278)
* [Vídeo de visão geral da versão de outubro de 2021](https://video.tv.adobe.com/v/338253)
* [Vídeo de visão geral da versão de setembro de 2021](https://video.tv.adobe.com/v/337381)

### Novos cursos e tutoriais do Experience Manager {#tutorials-aem}

Novos vídeos, tutoriais e cursos publicados no mês passado.

| Publicado | Nome | Tipo | Descrição | Aplicativos |
| -----------| ---------- | ---------- | ---------- | ------|
| Setembro de 2022 | [Atualização da versão 2022.8.0 do AEM as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-release-overview-events/aemcsupdates/2022/2022-8-0.html?lang=en) | Vídeo | Ouça a equipe de produtos do AEM e saiba mais sobre os recursos e as inovações da versão mais recente do Adobe Experience Manager Assets, Assets Essentials, Sites, Commerce Integration Framework (CIF), Forms e Cloud Manager. | AEM |
| Setembro de 2022 | [Entrega de imagem otimizada para a Web](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/components/web-optimized-image-delivery.html?lang=en) | Vídeo | Saiba como habilitar a entrega de imagens otimizadas da Web em sites as a Cloud Service usando os Componentes principais AEM. | AEM Sites |
| Setembro de 2022 | [Integração com o Microsoft Power Automate](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/forms-cs-and-power-automate/integrate-formscs-power-automate.html?lang=en) | Vídeo | Chame fluxos do Power Automate em um envio de formulário adaptável. Saiba mais sobre as etapas para configurar e integrar o Forms CS com o Microsoft Power Automate. Analise os dados do formulário enviado e envie DoR como um anexo de email. | AEM Forms CS |
| Setembro de 2022 | [Série de eventos do Adobe Content Management Forum - 2022](https://experienceleague.adobe.com/docs/adobe-content-management-forum-events/events/2022/welcome.html?lang=en) | Vídeo | Assista ao endereço de boas-vindas e obtenha uma visão geral AEM, entregue por Elliot Sedegah. Também abrange desbloquear o poder da velocidade do conteúdo e muito mais. | AEM CS |
| Setembro de 2022 | [O Skill Exchange - Track do desenvolvedor - Destaque dos Experience Makers](https://experienceleague.adobe.com/docs/skill-exchange-events/events/aem/aug2022/developer-track/spotlight.html?lang=en) | Vídeo | Junte-se a nós como destacamos dois usuários AEM especialistas. Cada um compartilha sua melhor dica AEM ou truque. | AEM CS |
| Setembro de 2022 | [THe Skill Exchange - profissional de marketing/editor da Web](https://experienceleague.adobe.com/docs/skill-exchange-events/events/aem/aug2022/marketer/reusability.html?lang=en) | Vídeo | Saiba como utilizar fragmentos de experiência para direcionar a reutilização e a eficiência em todo o ecossistema. Isso afetará o ROI e a velocidade do drive. | AEM CS |
| Setembro de 2022 | [Como usar AEM React Editable Components v2](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/spa-editor/how-to/react-core-components-v2.html?lang=en) | Vídeo | Saiba como usar AEM React Editable Components. O AEM fornece AEM React Editable Components v2, um SDK baseado em Node.js que permite a criação de componentes React, que oferecem suporte à edição de componentes no contexto usando AEM Editor SPA. | AEM CS |

{style=&quot;table-layout:auto&quot;}

### Informações sobre a versão do Experience Manager

Todas as notas de versão do Experience Manager são mantidas nas seguintes páginas:

* [Informações sobre a versão do Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=en)
* [Notas de versão do Experience Manager Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/release-notes/current.html?lang=pt-BR)
* [Notas de versão do Serviço de conversão automatizada de formulários](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=pt-BR)
* [Notas de versão do Service Pack do Experience Manager 6.5](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=pt-BR)
* [Notas de versão do Cumulative Fix Pack do Experience Manager 6.4](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=pt-BR)
* [Notas de versão do Experience Manager Assets Dynamic Media](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=pt-BR)
* [Notas de versão do Experience Manager Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=pt-BR)
* [Notas de versão do aplicativo para desktop Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=pt-BR)
* [Notas de versão do Experience Manager Dispatcher](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=pt-BR)
* [Notas de versão do Adobe Primetime](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=pt-BR)
* [Notas de versão do Livefyre](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=pt-BR)

### Outros recursos de Ajuda do Experience Manager

* [Guias do Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=pt-BR)
* [Guia do Usuário do Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/introduction.html?lang=pt-BR)
* [Página de aprendizagem e suporte do Experience Manager 6.5](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=pt-BR)
* [Página de aprendizagem e suporte do Experience Manager 6.4](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=pt-BR)
* [Página de aprendizagem e suporte do Experience Manager 6.3](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=pt-BR)
* [Página de aprendizagem e suporte do Experience Manager 6.2](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=pt-BR#previous-updates)html
* [Versões anteriores da documentação do Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Página inicial de ajuda do Dynamic Media Classic](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=pt-BR)
* [Documentação do Experience Manager: atualizações recentes](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=pt-BR#aem-as-a-cloud-service)

## ![ícone](/assets/ec_appicon_24.png) Adobe [!DNL Experience Manager Guides] {#xml-doc}

[!DNL Experience Manager Guides]O é um aplicativo implantado no AEM. É uma solução poderosa de gerenciamento de conteúdo de componentes (CCMS) de nível empresarial que permite o suporte ao DITA nativo no Adobe Experience Manager, permitindo que o AEM lide com a criação e a entrega de conteúdo baseado em DITA.

Saiba mais sobre [[!DNL Experience Manager Guides]](https://www.adobe.com/br/products/xml-documentation-for-experience-manager/features.html).

### Recursos adicionais

* [[!DNL Experience Manager Guides]](https://experienceleague.adobe.com/docs/experience-manager-guides-learn/videos/overview.html?lang=pt-BR) - tutoriais na Experience League
* Aprendizagem e suporte do [[!DNL Experience Manager Guides] ](https://helpx.adobe.com/br/support/xml-documentation-for-experience-manager.html) - documentação do produto

## ![Ícone](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

Consulte os seguintes links para as notas de versão do Adobe Commerce:

* [Notas de versão do Adobe Commerce e Magento Open Source 2.4.x](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Notas de versão do Cloud Suite](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)
* [Notas de versão para Serviços de pagamento](https://experienceleague.adobe.com/docs/commerce-merchant-services/payment-services/release-notes.html)
* [Notas de versão do Product Recommendations](https://experienceleague.adobe.com/docs/commerce-merchant-services/product-recommendations/release-notes.html)
* [Notas de versão do Live Search](https://experienceleague.adobe.com/docs/commerce-merchant-services/live-search/release-notes.html)
* [Notas de versão para o preenchimento da loja](https://experienceleague.adobe.com/docs/commerce-merchant-services/store-fulfillment/release-notes.html)
* [Notas de versão do Amazon Sales Channel](https://experienceleague.adobe.com/docs/commerce-channels/amazon/release-notes.html)

>[!NOTE]
>
>[!DNL Adobe Search&Promote] o fim do serviço está programado para **1 de setembro de 2022**. Para pesquisa de produto e comércio, [Live Search](https://experienceleague.adobe.com/docs/commerce-merchant-services/live-search/overview.html?lang=en) é Adobe. Consulte a [anúncio do fim da vida útil](https://experienceleague.adobe.com/docs/search-promote/using/sp-eol.html?lang=en) para obter mais informações.

### Novos tutoriais e documentação do Adobe Commerce {#tutorials-commerce}

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Setembro de 2022 | [Nova classe-mestre do Relic - Assuma o controle de sua infraestrutura](https://experienceleague.adobe.com/docs/commerce-events/events/2022/new-relic.html?lang=en) | Vídeo | Associe-se a este webinário para saber como controlar sua infraestrutura com [!UICONTROL Novo Relic]. |
| Setembro de 2022 | [Benefícios da atualização para o Adobe Commerce 2.4.4](https://experienceleague.adobe.com/docs/commerce-events/events/2022/upgrade.html?lang=en) | Vídeo | Participe deste webinário para descobrir como planejar e executar uma atualização suave para aproveitar as vantagens das melhorias mais recentes. |
| Setembro de 2022 | [Fornecer experiências headless com o Adobe Experience Manager](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/headless.html?lang=pt-BR) | Vídeo | Saiba mais sobre o gerenciamento de experiência headless usando as melhorias mais recentes do Fragmento de conteúdo do Experience Manager e a nova API GraphQL para a entrega de conteúdo headless. |
| Setembro de 2022 | [Guia de gerenciamento do catálogo do Adobe Commerce](https://experienceleague.adobe.com/docs/commerce-admin/catalog/guide-overview.html) | Vídeo | Obtenha informações detalhadas sobre conteúdo e recursos de design, incluindo a criação de componentes básicos de conteúdo. |
| Setembro de 2022 | [Configurar vários sistemas de comércio](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/content-and-commerce/storefront/administering/multiple-commerce-systems-setup.html) | Vídeo | Saiba como configurar AEM com vários ambientes de comércio Adobe. |

{style=&quot;table-layout:auto&quot;}

## ![Ícone](/assets/target.png) [!DNL Adobe Target] {#target}

Última atualização: **6 de setembro de 2022**

* Para obter informações de pré-lançamento, consulte [Pré-lançamento do Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=pt-BR)
* Para obter informações atuais, consulte [Notas de versão do Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=pt-BR)

## ![Ícone](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

O Adobe Campaign oferece uma maneira intuitiva e automatizada de enviar mensagens individuais por canais de marketing online e offline. Agora, é possível prever o que seus clientes desejam usando as experiências determinadas por seus hábitos e preferências.

### Últimas versões de produto do Campaign

Saiba mais sobre as funcionalidades, as melhorias e as correções mais recentes nas notas de versão do [Campaign v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=pt-BR), do [Campaign v8](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html?lang=pt-BR) e do [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=pt-BR).

### Novos tutoriais e cursos do [!DNL Campaign] {#tutorials-campaign}

Novos vídeos, tutoriais ou cursos publicados para o Adobe Campaign.

| Publicado | Nome | Tipo | Descrição | Aplicativos |
| -----------| ---------- | ---------- | ---------- |---------- |
| Setembro de 2022 | [Configurar SMS para o Adobe Campaign](https://experienceleague.adobe.com/?recommended=Campaign-A-1-2022.classic.setupsms) | Curso | Saiba como conectar a instância do Campaign ao provedor SMTP e como analisar e solucionar problemas de configuração. | Campaign Classic v7 |
| Setembro de 2022 | [Configurar SMS para o Adobe Campaign](https://experienceleaguecommunities.adobe.com/t5/adobe-campaign-classic/course-discussion-set-up-sms-for-adobe-campaign/m-p/542687#M2301) | Curso | Saiba como conectar a instância do Campaign ao provedor SMTP e como analisar e solucionar problemas de configuração. | Campaign v8 |
| Setembro de 2022 | [Solução de problemas e detalhamentos sobre o protocolo SMPP](https://experienceleague.adobe.com/docs/campaign-learn/set-up-sms-for-adobe-campaign/smpp-deep-dive-and-troubleshooting.html?lang=pt-BR) | Vídeo | Saiba como as conexões SMPP são estabelecidas e como o SMPP troca dados por meio de PDUs. Saiba como solucionar problemas de conexão. | Campanha v8 |

{style=&quot;table-layout:auto&quot;}

### Recursos de ajuda do Campaign

* Adobe Campaign v8: [Documentação](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) - [Guias de implementação](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=pt-BR)
* Adobe Campaign Standard: [Documentação do Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=pt-BR) - [Planejamento de lançamento](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=pt-BR) - [Atualizações mais recentes da documentação](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=pt-BR)
* Adobe Campaign Classic: [Documentação do Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=pt-BR) - [Atualizações mais recentes da documentação](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=pt-BR)
* Painel de controle do Adobe Campaign: [Documentação](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=pt-BR)     - Vídeos tutoriais para [Vídeos tutoriais](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/control-panel-overview.html?lang=pt-BR)

## ![Ícone](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

Com [!DNL Journey Optimizer], você pode gerenciar campanhas programadas omnicanais e momentos individuais para milhões de clientes a partir de um único aplicativo, e toda a jornada é otimizada com decisões e insights inteligentes.

### Versões mais recentes do produto Journey Optimizer

Saiba mais sobre os recursos, melhorias e correções mais recentes nas [Notas de versão do Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=pt-BR).

### Novos tutoriais e cursos do Journey Optimizer {#tutorials-ajo}

Novos vídeos, tutoriais ou cursos publicados para o Adobe [!DNL Journey Optimizer].

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Setembro de 2022 | [Introdução ao gerenciamento de decisões para profissionais de marketing](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2020.1.offerdecisioning) | Vídeo | Saiba mais sobre os recursos de gerenciamento de decisões da Adobe Journey Optimizer. Este curso foi projetado para profissionais de marketing que desejam gerar receita, experiência do cliente e fidelidade, fornecendo as melhores ofertas aos clientes |
| Setembro de 2022 | [Criar uma campanha](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-campaigns/create-a-campaign.html?lang=en) | Vídeo | Saiba como fornecer conteúdo único a um público-alvo específico executando ações imediatamente ou em um cronograma especificado. |

{style=&quot;table-layout:auto&quot;}

### Mais recursos para o [!DNL Journey Optimizer]

* [Documentação do Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Tutoriais em vídeo](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=pt-BR)
* [Documentação do Gerenciamento de decisões](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioning/get-started-decision/starting-offer-decisioning.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Tutoriais em vídeo](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/introduction-to-decision-management.html?lang=pt-BR) - [Atualizações mais recentes da documentação](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=pt-BR)

## ![Ícone](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

Use a Experience Platform para orquestrar a jornada de um cliente em escala nos canais de experiência, antecipando de forma inteligente as necessidades de cada indivíduo em tempo real.

### Últimas versões de produto do [!DNL Journey Orchestration]

Saiba mais sobre os recursos, melhorias e correções mais recentes nas Notas de versão do [[!DNL Journey Orchestration] ](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=pt-BR).

#### Mais recursos para o [!DNL Journey Orchestration]

* [Documentação do Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [Tutoriais em vídeo](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=pt-BR) - [Atualizações mais recentes da documentação](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=pt-BR)

## ![Ícone](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

O [!DNL Marketo Engage] é um aplicativo completo para o gerenciamento de clientes potenciais e para os profissionais de marketing B2B que procuram transformar as experiências dos clientes envolvendo-se em cada estágio de jornadas de compras complexas.

### Atualizações do Core Marketo Engage

Consulte a [programação de lançamento](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=pt-BR) do [!DNL Marketo Engage] para obter as informações mais recentes sobre a programação de lançamento e notas de versão.

### Novos tutoriais e cursos do Marketo {#tutorials-marketo}

Novos vídeos, tutoriais ou cursos publicados para o Adobe Marketo.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Agosto de 2022 | [Tutoriais do Marketo Engage](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/overview.html?lang=en) | Vídeos | Visite a [Página inicial do tutorial do Marketo Engage](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/overview.html?lang=en) na Experience League para todos os tutoriais antigos e novos do Marketo Engage. |

{style=&quot;table-layout:auto&quot;}

Para obter a documentação mais recente do produto, consulte a página inicial da [Documentação de produto do Marketo](https://experienceleague.adobe.com/docs/marketo/using/home.html?lang=en)

## ![Ícone](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

O Adobe [!DNL Workfront] é um aplicativo unificado de gerenciamento de trabalho para compartilhar ideias, criar conteúdos, gerenciar processos complexos e fazer o melhor trabalho.

### Novos cursos e tutoriais do Adobe Workfront {#tutorials-workfront}

Novo curso do Workfront e coleções de tutoriais no Experience League.

**Observação:** A tradução no Experience League de todos os tutoriais e documentação do produto da Workfront será lançada em breve!

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Setembro de 2022 | [Cursos de Workfront](https://experienceleague.adobe.com/?recommended=Workfront-A-1-2022.1.admin&amp;lang=pt-BR) | Cursos | Navegue pelos novos cursos disponíveis para o Workfront no Experience League. |
| Setembro de 2022 | [Práticas recomendadas](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/best-practices/agile-bp.html?lang=en) | Artigos | Conheça as práticas recomendadas internas e externas [!DNL Workfront] especialistas em como usar o [!DNL Workfront] ferramentas para melhorar os processos de trabalho. |
| Setembro de 2022 | [Quadros](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/agile/boards/add-and-edit-column-settings-on-a-board.html?lang=en) | Vídeo | Assista a novos tutoriais que mostram como usar a nova ferramenta Quadros com a funcionalidade atual. |
| Setembro de 2022 | [Ágil: Scrum](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/agile/scrum/create-a-scrum-agile-team.html?lang=en) | Vídeo | Saiba como criar uma equipe ágil, selecionar a metodologia de arranhão e determinar as configurações para a equipe de arranhão. Assista aos tutoriais migrados do [!DNL Workfront One] que mostram como fazer a metodologia Scrum agile dentro do [!DNL Workfront]. |
| Setembro de 2022 | [Ágil: Kanban](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/agile/kanban/create-a-kanban-team.html?lang=en) | Vídeo | Assista aos tutoriais migrados do [!DNL Workfront One] que mostram como fazer a metodologia ágil kanban dentro do [!DNL Workfront] |
| Setembro de 2022 | [Calendário de Hora de Desligar Pessoal](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/manage-resources/personal-time-off-calendar/how-time-off-affects-project-timelines.html?lang=en) | Artigos | Visualize tutoriais que mostram por que o tempo limite pessoal é importante e como adicioná-lo no Workfront ao gerenciamento de recursos é mais fácil. |
| Setembro de 2022 | [Treinamento em Workfront Fusion](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/fusion/welcome-to-workfront-fusion/workfront-fusion-overview.html?lang=en) | Vídeo | Cada seção do Workfront Fusion contém vários tutoriais, com cada tutorial, apresentando os conceitos que você precisa entender antes de avançar para o próximo tutorial. Um exercício de explicação passo a passo ajuda você a principal a maioria dos conceitos. |

{style=&quot;table-layout:auto&quot;}

Consulte a página de [[!DNL Workfront] lançamentos de produtos](https://experienceleague.adobe.com/docs/workfront/using/product-announcements/product-releases/product-releases.html?lang=pt-BR) para obter um resumo das informações mais recentes de todos os produtos.

## ![Ícone](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

Notas de versão para [!DNL Adobe Advertising Cloud].

<!-- * [New features across [!DNL Advertising Cloud]](#adcloud-all) -->
<!-- * [New features in [!DNL Advertising Cloud DSP]](#adcloud-dsp) -->
* [Novos recursos no  [!DNL Advertising Cloud Search]](#adcloud-search)

<!-- * [New [!DNL Advertising Cloud] tutorials](#tutorials-ad-cloud) -->

<!--
### New features across [!DNL Advertising Cloud] {#adcloud-all}

Last updated: **August 9, 2022**

| Feature | Description |
| ------- | ----------- |
| Integration with [!DNL Adobe Analytics] | (August 6 release) Improvements to the data feed that Advertising Cloud sends to [!DNL Analytics] result in fewer mismatches between click/cost/impression data from the search engines and related conversion data in [!DNL Analytics]. |

{style="table-layout:auto"}
  
-->

<!--

### New features in [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Last updated: **July 27, 2022**

| Feature | Description |
| ------- | ----------- |
| [!UICONTROL Inventory] | (July 27 release) [!UICONTROL Auction Insights] is a new troubleshooting tool that allows you to analyze the deal composition of both guaranteed and non-guaranteed private deals. Using data visualizations, this tool shows the trend and relative proportions of values received for key auction attributes within a specific time period. |

-->

### Novos recursos no [!DNL Advertising Cloud Search] {#adcloud-search}

Última atualização: **9 de setembro de 2022** para a versão de 10 de setembro

| Recurso | Descrição |
| ------- | ----------- |
| [!UICONTROL Campanhas] | ([!DNL Google Ads] Contas; recurso beta) agora é possível criar e gerenciar [!DNL Google Ads] campanhas máximas de desempenho, que mostram e otimizam conversões de seus anúncios em canais usando [!DNL Google Ads] lance inteligente, utilizando o [!UICONTROL Tipo de campanha] &quot;[!UICONTROL Máximo de desempenho].&quot; |
|  | ([!DNL Google Ads] contas) A exibição Campanhas > Anúncios agora inclui uma [!UICONTROL Intensidade do anúncio] coluna, que indica o desempenho de cada anúncio de pesquisa responsiva (RSA) [!DNL Google Ads] práticas recomendadas para desempenho.<br><br>[!DNL Microsoft Advertising] O ainda não habilita suporte semelhante por meio da API. |
|  | ([!DNL Microsoft Advertising] contas) O suporte para sincronização, somente leitura e relatórios (incluindo dados de view-through) agora está disponível para suas campanhas de anúncios nativas na [!DNL Microsoft Audience Network], incluindo os que [!DNL Microsoft] anúncios de público-alvo. |
| [!UICONTROL Campanhas], [!UICONTROL Relatórios] | Mais métricas de compartilhamento de impressões do editor serão disponibilizadas nas semanas seguintes como colunas nas exibições e relatórios de gerenciamento de campanha. |
| [!UICONTROL Regras de valor de conversão] | ([!DNL Google Ads accounts]; recurso beta) Agora você pode visualizar suas regras de valor de conversão de [!UICONTROL Otimização] > [!UICONTROL Regras de valor de conversão]. Anunciantes com [!DNL Google Ads] o rastreamento de conversão no nível da conta individual ou inferior também pode criar e gerenciar regras.<br><br>A otimização automática das regras de valor de conversão estará disponível em uma versão futura. |
| [!UICONTROL Portfólios] | (recurso beta de Opt-in; [!DNL Google Ads] contas) [!DNL YouTube] campanhas com a [!UICONTROL Maximizar conversões] a estratégia de lance em portfólios híbridos agora é incluída nos resultados da simulação personalizada. O portfólio híbrido deve incluir apenas [!DNL YouTube] campanhas.<br><br>Para participar do programa beta, entre em contato com a equipe de conta. |
| [!UICONTROL Insights de publicidade] | O [!UICONTROL Insights de publicidade] A visualização tem uma nova aparência e fluxo de trabalho, com base em uma nova infraestrutura que melhora o desempenho e a confiabilidade. Agora, apenas clique em um nome de insight, selecione ou insira as configurações e clique em [!UICONTROL Gerar Insight].<br><br>Para retornar temporariamente para a exibição herdada, habilite [!UICONTROL Alternar para a interface antiga] no canto superior direito. A exibição herdada será removida no final de setembro. |
|  | O [!UICONTROL Consulta beta de correspondência cruzada] A análise agora está disponível. |
| [!UICONTROL Relatórios ] | ([!DNL Google Ads] somente contas) O novo relatório de especialidade [!UICONTROL Relatório de ativos RSA] mostra métricas de impressão para cada ativo ([!UICONTROL Título criativo] ou [!UICONTROL Descrição]) para anúncios de pesquisa responsivos (RSAs) em um ou mais portfólios ou uma ou mais contas, campanhas e grupos de anúncios. Por padrão, os dados incluem uma linha para cada ativo que recebeu pelo menos uma impressão no intervalo de dados especificado, mesmo que o ativo tenha sido desativado (removido) durante o período do relatório. **Observação:** Ao selecionar a opção para &quot;[!UICONTROL Incluir linhas sem dados de desempenho],&quot; os dados ainda não incluirão dados para ativos que nunca receberam dados. |
|  | O suporte adicional para anúncios de pesquisa responsivos (RSA) está disponível no [!UICONTROL Relatório de variação de anúncios]:<ul><ul>([!DNL Google Ads] somente contas) Na [!UICONTROL Colunas] , um novo &quot;[!UICONTROL Intensidade do anúncio]&quot; indica o desempenho do RSA [!DNL Google Ads] práticas recomendadas para desempenho. A mesma coluna está disponível no [!UICONTROL Campanhas] > [!UICONTROL Anúncios] exibir. [!DNL Microsoft Advertising] O ainda não habilita suporte semelhante por meio da API.</li><li>No [!UICONTROL Colunas] , você pode classificar os resultados do relatório por [!UICONTROL Títulos Criativos] e [!UICONTROL Descrições].</li><li>No [!UICONTROL Filtros avançados] , você pode filtrar pela variável [!UICONTROL Texto da Publicidade] , que se aplica a ambos [!UICONTROL Títulos Criativos] e [!UICONTROL Descrições].</li></ul> |
| [!UICONTROL Recomendações] | ([!DNL Google Ads] Contas; recurso beta) em [!UICONTROL Insights e relatórios] > [!UICONTROL Recommendations Beta], você pode:<ul><li>Veja imediatamente todas as recomendações que não foram seguidas para uma [!DNL Google Ads] conta.</li><li>Aplique e ignore as recomendações de uma conta.</li><li>Visualize logs de cada recomendação que foi aplicada para uma conta.</li></ul> |
| [!UICONTROL Importar campanhas] | (Recurso Beta) Você pode importar seu [!DNL Google Display Network] campanhas, incluindo imagens de anúncios, em [!DNL Microsoft Advertising] campanhas de público-alvo na [!DNL Microsoft Audience Network] from [!UICONTROL Ferramentas] > [!UICONTROL Importar campanhas]. Depois de importar campanhas, você pode verificar o status do seu trabalho de importação, revisar possíveis logs de erro e editar, pausar ou excluir o cronograma de importação. |

{style=&quot;table-layout:auto&quot;}

## ![Ícone](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

Novos tutoriais e cursos publicados para o Adobe Document Cloud, incluindo [!DNL Document Services] e [!DNL Acrobat Sign].

| Publicado | Nome | Tipo | Descrição | Aplicativo |
| -----------| ---------- | ---------- | ---------- |---------- |
| Setembro de 2022 | [Inscrever-se em uma conta de desenvolvedor](https://experienceleague.adobe.com/docs/document-services/tutorials/acrobatsign/sign-up-developer-account.html?lang=en) | Vídeo | Na parte 1 do _Guia de início rápido do Acrobat Sign Embed_, saiba como se inscrever em uma conta de desenvolvedor da API do Acrobat Sign. Sua nova conta do desenvolvedor é totalmente ativada com a funcionalidade Assinar e API . | Document Services |
| Setembro de 2022 | [Criação do aplicativo](https://experienceleague.adobe.com/docs/document-services/tutorials/acrobatsign/creating-your-application.html?lang=en) | Vídeo | Na parte 2 do _Guia de início rápido do Acrobat Sign Embed_, saiba como criar um aplicativo usando a API do Acrobat Sign. | Serviços de documento |
| Setembro de 2022 | [Criação de um link incorporado](https://experienceleague.adobe.com/docs/document-services/tutorials/acrobatsign/creating-an-embed-link.html?lang=en) | Vídeo | Na parte 3 do _Guia de início rápido do Acrobat Sign Embed_, saiba como criar um link incorporado para OAuth. Seu aplicativo obtém permissões para usuários usando esse método OAuth. | Serviços de documento |
| Setembro de 2022 | [Gerar um token de acesso](https://experienceleague.adobe.com/docs/document-services/tutorials/acrobatsign/generating-an-access-token.html?lang=en) | Vídeo | Na parte 4 do _Guia de início rápido do Acrobat Sign Embed_, saiba como gerar um token de acesso que pode ser usado com a API do Acrobat Sign. | Serviços de documento |
| Setembro de 2022 | [Criar um documento transitório](https://experienceleague.adobe.com/docs/document-services/tutorials/acrobatsign/creating-a-transient-document.html?lang=en) | Vídeo | Na parte 5 do _Guia de início rápido do Acrobat Sign Embed_, saiba como criar um documento transitório. | Serviços de documento |
| Setembro de 2022 | [Layout de ajuste automático](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/auto-adjust-layout.html?lang=en) | Vídeo | Saiba mais sobre o novo modo de edição que reflui o conteúdo e ajusta automaticamente o layout entre páginas no PDF. | Acrobat |
| Setembro de 2022 | [Adicionar página personalizada](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/add-custom-page.html) | Vídeo | Saiba como adicionar páginas personalizadas ao seu PDF usando o aplicativo Adobe Express integrado, que oferece milhares de modelos para escolher. | Acrobat |
| Setembro de 2022 | [Modificar um formulário web existente](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-managing/modify-webform.html?lang=en) | Vídeo | Saiba como desativar, editar e reativar um formulário da Web existente. | Acrobat Sign |
| Setembro de 2022 | [Criação de um relatório](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-managing/creating-a-report.html?lang=en) | Vídeo | Saiba como criar seus próprios relatórios para obter visibilidade sobre o processo de assinatura de documentos ou ver como grupos individuais ou usuários estão fazendo. | Acrobat Sign |
| Setembro de 2022 | [Criação de um gráfico de relatório](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/create-a-report.html?lang=en) | Vídeo (atualizado) | Saiba como criar, salvar e gerenciar seus próprios relatórios e exportações de dados personalizados em uma exibição personalizada com a nova experiência de relatórios. | Acrobat Sign |
| Setembro de 2022 | [Criação de um fluxo de trabalho personalizado](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/building-a-custom-workflow.html?lang=en) | Vídeo (atualizado) | Saiba como personalizar e automatizar fluxos de trabalho de documentos para obter assinaturas eletrônicas, coletar dados de formulários e confirmar a entrega de um documento importante para simplificar o gerenciamento do fluxo de trabalho. | Acrobat Sign |
| Setembro de 2022 | [Enviar para assinatura no Microsoft Teams](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/microsoft/adobe-sign-teams-mortgage.html?lang=en) | Vídeo (atualizado) | Saiba como enviar contratos para assinatura, verificar o status dos contratos e enviar lembretes de dentro do Microsoft Teams. | Acrobat Sign |
| Setembro de 2022 | [Adicionar campos aos documentos](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/adding-fields.html?lang=en) | Vídeo (atualizado) | Saiba como colocar campos automaticamente no documento ou usar o ambiente de criação de arrastar e soltar dentro do Acrobat Sign. | Acrobat Sign |
| Setembro de 2022 | [Configurar opções de envio](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/sending-options.html?lang=en) | Vídeo (atualizado) | Saiba como configurar várias opções ao enviar um documento para assinatura. | Acrobat Sign |

{style=&quot;table-layout:auto&quot;}

Para obter ajuda sobre a Document Cloud, consulte:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=pt-BR)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=pt-BR)
* [Aprendizagem &amp; suporte da Document Cloud](https://helpx.adobe.com/br/support/document-cloud.html)

## ![Ícone](/assets/creative-cloud-24.png) Adobe Creative Cloud para corporações {#creative-cloud}

Novos vídeos, tutoriais ou cursos publicados para o Adobe Campaign.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Setembro de 2022 | [Ansiedade da fonte de jogos com o Adobe Fonts ](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/assets/TamingTypeAnxiety.pdf?lang=en) | PDF | Saiba como o Adobe Fonts funciona neste tutorial prático. |
| Setembro de 2022 | [Adobe Acrobat para criadores de conteúdo](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/assets/AcrobatforContentCreators.pdf?lang=en) | PDF | Como criador de conteúdo, você provavelmente gera PDF e, em seguida, visualiza esses arquivos PDF no Adobe Acrobat. Mas o Acrobat também inclui muitas ferramentas que ajudam a simplificar os fluxos de trabalho criativos típicos. Aprenda duas ferramentas específicas: [!UICONTROL Compartilhamento com outros] e [!UICONTROL Proteção]. |

{style=&quot;table-layout:auto&quot;}

Consulte [Tutoriais da Creative Cloud para corporações](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=en) para obter os tutoriais mais recentes.

## ![Ícone](/assets/experience-league.png) Gerenciamento de dados do cliente — Vozes {#voices}

[Gerenciamento de dados do cliente — Vozes](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=pt-BR) é o seu destino como técnico de gerenciamento de dados e líder e especialista de práticas de marketing. Essa coleção de tutoriais é o seu balcão central para ouvir outros usuários, inspirar-se e conhecer os desenvolvimentos na MarTech. Não é necessário fazer um registro. Clique e assista.

## ![Ícone](/assets/experience-league.png) Blueprints de experiência digital {#blueprints}

Os [Blueprints de experiência digital](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=pt-BR) são implementações replicáveis que permitem abordar estratégias e solucionar problemas comerciais estabelecidos de maneira rápida. Cada blueprint oferece uma série de artefatos que explicam o problema comercial de alto valor e fornecem arquiteturas, etapas de implementação, considerações técnicas e links para a documentação relevante.

[Topo](#events)
