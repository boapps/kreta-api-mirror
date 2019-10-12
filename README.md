# kreta-api-mirror

Ez egy másolat a krétás iskolák listájáról, mert a krétások nem tartják be a 20 éves standardot, hogy a header kulcsának case-insensitive-nek kell lennie. "Field names are case-insensitive." https://www.w3.org/Protocols/rfc2616/rfc2616-sec4.html#sec4.2
Így van néhány nyelv/sdk amiben nem engedik, hogy a header case-sensitive legyen és azokban nem lehet a krétás iskolákat lekérni.

```bash
curl -o school-list.json -H "apiKey: 7856d350-1fda-45f5-822d-e1a2f3f1acf0"  https://kretaglobalmobileapi.ekreta.hu/api/v1/Institute
```
