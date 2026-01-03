---
layout: default
title: Kontakt
permalink: /kontakt.html
---

<div class="contact-grid">
    <div class="contact-intro">
        <h1 style="font-size: 3rem; margin-bottom: 1.5rem;">Kontaktiere mich</h1>
        <p style="color: var(--text-muted); margin-bottom: 2rem;">
            Du hast Fragen oder möchtest einen Termin zum Kennenlernen vereinbaren? Schreib mir gerne eine Nachricht bei Whatsapp oder ruf an.
        </p>
    </div>
    <div class="whatsapp-card-container">
        <div class="card" style="display: flex; flex-direction: column; gap: 1.5rem; text-align: center;">
            <h3 style="margin-bottom: 1rem;">Schreib mir!</h3>
            <p>Am schnellsten erreichst du mich per WhatsApp.<br>
            Klick einfach auf den Button unten, um einen Chat zu starten.</p>
            <a href="https://wa.me/{{ site.telefon_wa }}" class="btn btn-whatsapp" target="_blank" style="display: inline-flex; align-items: center; justify-content: center; gap: 10px;">
                <img src="{{ '/assets/images/whatsapp.svg' | relative_url }}" alt="WhatsApp" width="24" height="24">
                WhatsApp Chat starten
            </a>
        </div>
    </div>
    <div class="contact-address">
        <h3 style="color: var(--primary-color); margin-bottom: 0.5rem;">Anschrift</h3>
        <p style="color: var(--text-muted);">
            Leonis Hundewelt<br>
            Havkamp 16<br>
            23795 Bad Segeberg
        </p>
    </div>
    <div class="contact-details">
        <h3 style="color: var(--primary-color); margin-bottom: 0.5rem;">Kontakt</h3>
        <p style="color: var(--text-muted);">
            Telefon: <a href="tel:{{ site.telefon_url }}">{{ site.telefon }}</a><br>
            E-Mail: <a href="mailto:{{ site.email }}">{{ site.email }}</a>
        </p>
    </div>
    <div class="contact-hours">
        <h3 style="color: var(--primary-color); margin-bottom: 0.5rem;">Öffnungszeiten</h3>
        <p style="color: var(--text-muted);">
            individuell nach Vereinbarung
        </p>
    </div>
    <div class="contact-legal">
        <h3 style="color: var(--primary-color); margin-bottom: 0.5rem;">Rechtliches</h3>
        <p style="color: var(--text-muted);">
            <a href="{{ '/impressum.html' | relative_url }}">Impressum</a><br>
            <a href="{{ '/datenschutz.html' | relative_url }}">Datenschutzerklärung</a><br>
            <span>Gemäß § 19 UStG wird keine Umsatzsteuer berechnet.</span>
        </p>
    </div>
</div>
