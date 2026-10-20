# Java D?ng?leri ile Elmas Deseni

?? i?e d?ng?lerle y?ld?z karakterlerinden elmas ve ??gen desenleri olu?turmay? ad?m ad?m g?steren Java e?itim uygulamas?.

## ?zellikler

- Desen boyutunu belirleyip ??kt?y? g?rselle?tirme
- D?ng?lerin ?al??ma ad?mlar?n? izleme
- Java kaynak kodu ve interaktif konsol sim?lat?r?

## Teknolojiler

- React
- TypeScript
- Vite

Uygulama, Java algoritmalar?n? taray?c? tabanl? etkile?imli bir aray?zde ??retmek ve sim?le etmek i?in haz?rlanm??t?r. Java kaynak kodlar? uygulama i?inden incelenebilir. Web aray?z?n? ?al??t?rmak i?in Node.js gerekir.

## Kurulum ve ?al??t?rma

**Gereksinimler:** G?ncel bir Node.js LTS s?r?m? ve npm.

```bash
npm install
npm run dev
```

Geli?tirme sunucusu ba?lad?ktan sonra terminalde g?sterilen yerel adresi taray?c?da a??n.

## Kontroller ve ?retim derlemesi

```bash
npm run lint
npm run build
```

`npm run lint`, TypeScript denetimini; `npm run build`, da??t?m derlemesini ?al??t?r?r. Derlemeyi yerel olarak g?r?nt?lemek i?in `npm run build` sonras?nda `npm run preview` komutunu kullan?n.

## Proje yap?s?

- `src/components/` ? aray?z, kod g?r?n?m? ve algoritma sim?lat?rleri
- `src/main.tsx` ? uygulaman?n ba?lang?? noktas?
- `package.json` ? ba??ml?l?klar ve npm komutlar?

## Katk?

De?i?iklik yaparken algoritma sonu?lar?n? ve ad?m ad?m sim?lasyonlar? do?rulay?n; mevcut TypeScript tiplerini ve proje bi?imini koruyun.
