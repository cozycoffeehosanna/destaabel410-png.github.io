# Cozy Coffee — በስልክ ማተም (በአማርኛ)

ይህ ፓኬጅ ሁሉም ፋይሎች በአንድ ደረጃ ላይ ናቸው (ምንም አቃፊ የለም)፤ ስለዚህ በስልክ ለመጫን ቀላል ነው።
ትዕዛዝ ሲጨርሱ Telegram ወደ `@destisha12` ይከፈታል፤ ደንበኛው "Send" ይጫናል።

## መንገድ 1 — Netlify Drop (በጣም ቀላሉ)
1. ዚፑን በስልክህ "Files" መተግበሪያ ውስጥ ፍታው (ዚፑን ንካ → Extract)።
2. በስልክ አሳሽ (Chrome) ውስጥ **app.netlify.com/drop** ክፈት።
3. አቃፊውን ወይም ዚፑን ለመጫን "browse to upload" ተጫን፤ ፋይሎቹን ምረጥ።
4. በጥቂት ሰከንዶች ውስጥ link (`xxxx.netlify.app`) ይሰጥሃል። የ Netlify አካውንት ክፈት (በነጻ) አለበለዚያ link ከ1 ሰዓት በኋላ ይጠፋል።

## መንገድ 2 — GitHub + Netlify (መንገድ 1 ካልሰራ)
1. github.com ላይ አካውንት ክፈት → New repository (`cozy-coffee`)።
2. **Add file → Upload files** ተጫን፤ ሁሉንም ፋይሎች በአንድ ላይ ምረጥ → Commit።
3. app.netlify.com → Add new site → Import from Git → `cozy-coffee` → Deploy።

## ከታተመ በኋላ
- ድረ-ገጹን ሞክር፤ አንድ ትዕዛዝ አድርግና Telegram እንደሚከፈት አረጋግጥ።
- **Google Business Profile** ላይ የድረ-ገጹን አድራሻ ጨምር።
- **ጠቃሚ፦** `index.html`፣ `sitemap.xml` እና `robots.txt` ውስጥ `https://REPLACE-ME` የሚለውን በእውነተኛው አድራሻ መተካት አለበት፤ አድራሻውን ንገረኝ፣ እኔ እተካዋለሁ።
