# Guia de Contribució per a l'Equip de Treball

Aquesta guia estableix les regles de desenvolupament que tots els integrants de l'equip de l'Iman han de complir per treballar al repositori sense generar conflictes de codi.

## Directrius del Projecte
1. **Seguretat i Secrets:** Sota cap concepte es permetrà penjar codi font a GitHub que contingui claus API en text clar (*hardcoding*). Cada membre de l'equip ha d'usar les seves pròpies variables d'entorn.
2. **Invariabilitat del Context:** Les regles de sostenibilitat (prohibició de paper) i dades de servei de Can Font són constants del món real. Cap membre les pot modificar sense l'aprovació del grup.
3. **Estàndard de Missatges de Commit (GitHub Professional):** Cada membre ha de registrar els seus canvis a la branca utilitzant els següents prefixos:
   * `feat:` si afegeixes un nou fragment de codi o funcionalitat.
   * `fix:` si soluciones algun error o trencament del bucle de control.
   * `docs:` si fas canvis o correccions de text als fitxers Markdown.
