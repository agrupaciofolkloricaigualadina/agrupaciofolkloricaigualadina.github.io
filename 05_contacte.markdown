---
layout: page
title: Contacta amb nosaltres
permalink: /contacte/
---

## 📞 Informació de contacte

<div class="grid-2" style="margin: 3rem 0;">
  <div class="content-section">
    <h3>📧 Dades de contacte</h3>
    <p><strong>Correu electrònic:</strong><br>
    <a href="mailto:{{ site.email }}">{{ site.email }}</a></p>

    <p><strong>Telèfon:</strong><br>
    <a href="tel:+34938041234">938 04 12 34</a></p>

    <p><strong>Adreça:</strong><br>
    Local de l'AFI<br>
    Carrer de la Dansa, 15<br>
    08700 Igualada<br>
    Barcelona, Catalunya</p>

    <h4>🕒 Horaris d'atenció</h4>
    <p>Dijous: 19:30 - 22:30<br>
    Dissabtes: 09:30 - 13:00<br>
    O per cita prèvia</p>
  </div>

  <div class="content-section">
    <h3>🌐 Xarxes socials</h3>
    <p><strong>Instagram:</strong><br>
    <a href="https://instagram.com/{{ site.instagram_username }}" target="_blank">@{{ site.instagram_username }}</a></p>

    <p><strong>Twitter:</strong><br>
    <a href="https://twitter.com/{{ site.twitter_username }}" target="_blank">@{{ site.twitter_username }}</a></p>

    <p><strong>Facebook:</strong><br>
    <a href="https://facebook.com/agrupaciofolkloricaigualadina" target="_blank">Agrupació Folklòrica Igualadina</a></p>

    <h4>📱 WhatsApp</h4>
    <p>Grup de famílies i dansaires<br>
    <em>(Enllaç proporcionat en incorporar-se)</em></p>
  </div>
</div>

## ✉️ Envia'ns un missatge

<div class="content-section">
  <p>Si tens qualsevol pregunta sobre els nostres cursos, espectacles o vols més informació, omple el formulari i ens posarem en contacte amb tu el més aviat possible.</p>

  <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST" class="contact-form">
    <div class="form-group">
      <label for="name">Nom complet *</label>
      <input type="text" id="name" name="name" required placeholder="El teu nom i cognoms">
    </div>

    <div class="form-group">
      <label for="email">Correu electrònic *</label>
      <input type="email" id="email" name="_replyto" required placeholder="exemple@correu.com">
    </div>

    <div class="form-group">
      <label for="phone">Telèfon</label>
      <input type="tel" id="phone" name="phone" placeholder="123 456 789">
    </div>

    <div class="form-group">
      <label for="age">Edat de la persona interessada</label>
      <select id="age" name="age">
        <option value="">Selecciona un rang d'edat</option>
        <option value="infantil">4-8 anys (Infantils)</option>
        <option value="mitjans">9-12 anys (Mitjans)</option>
        <option value="juvenils">13-16 anys (Juvenils)</option>
        <option value="cos-dansa">17-45 anys (Cos de Dansa)</option>
        <option value="veterans">45+ anys (Veterans)</option>
      </select>
    </div>

    <div class="form-group">
      <label for="interest">Tipus de consulta</label>
      <select id="interest" name="interest">
        <option value="">Selecciona el tema</option>
        <option value="classes">Informació sobre classes</option>
        <option value="espectacles">Contractació d'espectacles</option>
        <option value="events">Participació en esdeveniments</option>
        <option value="collaboration">Col·laboració</option>
        <option value="other">Altres consultes</option>
      </select>
    </div>

    <div class="form-group">
      <label for="message">Missatge *</label>
      <textarea id="message" name="message" rows="6" required placeholder="Explica'ns la teva consulta o interès..."></textarea>
    </div>

    <div class="form-group checkbox-group">
      <input type="checkbox" id="privacy" name="privacy" required>
      <label for="privacy">He llegit i accepto la <a href="/privacitat">política de privacitat</a> *</label>
    </div>

    <div class="form-group checkbox-group">
      <input type="checkbox" id="newsletter" name="newsletter">
      <label for="newsletter">Vull rebre informació sobre activitats i espectacles</label>
    </div>

    <input type="hidden" name="_subject" value="Nova consulta des de la web AFI">
    <input type="hidden" name="_next" value="/contacte/gracies">

    <div class="form-actions">
      <button type="submit" class="btn btn-primary">Enviar missatge</button>
      <button type="reset" class="btn btn-secondary">Esborrar formulari</button>
    </div>
  </form>
</div>

## 🗺️ Com arribar

<div class="content-section">
  <h3>📍 Ubicació del local</h3>
  <p>El nostre local es troba al centre d'Igualada, a prop de la plaça de l'Ajuntament. És fàcilment accessible tant en transport públic com en vehicle privat.</p>

  <div class="grid-2" style="margin: 2rem 0;">
    <div>
      <h4>🚗 En cotxe</h4>
      <p>Aparcament gratuït al carrer o als aparcaments públics propers.</p>

      <h4>🚌 Transport públic</h4>
      <p>Línies d'autobús urbà que passen pel centre històric.</p>

      <h4>🚶‍♂️ A peu</h4>
      <p>5 minuts caminant des de la plaça de l'Ajuntament.</p>
    </div>
    <div>
      <div class="map-placeholder">
        <img src="/assets/images/logo_afi.jpg" alt="Mapa ubicació AFI" class="section-image">
        <p style="text-align: center; margin-top: 1rem;">
          <em>Mapa de la ubicació del local</em>
        </p>
      </div>
    </div>
  </div>
</div>

<style>
.contact-form {
  max-width: 800px;
  margin: 0 auto;
}

.form-group {
  margin-bottom: 2rem;
}

.form-group label {
  display: block;
  font-weight: 600;
  color: var(--primary-green);
  margin-bottom: 0.5rem;
  font-size: 1rem;
}

.form-group input,
.form-group select,
.form-group textarea {
  width: 100%;
  padding: 12px 16px;
  border: 2px solid var(--border-green);
  border-radius: 12px;
  font-size: 1rem;
  font-family: inherit;
  background: white;
  transition: all 0.3s ease;
}

.form-group input:focus,
.form-group select:focus,
.form-group textarea:focus {
  outline: none;
  border-color: var(--primary-green);
  box-shadow: 0 0 0 3px rgba(45, 134, 89, 0.1);
  background: var(--pale-green);
}

.form-group textarea {
  resize: vertical;
  min-height: 120px;
}

.checkbox-group {
  display: flex;
  align-items: flex-start;
  gap: 0.75rem;
}

.checkbox-group input[type="checkbox"] {
  width: auto;
  margin: 0;
  transform: scale(1.2);
}

.checkbox-group label {
  margin: 0;
  font-weight: 400;
  font-size: 0.95rem;
  line-height: 1.5;
}

.form-actions {
  display: flex;
  gap: 1rem;
  justify-content: center;
  margin-top: 2rem;
}

.map-placeholder {
  text-align: center;
  padding: 2rem;
  background: var(--pale-green);
  border-radius: 15px;
  border: 2px dashed var(--border-green);
}

@media (max-width: 768px) {
  .form-actions {
    flex-direction: column;
  }

  .form-actions .btn {
    width: 100%;
  }
}
</style>
