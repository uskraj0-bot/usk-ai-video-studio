USK AI VIDEO STUDIO — Android Studio प्रोजेक्ट

यह एक शुरुआती Android ऐप प्रोटोटाइप है। इसमें Prompt, भाषा, वीडियो की लंबाई और YouTube/Shorts फॉर्मेट चुनने का इंटरफेस है।

महत्वपूर्ण:
- यह ZIP अभी APK नहीं है; यह Android Studio में खुलने वाला source project है।
- Generate बटन अभी डेमो स्थिति दिखाता है। यह असली MP4 वीडियो नहीं बनाता।
- असली वीडियो जनरेशन के लिए किसी वीडियो AI सेवा की API और एक सुरक्षित backend/server जोड़ना होगा।
- API key को APK के अंदर कभी hard-code न करें।

APK बनाने के लिए:
1. कंप्यूटर पर Android Studio इंस्टॉल करें।
2. इस ZIP को extract करें और Android Studio में project folder खोलें।
3. Gradle sync पूरा होने दें।
4. Build > Build Bundle(s) / APK(s) > Build APK(s) चुनें।
5. APK app/build/outputs/apk/debug/ में बनेगा।

अगला विकास चरण:
Backend में prompt भेजना, scenes बनाना, voice/music जोड़ना, video render करना, progress दिखाना और तैयार MP4 डाउनलोड करना।
