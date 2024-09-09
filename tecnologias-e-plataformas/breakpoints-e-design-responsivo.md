---
description: Diretrizes para adaptar layouts a diferentes tamanhos de tela responsivamente.
---

# Breakpoints e Design Responsivo

No desenvolvimento de interfaces modernas, garantir que o design seja responsivo é fundamental para proporcionar uma experiência consistente e otimizada em diferentes dispositivos. Aqui definimos as diretrizes para adaptar layouts a diferentes larguras de tela, desde smartphones até grandes monitores de desktop.

Os **breakpoints** são pontos de corte que indicam quando o layout de uma interface deve se ajustar, permitindo que o conteúdo seja exibido de forma adequada, independentemente do tamanho da tela. No **Nafto** adotamos os cinco breakpoints padrão do **Material UI:** **extra-pequeno (xs)**, **pequeno (sm)**, **médio (md)**, **grande (lg)** e **extra-grande (xl)**. Esses brakpoints podem ser customizados para cada projeto/aplicação.

#### 1. **xs (extra-small): 0px**

* Esse é o ponto de partida para telas menores, como smartphones. **0px** significa que qualquer tela com largura a partir de **0 pixels** até **599px** se encaixa nessa categoria. Ou seja, qualquer tela, mesmo as muito pequenas, será considerada dentro do breakpoint **xs**.

#### 2. **sm (small): 600px**

* Telas com larguras a partir de **600 pixels** até **899px** entram na categoria **small**. Esse é o breakpoint comumente usado para tablets ou celulares maiores. Qualquer ajuste de layout ou estilo definido para **sm** será aplicado quando a tela atingir essa largura.

#### 3. **md (medium): 900px**

* Telas a partir de **900 pixels** até **1199px** são consideradas **médias**. Este é o breakpoint para tablets maiores e telas de laptop de pequeno porte. O layout ajusta-se novamente para caber melhor nessas dimensões.

#### 4. **lg (large): 1200px**

* A partir de **1200 pixels** até **1535px**, temos o breakpoint **large**, que é comumente aplicado para telas de desktop de tamanho médio. Layouts projetados para esse breakpoint visam aproveitar mais espaço horizontal.

#### 5. **xl (extra-large): 1536px**

* Telas acima de **1536 pixels** de largura são consideradas **extra-large**. Essas telas geralmente são monitores grandes de desktop ou telas ultra-wide. O layout pode ser maximizado para utilizar toda a largura disponível, aproveitando o grande espaço.
