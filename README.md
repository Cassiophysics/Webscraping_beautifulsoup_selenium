# Práticas de Web Scraping com Python utilizando BeautifulSoup e Selenium

![capa_ws](https://github.com/Cassiophysics/Webscraping_beautifulsoup_selenium/assets/108491443/230a9e58-c92a-4183-adfc-4b9554efef12)

Aqui estão listadas algumas práticas de Web Scraping com Python utilizando as bibliotecas BeautifulSoup e Selenium.

Os sites utilizados para realizar a extração dos dados foram: 

https://www.scrapethissite.com/pages/

http://books.toscrape.com/index.html

https://webscraper.io/test-sites/e-commerce/static

https://en.wikipedia.org/wiki/List_of_Academy_Award-winning_films

Apesar dos três primeiros sites serem específicos para a prática de Web Scraping, em todos eles foi verificado, por meio do uso do arquivo robots.txt, quais diretórios permitiam o acesso à raspagem de dados e como isso era autorizado, a fim de cumprir todas as normas da Lei Geral de Proteção de Dados Pessoais (LGPD).

A primeira biblioteca utilizada foi o BeautifulSoup, que é usada para extrair dados de sites com páginas bem estruturadas. Com essa biblioteca, é possível obter o código-fonte da página da Web e filtrá-lo para encontrar as informações necessárias. O BeautifulSoup é relativamente simples de executar e usar, sendo ideal para casos em que a estrutura das páginas da Web a serem analisadas é conhecida.

Por outro lado, o Selenium é uma ferramenta de renderização de páginas da Web de uso geral, originalmente projetada para testes automatizados. Em outras palavras, o Selenium atua como um webdriver, permitindo a execução de scripts de teste para simular os possíveis comportamentos de um usuário real no navegador. É uma opção adequada para Web Scraping quando a página possui conteúdo dinâmico e requer interações, como clicar em botões e selecionar elementos, o que exige mais poder de processamento.

