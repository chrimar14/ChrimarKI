# Chrimar KI

'n Eerste volledige web-app vir **Chrimar KI** met:
- Afrikaanse KI-klets
- KI-prentgenerering
- Gespreksgeskiedenis op die toestel
- Prent aflaai
- Mobiele ontwerp vir Android

## Wat jy nodig het

1. Node.js 20+.
2. 'n OpenAI API-sleutel.
3. API-krediet/billing op jou OpenAI API-projek.

## Installasie

Maak 'n terminal/Command Prompt in hierdie projek se gids oop:

```bash
npm install
```

Kopieer `.env.example` na `.env` en plaas jou API-sleutel in:

```text
OPENAI_API_KEY=jou_sleutel
```

Begin die app:

```bash
npm start
```

Maak dan:

```text
http://localhost:3000
```

op jou rekenaar of foon oop.

## Belangrik

Moenie jou API-sleutel in `public/app.js` of enige ander frontend-lêer plaas nie. Die sleutel bly op die bediener in `.env`.

## Volgende weergawe

Hierdie basis kan uitgebrei word met:
- Google/Apple-aanmelding
- gebruikerprofiele
- wolk-geskiedenis
- steminvoer en stemantwoorde
- meer prentstyle en beeldformate
- betaalde planne
- 'n regte Android APK
- administrateurpaneel
