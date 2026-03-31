# MANUAL

---

## ■検証手順

```
fetch-tsa-cert

verify-sign UnstopSystem.zip
verify-sign UnstopSystem.hash.txt

verify-hash UnstopSystem.hash.txt

verify-timestamp UnstopSystem.zip
verify-timestamp UnstopSystem.hash.txt
```

---

## ■前提

- fetch-tsa-cert を先に実行すること  
- cacert.pem / tsa.crt が必要  

---

## ■検証できること

- 改ざんされていない  
- 誰が作ったか  
- いつ存在したか  

---

## ■注意

検証を行わずに内容を信用しないこと

---