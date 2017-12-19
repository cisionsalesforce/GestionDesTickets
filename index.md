---
title: Gestion des tickets
layout: default
---

<div class="ui text container">
    <div class="ui one column grid">

      <div class="column">
        <h2 id="heading-main" class="ui blue header">
          <i class="puzzle icon"></i>
          <div class="content">
            <span>{{ page.title }}</span>
            <div class="sub header">Afin de traiter au mieux vos demandes, nous vous remercions de remplir le formulaire ci-dessous.</div>
          </div>
        </h2>
      </div>

      <div class="column">
        <form id="request-form" class="ui form">

          <h4 class="ui dividing blue header">Informations personnelles</h4>

          <div class="field">
            <div class="two fields">
              <div class="required field">
                <label>Prénom</label>
                <input type="text" name="request-form-name" placeholder="Prénom">
              </div>
              <div class="required field">
                <label>Nom</label>
                <input type="text" name="request-form-last-name" placeholder="Nom">
              </div>
            </div>
          </div>

          <div class="field">
            <div class="fields">
              <div class="eight wide required field">
                <label>Téléphone</label>
                <input type="tel" name="request-form-phone" placeholder="Téléphone">
              </div>
              <div class="eight wide required field">
                <label>E-mail</label>
                <input type="email" name="request-form-email" placeholder="E-mail">
              </div>
            </div>
          </div>

          <h4 class="ui dividing blue header">Description de votre demande</h4>

          <div class="required field">
            <label>Titre</label>
            <div class="ui pointing below label">Veuillez indiquer un titre à votre demande</div>
            <input type="text" name="request-form-title" placeholder="Titre">
          </div>

          <div id="request-form-date" class="required field calendar">
            <label>Date d'ouverture</label>
            <input type="text" name="request-form-date" placeholder="Date d'ouverture">
          </div>

          <div class="required field">
            <label>Objet</label>
            <div class="ui pointing below label">Veuillez préciser sur quel objet vous travaillez (ex: compte, contact, opportunité, etc.)</div>
            <select id="request-form-object" class="ui dropdown" name="request-form-object">
              <option value="">Objet</option>
              <option value="Compte">Compte</option>
              <option value="Contact">Contact</option>
              <option value="Opportunité">Opportunité</option>
            </select>
          </div>

          <div class="required field">
            <label>Cheminement</label>
            <div class="ui pointing below label">Nous avons besoin de maximum d'informations afin de pouvoir reproduire votre erreur</div>
            <textarea rows="2" name="request-form-information"></textarea>
          </div>

          <div class="field">
            <label>Message d'erreur</label>
            <div class="ui pointing below label">Faites le copier-coller de votre message d'erreur</div>
            <textarea rows="2" name="request-form-error"></textarea>
          </div>

          <div class="field">
            <label>Comportement souhaité</label>
            <textarea rows="2" name="request-form-behaviour"></textarea>
          </div>

          <div class="field">
            <label>Exemple</label>
            <textarea rows="2" name="request-form-example"></textarea>
          </div>

          <div class="ui blue primary submit button">Envoyer une demande</div>

          <div class="ui error message"></div>

        </form>
      </div>

    </div>
  </div>
