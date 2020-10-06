कभी-कभी आपके पास एक स्ट्रिंग हो सकती है जो एक ऐरे के रूप में आपके लिए अधिक उपयोगी होगी। उदाहरण के लिए:

```javascript
var data = "butter sugar eggs flour";
```

स्ट्रिंग `data` रिक्त स्थान द्वारा अलग की गई कुछ जानकारी सम्मिलित करता है। जहां भी रिक्त स्थान है वहां स्ट्रिंग को विभाजित करने के लिए और परिणामों को `ingredients` नामक एक ऐरे में डालने के लिए आप यह कर सकते हैं:

```javascript
var data = "butter sugar eggs flour";
var ingredients = data.split(" ");
```

देखें कि यह कोड कैसे काम करता है और इसे स्वयं यहाँ आज़माएँ: 
<iframe src="https://trinket.io/embed/html/3e59e1063a" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>
