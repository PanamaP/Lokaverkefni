---
layout: form
title: Nettilboð
---
<form>
  <fieldset class="account-info">
    <label for='nafn'> Nafn </label>
    <input id="nafn" type="text" name="name" placeholder="Fullt Nafn" required autofocus>
    <br>
    <br>
    <label for='email'> Tölvupóstur </label>
    <input type="email" name="email" placeholder="domain@address.com" required>
    <br>
    <br>
    <label for='midar'> Hversu marga miða? </label>
    <select name="midar">
    <option value="1" selected>1</option>
    <option value="2">2</option>
    <option value="3">3</option>
    <option value="4">4</option>
    <option value="5">5</option>
    </select>
    <br>
    <br>
    <label for='born'> Börn? </label>
    <input id='born' type="radio" name="born" value="Yes"> Já
    <input id='born' type="radio" name="born" value="No" checked> Nei
    <br>
    <Br>
    <label for='fjoldi'> hversu mörg? </label> 
        <select id='fjoldi' name="bornfjoldi">
        <option value="0" selected>0</option>
        <option value="1">1</option>
        <option value="2">2</option>
        <option value="3">3</option>
        <option value="4">4</option>
        <option value="5">5</option>
        </select>
    <br>
    <br>
    <label for='leiga'> Ég vil leiga - </label> 
      <input id='leiga' type="checkbox" name="SogH" value="skautaoghjalm" checked>Skauta og Hjálm
      <br>
      <input id='leiga' type="checkbox" name="grind" value="skautagrind">Skautagrind
      <br>
      <input id='leiga'type="checkbox" name="eignSogH"           value="eigin">Er með eigin skauta og Hjálm
    <br>
    <br>
    <label for='name'> Sérstakar spurningar? </label> 
        <textarea rows="4" name="comment" required></textarea>
    <br>
    Við reynum að svara innan 24klst. 
  </fieldset>
  <div class="buttonholder">
  <fieldset class="account-action">
    <input class="btn" type="submit" name="submit" value="Senda">
  </fieldset>
  </div>
</form>
