
# Vytauto Bartušio Virtualus Asistentas 🛠️

Šis projektas yra išmanus AI chatbot'as, skirtas Vytauto Bartušio santechnikos paslaugoms pristatyti.

## 🚀 Kodėl šis chatbot'as?
- **Tikslumas:** Atsako tik remdamasis oficialia informacija.
- **Regionas:** Specializuojasi Vilniuje ir aplink (+50km).
- **Konkreti specializacija:** Nauja statyba, vandentiekis, šildymas.

## 🛠️ Kaip įkelti į GitHub (Terminalo komandos)

Jei naudojate terminalą, įvykdykite šias komandas savo projekto aplanke:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/aurimasdabro-dev/vytautui.git
git push -u origin main
```

## 🌐 Talpinimas (Vercel)

1. Prisijunkite prie [Vercel.com](https://vercel.com) su savo GitHub paskyra.
2. Pasirinkite **"Add New Project"** ir importuokite `vytautui` saugyklą.
3. **SVARBU:** Nustatymuose pridėkite Environment Variable:
   - **Key:** `API_KEY`
   - **Value:** [Jūsų Google Gemini API raktas iš AI Studio]
4. Spauskite **Deploy**.

## 📦 Įdėjimas į WordPress svetainę

Naudokite šį kodą (pakeiskite `JŪSŲ_NUORODA` į gautą iš Vercel):

```html
<iframe 
  src="https://JŪSŲ_NUORODA.vercel.app" 
  style="border:none; width:400px; height:600px; position:fixed; bottom:20px; right:20px; z-index:9999; border-radius:15px; shadow: 0 10px 15px rgba(0,0,0,0.1);" 
  title="Chatbot">
</iframe>
```

---
*VYTAUTO BARTUŠIO • VIRTUALUS PAGALBININKAS*
