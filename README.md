# 🎨 Art About Color

### Smart Web Experience — No-code, padrões Web e automação

Projeto acadêmico da disciplina **Padrões Web para No Code e Low Code**, da **UniFECAF**, desenvolvido por **Daniel Fernandes Nakahara**.

A Art About Color é uma proposta de presença digital para um negócio de consultoria em cores, design e workshops. O projeto combina o editor visual do Wix com o desenvolvimento de um componente de atendimento personalizado.

🔗 **[Acessar o site](https://danfernaka26.wixsite.com/art-about-color)**

> **Estado do projeto:** interface publicada no endereço acima e documentada por capturas de tela. O fluxo completo do chatbot, o encaminhamento para o WhatsApp e a experiência em dispositivos móveis ainda precisam de validação final.

## 📌 Sumário

- [Problema e público](#problema-e-público)
- [Solução e funcionalidades](#solução-e-funcionalidades)
- [Tecnologias e ferramentas](#tecnologias-e-ferramentas)
- [Personalizações com padrões Web](#personalizações-com-padrões-web)
- [Automação de atendimento](#automação-de-atendimento)
- [Responsividade e acessibilidade](#responsividade-e-acessibilidade)
- [Imagens do projeto](#imagens-do-projeto)
- [Como acessar e testar](#como-acessar-e-testar)
- [Organização do repositório](#organização-do-repositório)
- [Limitações e aprendizados](#limitações-e-aprendizados)
- [Vídeo de apresentação](#vídeo-de-apresentação)

## Problema e público

Uma pequena empresa de serviços precisa apresentar seu trabalho na internet e facilitar o contato com possíveis clientes. Quando as informações ficam dispersas e todas as dúvidas dependem de atendimento manual, o visitante pode ter dificuldade para entender os serviços ou iniciar uma contratação.

A solução foi pensada para pessoas interessadas em **arte, cores, decoração, consultoria de design e workshops criativos**. Seu objetivo é reunir a apresentação do negócio e um acesso rápido ao atendimento em uma experiência web.

## Solução e funcionalidades

O site foi construído no Wix e apresenta uma identidade visual baseada em tons claros, detalhes em laranja e imagens relacionadas à arte.

| Recurso | Finalidade | Situação documentada |
| --- | --- | --- |
| Página inicial | Apresentar a marca e sua proposta | Visível na captura |
| Menu de navegação | Organizar o acesso às áreas do site | Visível; destinos a conferir |
| Botão “Explorar workshops” | Convidar o visitante a conhecer as atividades | Visível; ação a conferir |
| Vitrine de produtos | Exibir itens e seus preços | Visível; fluxo de compra não validado |
| Acesso ao chat | Facilitar o início do atendimento | Botão e saudação visíveis |
| Respostas automáticas | Orientar sobre dúvidas iniciais | Fluxo completo a validar |
| Encaminhamento para WhatsApp | Dar continuidade ao atendimento humano | Pendente de validação após erro identificado |

## Tecnologias e ferramentas

| Tecnologia ou ferramenta | Aplicação no projeto |
| --- | --- |
| **Wix** | Construção visual, organização das páginas e publicação |
| **HTML** | Estrutura do componente personalizado de atendimento |
| **CSS** | Aparência, dimensões, espaçamento e posicionamento do componente |
| **JavaScript** | Interações de abertura, fechamento, envio e lógica de atendimento |
| **WhatsApp** | Destino previsto para continuidade do contato com um atendente |
| **GitHub e Markdown** | Documentação do projeto e organização das evidências |

O Wix foi escolhido por permitir a criação visual do site e a publicação com menor complexidade inicial. A personalização por código complementa os recursos prontos da plataforma.

## Personalizações com padrões Web

A personalização trabalhada no desenvolvimento foi um **chat acessado por um botão**, com janela de conversa, campo para digitar mensagens e ação de envio.

- **HTML:** organiza os elementos da interface de atendimento.
- **CSS:** define a apresentação visual e o espaço ocupado pelo chat.
- **JavaScript:** controla os eventos e o comportamento da conversa.

Outro requisito do componente é manter o acesso ao atendimento disponível durante a rolagem. Esse comportamento envolve posicionamento fixo e a configuração do elemento incorporado no Wix. Em um `iframe`, o posicionamento interno depende da área do contêiner; por isso, precisa ser verificado na página publicada.

A captura comprova a presença visual do chat, mas não permite conferir o código efetivamente publicado. A versão final do código personalizado deve ser incluída neste repositório após a conferência no editor do Wix.

## Automação de atendimento

O fluxo de atendimento previsto é:

1. O visitante abre a janela de chat.
2. O assistente apresenta uma saudação.
3. O visitante envia sua dúvida.
4. A lógica de atendimento apresenta uma resposta ou orientação.
5. Quando necessário, o visitante segue para o WhatsApp para continuar o atendimento.

O recurso é documentado como **automação de atendimento**. Não há confirmação de integração com uma API de IA generativa. Respostas por regras ou palavras-chave não devem ser apresentadas como geração de texto por IA.

O enunciado permite um recurso de **IA, automação ou integração**. A proposta utiliza automação e encaminhamento externo, cuja operação completa ainda precisa ser demonstrada.

## Responsividade e acessibilidade

A revisão da interface considera:

- Ajuste de textos, imagens e seções para telas menores.
- Janela de chat que caiba na tela e não impeça a navegação.
- Botões identificáveis e com área adequada para toque.
- Contraste suficiente entre texto e fundo.
- Texto alternativo nas imagens informativas.
- Campos com rótulos claros e navegação por teclado com foco visível.

Esses pontos compõem os critérios de validação. **Os testes em celular e a verificação de acessibilidade ainda não estão documentados como concluídos.**

## Imagens do projeto

### Página inicial e acesso ao atendimento


<img width="577" height="358" alt="pagina-inicial" src="https://github.com/user-attachments/assets/f41d5d57-027d-49fe-8bd7-7aa20480341f" />



### Vitrine de produtos

<img width="577" height="282" alt="vitrine" src="https://github.com/user-attachments/assets/7fc9abc3-c0d8-4383-97b0-b06dace3ed9b" />

As imagens são recortes da captura do site fornecida em **31 de outubro de 2026**. Elas documentam a interface; os resultados das interações devem ser complementados com testes e vídeo.

## Como acessar e testar

Não é necessário instalar o projeto para acessar a página publicada.

1. Abra **https://danfernaka26.wixsite.com/art-about-color**.
2. Confira a apresentação da empresa e a vitrine.
3. Utilize o menu e o botão de workshops para verificar seus destinos.
4. Clique no botão do chat e confira se a janela abre e fecha.
5. Envie uma mensagem de teste, como **“Quero saber sobre os workshops”**.
6. Confira se a resposta é adequada à pergunta e se a mensagem aparece na conversa.
7. Utilize a opção de WhatsApp, caso esteja disponível, e confira se o destino correto é aberto. Não é necessário enviar a mensagem para verificar o redirecionamento.
8. Repita a navegação em um celular e verifique se o chat e os demais elementos permanecem utilizáveis.

### Verificações antes da entrega

- [ ] Conferir todos os links de navegação.
- [ ] Testar abertura, fechamento e envio no chat.
- [ ] Conferir respostas para perguntas previstas e não previstas.
- [ ] Validar o encaminhamento para o WhatsApp.
- [ ] Verificar o comportamento do chat durante a rolagem.
- [ ] Testar em desktop e celular.
- [ ] Revisar rótulos, contraste, imagens e navegação por teclado.
- [ ] Adicionar o código personalizado final ao repositório.
- [ ] Publicar o vídeo e inserir seu link neste README.

## Organização do repositório

| Arquivo ou pasta | Conteúdo |
| --- | --- |
| `README.md` | Descrição, tecnologias, evidências e instruções de teste |
| `imagens/pagina-inicial.png` | Captura da apresentação do site e acesso ao chat |
| `imagens/vitrine.png` | Captura da vitrine |

A aplicação principal é mantida no **Wix**. Este conjunto de arquivos contém a documentação e as imagens; não é uma exportação executável do site. O código personalizado do chatbot deve ser acrescentado ao repositório a partir da versão utilizada na plataforma.

## Limitações e aprendizados

Durante o desenvolvimento, surgiram dificuldades com o envio de mensagens, o encaminhamento para o WhatsApp e o posicionamento do chat. A interface também precisa de revisão dos espaços vazios, da consistência do idioma no menu e dos dados de contato exibidos.

O principal aprendizado é que a construção visual reduz o trabalho inicial, mas compreender **HTML, CSS e JavaScript** continua sendo necessário para adaptar componentes, investigar erros e integrar serviços. Também é essencial distinguir uma interface que aparece corretamente de um fluxo que foi testado do início ao fim.

Como evolução, o projeto pode receber uma base de perguntas frequentes mais completa e, se houver necessidade, uma integração real com um serviço de IA.

## Vídeo de apresentação

**Link: pendente de inclusão.**

O vídeo deve ter até **4 minutos** e apresentar o problema, a solução funcionando, o uso do Wix, as personalizações com padrões Web, a automação e o principal diferencial do projeto.

## Autor

**Daniel Fernandes Nakahara**  
UniFECAF — Padrões Web para No Code e Low Code  
Projeto acadêmico Smart Web Experience.
