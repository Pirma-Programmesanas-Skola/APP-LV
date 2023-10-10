---
title: 3 - Space Invaders
author: Veronika Lohmanova
date: 2023-10-08
category: projects
layout: post
---

- [Attēli](https://drive.google.com/drive/folders/13ve9YIAdTJ9foMBpLh08bOc-ZukYtX_w?usp=sharing)
- [Bezmaksas pixel art](https://craftpix.net/freebies/)

## Projekta apraksts

Visiem zināma spēlē :D

## Projektā izmantotas komponentas

- `Drawing and Animation` > `Canvas` - **kanva**
  > Divdimensiju skārienjutīgs taisnstūra panelis, uz kura var zīmēt un pārvietot gariņus
- `Drawing and Animation`> `ImageSprite` - **gariņš**
  > Var reaģēt uz pieskārieniem un vilkšanu, mijiedarboties ar citiem gariņiem
- `Layout` > `HorizontalArrangment`
- `UserInterface` > `Button`
- `Sensors` > `Clock` - **Pulksteņis**
  > Neredzama komponenta, kas nodrošina laika mīrklī, izmantojot tālruņa iekšējo pulksteni. Tā var regulāri noteiktos intervālos iedarbināt taimeri un veikt laika aprēķinus, manipulācijas un konvertēšanu.

## Projektā izmantotas kompontetu metodes un īpašības

- `Screen.Initialize`
- `ImageSprite.X` - gariņa X koordināte
- `ImageSprite.Y` - gariņa Y koordināte
- `ImageSprite.Speed` - gariņa ātrums, ar kuru tas kustās
- `ImageSprite.Heading` - gariņa virziens, kur tas kustās
- `ImageSprite.MoveTo` - pārvietot gariņu
- `ImageSprite.Dragged` - notikums, kad gariņš tika vilkts
- `ImageSprite.EdgeReached` - notikums, kad gariņš ir uz kanvas malas
- `ImageSprite.CollidedWith` - notikums, kad gariņš satriecas ar kādu citu gariņu
- `Clock.Timer` - notikums, kad taimeris beidzas
- `{}.Visible`
- `Button.Click`
- `Label.Text`

## Projektā izmantoti koda bloki

- `random integer from {} to {}` - nejauši izvēlēts vesels skaitlis

## Projekta instrukcija

[:)](https://appinventor.mit.edu/explore/ai2/space-invaders)
Ar modifikācijam:

1. Gariņiem ir noteikta sākumpozīcija.
2. Ienadnieku kosmosa kuģim kustās ar noteikto ātrumu.
3. Kad ienadnieku kosmosa kuģis ir uz malas, tās pārvietojas nejauši izvēlēta X pozīcija.

## Papildizaicinājumi

1. Pielikt vienu tādu pašu ienadnieku kosmosa kuģi, kas pārvietojas pretēja virzienā.
2. Pielikt dažāda veida ienaidniekus - citādāks attēls, ātrums un punkti.
3. Have some fun :D
