# Práticas de Web Scraping com Python utilizando BeautifulSoup e Selenium

![capa_ws](https://github.com/Cassiophysics/Webscraping_beautifulsoup_selenium/assets/108491443/230a9e58-c92a-4183-adfc-4b9554efef12)

Aqui estão listadas algumas práticas de Web Scraping com Python utilizando as bibliotecas BeautifulSoup e Selenium.

Os sites utilizados para realizar a extração dos dados foram: 

https://www.scrapethissite.com/pages/

http://books.toscrape.com/index.html

https://webscraper.io/test-sites/e-commerce/static

https://en.wikipedia.org/wiki/List_of_Academy_Award-winning_films

Apesar dos três primeiros sites serem específicos para a prática de Web Scraping, em todos eles foi verificado através do uso do robots.txt em quais diretórios o acesso era autorizado a raspagem dos dados e a forma como isso era permitido, a fim de respeitar todas as normas da Lei Geral de Proteção de Dados Pessoais (LGPD).

A primeira biblioteca utilizada foi BeautifulSoup, usada para extrair dados de sites em que as páginas são bem estruturadas, onde se obtém o código-fonte da página da Web e a partir disso podemos filtrá-la para encontrar o que for necessário. Assim, BeautifulSoup é relativamente simples de executar e usar, é ideal para os casos em que se conhece a estrutura das páginas da web a se analisar.

Ao passo que Selenium é uma ferramenta de renderização de páginas da Web de uso geral, projetada para testes automatizados. Em outros termos, é um webdriver, ou seja, uma ferramenta  que permite a execução do script de teste para analisar os possíveis comportamentos de um usuário real no navegador. É uma opção adequada de Web Scraping quando a página apresenta conteúdo dinâmico e precisa de ações como clicar em botões e selecionar elementos, o que demanda maior custo computacional.

