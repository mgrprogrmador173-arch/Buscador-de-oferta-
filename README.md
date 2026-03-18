# Buscador de Ofertas no Meu Bairro

## Descrição
Aplicação web estática em arquivo único para encontrar ofertas de produtos usados perto da localização do usuário. Toda a interface, o estilo e a lógica estão concentrados em `index.html`, facilitando abrir o projeto diretamente no navegador.

## Funcionalidades
- Arquivo único em HTML com CSS e JavaScript embutidos.
- Detecção de geolocalização via navegador.
- Preenchimento automático de bairro, cidade e estado com reverse geocoding.
- Preview do termo de busca gerado automaticamente.
- Busca rápida em plataformas como Facebook Marketplace, OLX, Webmotors, Mercado Livre e Google.
- Seleção de plataformas, cópia da consulta e cópia de links individuais.
- Ajuste manual do bairro, raio e preço máximo para refinar a pesquisa.
- Interface responsiva pronta para abrir em celular.

## Tecnologias Utilizadas
- HTML5
- CSS3 embutido
- JavaScript embutido
- API de Geolocalização do navegador
- Nominatim / OpenStreetMap para reverse geocoding

## Como Usar
1. Clone este repositório.
2. Abra o arquivo `index.html` diretamente no navegador.
3. Se o navegador bloquear o GPS no arquivo local, rode opcionalmente `python3 -m http.server 4173`.
4. Abra `http://localhost:4173` no navegador.
5. Clique em **Usar minha localização** para detectar seu bairro.
6. Ajuste categoria, raio e preço máximo se quiser.
7. Abra individualmente as plataformas ou use **Abrir buscas selecionadas**.

## Observações
- O Facebook Marketplace e outros sites podem exigir login antes de exibir resultados.
- A precisão do bairro depende da permissão de GPS e da base de endereços disponível.
- Geolocalização costuma funcionar melhor em `localhost` ou `https`.
- Alguns navegadores podem bloquear múltiplas abas; nesse caso, use os botões individuais dos cards.

## Licença
Este projeto está licenciado sob a MIT License.
