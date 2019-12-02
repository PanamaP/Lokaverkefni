---
layout: form
title: Fresh Drop Info
---
<form>
  <fieldset class="account-info">
    <label>
         Nafn
        <Br>
      <input type="text" name="name" placeholder="Fullt Nafn" required autofocus>
    </label>
    <label>
        Tölvupóstur
        <Br>
        <input type="email" name="email" placeholder="domain@address.com" required>
    </label>
    <label>
    Hversu marga miða?
    <br>
    <select name="midar">
    <option value="1" selected>1</option>
    <option value="2">2</option>
    <option value="3">3</option>
    <option value="4">4</option>
    <option value="5">5</option>
  </select>
    </label>
    <label>
        Börn?
        <input type="radio" name="born" value="Yes">Já
        <input type="radio" name="born" value="No" checked>Nei 
        <Br>
        hversu mörg? <select name="bornfjoldi">
        <option value="0" selected>0</option>
        <option value="1">1</option>
        <option value="2">2</option>
        <option value="3">3</option>
        <option value="4">4</option>
        <option value="5">5</option>
    </select>
    </label>
    <label>
    <Br>
    Ég vil leiga -
    <br>
    <input type="checkbox" name="SogH" value="newdropEmailList" checked> Skauta og Hjálm
    <Br>
    <input type="checkbox" name="grind" value="pricedropList"> Skautagrind
    <br>
    <input type="checkbox" name="eignSogH"           value="emailList" > Er með eigin skauta og Hjálm
 </label>
 <label>
        Sérstakarspurningar?<br>
        <textarea rows="4" name="comment" required></textarea>
        <br>
        Við reynum að svara innan 24klst. 
    </label>
  </fieldset>
  <div class="buttonholder">
  <fieldset class="account-action">
    <input class="btn" type="submit" name="submit" value="Send">
  </fieldset>
  </div>
</form>
     