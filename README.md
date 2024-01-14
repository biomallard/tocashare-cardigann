# Toca Share Cardigann

Este README irá guiá-lo pelo processo de adição do Toca Share como um tracker customizado na sua instalação do Jackett/Prowlarr, usando o arquivo de configuração [tocashare-api.yml](https://github.com/soganakamaro/tocashare-cardigann/blob/main/tocashare-api.yaml)

# Pré-requisitos

- O Jackett ou o Prowlarr devem estar previamente instalados e configurados em seu sistema.
- Consulte instruções de instalação na documentação oficial destes softwares.

# Instruções de Instalação (Jackett)

1. **Baixe o arquivo de configuração**

   Primeiramente, baixe o arquivo de configuração `tosashare-api.yml` no seguinte link:
   
   [tocashare-api.yml](https://github.com/soganakamaro/tocashare-cardigann/blob/main/tocashare-api.yaml)

4. **Mova o arquivo para o diretório de definições do Jackett**

   Mova o arquivo `tocashare-api.yml` para o diretório de `Definitions` do Jackett. No Windows, este diretório está localizado em:

   ```
   C:\ProgramData\Jackett\Definitions
   ```
   
   Consulte o log do Jackett para obter a localização específica para seu sistema operacional.
   
6. **Reinicie o Jackett**

   Reinicie o Jackett para aplicar as mudanças.
   
8. **Adicione o Toca Share como um indexador personalizado**

   Uma vez que o Jackett tenha sido reinicido, você pode adicionar o Toca Share como um indexador seguindo os passos a seguir:

   - Clique em `Add indexer` na janela principal do Jackett.
   - Na barra de pesquisa (search), procure por "Toca Share" e selecione o Toca Share na lista.
   - Insira sua API key, que pode ser gerada/obtida no próprio site do Toca Share em `Minhas Configurações > Definições > API KEY`.
   - Edite as outras opções conforme sua preferência.
   - Salve suas alterações.
     
10. **Use o Toca Share como uma fonte de pesquisa**

    Agora o Toca Share estará disponível como fonte de pesquisa do Jackett.

    Você pode usá-lo para pesquisar torrents através do plugin do Jackett para o qBittorrent ou em seus clientes *arr.

    Boa sorte pesquisando e baixando o material desta incrível comunidade!

# Instruções de Instalação (Prowlarr)

1. **Baixe o arquivo de configuração**

   Primeiramente, baixe o arquivo de configuração `tosashare-api.yml`no seguinte link:
   
   [tocashare-api.yml](https://github.com/soganakamaro/tocashare-cardigann/blob/main/tocashare-api.yaml)

2. **Crie um diretório de definições customizadas do Prowlarr**

   Crie um diretório `Custom` dentro da pasta de `Definitions` do diretório de configurações do Prowlarr. No Windows, este novo diretório ficará localizado em:

   ```
   C:\ProgramData\Prowlarr\Definitions\Custom\
   ```

   Consulte a documentação oficial do programa para obter a localização específica deste diretório para seu sistema operacional.
   
4. **Mova o arquivo para o diretório de definições customizadas do Prowlarr**

   Mova o arquivo `tocashare-api.yml` para o diretório `Custom` criado no passo anterior. 
   
5. **Reinicie o Prowlarr**

   Reinicie o Prowlarr para aplicar as mudanças.
   
6. **Adicione o Toca Share como um indexador personalizado**

   Uma vez que o Prowlarr tenha sido reinicido, você pode adicionar o Toca Share como um indexador seguindo os passos a seguir:

   - Vá para a página `Indexadores` do Prowlarr.
   - Clique no botão de "+" para adicionar um indexador.
   - Na barra de pesquisa (search), procure por "Toca Share" e selecione o Toca Share na lista.
   - Insira sua API key, que pode ser gerada/obtida no próprio site do Toca Share em `Minhas Configurações > Definições > API KEY`.
   - Edite as outras opções conforme sua preferência.
   - Salve suas alterações.
     
7. **Use o Toca Share como uma fonte de pesquisa**

    Agora o Toca Share estará disponível como fonte de pesquisa do Prowlarr.

    Você pode usá-lo para pesquisar torrents diretamente ou através de seus clientes *arr, incluindo a possibilidade de realizar buscar pelos índices do IMDB.

    Boa sorte pesquisando e baixando o material desta incrível comunidade!
