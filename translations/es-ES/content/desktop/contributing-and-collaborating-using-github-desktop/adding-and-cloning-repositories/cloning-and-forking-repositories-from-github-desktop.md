---
title: Cómo clonar y bifurcar repositorios desde GitHub Desktop
intro: 'Puedes utilizar {% data variables.product.prodname_desktop %} para clonar y ramificar los repositorios que están en {% data variables.product.prodname_dotcom %}.'
redirect_from:
  - /desktop/contributing-to-projects/cloning-a-repository-from-github-desktop
  - /desktop/contributing-to-projects/cloning-and-forking-repositories-from-github-desktop
  - /desktop/contributing-and-collaborating-using-github-desktop/cloning-and-forking-repositories-from-github-desktop
versions:
  fpt: '*'
shortTitle: Clone & fork from Desktop
ms.openlocfilehash: e4182e56d0418e3aea07c94e0a3657ef8e104ea0
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 09/05/2022
ms.locfileid: '145092320'
---
## Acerca de los repositorios locales
Los repositorios de {% data variables.product.prodname_dotcom %} son remotos. Puedes clonar o bifurcar un repositorio con {% data variables.product.prodname_desktop %} para crear un repositorio local en tu computadora.

Puedes crear una copia local de cualquier repositorio de {% data variables.product.product_name %} al que tengas acceso si lo clonas. Si un repositorio te pertenece o si tienes permisos de escritura en él, puedes sincronizar la ubicación local y remota del mismo. Para más información, vea "[Sincronización de la rama](/desktop/contributing-and-collaborating-using-github-desktop/syncing-your-branch)".

Cuando clonas un repositorio, cualquier cambio que subas a {% data variables.product.product_name %} afectará al original. Para hacer cambios sin afectar al proyecto original, puedes crear una copia separada si bifurcas el repositorio. Puedes crear una solicitud de cambios para proponer que los mantenedores incorporen los cambios de tu bifurcación en el repositorio ascendente original. Para obtener más información, vea "[Acerca de las bifurcaciones](/pull-requests/collaborating-with-pull-requests/working-with-forks/about-forks)".

Cuando intentas utilizar {% data variables.product.prodname_desktop %} para clonar un repositorio en el que no tienes acceso de escritura, {% data variables.product.prodname_desktop %} te pedirá crear una bifurcación automáticamente. Puedes elegir utilizar tu bifurcación para contribuir con el repositorio ascendente original o trabajar independientemente en tu propio proyecto. Cualquier bifurcación existente estará predeterminada para contribuir con cambios hacia su repositorio ascendente. Puedes modificar esta elección en cualquier momento. Para obtener más información, consulta "[Administrar el comportamiento de una bifurcación](#managing-fork-behavior)".

También puedes clonar un repositorio directamente desde {% data variables.product.prodname_dotcom %} o {% data variables.product.prodname_enterprise %}. Para obtener más información, consulta "[Clonación de un repositorio de {% data variables.product.prodname_dotcom %} en {% data variables.product.prodname_desktop %}](/desktop/guides/contributing-to-projects/cloning-a-repository-from-github-to-github-desktop/)".

## Clonar un repositorio

{% data reusables.desktop.choose-clone-repository %} {% data reusables.desktop.cloning-location-tab %} {% data reusables.desktop.cloning-repository-list %} {% data reusables.desktop.choose-local-path %} {% data reusables.desktop.click-clone %}

## Bifurcar un repositorio
Si clonas un repositorio en el cual no tengas acceso de escritura, {% data variables.product.prodname_desktop %} creará una bifurcación. Después de crear o clonar una bifurcación, {% data variables.product.prodname_desktop %} te preguntará cómo piensas utilizarla.

{% data reusables.desktop.choose-clone-repository %} {% data reusables.desktop.cloning-location-tab %} {% data reusables.desktop.cloning-repository-list %} {% data reusables.desktop.choose-local-path %} {% data reusables.desktop.click-clone %} {% data reusables.desktop.fork-type-prompt %}

## Administrar el comportamiento de una bifurcación
Puedes cambiar la forma en la que se comporta una bifurcación con respecto su repositorio ascendente de {% data variables.product.prodname_desktop %}.

{% data reusables.desktop.open-repository-settings %} {% data reusables.desktop.select-fork-behavior %}

## Crear un alias para un repositorio local
Puedes crear un alias para de un repositorio local para ayudarte a diferenciar entre reposiotorios con el mismo nombre en {% data variables.product.prodname_desktop %}. Crear un alias no afecta el nombre del repositorio en {% data variables.product.prodname_dotcom %}. En la lista de repositorios, los alias aparecen en letra itálica.

1. En la esquina superior izquierda de {% data variables.product.prodname_desktop %}, a la derecha del nombre del repositorio actual, haz clic en {% octicon "triangle-down" aria-label="The triangle-down icon" %}.
2. Haz clic con el botón derecho en el repositorio para el que quieres crear un alias y, a continuación, haz clic en **Crear alias**.
3. Teclea un alias para el repositorio.
4. Haz clic en **Crear alias**.

## Información adicional
- [Acerca de los repositorios remotos](/github/getting-started-with-github/about-remote-repositories)
