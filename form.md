---
layout: form
title: Fresh Drop Info
---
<form>
  <fieldset class="account-info">
    <label>
        Name<input type="text" name="name" placeholder="Full name" required autofocus>
    </label>
    <label>
        Email<input type="email" name="email" placeholder="domain@address.com" required>
    </label>
    <label>
        Can we use your name in the article?<input type="radio" name="choice" value="Yes" checked> Yes
        <input type="radio" name="choice" value="No"> No. 
    </label>
    <label>
        Write Your info here
        <br>
        <textarea rows="4" name="comment" required></textarea>
    </label>
    <label>
    What would you like in return?
    <br>
    <select name="award">
    <option value="newShoe" selected>New Shoe</option>
    <option value="freeCleaning">Free Cleaning</option>
    <option value="shoutout">A shoutout</option>
    <option value="nothing">Nothing</option>
  </select>
    </label>
    <label>
    Subscribe To Our Email List
    Find Out When Your News Hit Our Blog!
    <Br>
    <input type="checkbox" name="list"           value="emailList" checked> Subscribe To All
    <input type="checkbox" name="list" value="newdropEmailList"> New Drop News
    <input type="checkbox" name="list" value="pricedropList"> Price Drop Exclusive List
 </label>
  </fieldset>
  <div class="buttonholder">
  <fieldset class="account-action">
    <input class="btn" type="submit" name="submit" value="Send">
  </fieldset>
  </div>
</form>
     