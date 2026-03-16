# 🤝 Guia de Contribució i Col·laboració

[cite_start]Per mantenir la qualitat del codi i la seguretat del xatbot, tots els membres de l'equip han de seguir aquestes normes[cite: 325, 338]:

## 🏆 Regles d'Or Tècniques
1. **Seguretat Absoluta:** Està prohibit escriure l'API Key directament al codi. [cite_start]S'ha d'utilitzar sempre `userdata.get("GOOGLE_API_KEY")`[cite: 339, 340].
2. [cite_start]**Context de la LAN:** No es poden modificar les instruccions de sistema que defineixen la ubicació (Els Costals) o els horaris, per evitar al·lucinacions del model[cite: 341, 342].
3. [cite_start]**Codi Supervisat:** Tot el codi generat per IA ha de ser revisat manualment i acompanyat de comentaris (`#`) que n'expliquin el funcionament[cite: 343, 344].

## 📝 Estàndard de Commits
[cite_start]Utilitzem missatges descriptius per garantir la traçabilitat[cite: 345]:
* [cite_start]`feat:` per a noves funcionalitats[cite: 346].
* [cite_start]`fix:` per a correcció d'errors[cite: 346].
* [cite_start]`docs:` per a canvis en la documentació[cite: 347].

## 🔄 Flux de Treball
* [cite_start]Tot el codi s'ha de provar a Google Colab abans de pujar-lo a GitHub[cite: 335].
* [cite_start]Les evidències visuals (captures del GEM i prompts) es centralitzen al portafolis[cite: 336].
