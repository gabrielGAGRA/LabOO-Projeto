# Projetos do Tipo A: Sistema Web

Os projetos deste tipo consistem em desenvolver uma aplicação acessada por meio de uma interface web intuitiva, esteticamente agradável e boa usabilidade. O sistema deverá obrigatoriamente interagir com alguma API pública de plataforma Web por meio de algum protocolo padrão (p.ex., REST) ou por meio de raspagem de dados automatizada de algum site.

Exigências Básicas: O sistema deve ter uma boa aparência, ser claro e fácil de se utilizar. As informações devem ser mostradas de uma forma bonita e bem organizada.

## A2 - Super Criador de Playlists
Use a API do Spotify para permitir que um usuário crie playlists personalizadas.


Requisitos:

1. O sistema deve permitir que o usuário crie playlists com suas músicas preferidas. Note que essas playlists podem tanto ser criadas dentro da conta de um usuários do Spotify quanto podem ser criadas localmente pelo seu sistema, a seu critério. Para inserir uma música numa playlist, o usuário deve primeiramente realizar uma busca e, então, selecionar uma ou mais das músicas encontradas pela busca para inserção em playlist de sua escolha.O sistema deve permitir a criação, remoção e listagem das playlists existentes. Deve também permitir a inserção e remoção de músicas de uma playlist.

2. O sistema deve permitir a busca por músicas de acordo com vários critérios: título, autor, nome do álbum, nome de playlists públicas do spotify (não confundir com suas playlists locais do seu sistema). Ao se clicar num álbum, o sistema deve mostrar todas as músicas daquele álbum (e permitir cada uma delas seja inserida em uma de suas playlists). Ao se clicar numa playlist pública do spotify, o sistema deve mostrar todas as músicas daquela playlist pública (e permitir que cada uma delas seja inserida em uma de suas playlists).

3. Para cada resultado de uma busca, o sistema deve permitir uma visão detalhada das músicas oferecendo uma série de parâmetros sobre a música, incluindo dançável, energia, andamento (tempo), força (loudness), fala (speechiness), instrumental, ao vivo, acústica.  Dada uma determinada playlist, todas essas informações devem ser mostradas na forma de uma tabela e o usuário poderá ordenar essa tabela por cada um desses parâmetros segundo o seu gosto. Observe que essas informações são fornecidas via a operação audio-features da API do Spotify.

4. Ao se mostrar um álbum ou playlist, deve-se mostrar as imagens a ele associadas. Ao se mostrar uma playlist, deve-se mostrar todas as informações disponíveis sobre cada um das músicas (título, artistas, ano, duração). Deve ser possível também se clicar numa música e ouvir o início da música.

5. O usuário deve ser capaz de realizar uma busca dentro de todas as playlists que ele criou usando um critério baseado nos parâmetros de análise do áudio das músicas (dançável, acústica, energia, etc.). Isso deverá ser feito graficamente definindo-se um string de busca (p.ex., "samba") e um intervalo aceitável para cada um dos parâmetros, por exemplo, dançavel entre 0,8 e 1,0; acústica entre 0,0 e 0,5; energia entre 0,7 e 0,8. Assim, o usuário poderá ser capaz de buscar, por exemplo, um samba dançável, pouco acústico e com muita energia.

## Equipe
Gabriel Agra de Castro Motta - 15452743

David Satoshi Aguina - 12552408

Gabriel Soares da Silva - 11808234

Maria Eduarda Dantas Leite Pessôa - 15587775

Mateus Silva de Araújo - 15497076
