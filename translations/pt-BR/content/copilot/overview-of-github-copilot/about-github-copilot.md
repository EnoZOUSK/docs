---
title: Sobre o GitHub Copilot
intro: '{% data variables.product.prodname_copilot %} pode ajudar você a codificar oferecendo sugestões de preenchimento automático. Você pode aprender o que considerar ao usar {% data variables.product.prodname_copilot %} e como {% data variables.product.prodname_copilot %} funciona.'
versions:
  feature: copilot
topics:
  - Copilot
shortTitle: Sobre o GitHub Copilot
---

## Sobre {% data variables.product.prodname_copilot %}

{% data variables.product.prodname_copilot %} is an AI pair programmer that offers autocomplete-style suggestions as you code. Você pode receber sugestões de {% data variables.product.prodname_copilot %}, começando a escrever o código que deseja usar ou escrevendo um comentário em linguagem natural, descrevendo o que você quer que o código faça. {% data variables.product.prodname_copilot %} analisa o contexto no arquivo que você está editando, bem como arquivos relacionados e oferece sugestões de dentro de seu editor de texto.

{% data variables.product.prodname_copilot %} é otimizado para ajudar você a escrever Python, JavaScript, TypeScript, Ruby, Go, C# ou C++. Você também pode usar {% data variables.product.prodname_copilot %} para gerar sugestões em outras linguagens e uma grande variedade de estruturas. {% data variables.product.prodname_copilot %} é alimentado pelo OpenAI Codex, um novo sistema de IA criado pela OpenAI.

{% data variables.product.prodname_copilot %} está disponível como uma extensão em Visual Studio Code, Visual Studio, Neovim e no conjunto de IDEs do JetBrains. Para obter mais informações, consulte "[Introdução ao {% data variables.product.prodname_copilot %}](/copilot/getting-started-with-github-copilot)".

## Usar {% data variables.product.prodname_copilot %}

Você pode ver exemplos reais de {% data variables.product.prodname_copilot %} em ação. Para obter mais informações, consulte o site [{% data variables.product.prodname_copilot %}](https://copilot.github.com/).

O GitHub Copilot oferece sugestões de um modelo que o OpenAI construiu a partir de bilhões de linhas de código-fonte aberto. Como resultado, o conjunto de treinamento para {% data variables.product.prodname_copilot %} pode conter padrões de codificação inseguros, erros ou referências a APIs ou expressões desatualizadas. Quando {% data variables.product.prodname_copilot %} produz sugestões com base nesses dados de treinamento, essas sugestões também podem conter padrões indesejáveis.

Você é responsável por garantir a segurança e a qualidade do seu código. Recomendamos que você tome as mesmas precauções ao usar o código gerado por {% data variables.product.prodname_copilot %} que você faria ao usar qualquer código que não foi escrito por você. Essas precauções incluem testes rigorosos, digitalização de IP e rastreamento de vulnerabilidades de segurança. {% data variables.product.company_short %} fornece uma série de funcionalidades para ajudar você a monitorar e melhorar a qualidade do código, como {% data variables.product.prodname_actions %}, {% data variables.product.prodname_dependabot %}, {% data variables.product.prodname_codeql %} e {% data variables.product.prodname_code_scanning %}. Todos esses recursos são gratuitos para uso em repositórios públicos. Para obter mais informações, consulte "[Entendendo {% data variables.product.prodname_actions %}](/actions/learn-github-actions/understanding-github-actions)" e "[Funcionalidades de segurança de {% data variables.product.company_short %}](/code-security/getting-started/github-security-features).".

{% data variables.product.prodname_copilot %} usa filtros para bloquear palavras ofensivas nas instruções e evitar produzir sugestões em contextos sensíveis. We are committed to constantly improving the filter system to more intelligently detect and remove offensive suggestions generated by {% data variables.product.prodname_copilot %}, including biased, discriminatory, or abusive outputs. If you see an offensive suggestion generated by {% data variables.product.prodname_copilot %}, please report the suggestion directly to copilot-safety@github.com so that we can improve our safeguards.

## Sobre a cobrança do {% data variables.product.prodname_copilot %}

{% data variables.product.prodname_copilot %} is a paid feature, requiring a monthly or yearly subscription. Verified students and maintainers of popular open source projects on {% data variables.product.prodname_dotcom %} are eligible to use {% data variables.product.prodname_copilot %} for free. If you meet the criteria for a free {% data variables.product.prodname_copilot %} subscription, you will be automatically notified when you visit the {% data variables.product.prodname_copilot %} subscription page. If you do not meet the criteria for a free {% data variables.product.prodname_copilot %} subscription, you will be offered a 60 day free trial, after which a paid subscription is required for continued use. Para obter mais informações, consulte "[Sobre a cobrança do {% data variables.product.prodname_copilot %}](/billing/managing-billing-for-github-copilot/about-billing-for-github-copilot)".

## {% data variables.product.prodname_copilot %} Licensing Information for JetBrains Plugin

{% data variables.product.prodname_dotcom %}, Inc. is the licensor of the JetBrains plugin. The end user license agreement for this plugin is the [{% data variables.product.prodname_dotcom %} Terms for Additional Products and Features](/free-pro-team@latest/site-policy/github-terms/github-terms-for-additional-products-and-features#github-copilot) and use of this plugin is subject to those terms. JetBrains has no responsibility or liability in connection with the plugin or such agreement. By using the plugin, you agree to the foregoing terms.

## Leia mais

- "[{% data variables.product.company_short %} Terms for Additional Products and Features](/free-pro-team@latest/site-policy/github-terms/github-terms-for-additional-products-and-features#github-copilot)"
