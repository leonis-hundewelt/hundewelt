---
layout: default
title: Kontakt
permalink: /kontakt.html
---

<div class="container" style="padding: 4rem 2rem;">
  <div class="grid" style="grid-template-columns: 1fr 1fr; gap: 4rem;">
    
    <div>
      <h1 style="font-size: 3rem; margin-bottom: 1.5rem;">Kontaktiere uns</h1>
      <p style="color: var(--text-muted); margin-bottom: 2rem;">
        Du hast Fragen oder möchtest einen Termin zum Kennenlernen vereinbaren? Schreib uns gerne eine Nachricht oder ruf an.
      </p>
      
      <div style="margin-bottom: 2rem;">
        <h3 style="color: var(--primary-color); margin-bottom: 0.5rem;">Anschrift</h3>
        <p style="color: var(--text-muted);">
          Leonis Hundewelt<br>
          Musterstraße 12<br>
          12345 Hundestadt
        </p>
      </div>

      <div style="margin-bottom: 2rem;">
        <h3 style="color: var(--primary-color); margin-bottom: 0.5rem;">Kontakt</h3>
        <p style="color: var(--text-muted);">
          Telefon: <a href="tel:+49123456789">+49 123 456 789</a><br>
          Email: <a href="mailto:kontakt@leonis-hundewelt.de">kontakt@leonis-hundewelt.de</a>
        </p>
      </div>

      <div>
        <h3 style="color: var(--primary-color); margin-bottom: 0.5rem;">Öffnungszeiten</h3>
        <p style="color: var(--text-muted);">
          Mo - Fr: 07:00 - 19:00 Uhr<br>
          Sa: Nach Vereinbarung<br>
          So: Ruhetag (außer Urlaubsbetreuung)
        </p>
      </div>
    </div>

    <div>
      <form action="#" method="post" class="card" style="display: flex; flex-direction: column; gap: 1.5rem;">
        <div>
          <label for="name" style="display: block; margin-bottom: 0.5rem; color: var(--text-main);">Name</label>
          <input type="text" id="name" name="name" style="width: 100%; padding: 1rem; background: rgba(255,255,255,0.05); border: 1px solid rgba(255,255,255,0.1); color: var(--text-main); border-radius: 8px;" placeholder="Dein Name">
        </div>
        
        <div>
          <label for="email" style="display: block; margin-bottom: 0.5rem; color: var(--text-main);">Email</label>
          <input type="email" id="email" name="email" style="width: 100%; padding: 1rem; background: rgba(255,255,255,0.05); border: 1px solid rgba(255,255,255,0.1); color: var(--text-main); border-radius: 8px;" placeholder="deine@email.de">
        </div>

        <div>
          <label for="message" style="display: block; margin-bottom: 0.5rem; color: var(--text-main);">Nachricht</label>
          <textarea id="message" name="message" rows="5" style="width: 100%; padding: 1rem; background: rgba(255,255,255,0.05); border: 1px solid rgba(255,255,255,0.1); color: var(--text-main); border-radius: 8px;" placeholder="Wie können wir dir helfen?"></textarea>
        </div>

        <button type="submit" class="btn" style="border: none; cursor: pointer; width: 100%;">Nachricht senden</button>
      </form>
    </div>

  </div>
</div>
