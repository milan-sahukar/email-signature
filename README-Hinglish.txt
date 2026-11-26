MILAN SAHUKAR - ANIMATED EMAIL SIGNATURE (FREE SETUP)
=====================================================

ZIP ke andar kya hai
- upload-to-github/  -> ye sab files GitHub par upload karni hain
    signature.gif         = animated signature (isme aapki photo wala card hai)
    signature-static.png  = static fallback (GIF na chale to iska use karo)
    icon-linkedin.png, icon-github.png, icon-leetcode.png, icon-portfolio.png
    index.html            = Gmail ke liye signature page (Copy button ke saath)
    local-preview.html    = sirf computer par dekhne ke liye
- README-Hinglish.txt   -> ye file

PART 1: FREE HOSTING (GitHub Pages) - sirf ek baar
---------------------------------------------------
Gmail ko images ek public link se chahiye hoti hain. GitHub Pages bilkul free hai.

1. github.com par apne account (milan-sahukar) mein login karo.
2. Upar right mein "+" dabao -> "New repository".
3. Repository name EXACTLY ye likho:  email-signature
4. "Public" select karo. Baaki kuch mat badlo. "Create repository" dabao.
5. Page par "uploading an existing file" link dikhega, usko dabao.
6. ZIP ko pehle extract karo. Phir "upload-to-github" folder ke ANDAR ki saari 8 files
   (folder nahi, sirf files) drag karke daal do.
7. Neeche "Commit changes" dabao.
8. Repository ki "Settings" -> left side mein "Pages" kholo.
9. "Build and deployment" mein Source = "Deploy from a branch".
   Branch = "main", folder = "/ (root)" -> "Save" dabao.
10. 1 se 3 minute ruko. Phir ye link browser mein kholo:
    https://milan-sahukar.github.io/email-signature/
    Agar signature animate hota dikh raha hai, hosting ho gayi.

Dhyan do: agar aapne repository ka naam kuch aur rakha, to mujhe batao.
Links us naam ke hisaab se badalne padenge.

PART 2: GMAIL MEIN PERMANENT INSTALL (computer ke browser se)
-------------------------------------------------------------
1. Upar wala GitHub Pages link kholo.
2. "Copy Signature" button dabao.
3. Gmail kholo (mail.google.com) -> upar right mein Gear icon -> "See all settings".
4. "General" tab mein neeche scroll karke "Signature" tak jao.
5. "Create new" dabao, naam likho: Milan, phir "Create".
6. Signature box mein click karo aur Ctrl+V (Mac: Cmd+V) se paste karo.
   Aapko animated card, 4 icons, phone aur email dikhne chahiye.
7. Signature box ke neeche "Signature defaults" mein:
     FOR NEW EMAILS USE: Milan
     ON REPLY/FORWARD USE: Milan
   (Isse har naye mail aur reply mein signature apne aap aayega.)
8. Sabse neeche "Save Changes" dabao. (Ye step zaroori hai.)
9. "Compose" dabao aur dekho signature aa gaya ya nahi.

Agar paste mein image nahi aayi (backup tareeka):
- Signature box ke toolbar mein Image icon -> "Web address (URL)" -> ye link daalo:
  https://milan-sahukar.github.io/email-signature/signature.gif
- Phir us image par click karke Link icon se portfolio link lagao:
  https://milan-sahukar-portfolio.onrender.com/
- Neeche text mein phone aur email apne aap clickable ho jaate hain.

PART 3: TEST KARO
-----------------
- Khud ko ek mail bhejo, aur kisi dusre email account par bhi bhejo.
- Check karo: GIF animate ho raha hai, 4 icons aur phone/email click hote hain.

DHYAN DENE WALI BAATEN
----------------------
- Gmail ka mobile app HTML/animated signature support nahi karta. Phone se bheji mail mein
  ye signature nahi aayega. Animated signature sirf computer ke browser se bheji mail mein
  lagega. (Phone par receiver ko signature properly dikhta hai.)
- Kuch apps (jaise Outlook desktop) GIF ka sirf pehla frame dikhate hain. Isliye pehla frame
  poora complete banaya hai, taaki wahan bhi signature poora dikhe.
- GIF ke andar ke icons sirf design ke liye hain. Clickable icons GIF ke neeche wali row mein hain.
- Photo/details badalni ho to mujhse bolo, main naya GIF bana dunga.
