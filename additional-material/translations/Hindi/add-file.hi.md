## एक नई फ़ाइल जोड़ने का ट्यूटोरियल

यदि आप एक नई फ़ाइल को अपने Git रिपॉज़िटरी में जोड़ना चाहते हैं, तो यह ट्यूटोरियल आपकी मदद करेगा।

1. **नई फ़ाइल बनाएं**:
   - अपने प्रोजेक्ट फ़ोल्डर में जाएं।
   - नई फ़ाइल बनाने के लिए अपने पसंदीदा टेक्स्ट संपादक का उपयोग करें या आपका कोई IDE हो तो वहां से नई फ़ाइल बना सकते हैं।
   - फ़ाइल को विशेष नाम दें और सहेजें।

2. **फ़ाइल को स्टेज करें**:
   - टर्मिनल खोलें और रिपॉज़िटरी फ़ोल्डर में जाएं।
   - नई फ़ाइल को स्टेज करने के लिए निम्नलिखित कमांड का उपयोग करें:
     ```
     git add नया_फ़ाइल.एक्शन
     ```

3. **कमिट करें**:
   - फ़ाइल को स्टेज करने के बाद, एक कमिट बनाएं।
   - निम्नलिखित कमांड का उपयोग करें:
     ```
     git commit -m "नई फ़ाइल जोड़ी गई"
     ```

4. **रिमोट रिपॉज़िटरी में पुश करें**:
   - आपकी फ़ाइल अब आपके लोकल रिपॉज़िटरी में है। अब इसे रिमोट रिपॉज़िटरी में भेजने के लिए निम्नलिखित कमांड का उपयोग करें:
     ```
     git push दूरस्थ_शाखा
     ```
   - यहाँ "दूरस्थ_शाखा" वह नाम है जिसमें आप फ़ाइल जोड़ना चाहते हैं।

अब आपने एक नई फ़ाइल अपने रिपॉज़िटरी में जोड़ दी है।