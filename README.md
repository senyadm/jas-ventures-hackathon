![image](https://user-images.githubusercontent.com/74203105/174469385-36c91e10-221a-4754-9196-3add8c1ecf3e.png)


# Название команды/Team name: 
Aday Labs

## Состав/Developers:
Айсұлтан Кайпиев/Aisultan Kaipiyev	
Арсен Әбдіғали/Arsen Abdigali	
Арсений Мезенцев/Arsenis Mezentsev
Алдияр Сериков/Aldiyar Serikov
Алмаз Балгали/Almaz Bagali

## Темы Хакатона/Hackathon Topics:
RU
1. Крипто Кошелек с обменом валют по текущему курсу
2. Разработать концепцию игры с внутри игровой валютой с возможностью обмена на NFT token
3. Бонусная сеть с вознаграждением в виде токенов в маркетинговых целях
4. Разработать блокчейн бридж между двумя любыми двумя сетями с возможностью перенесения NFT токенов с одной сети в другую и обратно
5. Разработать систему NFT маркетплейса совмещенную с механизмом DAO
6. Разработка смарт контракта на ERC 1155 c механизмом DAO
7. Разработка NFT маркетплейса в области сельского хозяйства
8. Разработка мобильного приложения NFT маркетплейса
9. Разработка токена вознаграждения при посещении NFT маркетплейса
EN
1. A crypto wallet with currency exchange at the current exchange rate
2. Develop the concept of a game with in-game currency with the possibility of exchanging for a TAE token
3. Bonus network with reward in the form of tokens for marketing purposes
4. Develop a blockchain bridge between any two networks with the possibility of transferring TAE tokens from one network to another and back
5. To develop an NFT marketplace system combined with the DAO mechanism
6. Development of a smart contract for ERC 1155 with the DAO mechanism
7. Development of the NFT marketplace in the field of agriculture
8. Development of the NFT marketplace mobile application
9. Development of a reward token when visiting the NFT marketplace

Охватываемые темы: 4,5,6. / Covered topics: 4,5,6.
Идея проекта: / Project Idea:
NFT маркетплейс для ДАО сервисов. / NFT marketplace for DAO services.

Цель проекта / Project Goal:
Предоставить пользователям возможность пользоваться ДАО сервисом без непосредтсвенной разработки организации. / Provide users with access to DAO services without direct organizational development.

Характеристики / Features:
Обзор / Overview:
Система из себя представляет собой NFT маркетплейс связанный с децентрализованной автономной организацией (ДАО). / The system is an NFT marketplace connected with a decentralized autonomous organization (DAO). В ДАО токен ERC 1155 стандарта является токеном доступа, который дает право пользователю голосовать. / In the DAO, the ERC 1155 token standard serves as an access token that grants users voting rights. У каждого токена доступа есть свой идентификатор и категория которые будут их отличать друг от друга. / Each access token has its own identifier and category, distinguishing them from one another. Токен доступа минтится и покупается за счет OtrarCoin, местной валюты. / The access token is minted and purchased using OtrarCoin, the local currency. Также за местную валюту можно создавать собственные голосования в которых могут участвовать только владельцы токенов доступа с определенным идентификатором. / Additionally, local currency can be used to create custom polls that only holders of access tokens with a specific identifier can participate in.

Функционал системы / System Functionality:
Система вмещает в себя следующие функции: / The system includes the following features:

Минт и сжигание локального ERC 20 токена (OTC). / Minting and burning of the local ERC 20 token (OTC).
Создание голосование внутри ДАО за счет локального токена. / Creation of DAO polls using the local token.
Покупка имеющихся токенов ERC 1155 за локальные токены, которые дают доступ участия в ДАО. / Purchasing ERC 1155 tokens with local tokens, granting access to DAO participation.
Голосовать на определенных выборах внутри ДАО для участников организации. / Voting in specific DAO elections for organization members.
Компоненты / Components:
В системе находятся следующие компоненты: / The system includes the following components:

ERC 20 и 1155 токены. / ERC 20 and 1155 tokens.
ДАО и его ответвления. / DAO and its branches.
Маркетплейс / Marketplace.
Смарт-контракт моста между ETH и BNB / Smart contract bridge between ETH and BNB.
ERC 20 и 1155 токены / ERC 20 and 1155 Tokens:
ERC 20 (ОТС) и ERC 1155 (токен доступа) будут являются главными единицами управления в системе. / ERC 20 (OTC) and ERC 1155 (access tokens) will be the main governance units in the system. ОТС будет использоваться в виде расходного материала и платежной валюты, а токен доступа будет являться единицей которая дает право участвовать в голосовании ДАО. / OTC will serve as expendable material and currency, while access tokens will allow participation in DAO voting. Токен доступа будет добываться только за счет ОТС. / The access token will be obtainable only through OTC.

ДАО и внутриорганизационные опросы / DAO and Internal Polls:
ДАО будет вмещать себя тех пользователей которые имеют в своем кошельке ERC 1155. / The DAO will include users who have ERC 1155 tokens in their wallets. К нашему ДАО присущи следующие функционалы: / Our DAO will offer the following functionalities: Создание нового опроса с определенной темой/проблемой или вопросом и уникальным для опроса идентификационным номером. / Creating new polls with specific topics/issues or questions and a unique poll identifier. То есть с созданием каждого опроса, будет создаваться определенное количество токенов доступа, которые будут давать право на голосование в этом опросе. / For each poll created, a specific number of access tokens will be issued, allowing voting rights in that poll. Вдобавок токен доступа будет давать право участвовать в голосованиях затрагивающих все ДАО. / Additionally, the access token will grant participation rights in DAO-wide voting.

Вес голоса в ДАО будет определяться количеством токенов доступа в кошельке пользователя. / Voting weight in the DAO will be determined by the number of access tokens in a user's wallet. Один токен доступа можно будет использовать только один раз и после этого он будет использоваться только при подсчете веса голоса для всей системы. / Each access token can only be used once for voting and thereafter counts only towards overall voting weight in the system. Также все опросы и действия которые они произвели после активации будут записаны на блокчейне, то есть каждый из токенов доступа в потенциале может иметь историческую ценность. / All polls and subsequent actions will be recorded on the blockchain, giving each access token potential historical value.

Маркетплейс / Marketplace:
Маркетплейс будет из себя представлять место где будут продаваться токены доступа за ОТС. / The marketplace will be a space where access tokens can be purchased with OTC. Когда будет осуществляться покупка токена доступа для пользователя на Солана, будет активироваться мост между сетями и переносить токен из одной сети в другую. / When an access token is purchased for a user on Solana, a network bridge will transfer the token between networks. Даже после того как опрос закончится пользователи могут продать свои токены доступа другим пользователям которые не принимали участия в опросах до этого, а просто хотят стать частью самой организации. / Even after a poll ends, users can sell their access tokens to others who did not participate in the polls but want to join the organization.

Кросс-чейн Мост между Эфиром и Бинанс Смарт Чейном / Cross-chain Bridge between Ethereum and Binance Smart Chain:
Проект содержит в себе одну общую реализацию простого офф-чейн бриджа. / The project includes a single implementation of a basic off-chain bridge. В добавок к нему, существуют два отдельных контракта, определяющих бриджи со стороны каждого из блокчейнов. / Additionally, there are two separate contracts defining bridges from each blockchain side. Контракты полностью завязаны под события, которые должны будут считываться на сервере или клиенте, тем самым передавая крипту или токены (обертки). / The contracts are entirely event-based, reading data on the server or client side and transferring wrapped tokens or crypto accordingly. К сожалению, из-за малых временых рамок, мы не успели до конца закончить данную фичу. / Unfortunately, due to limited time, we were unable to complete this feature.

Запуск программы / Program Launch:
git clone project

npm install -> to install dependencies 

after npm install restart your IDE

npm start -> to start project
