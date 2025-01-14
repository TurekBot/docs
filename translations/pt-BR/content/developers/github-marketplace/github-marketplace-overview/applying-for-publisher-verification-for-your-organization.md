---
title: Candidatar-se à verificação de publicador para a sua organização
intro: 'Para oferecer planos pagos para seu aplicativo ou para incluir um selo no Marketplace no anúncio do seu aplicativo, você deverá concluir o processo de verificação de publicação para a sua organização.'
versions:
  fpt: '*'
  ghec: '*'
topics:
  - Marketplace
redirect_from:
  - /developers/github-marketplace/applying-for-publisher-verification-for-your-organization
shortTitle: Publisher verification
ms.openlocfilehash: 34085acb78eba5057cea382ab250e4704dd958d1
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/05/2022
ms.locfileid: '145083954'
---
A verificação do editor garante que {% data variables.product.prodname_dotcom %} tem uma forma de entrar em contato com você, que você habilitou a autenticação de dois fatores para a sua organização e que o domínio da sua organização foi verificado.

Assim que sua organização for verificada, você poderá publicar planos pagos para o seu aplicativo. Para obter informações, confira "[Como definir planos de preços para sua listagem](/developers/github-marketplace/setting-pricing-plans-for-your-listing)".

Para oferecer planos pagos para o seu aplicativo, este deverá pertencer a uma organização e você deverá ter permissões de proprietário na organização. Se seu aplicativo pertence atualmente a uma conta pessoal, você precisará transferir a propriedade do aplicativo para uma organização. Para obter mais informações, confira "[Como transferir a propriedade de um Aplicativo do GitHub](/developers/apps/transferring-ownership-of-a-github-app)" ou "[Como transferir a propriedade de um Aplicativo OAuth](/developers/apps/transferring-ownership-of-an-oauth-app)".

## Solicitar verificação de publicador


{% data reusables.profile.access_org %} {% data reusables.profile.org_settings %}
1. Na barra lateral esquerda, clique em **Configurações do desenvolvedor**.
  ![Opção Configurações do desenvolvedor na barra lateral das configurações da organização](/assets/images/marketplace/developer-settings-in-org-settings.png)
1. Em "Configurações do desenvolvedor", clique em **Verificação do Fornecedor**.
  ![Opção Verificação do fornecedor na barra lateral das configurações da organização](/assets/images/marketplace/publisher-verification-settings-option.png)
1. Em "Verificação do Publicador, preencha as informações na lista de verificação:
   - Certifique-se de que as suas informações básicas do perfil estejam presentes e precisas. Além disso, certifique-se de incluir o melhor endereço de e-mail para suporte e atualizações de {% data variables.product.company_short %}.
   - Certifique-se de que a autenticação de dois fatores esteja habilitada para a sua organização. Para obter mais informações, confira "[Como exigir a autenticação de dois fatores na sua organização](/organizations/keeping-your-organization-secure/requiring-two-factor-authentication-in-your-organization)".
   - Envie um domínio verificado e certifique-se de que um selo "Verificado" seja exibido na página de perfil da sua organização. Para obter informações relacionadas, confira "[Como verificar ou aprovar um domínio para sua organização](/organizations/managing-organization-settings/verifying-or-approving-a-domain-for-your-organization)".

  ![Lista de verificação do publicador](/assets/images/marketplace/publisher-verification-checklist.png)

2. Clique em **Solicitar Verificação**. {% data variables.product.company_short %} analisará as suas informações e informará assim que a verificação de publicação for concluída.

## Leitura adicional

Para obter informações sobre o processo de publicação de aplicativos, confira "[Sobre o GitHub Marketplace](/developers/github-marketplace/about-github-marketplace)".
