# Instruktioner

Denna övning är till för förstå delarna i ett formulär samt att kunna styla dessa delar med CSS.

1. Ladda hem starfilerna genom att välja _Download ZIP_

2. I denna övning ska du utgå från befintlig designskiss av formuläret och försöka efterlikna detta så långt som möjligt. Designskissen finns i programmet/webbappen Figma. Gå till [Figma](https://www.figma.com) och börja med att skapa ett eget konto (gratis!).

3. Öppna filen form.fig i Figma (filen ska finnas i din nerladdade mapp)

4. Öppna Visual Studio Code och välj _File->Open Folder_ för att öppna din nerladdade mapp

5. Studera de olika elementen inuti _body_ och förstå de olika delarna i formuläret

6. Gå till Figma och exportera bakgrunden och lägg den i din _images_-mapp

7. Öppna _style.css_. Här ska du nu börja skriva alla stilmallsregler för att styla formuläret.

8. Lägg in bakgrunden som du sparat i din imagesmapp som en _background-image_. Repetera bakgrunden (\*background-repeat) så att den täcker hela viewporten (d.v.s browserytan).

9. Ange lämplig _font-family_ på _body:n_

10. Styla rätt dimensioner av _.form-container_: Försök att få samma _width_ som i designskissen. Centrera m.h.a _margin: 0 auto_ och ge det ett lämpligt avstånd från toppen med _margin-top_.

11. Styla _.form-container_ så att bakgroundsfärgen blir den samma som i designskissen samt ge den en svart kantlinje på 1px solid. Runda även hörnen med _border-radius_. Lägg en skugga med [_box-shadow_](https://css-tricks.com/almanac/properties/b/box-shadow/) på denna container och använd rgba som färg så att skuggan blir lite genomsknling.

12. Gå vidare och styla _.form-header_. Gör dimensionerna rätt, d.v.s. _height_ och _padding_ av texten.
    Styla _font-size_, textfärg (_color_), bakgrundsfärg (*background-color) samt en nedre kantlinje på 1px. Runda även de båda övre örnen. Texten ska vara versalet (*text-transform*). Lägg även in en innerskugga (se [*box-shadow och inset\*](https://css-tricks.com/almanac/properties/b/box-shadow/)

13. Styla varje inmatningsfält (_input_). Gör dimenionserna rätt, d.v.s _width_, _padding_ av den inskrivna texten. Ge även varje inmatningsfält rätt avstånd till varandra med _margin-bottom_. Fonten kanske bör vara större och tjockare (_font-size_ och _font-weight_) Styla rätt text- och bakgrundsfärg samt ge en kantlinje och rundade hörn. Här ska du lägga in både en ytter- och innerskugga :-).

14. Ge _form_ en _padding_ som passar.

15. Styla nu _#submit_. Placera den til höger med _float:right_. Använd _background_ och ge en bakgrundsbild som ligger centrerad och till vänster. Du exporterar bakgrundsbidlen från figma (_bubble.png_). Ge lämplig _padding_, _color_. Lägg även in både ytter- och innerskuga.

16. Lägg slutligen in en _clear:both;_ på element med *class="clear". Detta gör att *float\* återgår till normala flödet.
