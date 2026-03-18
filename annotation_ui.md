# Rozhraní pro anotace snímků

Po načtení snímku v DICOM menu uvidíte následující rozhraní pro anotaci

![](screenshots/login/step_9-vertemark_annotate.png)

Vlevo v dolním rohu naleznete `identifikační jméno`, `roli` a `název snímku`.

![](screenshots/login/step_10-ID_ROLE_FILE.png)

Vpravo v dolním rohu naleznete posuvnou lištu pro přiblížení.

![](screenshots/login/step_11-zoom_and_shortcuts.png)

## Anotační část

Na pravo se nachází lišta pro anotaci obratlů.

![](screenshots/login/step_12-choose_vertebrae_to_annotate.png)

V případě, že se na snímku nachází více fúzí či implantatů lze anotací udělat více kliknutím na symbol `+`.

![](screenshots/login/step_13-add_more_fusions_or_implantants.png)

V případě, že jste v režimu **validátora** budete navíc moct manipulovat se zaškrtávacími políčky u obratlů. Tato políčka nemají žádný vliv na ukládání a zpracování snímků. Slouží pouze jako pomůcka pro průchod validátora kontrolovaným snímkem. Políčka jsou po otevření snímku vždy všechna zaškrtlá.

![](screenshots/login/step_26-valid_annotations.png)

## Oříznutí, zrcadlení a smazání vybrané anotace

Vlevo v horním rohu se nachází panel pro **oříznutí** snímku, **zrcadlení** snímku, **přepnutí** zpět na anotaci a také **smazání** vybrané anotace.

![](screenshots/login/step_14-panel_pro_oriznout_nebo_zrcadlit_snimek-kreslit-zahodit_vsechny_anotace.png)

Oříznutí lze provést následovně.

![](screenshots/login/step_15-orez.png)

Pro smazání vybrané anotace klikněte vpravo v panelu obratlů na příslušný obratel (např. `C1`) a poté vlevo na ikonku `Smazat anotaci pro vybraný obratel...`.

![](screenshots/login/step_27-remove_annotation.png)

![](screenshots/login/step_28-removed_annotation.png)

## Obnovit původní snímek a označit vadný snímek

Vpravo v horním rohu naleznete možnost pro obnovení původního snímku.

![](screenshots/login/step_19-remove_all_changes.png)

Před smazáním na vás vyskočí výzva o potvrzení, že opravdu chcete smazat veškeré úpravy na snímku.

![](screenshots/login/step_20-remove_all_changes_dialog.png)

Dále naleznete možnost pro označení neplatného snímku.

![](screenshots/login/step_21-invalid_file.png)

V případě, že takto snímek klasifikujete budete jej moct zpětně nalézt pod stejným názvem a to ve složce `Nevalidní snímky`.

![](screenshots/login/invalid_image.png)

