# Hack AI — GitHub Pages + APK Setup

## Step 1 — GitHub par upload (phone se)
1. github.com par free account banao
2. New repository banao, naam: `hack-ai`
3. `index.html`, `manifest.json`, `icon-192.png`, `icon-512.png` — ye 4 files upload karo (Add file → Upload files)
4. Repo → Settings → Pages → Source = `main` branch → Save
5. 1-2 minute mein URL milega: `https://<yourusername>.github.io/hack-ai/`

## Step 2 — APK banane ke liye
1. pwabuilder.com kholo
2. Wahi GitHub Pages URL paste karo → Start
3. "Android" package select karo → Generate → APK download ho jayega
4. Ye APK WhatsApp/Drive se kisi ko bhi share kar sakte ho

## Abhi jo cheez baaki hai (real app banane ke liye)
- Har feature (Video/Image/Song/Prompt/Upscale/Story Map) abhi **placeholder** hai — real API connect nahi hui
- Real AI generation ke liye actual API key + confirmed endpoint chahiye (Gemini official ya jo bhi service decide karo)
- AdMob real ad unit IDs abhi nahi lagaye — placeholder text hai bottom banner mein
- Login abhi sirf UI hai, koi backend save nahi kar raha

Jab API confirm ho jaye, mujhe bata dena — us feature ka real working code add kar dunga.
