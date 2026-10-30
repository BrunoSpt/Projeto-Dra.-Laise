# Anamnese Digital — Pele Coreana Experience (protótipo)

Protótipo interativo de um formulário de anamnese digital para uma clínica de estética, criado para o atendimento de **limpeza de pele coreana**. A ideia é transformar a anamnese em parte da experiência: a paciente recebe um link, é acolhida com uma tela de boas-vindas e responde o formulário em etapas, em vez de preencher uma ficha em papel ou um formulário genérico.

> **Projeto de demonstração.** Nenhum dado é enviado, coletado ou armazenado. Tudo roda no navegador.

## Demonstração

🔗 [link ao vivo em breve]

## Fluxo do protótipo

1. **Boas-vindas**: apresenta a experiência antes das perguntas
2. **Etapa 1, "Sua pele hoje"**: nome, tipo de pele e interesse no ritual
3. **Etapa 2, "Sua rotina atual"**: limpeza de pele anterior e uso de protetor solar
4. **Confirmação**: mensagem personalizada com o primeiro nome informado pela paciente

## Funcionalidades

- Transições suaves entre as telas, sem recarregar a página
- Validação de campo obrigatório: a pergunta balança e mostra um aviso se a paciente tentar avançar sem responder
- Barra de progresso animada entre as etapas
- Opções de seleção única e de múltipla escolha
- Personalização da tela final com o nome digitado na primeira etapa
- Botão para recomeçar o protótipo, útil em apresentações
- Layout mobile-first, pensado para quem acessa o link pelo celular

## Tecnologias

- HTML5
- CSS3 (variáveis nativas, `clamp()` para tipografia e espaçamentos fluidos)
- JavaScript puro, sem frameworks nem dependências
- Fontes: Fraunces e Inter (Google Fonts)

## Como rodar localmente

1. Clone o repositório
2. Abra a pasta no VS Code
3. Instale a extensão **Live Server**
4. Clique com o botão direito em `index.html` e escolha **Open with Live Server**

Também funciona abrindo o `index.html` direto no navegador.

## Estrutura

```
anamnese-pele-coreana-prototipo/
├── index.html    # HTML, CSS e JS em um único arquivo
└── README.md
```

## Decisões de design

- **Uma tela por vez:** em vez de um formulário longo, cada etapa tem poucas perguntas, o que reduz o esforço percebido no celular.
- **Acolhimento antes das perguntas:** a tela inicial apresenta o ritual, e as etapas seguem a ideia de construir o cuidado com a pele em camadas.
- **Feedback imediato:** validação visual e progresso animado deixam claro onde a paciente está e o que falta.

## Próximos passos (versão de produção)

Este protótipo valida a experiência visual e o fluxo. Uma versão real exigiria:

- Envio e armazenamento seguro das respostas (por exemplo, planilha com acesso restrito ou banco de dados)
- Tela de consentimento explícito para tratamento de dados de saúde, conforme a LGPD
- Mais etapas de perguntas clínicas, definidas com a profissional
- Hospedagem com domínio próprio

## Autor

Desenvolvido por Bruno Lima e Silva · [GitHub](https://github.com/BrunoSpt)
