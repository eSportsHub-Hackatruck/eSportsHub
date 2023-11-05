
# 📱 ⚽ eSportsHub
Esse projeto foi feito no [Projeto Hackatruck](https://hackatruck.com.br), nos foi desafiado a criar um prototipo de app sobre os ensinamentos aprendidos no projeto, nosso grupo decidiu juntar nossa paixão sobre eSports para criar nosso app, dai surgiu o "eSportsHub". Um app que traz informações diversas sobre os jogadores, times, campeonatos e calendario de jogos futuros.

## Um pouco sobre a interface do código

 ### Esse foi o prototipo inicial feito: 
![App Screenshot](https://cdn.gamma.app/coz5mm93vwdyfi2/9df212ea7a3a4f7fb41d431a1d9054de/original/Screenshot-2023-09-22-at-14-35-47-Figma.png)

Nosso protótipo inicial constituia em 5 telas:

- 🏠 Home
  
Nossa HomePage conteria as informações sobre os próximos jogos, contendo o horário do jogo, dia, liga e os times que se enfrentariam.
- 🕹 Games
  
Nessa pagina contem os jogos que são contemplados no nosso app.
- 👤 Players
  
Nessa pagina contem os players dos times, nela contem informações detalhadas sobre os players, como nome, idade, etc.

- 👥 Teams
  
Nessa pagina contém os times, nela contém informações detalhadas sobre os times, em quais campeonatos eles participam e os players dessa equipe.
-  🏆 Leagues
  
Nessa pagina contém os campeonatos, nela contém informações detalhadas sobre os campeonatos, ondem ocorrem, quais os times participatem e as premiações.

 ### Esse é o protótipo final feito:
[Link para visualização da interface](https://www.youtube.com/watch?v=15SDSOeP4pY)

Nosso protótipo final foi feito com o auxilio da UX (User Xperience), onde foi feito para agradar da melhor forma o usuário do App.
## Documentação da API 
Nossa API está no formato ".json"

[Você pode acompanhar nossa API clicando aqui!](https://github.com/JuanSantos64/eSportsHub/tree/main/api)


Nossa API contém as seguintes informações:

- Jogadores 
- Jogos 
- Times 
- Torneios 

## 👤 Jogadores
Nossa API de jogadores contém as seguintes informações:

- id
Contém a identificação dos jogadores
- nickJogador
Contém o nick dos jogadores
- nameJogador
Contém o nome verdadeiro dos jogadores
- countryJogador
Contém o local de nascimento dos jogadores
- birthdayJogador
Contém a data de aniversário dos jogadores
- photoJogador
Contém a foto dos jogadores
- teamJogador
Contém o time que os jogadores jogam
- teamPhotoJogador
Contém a foto do time que os jogadores jogam

Um exemplo do uso dessa API é a seguinte:

```bash
{
        "id": 1,
        "nickJogador": "s1mple",
        "nameJogador": "Oleksandr Kostyliev",
        "countryJogador": "Ukraine",
        "countryPhotoJogador": "https://cdn.discordapp.com/attachments/1152325417483649078/1156299444699013200/uk.png?ex=65147746&is=651325c6&hm=967a7d75506509f78ddad395cee4cf30b432b013bac77000987889a70c5476a1&",
        "birthdayJogador": "October 2, 1997",
        "photoJogador": "https://prosettings.net/cdn-cgi/image/dpr=1%2Cf=auto%2Cfit=contain%2Cheight=240%2Cq=99%2Csharpen=1%2Cwidth=240/wp-content/uploads/s1mple.png",
        "teamJogador": "Natus Vincere",
        "teamPhotoJogador": "https://cdn.discordapp.com/attachments/1152325417483649078/1156300026075680910/natus-vincere.png?ex=651477d1&is=65132651&hm=56c44fbad0d288daf202f1e25fa388d33dee187349da631f7112225ec81c308d&"
    }
```

## 🕹 Jogos 
Nossa API de jogos contém as seguintes informações

- id 
Contém a identificação dos jogos
- nameJogos
Contém o nome dos jogos
- desenvolvedoraJogos 
Contém o nome da desenvolvedora dos jogos
- descricaoJogos
Contém uma breve descrição sobre os jogos
- photoJogos 
Contém uma foto dos jogos

Um exemplo do uso dessa API é a seguinte: 
```bash
{
        "id": "11",
        "nameJogos": "PUBG",
        "desenvolvedoraJogos": "Player Unknown",
        "descricaoJogos": "PUBG é um jogo Battle Royale multijogador competitivo feito por Player Unknown.",
        "photoJogos": "https://cdn.discordapp.com/attachments/1152325417483649078/1156320818712817684/pubg-2.png?ex=65148b2e&is=651339ae&hm=83a673f8810274a0a87e3972d73a42b45429fde00944158a40093a85f8554187&"
    }
```

## 👥 Times

Nossa API de times contém as seguintes informações:
- id 
Contém a identificação dos times
- nomeTime
Contém o nome dos times
- photoTime
Contém a foto dos times

Um exemplo do uso dessa API é a seguinte: 

```bash
"id" : 21,
        "nomeTime" : "Faze Clan",
        "photoTime" : "https://cdn.discordapp.com/attachments/1152325417483649078/1156271630809579640/image.png?ex=65145d5f&is=65130bdf&hm=3c10cd7e99d34655061b9e7fe26172eb2bb47e75b8efec4e76ccafab6a4f7c12&"
    }
```
## 🏆 Torneios
Nossa API de Torneios contém as seguintes informações:
- id 
Contém a identificação dos Torneios
- nomeCampeonato
Contém o nome dos Torneios
- imagemCampeonato
Contém a imagem dos Torneios
- logoCampeonato
Contém o logo dos Torneios
- descricaoCampeonato
Contém uma breve descrição sobre os Torneios
- logoDoJogo
Contém o logo do jogo que pertence aos Torneios

Um exemplo do uso dessa API é a seguinte: 

```bash
{
        "id" : "42",
        "nomeCampeonato" : "CCT South America Series",
        "imagemCampeonato" : "https://liquipedia.net/commons/images/thumb/5/52/CCT_South_America_full_allmode.png/600px-CCT_South_America_full_allmode.png",
        "logoCampeonato": "https://storage.ensiplay.com/logos/tournaments/27e3eacab79e6310f91c6c19d71460e5.png",
        "descricaoCampeonato": "CCT South America Series é um torneio online Sul-Americano Global Offensive organizado pela BTS Brasil.",
        "logoDoJogo": "https://cdn.discordapp.com/attachments/1152325417483649078/1156322785178693702/counter-strike-global-offensive-logo.png?ex=65148d03&is=65133b83&hm=2ffa6fdbe5bdb9dcb5e90e473e7cc1c02d0d03427be5b343e97bb8dd07743fc0&"
    }
```

## 👨‍💻 Criação do App
[Aqui você pode acompanhar um pouco mais profundamente como foi a criação do app](https://gamma.app/docs/eSportsHub-o9dta7e5dsc8bm3?mode=doc)

## 👥 Equipe

Nosso trabalho em equipe foi fundamental para a realização desse projeto, quero destacar o comprometimento de todos em tornar o app algo unico e divertido.

Agradeço a nossa equipe:
- [André Veras Fernandes](https://www.linkedin.com/in/andre-veras-fernandes/)
- [João Vitor Teixeira Lechinovski](https://www.linkedin.com/in/joãolechinovski/)
- [Juan Augusto Dias Santos](https://www.linkedin.com/in/juan-santos-28a001288/)
- [Kauan Feitoza Mendes](https://www.linkedin.com/in/kauanfm123/)



