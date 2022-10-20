# "पुराने" DAI से "नए" DAI में माइग्रेट कैसे करें

[मेकरडीएओ](https://makerdao.com/en/) द्वारा प्रबंधित डीएआई टोकन को 2019-11-18 को 16:00 यूटीसी पर एक अन्य टोकन पते का उपयोग करने के लिए माइग्रेट किया गया था।

आप [मेकरडीएओ के ब्लॉग](https://blog.makerdao.com/multi-collateral-dai-is-live/) पर माइग्रेशन के विशिष्ट विवरण के बारे में अधिक पढ़ सकते हैं।.

* 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359 पर पुराना DAI टोकन अब SAI बन गया है।
* नया बहु-संपार्श्विक डीएआई टोकन अनुबंध (**Multi-Collateral DAI**)0x6b175474e89094c44da98b954eedeac495271d0f है



SAI और DAI के बीच एक माइग्रेशन टूल [माइग्रेट.मेकरडाओ.कॉम ](https://migrate.makerdao.com/)पर उपलब्ध है।

"पुराने" डीएआई (उर्फ एसएआई) टोकन रखने वाले किसी भी संगठन के लिए, 2019-11-25 के आसपास रिलीज के बाद आरागॉन क्लाइंट ने सही नाम दिखाना शुरू कर दिया है।

SAI धारण करने वाले संगठनों के लिए, बहु-संपार्श्विक DAI में अपग्रेड करने के लिए दो अनुशंसित पथ हैं:

SAI को किसी बाहरी खाते या बहु-हस्ताक्षर अनुबंध में स्थानांतरित करें जिसे आप नियंत्रित करते हैं। वहां से, [migrate.makerdao.com](https://migrate.makerdao.com) पर माइग्रेशन इंटरफ़ेस का उपयोग करके SAI को DAI में बदलें, और नए DAI को वापस अपने संगठन में जमा करें।

* अगर आपके संगठन ने अभी तक [एजेंट ऐप](https://app.gitbook.com/o/3h8kxj8geKVXgyMnGbYT/s/qbJnwSlPYXvqQ6buM1wp/) इंस्टॉल नहीं किया है, तो एजेंट ऐप इंस्टॉल करें। SAI को एजेंट ऐप में स्थानांतरित करें, एजेंट ऐप के साथ बातचीत की अनुमति देने के लिए आवश्यक अनुमतियाँ सेट करें, और [फ़्रेम](https://frame.sh/) के माध्यम से [migrate.makerdao.com](https://migrate.makerdao.com) का उपयोग करें।



पुराने SAI Collateralized Debt Position (CDPs) (CDPs) रखने वाले संगठनों के लिए, अनुशंसित माइग्रेशन पथ समान हैं यदि संगठन केवल SAI धारण कर रहा था: संगठन के SAI CDP स्वामित्व को किसी बाहरी खाते, मल्टीसिग या इंस्टॉल किए गए एजेंट ऐप में स्थानांतरित करें, जिसके साथ आप बातचीत कर सकते हैं, और [migrate.makerdao.com](https://migrate.makerdao.com) इंटरफेस का उपयोग करें। इस परिदृश्य में, सुनिश्चित करें कि SAI CDP के स्वामित्व वाले खाते में किसी भी बकाया स्थिरता शुल्क का भुगतान करने के लिए पर्याप्त $MKR भी है।

जो संगठन नए डीएआई वॉल्ट बनाना चाहते हैं, उन्हें स्थापित एजेंट ऐप और फ़्रेम का उपयोग करके ओएसिस ट्रेड एप्लिकेशन के साथ इंटरैक्ट करना चाहिए।