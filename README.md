Como Usar o Script Sitemap URL Processor

Antes de rodar o script, instale as bibliotecas necessárias no terminal com o comando:

pip install requests pandas beautifulsoup4 openpyxl

Baixe o script nome_do_script.py e salve-o em uma pasta. Abra o terminal ou prompt de comando e navegue até essa pasta usando o comando cd /caminho/da/pasta. Para executar o script, use:


python nome_do_script.py

O script pedirá a URL do sitemap do site que deseja analisar. Cole a URL no terminal. Se houver mais de um sitemap, separe as URLs com uma vírgula e pressione Enter. Exemplo de entrada:

https://exemplo.com/sitemap.xml, https://exemplo.com/sitemap2.xml

O script buscará todas as URLs do sitemap, analisará a estrutura e gerará um arquivo Excel automaticamente. O nome do arquivo será o domínio analisado, como exemplo.com.xlsx. O arquivo será salvo na mesma pasta onde o script foi executado.

Abra o arquivo Excel gerado e explore as abas disponíveis. A aba Segmented URLs contém a estrutura detalhada das URLs. A aba Serviço e Localização apresenta informações extraídas sobre serviços e localização. A aba Indexação contém consultas para verificar a indexação no Google.

Agora você pode utilizar essas informações para suas análises de SEO ou auditorias técnicas. Caso tenha dúvidas ou precise de suporte, consulte a documentação ou abra uma Issue no repositório do projeto.
