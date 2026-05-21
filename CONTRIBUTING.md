# Guia de Contribuição (Contributing Guide)

Seja muito bem-vindo! Ficamos extremamente felizes com o seu interesse em contribuir para o **OpenTaipa**! 🎉

Este documento fornece as diretrizes básicas para que você possa colaborar com o projeto de forma eficiente, respeitosa e produtiva.

---

## 🗺️ Como Posso Contribuir?

Você pode apoiar o OpenTaipa de diversas maneiras, não apenas escrevendo código:

1. **Relatando Bugs:** Se você encontrou algo que não funciona como esperado, abra uma **Issue** relatando o problema.
2. **Propondo Novas Ideias:** Tem uma sugestão de recurso ou melhoria na arquitetura? Adoraríamos discutir na aba de **Discussions** ou através de uma Issue de proposta.
3. **Melhorando a Documentação:** Correções ortográficas, melhorias em tutoriais e exemplos práticos são contribuições valiosíssimas.
4. **Enviando Código:** Correções de bugs e novas funcionalidades são sempre bem-vindas via Pull Requests (PRs).

---

## 🐛 Relatando um Bug

Antes de abrir uma nova Issue, por favor:
* Verifique se já não existe uma Issue ativa relatando o mesmo problema.
* Se for um problema de segurança crítico, consulte nossa [Política de Segurança](SECURITY.md) para saber como relatar de forma privada.

Ao abrir a Issue, forneça o máximo de informações possível:
* **Descrição Clara:** O que aconteceu e qual era o comportamento esperado.
* **Passo a Passo para Reproduzir:** Comandos executados ou trecho de código utilizado.
* **Detalhes do Ambiente:** Sistema operacional, versão do Node.js/Bun e versão do OpenTaipa instalada.

---

## 🛠️ Enviando uma Pull Request (PR)

Se você decidiu colocar as mãos na massa e escrever código ou documentação, siga este fluxo de trabalho básico:

1. **Fork e Clone:**
   * Faça um fork do repositório correspondente no GitHub.
   * Clone o seu fork localmente:
     ```bash
     git clone git@github.com:seu-usuario/nome-do-repositorio.git
     ```
2. **Crie uma Branch Temática:**
   * Sempre crie uma branch específica para a sua alteração, baseada na branch `main`:
     ```bash
     git checkout -b feature/minha-nova-funcionalidade
     # ou
     git checkout -b fix/correcao-do-bug-x
     ```
3. **Desenvolva e Teste:**
   * Faça as alterações necessárias no código ou documentação.
   * Certifique-se de seguir as regras de estilo de código do projeto.
   * **Rode os testes locais** (quando aplicável) para garantir que nada foi quebrado.
4. **Commite com Clareza:**
   * Faça commits pequenos e com mensagens claras que facilitem a revisão histórica.
5. **Faça o Push e Abra a PR:**
   * Envie a branch para o seu fork:
     ```bash
     git push origin minha-nova-funcionalidade
     ```
   * Vá ao repositório original do OpenTaipa no GitHub e abra uma Pull Request.
   * Descreva de forma concisa o que a sua PR resolve e qual o impacto planejado.

---

## ⚖️ Código de Conduta

Ao interagir com este projeto, você concorda em seguir e respeitar as diretrizes de convivência do nosso [Código de Conduta](CODE_OF_CONDUCT.md). Ajudar a construir uma comunidade diversa e acolhedora é de responsabilidade de todos nós.

Agradecemos imensamente a sua colaboração!
