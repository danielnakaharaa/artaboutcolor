# 🎨 ArtAboutColor

## Smart Web Experience — No-code, padrões Web e atendimento digital

Projeto acadêmico desenvolvido por **Daniel Fernandes Nakahara** para a disciplina **Padrões Web para No Code e Low Code**, da **UniFECAF**.

**🌐 [Acessar o site publicado](https://danfernaka26.wixsite.com/art-about-color)**

## 1. Apresentação do projeto

A **ArtAboutColor** é uma proposta de site para um negócio voltado à arte, consultoria em cores, design e workshops. A aplicação foi construída no **Wix Harmony**, combinando os recursos visuais da plataforma com uma personalização em **HTML, CSS e JavaScript**.

A personalização desenvolvida é um título interativo: ao clicar em **ArtAboutColor**, o visitante alterna a cor do texto entre laranja e roxo. A interação conecta a identidade da marca ao tema central do projeto: as cores.

## 2. Problema e público-alvo

O desafio apresentado na disciplina é modernizar a presença digital de uma pequena empresa de serviços que depende de informações dispersas e contatos manuais para atender seus clientes.

A solução reúne a apresentação do negócio, acesso às áreas do site e um canal de atendimento em uma mesma página. O público-alvo são pessoas interessadas em arte, combinação de cores, decoração, consultoria de design e atividades criativas.

## 3. Funcionalidades e interface

- Apresentação da marca e de sua proposta na página inicial.
- Menu com acesso a serviços, eventos, loja e agendamento online.
- Botão **“Explorar workshops”** para orientar a navegação.
- Título **ArtAboutColor** com mudança de cor ao clicar.
- Widget de chat disponível na interface para acesso ao atendimento.

A presença dos itens de menu e do chat na captura documenta a interface. Ela não comprova, por si só, a conclusão dos fluxos de compra, agendamento ou resposta automática.

## 4. Ferramentas e tecnologias

| Ferramenta ou tecnologia | Utilização |
| --- | --- |
| **Wix Harmony** | Construção visual do layout e publicação do site |
| **HTML** | Criação do título com a tag `<h1>` |
| **CSS** | Definição da cor inicial e do cursor no atributo `style` |
| **JavaScript** | Alternância da cor do título por meio do evento `onclick` |
| **GitHub e Markdown** | Organização do código, documentação e evidências |

O Wix foi escolhido por facilitar a criação e publicação de uma página sem desenvolver toda a estrutura do zero. A incorporação do título demonstra como um pequeno trecho de código pode complementar os componentes prontos de uma plataforma no-code/low-code.

## 5. Personalização com HTML, CSS e JavaScript

O trecho abaixo foi utilizado no elemento HTML incorporado ao site:

```html
<h1
  style="color: #b74700; cursor: pointer;"
  onclick="this.style.color = this.style.color === 'purple' ? '#b74700' : 'purple'"
>
  ArtAboutColor
</h1>
```

### Como o código funciona

**HTML:** a tag `<h1>` cria o título com o texto `ArtAboutColor`.

**CSS:** o atributo `style` define a cor inicial como `#b74700`, um tom de laranja, e aplica `cursor: pointer` para indicar uma possibilidade de interação com o mouse.

**JavaScript:** o atributo `onclick` executa a troca de cor. A palavra `this` representa o próprio título. A expressão verifica se sua cor é `purple`: se for, muda para laranja; caso contrário, muda para roxo.

| Momento | Cor do título |
| --- | --- |
| Antes do primeiro clique | Laranja — `#b74700` |
| Primeiro clique | Roxo — `purple` |
| Segundo clique | Laranja — `#b74700` |
| Cliques seguintes | Alternância entre as duas cores |

Essa implementação utiliza CSS e JavaScript **inline**, dentro do elemento HTML. A alteração afeta somente o título incorporado, sem modificar o tema global da página. Não utiliza bibliotecas externas nem salva a preferência após recarregar a página.

## 6. Atendimento e requisito de automação ou IA

O site apresenta um widget de chat para acesso ao atendimento. A captura mostra o botão no canto inferior direito da página.

O objetivo desse recurso é facilitar o contato do visitante com a empresa. Entretanto, o tipo de atendimento — humano, automatizado por regras ou integrado a IA — e suas respostas precisam ser demonstrados por um teste da configuração publicada.

**A mudança de cor do título é uma interação em JavaScript e não é apresentada como inteligência artificial.** Para comprovar o requisito de integração, automação ou IA do trabalho, é necessário registrar o recurso efetivamente configurado no chat, por exemplo uma resposta automática, e demonstrá-lo funcionando no vídeo.

## 7. Responsividade e acessibilidade

O projeto utiliza a organização visual do Wix para distribuir o conteúdo. Na revisão para diferentes telas, é necessário conferir se o menu, as imagens e o título incorporado permanecem legíveis e não apresentam cortes.

O título usa uma marcação de cabeçalho, e o cursor indica a interação com o mouse. Porém, **o código atual não oferece ativação por teclado**, pois o `<h1>` não é um botão. Uma melhoria futura é utilizar um botão acessível dentro do título ou acrescentar suporte adequado ao teclado.

Também devem ser verificados o contraste das duas cores sobre o fundo, os textos alternativos das imagens e a hierarquia de títulos. Como o HTML está incorporado em um iframe, sua estrutura não deve ser considerada automaticamente parte da hierarquia de cabeçalhos da página principal.

## 8. Evidência visual

<img width="577" height="282" alt="vitrine" src="https://github.com/user-attachments/assets/56d9177a-7648-40bf-87c1-7f61cc6e1ee7" />
<img width="577" height="358" alt="pagina-inicial" src="https://github.com/user-attachments/assets/c74cd316-41a2-437e-8aaa-938526b8ce95" />


*Captura fornecida em 31 de outubro de 2026. A imagem documenta a interface publicada. A alternância de cores deve ser observada clicando no título ou assistindo à demonstração em vídeo.*

## 9. Como acessar e testar

1. Acesse **https://danfernaka26.wixsite.com/art-about-color**.
2. Localize o título **ArtAboutColor** no cabeçalho.
3. Clique no título e observe a mudança para roxo.
4. Clique novamente para retornar ao laranja.
5. Repita a ação para verificar a alternância.
6. Explore o menu e o botão de workshops para conferir seus destinos.
7. Abra o chat e teste o atendimento disponível.
8. Acesse em um celular para verificar o layout e a interação por toque.

Para testar somente a personalização, abra o arquivo `titulo-interativo.html` em um navegador. Ele contém exatamente o trecho utilizado no projeto e não representa uma exportação do site completo.


## 10. Limitações e aprendizados

A principal limitação encontrada foi o isolamento do HTML incorporado em relação ao restante da página. Uma tentativa anterior de criar um modo escuro global dependia de integração com código da página, que não estava disponível no editor utilizado. Por isso, a personalização escolhida atua dentro do próprio componente.

O projeto permitiu aplicar a estrutura do HTML, o estilo do CSS e um evento JavaScript em uma plataforma visual. Também mostrou a importância de escolher uma funcionalidade compatível com o editor e de testar o comportamento publicado.

Como melhorias futuras, estão previstos o suporte ao teclado no título, a revisão em telas menores e a documentação dos testes do atendimento.

