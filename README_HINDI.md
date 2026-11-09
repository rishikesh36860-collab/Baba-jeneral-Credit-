# Baba General Store – Digital Udhari Khata (Android starter)

इस Android project में शुरुआती स्क्रीन, ग्राहक जोड़ना, उधार/जमा एंट्री और ग्राहक का बाकी बैलेंस दिखाने का UI शामिल है।

## महत्वपूर्ण स्थिति
यह अभी **starter source project** है, तैयार APK नहीं। मौजूदा demo data app बंद करने पर सुरक्षित नहीं रहता। इसे असली दुकान में इस्तेमाल करने से पहले नीचे दिए काम पूरे करना जरूरी है:
1. Room database जोड़कर ग्राहक और लेन-देन को फोन में स्थायी रूप से सेव करना।
2. Firebase project बनाकर `app/google-services.json` जोड़ना।
3. Firebase Authentication और Firestore security rules सेट करके दोनों डिवाइस में सुरक्षित cloud sync बनाना।
4. बैकअप/रिस्टोर, PIN लॉक, PDF/WhatsApp स्टेटमेंट और डेटा एक्सपोर्ट की जाँच करना।

## Build
Android Studio में यह folder खोलें, Gradle sync करें और Android device पर Run करें। `google-services.json` न होने पर Google Services plugin के कारण sync/build रुक सकता है; cloud setup से पहले plugin और Firebase dependencies अस्थायी रूप से हटाकर केवल UI preview किया जा सकता है।

## दुकान की जानकारी
- Baba General Store
- संपर्क: 8873543425 / 7654070570
- पता: Molama Basauli, Muzaffarpur – 844127

## सुरक्षा
ग्राहकों का असली उधार डेटा इस demo में न डालें। Cloud sync को Firebase rules और authentication के बिना सार्वजनिक न करें।
