# JAVASCRIPT एल्गोरिदम और डेटा संरचनाएं

[![Build Status](https://travis-ci.org/trekhleb/javascript-algorithms.svg?branch=master)](https://travis-ci.org/trekhleb/javascript-algorithms)
[![codecov](https://codecov.io/gh/trekhleb/javascript-algorithms/branch/master/graph/badge.svg)](https://codecov.io/gh/trekhleb/javascript-algorithms)

इस रिपॉजिटरी में कई के जावास्क्रिप्ट आधारित उदाहरण हैं
लोकप्रिय एल्गोरिदम और डेटा संरचनाएँ।

प्रत्येक एल्गोरिदम और डेटा संरचना का अपना अलग README होता है
संबंधित स्पष्टीकरणों और आगे पढ़ने के लिए लिंक के साथ (जिनमें ये भी शामिल हैं)।
यूट्यूब वीडियो के लिए)।

_इसे अन्य भाषाओं में पढ़ें:_
[简体中文](README.zh-CN.md),
[繁體中文](README.zh-TW.md),
[한국어](README.ko_KR.md),
[अंग्रेज़ी](RREADME.md)

> हम एक किताब लिख रहे हैं जो मुख्य एल्गोरिदम को स्पष्ट रूप से विस्तार से बताएगी।
यदि आप "जावास्क्रिप्ट एल्गोरिदम" बुक करते समय सूचित होना चाहेंगे
लॉन्च, [यहां क्लिक करें](https://upscri.be/402324/)।

## डेटा संरचनाएं

डेटा संरचना कंप्यूटर में डेटा को व्यवस्थित और संग्रहीत करने का एक विशेष तरीका है ताकि वह कर सके
कुशलतापूर्वक पहुँचा और संशोधित किया जा सके। अधिक सटीक रूप से, डेटा संरचना डेटा का एक संग्रह है
मूल्य, उनके बीच संबंध और वे कार्य या संचालन जिन पर लागू किया जा सकता है
आंकड़ा।

`बी` - शुरुआती, `ए` - उन्नत

* `बी` [लिंक्ड सूची](src/data-structures/linked-list)
* `बी` [डबल लिंक्ड सूची](src/data-structures/doubly-linked-list)
* `बी` [कतार](src/data-structures/queue)
* `बी` [स्टैक](src/data-structures/stack)
* `बी` [हैश टेबल](src/data-structures/heap)
* `बी` [ढेर](src/data-structures/priority-queue)
* `बी` [प्राथमिकता कतार](src/data-structures/hash-table)
* `ए` [ट्राई](src/data-structures/trie)
* `ए` [वृक्ष](src/data-structures/tree)
    * `ए` [बाइनरी सर्च ट्री](src/data-structures/tree/binary-search-tree)
    * `ए` [एवीएल ट्री](src/data-structures/tree/avl-tree)
    * `ए` [लाल-काला पेड़](src/data-structures/tree/red-black-tree)
    * `ए` [सेगमेंट ट्री](src/data-structures/tree/segment-tree) - न्यूनतम/अधिकतम/योग श्रेणी क्वेरी उदाहरणों के साथ
    * `ए` [फेनविक ट्री](src/data-structures/tree/fenwick-tree) (बाइनरी इंडेक्स्ड ट्री)
* `ए` [ग्राफ](src/data-structures/graph) (निर्देशित और अप्रत्यक्ष दोनों)
* `ए` [डिसजॉइंट सेट](src/data-structures/disjoint-set)
* `ए` [ब्लूम फ़िल्टर](src/data-structures/bloom-filter)

## एल्गोरिदम

एल्गोरिथम समस्याओं के एक वर्ग को कैसे हल किया जाए इसका एक स्पष्ट विवरण है। यह है
नियमों का एक सेट जो संचालन के अनुक्रम को सटीक रूप से परिभाषित करता है।

`बी` - शुरुआती, `ए` - उन्नत

### विषय के अनुसार एल्गोरिदम

* **गणित**
  * `बी` [बिट मैनिपुलेशन](src/algorithms/math/bits) - बिट्स सेट/प्राप्त/अपडेट/स्पष्ट करें, दो से गुणा/विभाजन, नकारात्मक बनाएं आदि।
  * `बी` [फैक्टोरियल](src/algorithms/math/factorial)
  * `बी` [फाइबोनैचि संख्या](src/algorithms/math/fibonacci)
  * `बी` [प्रारंभिकता परीक्षण](src/algorithms/math/primality-test) (परीक्षण प्रभाग विधि)
  * `बी` [यूक्लिडियन एल्गोरिथम](src/algorithms/math/euclidean-algorithm) - महानतम सामान्य भाजक (जीसीडी) की गणना करें
  * `बी` [न्यूनतम सामान्य गुणक](src/algorithms/math/least-common-multiple) (एलसीएम)
  * `बी` [एराटोस्थनीज की छलनी](src/algorithms/math/sieve-of-eratosthenes) - किसी भी सीमा तक सभी अभाज्य संख्याओं का पता लगाना
  * `बी` [दो की शक्ति है](src/algorithms/math/is-power-of-two) - जांचें कि क्या संख्या दो की शक्ति है (निष्क्रिय और बिटवाइज़ एल्गोरिदम)
  * `बी` [पास्कल का त्रिकोण](src/algorithms/math/pascal-triangle)
  * `ए` [पूर्णांक विभाजन](src/algorithms/math/integer-partition)
  * `ए` [लियू हुई π एल्गोरिदम](src/algorithms/math/liu-hui) - एन-गॉन पर आधारित अनुमानित π गणना
* **सेट**
  * `बी` [कार्टेशियन उत्पाद](src/algorithms/sets/cartesian-product) - कई सेटों का उत्पाद
  * `बी` [फिशर-येट्स शफल](src/algorithms/sets/fisher-yates) - एक परिमित अनुक्रम का यादृच्छिक क्रमपरिवर्तन
  * `ए` [पावर सेट](src/algorithms/sets/power-set) - एक सेट के सभी सबसेट
  * `ए` [क्रमपरिवर्तन](src/algorithms/sets/permutations) (दोहराव के साथ और बिना)
  * `ए` [संयोजन](src/algorithms/sets/combinations) (दोहराव के साथ और बिना)
  * `ए` [सबसे लंबा सामान्य अनुवर्ती](src/algorithms/sets/longest-common-subsequence) (एलसीएस)
  * `ए` [सबसे लंबे समय तक बढ़ने वाला क्रम](src/algorithms/sets/longest-increasing-subsequence)
  * `ए` [सबसे छोटा सामान्य सुपरसीक्वेंस](src/algorithms/sets/shortest-common-supersequence) (एससीएस)
  * `ए` [नैपसेक समस्या](src/algorithms/sets/knapsack-problem) - "0/1" और "अनबाउंड" वाले
  * `ए` [अधिकतम सबरे](src/algorithms/sets/maximum-subarray) - "ब्रूट फोर्स" और "डायनेमिक प्रोग्रामिंग" (कडाने के) संस्करण
  * `ए` [संयोजन योग](src/algorithms/sets/combination-sum) - विशिष्ट योग बनाने वाले सभी संयोजन खोजें
* **स्ट्रिंग्स**
  * `बी` [हैमिंग दूरी](src/algorithms/string/hamming-distance) - उन स्थितियों की संख्या जिन पर प्रतीक भिन्न हैं
  * `ए` [लेवेनशेटिन दूरी](src/algorithms/string/levenshtein-distance) - दो अनुक्रमों के बीच न्यूनतम संपादन दूरी
  * `ए` [नुथ-मॉरिस-प्रैट एल्गोरिथम](src/algorithms/string/knuth-morris-pratt) (केएमपी एल्गोरिथम) - सबस्ट्रिंग खोज (पैटर्न मिलान)
  * `ए` [जेड एल्गोरिदम](src/algorithms/string/z-algorithm) - सबस्ट्रिंग खोज (पैटर्न मिलान)
  * `ए` [राबिन कार्प एल्गोरिथम](src/algorithms/string/rabin-karp) - सबस्ट्रिंग खोज
  * `ए` [सबसे लंबा सामान्य सबस्ट्रिंग](src/algorithms/string/longest-common-substring)
  * `ए` [नियमित अभिव्यक्ति मिलान](src/algorithms/string/regular-expression-matching)
* **खोजें**
  * `बी` [रैखिक खोज](src/algorithms/search/linear-search)
  * `बी` [जंप सर्च](src/algorithms/search/jump-search) (या ब्लॉक सर्च) - क्रमबद्ध सरणी में खोजें
  * `बी` [बाइनरी खोज](src/algorithms/search/binary-search) - क्रमबद्ध सरणी में खोजें
  * `बी` [इंटरपोलेशन सर्च](src/algorithms/search/interpolation-search) - समान रूप से वितरित क्रमबद्ध सरणी में खोजें
* **छंटाई**
  * `बी` [बबल सॉर्ट](src/algorithms/sorting/bubble-sort)
  * `बी` [चयन सॉर्ट](src/algorithms/sorting/selection-sort)
  * `बी` [सम्मिलन सॉर्ट](src/algorithms/sorting/insertion-sort)
  * `बी` [हीप सॉर्ट](src/algorithms/sorting/heap-sort)
  * `बी` [मर्ज सॉर्ट](src/algorithms/sorting/merge-sort)
  * `बी` [क्विकसॉर्ट](src/algorithms/sorting/quick-sort) - इन-प्लेस और नॉन-इन-प्लेस कार्यान्वयन
  * `बी` [शेलसॉर्ट](src/algorithms/sorting/shell-sort)
  * `बी` [गिनती क्रमबद्ध](src/algorithms/sorting/counting-sort)
  * `बी` [रेडिक्स सॉर्ट](src/algorithms/sorting/radix-sort)
* **पेड़**
  * `बी` [गहराई-पहली खोज](src/algorithms/tree/depth-first-search) (डीएफएस)
  * `बी` [चौड़ाई-पहली खोज](src/algorithms/tree/breadth-first-search) (बीएफएस)
* **ग्राफ़**
  * `बी` [गहराई-पहली खोज](src/algorithms/graph/depth-first-search) (डीएफएस)
  * `बी` [चौड़ाई-पहली खोज](src/algorithms/graph/breadth-first-search) (बीएफएस)
  * `बी` [क्रुस्कल का एल्गोरिदम](src/algorithms/graph/kruskal) - भारित अप्रत्यक्ष ग्राफ के लिए न्यूनतम स्पैनिंग ट्री (एमएसटी) खोजना
  * `ए` [डिज्कस्ट्रा एल्गोरिथम](src/algorithms/graph/dijkstra) - एकल शीर्ष से सभी ग्राफ़ शीर्षों के लिए सबसे छोटा पथ ढूंढना
  * `ए` [बेलमैन-फोर्ड एल्गोरिदम](src/algorithms/graph/bellman-ford) - एकल शीर्ष से सभी ग्राफ़ शीर्षों के लिए सबसे छोटा पथ ढूंढना
  * `ए` [फ्लोयड-वॉर्शल एल्गोरिथम](src/algorithms/graph/floyd-warshall) - शीर्षों के सभी युग्मों के बीच सबसे छोटा पथ ढूंढें
  * `ए` [डिटेक्ट साइकिल](src/algorithms/graph/detect-cycle) - निर्देशित और अप्रत्यक्ष ग्राफ़ दोनों के लिए (डीएफएस और डिसजॉइंट सेट आधारित संस्करण)
  * `ए` [प्राइम का एल्गोरिदम](src/algorithms/graph/prim) - भारित अप्रत्यक्ष ग्राफ के लिए न्यूनतम स्पैनिंग ट्री (एमएसटी) खोजना
  * `ए` [टोपोलॉजिकल सॉर्टिंग](src/algorithms/graph/topological-sorting) - डीएफएस विधि
  * `ए` [आर्टिक्यूलेशन पॉइंट्स](src/algorithms/graph/articulation-points) - टार्जन का एल्गोरिदम (डीएफएस आधारित)
  * `ए` [पुल](src/algorithms/graph/bridges) - डीएफएस आधारित एल्गोरिदम
  * `ए` [यूलेरियन पथ और यूलेरियन सर्किट](src/algorithms/graph/eulerian-path) - फ़्ल्यूरी का एल्गोरिदम - प्रत्येक किनारे पर ठीक एक बार जाएँ
  * `ए` [हैमिलटोनियन चक्र](src/algorithms/graph/hamiltonian-cycle) - प्रत्येक शीर्ष पर ठीक एक बार जाएँ
  * `ए` [मज़बूती से जुड़े घटक](src/algorithms/graph/strongly-connected-components) - कोसाराजू का एल्गोरिदम
  * `ए` [ट्रैवलिंग सेल्समैन समस्या](src/algorithms/graph/travelling-salesman) - सबसे छोटा संभव मार्ग जो प्रत्येक शहर का दौरा करता है और मूल शहर में लौटता है
* **अवर्गीकृत**
  * `बी` [हनोई का टॉवर](src/algorithms/uncategorized/hanoi-tower)
  * `बी` [स्क्वायर मैट्रिक्स रोटेशन](src/algorithms/uncategorized/square-matrix-rotation) - इन-प्लेस एल्गोरिदम
  * `बी` [जंप गेम](src/algorithms/uncategorized/jump-game) - बैकट्रैकिंग, डायनेमिक प्रोग्रामिंग (टॉप-डाउन + बॉटम-अप) और लालची उदाहरण
  * `बी` [अद्वितीय पथ](src/algorithms/uncategorized/unique-paths) - बैकट्रैकिंग, गतिशील प्रोग्रामिंग और पास्कल के त्रिभुज आधारित उदाहरण
  * `ए` [एन-क्वींस समस्या](src/algorithms/uncategorized/n-queens)
  * `ए` [नाइट्स टूर](src/algorithms/uncategorized/knight-tour)

### प्रतिमान द्वारा एल्गोरिदम

एक एल्गोरिथम प्रतिमान एक सामान्य विधि या दृष्टिकोण है जो एक वर्ग के डिजाइन को रेखांकित करता है
एल्गोरिदम का. यह एक एल्गोरिदम की धारणा से उच्चतर एक अमूर्तता है, जैसे कि एक
एल्गोरिथम एक कंप्यूटर प्रोग्राम से भी ऊंचा एक अमूर्त है।

* **क्रूर बल** - सभी संभावनाओं को देखें और सर्वोत्तम समाधान का चयन करें
  * `बी` [रैखिक खोज](src/algorithms/search/linear-search)
  * `ए` [अधिकतम उपसरणी](src/algorithms/sets/maximum-subarray)
  * `ए` [ट्रैवलिंग सेल्समैन समस्या](src/algorithms/graph/travelling-salesman) - सबसे छोटा संभव मार्ग जो प्रत्येक शहर का दौरा करता है और मूल शहर में लौटता है
* **लालची** - भविष्य के बारे में कोई विचार किए बिना, वर्तमान समय में सबसे अच्छा विकल्प चुनें
  * `बी` [जंप गेम](src/algorithms/uncategorized/jump-game)
  * `ए` [अनबाउंड नैपसैक समस्या](src/algorithms/sets/knapsack-problem)
  * `ए` [डिज्कस्ट्रा एल्गोरिथम](src/algorithms/graph/dijkstra) - सभी ग्राफ शीर्षों के लिए सबसे छोटा रास्ता खोजना
  * `ए` [प्राइम का एल्गोरिदम](src/algorithms/graph/prim) - भारित अप्रत्यक्ष ग्राफ के लिए न्यूनतम स्पैनिंग ट्री (एमएसटी) खोजना
  * `ए` [क्रुस्कल का एल्गोरिदम](src/algorithms/graph/kruskal) - भारित अप्रत्यक्ष ग्राफ के लिए न्यूनतम स्पैनिंग ट्री (एमएसटी) खोजना
* **फूट डालो और राज करो** - समस्या को छोटे-छोटे हिस्सों में बांटें और फिर उन हिस्सों को हल करें
  * `बी` [बाइनरी खोज](src/algorithms/search/binary-search)
  * `बी` [हनोई का टॉवर](src/algorithms/uncategorized/hanoi-tower)
  * `बी` [पास्कल का त्रिकोण](src/algorithms/math/pascal-triangle)
  * `बी` [यूक्लिडियन एल्गोरिथम](src/algorithms/math/euclidean-algorithm) - महानतम सामान्य भाजक (जीसीडी) की गणना करें
  * `बी` [मर्ज सॉर्ट](src/algorithms/sorting/merge-sort)
  * `बी` [क्विक सॉर्ट](src/algorithms/sorting/quick-sort)
  * `बी` [ट्री डेप्थ-फर्स्ट सर्च](src/algorithms/tree/depth-first-search) (डीएफएस)
  * `बी` [ग्राफ़ गहराई-प्रथम खोज](src/algorithms/graph/depth-first-search) (डीएफएस)
  * `बी` [जंप गेम](src/algorithms/uncategorized/jump-game)
  * `ए` [क्रमपरिवर्तन](src/algorithms/sets/permutations) (दोहराव के साथ और बिना)
  * `ए` [संयोजन](src/algorithms/sets/combinations) (दोहराव के साथ और बिना)
* **डायनेमिक प्रोग्रामिंग** - पहले पाए गए उप-समाधानों का उपयोग करके एक समाधान बनाएं
  * `बी` [फाइबोनैचि संख्या](src/algorithms/math/fibonacci)
  * `बी` [जंप गेम](src/algorithms/uncategorized/jump-game)
  * `बी` [अद्वितीय पथ](src/algorithms/uncategorized/unique-paths)
  * `ए` [लेवेनशेटिन दूरी](src/algorithms/string/levenshtein-distance) - दो अनुक्रमों के बीच न्यूनतम संपादन दूरी
  * `ए` [सबसे लंबा सामान्य अनुवर्ती](src/algorithms/sets/longest-common-subsequence) (एलसीएस)
  * `ए` [सबसे लंबा सामान्य सबस्ट्रिंग](src/algorithms/string/longest-common-substring)
  * `ए` [सबसे लंबे समय तक बढ़ने वाला क्रम](src/algorithms/sets/longest-increasing-subsequence)
  * `ए` [सबसे छोटा सामान्य सुपरसीक्वेंस](src/algorithms/sets/shortest-common-supersequence)
  * `ए` [0/1 नैपसैक समस्या](src/algorithms/sets/knapsack-problem)
  * `ए` [पूर्णांक विभाजन](src/algorithms/math/integer-partition)
  * `ए` [अधिकतम उपसरणी](src/algorithms/sets/maximum-subarray)
  * `ए` [बेलमैन-फोर्ड एल्गोरिथम](src/algorithms/graph/bellman-ford) - सभी ग्राफ शीर्षों के लिए सबसे छोटा रास्ता खोजना
  * `ए` [फ्लोयड-वॉर्शल एल्गोरिथम](src/algorithms/graph/floyd-warshall) - शीर्षों के सभी युग्मों के बीच सबसे छोटा पथ खोजें
  * `ए` [नियमित अभिव्यक्ति मिलान](src/algorithms/string/regular-expression-matching)
* **बैकट्रैकिंग** - क्रूर बल के समान, सभी संभावित समाधान उत्पन्न करने का प्रयास करें, लेकिन हर बार जब आप अगला समाधान उत्पन्न करते हैं तो आप परीक्षण करते हैं
यदि यह सभी शर्तों को पूरा करता है, और केवल तभी बाद के समाधान उत्पन्न करना जारी रखता है। अन्यथा, पीछे हटें, और आगे बढ़ें
समाधान खोजने का अलग रास्ता. आम तौर पर राज्य-अंतरिक्ष के डीएफएस ट्रैवर्सल का उपयोग किया जा रहा है।
  * `बी` [जंप गेम](src/algorithms/uncategorized/jump-game)
  * `बी` [अद्वितीय पथ](src/algorithms/uncategorized/unique-paths)
  * `ए` [हैमिलटोनियन चक्र](src/algorithms/graph/hamiltonian-cycle) - प्रत्येक शीर्ष पर ठीक एक बार जाएँ
  * `ए` [एन-क्वींस समस्या](src/algorithms/uncategorized/n-queens)
  * `ए` [नाइट्स टूर](src/algorithms/uncategorized/knight-tour)
  * `ए` [संयोजन योग](src/algorithms/sets/combination-sum) - विशिष्ट योग बनाने वाले सभी संयोजन खोजें
* **शाखा और बाउंड** - बैकट्रैकिंग के प्रत्येक चरण में पाए जाने वाले सबसे कम लागत वाले समाधान को याद रखें
खोजें, और अब तक पाए गए सबसे कम लागत वाले समाधान की लागत का उपयोग लागत पर कम सीमा के रूप में करें
समस्या का कम से कम लागत वाला समाधान, अधिक लागत वाले आंशिक समाधानों को त्यागने के लिए
अब तक का सबसे कम लागत वाला समाधान मिला। आम तौर पर राज्य-अंतरिक्ष के डीएफएस ट्रैवर्सल के साथ संयोजन में बीएफएस ट्रैवर्सल
पेड़ का उपयोग किया जा रहा है.

## इस भंडार का उपयोग कैसे करें

**सभी निर्भरताएँ स्थापित करें**
```
npm install
```

**ईएसलिंट चलाएँ**

आप कोड की गुणवत्ता जांचने के लिए इसे चलाना चाह सकते हैं।

```
npm run lint
```
**सभी परीक्षण चलाएँ**
```
npm test
```

**नाम से परीक्षण चलाएं**
```
npm test -- 'LinkedList'
```

**खेल का मैदान**

आप `./src/playground/playground.js` फ़ाइल में डेटा-संरचनाओं और एल्गोरिदम के साथ खेल सकते हैं और लिख सकते हैं
इसके लिए `./src/playground/__test__/playground.test.js` में परीक्षण करें।

फिर यह जांचने के लिए कि क्या आपका खेल का मैदान कोड अपेक्षा के अनुरूप काम करता है, बस निम्नलिखित कमांड चलाएँ:

```
npm test -- 'playground'
```

## उपयोगी जानकारी

### सन्दर्भ

[▶ यूट्यूब पर डेटा संरचनाएं और एल्गोरिदम](https://www.youtube.com/playlist?list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8)

### बिग ओ नोटेशन

बिग ओ नोटेशन में निर्दिष्ट एल्गोरिदम की वृद्धि का क्रम।

![बिग ओ ग्राफ़](./assets/big-o-graph.png)

स्रोत: [बिग ओ चीट शीट](http://bigochheatshield.com/)।

नीचे सबसे अधिक उपयोग किए जाने वाले कुछ बिग ओ नोटेशन और इनपुट डेटा के विभिन्न आकारों के विरुद्ध उनके प्रदर्शन की तुलना की सूची दी गई है।

| बिग ओ नोटेशन | 10 तत्वों की गणना | 100 तत्वों की गणना | 1000 तत्वों की गणना |
| -------------- | -------------------------------- | -------------------------------- | -------------------------------- |
| **ओ(1)** | 1 | 1 | 1 |
| **ओ(लॉग एन)** | 3 | 6 | 9 |
| **ओ(एन)** | 10 | 100 | 1000 |
| **ओ(एन लॉग एन)** | 30 | 600 | 9000 |
| **O(N^2)** | 100 | 10000 | 1000000 |
| **O(2^N)** | 1024 | 1.26e+29 | 1.07e+301 |
| **ओ(एन!)** | 3628800 | 9.3e+157 | 4.02e+2567 |

### डेटा संरचना संचालन जटिलता

| डेटा संरचना | पहुंच | खोजें | निवेशन | विलोपन | टिप्पणियाँ |
| ---------------------- | :-------: | :-------: | :-------: | :-------: | :------- |
| **सरणी** | 1 | n | n | n | |
| **स्टैक** | n | n | 1 | 1 | |
| **कतार** | n | n | 1 | 1 | |
| **लिंक्ड सूची** | n | n | 1 | 1 | |
| **हैश तालिका** | - | n | n | n | सही हैश फ़ंक्शन के मामले में लागत O(1) होगी |
| **बाइनरी सर्च ट्री** | n | n | n | n | संतुलित वृक्ष की स्थिति में लागत O(log(n)) होगी |
| **बी-ट्री** | log(n) | log(n) | log(n) | log(n) | |
| **लाल-काला पेड़** | log(n) | log(n) | log(n) | log(n) | |
| **एवीएल ट्री** | log(n) | log(n) | log(n) | log(n) | |
| **ब्लूम फ़िल्टर** | - | 1 | 1 | - | खोज करते समय गलत सकारात्मकताएं संभव हैं |

### सरणी सॉर्टिंग एल्गोरिदम जटिलता

| नाम | सर्वोत्तम | औसत | सबसे ख़राब | स्मृति | स्थिर | टिप्पणियाँ |
| ---------------------- | :----: | :-----------------: | :-----------------: | :-------: | :-------: | :------- |
| **बबल सॉर्ट** | n | n<sup>2</sup> | n<sup>2</sup> | 1 | हाँ | |
| **प्रविष्टि क्रम** | n | n<sup>2</sup> | n<sup>2</sup> | 1 | हाँ | |
| **चयन प्रकार** | n<sup>2</sup> | n<sup>2</sup> | n<sup>2</sup> | 1 | नहीं | |
| **ढेर प्रकार** | n&nbsp;log(n) | n&nbsp;log(n) | n&nbsp;log(n) | 1 | नहीं | |
| **मर्ज सॉर्ट** | n&nbsp;log(n) | n&nbsp;log(n) | n&nbsp;log(n) | n | हाँ | |
| **त्वरित समाधान** | n&nbsp;log(n) | n&nbsp;log(n) | n<sup>2</sup> | log(n) | नहीं | क्विकॉर्ट आमतौर पर O(log(n)) स्टैक स्पेस के साथ किया जाता है | 
| **शैल सॉर्ट** | n&nbsp;log(n) | अंतराल अनुक्रम पर निर्भर करता है | n&nbsp;(log(n))<sup>2</sup> | 1 | नहीं | |
| **गिनती क्रम** | n + r | n + r | n + r | n + r | हाँ | r - सरणी में सबसे बड़ी संख्या |
| **मूलांक प्रकार** | n * k | n * k | n * k | n + k | हाँ | k - सबसे लंबी कुंजी की लंबाई |
