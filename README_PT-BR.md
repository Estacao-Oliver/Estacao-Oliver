<div class="header" align="center">  
<img alt="Space Station 14" width="880" height="300" src="https://raw.githubusercontent.com/space-wizards/asset-dump/de329a7898bb716b9d5ba9a0cd07f38e61f1ed05/github-logo.svg">  
</div>

**Space Station 14** é um remake de **SS13** que roda sobre a [Robust Toolbox](https://github.com/space-wizards/RobustToolbox), nosso motor próprio escrito em C#.

Este é o repositório principal do Space Station 14. Para evitar que as pessoas façam fork do RobustToolbox, um pacote de “conteúdo” é carregado tanto pelo cliente quanto pelo servidor. Esse pacote contém tudo o que é necessário para jogar em um servidor específico.

Se você deseja hospedar ou criar conteúdo para o SS14, este é o repositório de que você precisa. Ele contém tanto o RobustToolbox quanto o pacote de conteúdo para o desenvolvimento de novos pacotes.

---

## Links

<div class="header" align="center">  

[Site oficial](https://spacestation14.com/) | [Discord](https://discord.ss14.io/) | [Fórum](https://forum.spacestation14.com/) | [Mastodon](https://mastodon.gamedev.place/@spacestation14) | [Lemmy](https://lemmy.spacestation14.com/) | [Patreon](https://www.patreon.com/spacestation14) | [Steam](https://store.steampowered.com/app/1255460/Space_Station_14/) | [Download Standalone](https://spacestation14.com/about/nightlies/)  

</div>

---

## Documentação/Wiki

Nosso [site de documentação](https://docs.spacestation14.com/) contém informações sobre o conteúdo do SS14, motor, design do jogo e muito mais.  
Além disso, consulte estes recursos sobre licenças e atribuições:  
- [Atribuição Genérica do Robust](https://docs.spacestation14.com/en/specifications/robust-generic-attribution.html)  
- [Imagem Robust Station](https://docs.spacestation14.com/en/specifications/robust-station-image.html)

Também temos muitos recursos para novos colaboradores do projeto.

---

## Contribuindo

Aceitamos contribuições de qualquer pessoa. Entre no Discord se quiser ajudar. Temos uma [lista de issues](https://github.com/space-wizards/space-station-14-content/issues) que precisam ser resolvidas e qualquer um pode pegá-las. Não tenha medo de pedir ajuda!  
Apenas certifique-se de que suas alterações e *pull requests* estejam de acordo com as [diretrizes de contribuição](https://docs.spacestation14.com/en/general-development/codebase-info/pull-request-guidelines.html).

Atualmente não estamos aceitando traduções do jogo em nosso repositório principal. Se quiser traduzir o jogo para outro idioma, considere criar um *fork* ou contribuir com um já existente.

---

## Compilação

1. Clone este repositório:
```shell
git clone https://github.com/space-wizards/space-station-14.git
```
2. Vá até a pasta do projeto e execute `RUN_THIS.py` para inicializar os submódulos e carregar o motor:
```shell
cd space-station-14
python RUN_THIS.py
```
3. Compile a solução:  

Construa o servidor usando:
```shell
dotnet build
```

[Instruções mais detalhadas sobre a compilação do projeto.](https://docs.spacestation14.com/en/general-development/setup.html)

---

## Licença

Todo o código do repositório de conteúdo está licenciado sob a [licença MIT](https://github.com/space-wizards/space-station-14/blob/master/LICENSE.TXT).  

A maioria dos recursos (*assets*) está licenciada sob [CC-BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) a menos que indicado de outra forma. Cada recurso possui a licença e os direitos autorais especificados em seu arquivo de metadados. Por exemplo, veja os [metadados de um pé-de-cabra](https://github.com/space-wizards/space-station-14/blob/master/Resources/Textures/Objects/Tools/crowbar.rsi/meta.json).  

> [!NOTA]  
> Alguns recursos estão licenciados sob [CC-BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/) (ou licenças similares não comerciais) e precisarão ser removidos caso você queira usar este projeto comercialmente.
