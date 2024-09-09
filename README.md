📈 Preços de Criptomoedas no Power BI
=

Este repositório contém um exemplo de visualização de preços de criptomoedas em tempo real, desenvolvido com HTML, CSS e JavaScript. O visual exibe preços atualizados de criptomoedas usando a API CoinGecko, e inclui uma barra de progresso dinâmica que mostra o tempo restante para a próxima atualização.

👤 Autor
=
Nome: Reed Iury

LinkedIn: https://www.linkedin.com/in/reediury/

📦 Arquivos
=

CRYPTO_HTML.pbix: Exemplo de relatório Power BI.

README.md: Este arquivo de documentação.

🚀 Instruções de Uso
=
Visual Personalizado:

Para usar este visual no Power BI, é necessário um visual que suporte HTML. Recomendo o HTML Content, que pode ser baixado e instalado através do site https://www.html-content.com/ ou pela opção "Obter mais visuais" no Power BI.

Arquivo de Exemplo:

O arquivo CRYPTO_HTML.pbix contém o exemplo completo de como os preços das criptomoedas são exibidos.

Variáveis Principais:
=

apiUrl: URL da API CoinGecko para buscar dados das criptomoedas.

refreshInterval: Intervalo de tempo (em milissegundos) para atualizar os preços automaticamente.

timerInterval: Variável usada para o controle do cronômetro e da barra de progresso.

Funções Principais:
=

fetchCryptocurrencyData(): Busca os dados das criptomoedas da API CoinGecko e atualiza a visualização.

displayCryptocurrencyData(data): Exibe os dados das criptomoedas na tela.

filterCryptos(): Filtra as criptomoedas com base na entrada da barra de pesquisa.

startTimer(): Inicializa e atualiza a barra de progresso e o cronômetro para a próxima atualização.

🛠 Como Personalizar
=

Ajuste o refreshInterval para modificar a frequência de atualização dos preços.

Modifique o CSS para alterar o estilo dos cards e da barra de progresso conforme suas preferências.

Adapte a lógica em fetchCryptocurrencyData() para integrar outras APIs ou dados adicionais.

🌟 Demonstração do Visual
=

https://github.com/user-attachments/assets/0749adb0-a62e-402b-8f86-3205678468f7

Se tiver dúvidas ou sugestões, entre em contato comigo pelo LinkedIn.
