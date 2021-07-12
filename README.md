# Starfleet is recruiting / A Frota Estelar está recrutando

## Objetivos / Aims

* Exercitar a criação de um página da web usando os recursos flexbox e efeito de sobreposição de divs manipulando sua opacidade no CSS. Orientações: professor Sidney Cardoso, SENAI-CIMATEC.
* <i> To practice the creation of a webpage using the feature flexbox and juxtaposition of divs effect by manipulating their opacity on CSS. Orientations: professor Sidney Cardoso, SENAI CIMATEC.</i>

## Problemas que consegui resolver / A problem I was able to solve

* Eu não estava conseguindo cortar a logo da Frota Estelar (série Star Trek) fora do quadro branco. Para solucionar o problema, editei o recurso border-radius para 120px. Qualquer número acima desse não faz mais diferença.

_I could not cut the Starfleet logo out of the white box. To solve this problem I edited the feature border-radius to 120px. Any number above that would not make a difference._

* Um outro problema foi com o footer: eu não estava conseguindo fazer com que o ícone do github ficasse estável manipulando só a classe do i ".fab" no CSS. Então o coloquei dentro de uma section separada do footer propriamente dito e logo após este. Além disso, não consegui manter a cor branca do ícone apenas no elemento section no CSS. Resolvi então manter essa configuração na class .fab no CSS, frustrando minha tentativa de diminuir algumas linhas de código.

_Another issue I had to deal with was the footer: I could not make the github icon stable by only manipulating the .fab class on CSS from the i element. So I placed it in a section separate from the footer itself and right after it. Besides, I didn't manage to maintain the color white for the icon when it was in the "section" element. Finally, I decided to maintain this setting in the .fab class on CSS, thus frustrating my attempt to reduce some code lines._

* Quando abria o projeto no "Live Server" do Visual Studio Code, o logo da Frota Estelar aparecia, mas no site criado no GitHub, não. Ao realizar outro projeto, me debati com o mesmo problema, e só então encontrei um video no Youtube elucidando sua solução: retirar a barra </> do caminho da imagem, pois é lido localmente, mas não remotamente (na página criada pelo GitHub).

_When I opened the project with the "Live Server" on Visual Studio Code, the Star Fleet logo appeared, but on the GitHub-created page, it didn't. Later on, when I was building another project, I faced the same issue, and only then did I find a tutorial on Youtube that helped me solve the problem by removing the slash </> from the image's path on the HTML file, because it only works locally, not remotely (on Github-created page)._

## Tecnologias / Technologies

* CSS

## Link da página / Webpage link

* [Clique aqui para ver a página / Click here to see page](https://romulocraveiro.github.io/starfleetrecruiting/); 

## Autor / Author

| Foto                                       | Nome        | GitHub                                         | Likedin                                                 | E-mail                |
| ------------------------------------------ | ----------- | ---------------------------------------------- | ------------------------------------------------------- | --------------------- |
| <img src="./img/fotogit.jpeg" width="100px"> | Romulo Craveiro de Sousa Tartaruga | [Romulo Craveiro](https://github.com/romulocraveiro) | [Linkedin](https://www.linkedin.com/in/romulocraveiro/) | romulocraveiro@gmail.com |