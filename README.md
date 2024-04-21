# pizza-delivery-algorithm

У робота Алгоритміуса з'явився електроскутер і тепер він працює в службі доставки. Його завдання привозити смачну піцу студентам.
Зазвичай маршрут доставки проходить спочатку ву- лицями міста, де Алгоритміус може їхати зі швидкістю 21 метрів на секунду, а потім через міський парк, де швид кість автоматично знижується до 12 метрів на секунду. Алгоритміус зазвичай дуже пунктуальний, але іноді бу- вають непередбачувані ситуації і робот обов'язково має попередити студентів, на скільки хвилин він запізнюєть- ся.
PIZZA
Нехай 1 метрів відстань, яку Алгоритміус має по- долати, при цьому вулицями міста зі швидкістю 21 йому треба проїхати К метрів і доставити піцу через Т хвилин. Розробіть програму для штучного інтелекту Алгоритміу- са, яка буде виводити інформацію про точний час достав- ки піци.
Формат входных данных
У першому рядку вхідних даних подається два цілих числа: L та Т. У другому рядку подається ціле число К. У третьому рядку цілі числа 21 та 22.
Ограничения
500 L < 10000
1<T<60
100 < K≤ 9000, K <L
3 <2 <1 <9
Формат выходных данных
Якщо Алгоритміус встигне вчасно, то виведіть повідомлення: «The pizza will be delivered on time».
Якщо Алгоритміус не встигне вчасно привезти піцу, то час запізнення треба округлити вгору до найближчого цілого числа хвилин № і вивести повідомлення: «Algorithmius will be N minutes late».

## Collaborate with GPT Engineer

This is a [gptengineer.app](https://gptengineer.app)-synced repository 🌟🤖

Changes made via gptengineer.app will be committed to this repo.

If you clone this repo and push changes, you will have them reflected in the GPT Engineer UI.

## Tech stack

This project is built with React and Chakra UI.

- Vite
- React
- Chakra UI

## Setup

```sh
git clone https://github.com/GPT-Engineer-App/pizza-delivery-algorithm.git
cd pizza-delivery-algorithm
npm i
```

```sh
npm run dev
```

This will run a dev server with auto reloading and an instant preview.

## Requirements

- Node.js & npm - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
