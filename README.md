# Rap-Bot
Dirbtinio intelekto modelis, kuriantis repo eilutes
Šis projektas yra repo eilių generavimo ir dialogo sistema, kuri naudoja **LSTM (Long Short-Term Memory)** modelį naujų eilių generavimui ir **LLM (Large Language Model)** modelį (Gemini) sugeneruoto teksto koregavimui, siekiant pagerinti gramatiką ir rimavimą. Galiausiai, eilės yra įgarsinamos (TTS), kad būtų galima simuliuoti interaktyvų repo mūšį.

## Tikslas
Sukurti interaktyvų repo botą, kuris gali reaguoti į kito boto (arba vartotojo) eilutes ir generuoti bei įgarsinti atsakomąsias eiles.

## Paleidimo instrukcijos
**1.1
Įsitikinkite, kad jūsų Google Drive yra šie failai ir aplankai:
* `/MyDrive/Rap-bot data/lyrics_dataset.csv` (Originalus dainų tekstų rinkinys)
* `/MyDrive/shared_seed.txt` (Naudojamas dviem botams "komunikuoti")
  
Šiam darbui duomenų rinkinys buvo paimtas iš https://www.kaggle.com/datasets/jamiewelsh2/rap-lyrics

**1.2 Google Colab aplinkoje paleiskite visus tris failus šia tvarka:
1) duomenys.ipynb
2) rapbot_modelis.ipynb
3) rap_bot_generate.ipynb
(Pastaba! Įsitikinkite, kad turite įsirašę GOOGLE_API_KEY į savo Google Colab aplinką.)

