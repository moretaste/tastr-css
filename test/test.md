# h1\. This is a very large header and even a much longer header

Sed pulvinar et arcu sed tempor. Mauris hendrerit libero eget quam consequat maximus. Fusce ac [link dignissim est](#), non varius diam. Donec sit amet purus suscipit, _emphasis rhoncus_ sem at, imperdiet sapien. **Strong sed pulvinar** et arcu sed tempor. Mauris hendrerit libero eget quam consequat maximus.

***

In viverra elementum rutrum. Nunc quis velit tellus. Nunc tristique magna sit amet mi dignissim pretium. Mauris lobortis nulla neque, eu tincidunt mauris volutpat a. Ut id sem rutrum, malesuada justo non, laoreet purus. Etiam a turpis vitae libero aliquet ultricies ut quis neque. Nunc in sagittis ante, ut bibendum nulla.

`Some lines in code for the nerds use <pre> for preformatted text </pre>`

* * *

## h2\. This is a large header.

Sed pulvinar et arcu sed tempor. Mauris hendrerit libero eget quam consequat maximus. Fusce ac dignissim est, non varius diam. Donec sit amet purus suscipit, rhoncus sem at, imperdiet sapien.

### h3\. This is a medium header.

In viverra elementum rutrum. Nunc quis velit tellus. Nunc tristique magna sit amet mi dignissim pretium. Mauris lobortis nulla neque, eu tincidunt mauris volutpat a. Ut id sem rutrum, malesuada justo non, laoreet purus. Etiam a turpis vitae libero aliquet ultricies ut quis neque. Nunc in sagittis ante, ut bibendum nulla.

#### h4\. This is a moderate header.

Praesent pellentesque enim vitae diam congue, at venenatis eros vestibulum. Duis ultrices neque eu diam viverra gravida. Morbi semper placerat pellentesque.

##### h5\. This is a small header.

Sed pulvinar et arcu sed tempor. Mauris hendrerit libero eget quam consequat maximus. Fusce ac dignissim est, non varius diam. Donec sit amet purus suscipit, rhoncus sem at, imperdiet sapien.

###### h6\. This is a tiny header.

Sed pulvinar et arcu sed tempor. Mauris hendrerit libero eget quam consequat maximus. Fusce ac dignissim est, non varius diam. Donec sit amet purus suscipit, rhoncus sem at, imperdiet sapien.

* * *

# h1\. This is a very large header - [link](#)

## h2\. This is a large header - [link](#)

### h3\. This is a medium header  - [link](#)

#### h4\. This is a moderate header  - [link](#)

##### h5\. This is a small header  - [link](#)

###### h6\. This is a tiny header  - [link](#)

* * *

### Definition List

##### Definition lists are great for small block of copy that describe the header

<dl>
<dt>Lower cost</dt>
<dd>The new version of this product costs significantly less than the previous one!</dd>
<dt>Easier to use</dt>
<dd>We've changed the product so that it's much easier to use!</dd>
<dt>Safe for kids</dt>
<dd>You can leave your kids alone in a room with this product and they won't get hurt (not a guarantee).</dd>
</dl>

* * *

##### Un-ordered lists are great for making quick outlines bulleted.

*   List item with a much longer description or more content.
*   List item
*   List item
    *   Nested List Item
    *   Nested List Item
        *   Nested List Item
        *   Nested List Item
        *   Nested List Item
    *   Nested List Item
*   List item
*   List item
*   List item

##### Ordered lists are great for lists that need order, duh.

1.  List Item 1
    *   Nested List Item
    *   Nested List Item
    *   Nested List Item
2.  List Item 2
1.  Nested List Item
2.  Nested List Item
3.  Nested List Item
4.  List Item 3
    1.  Nested List Item
    2.  Nested List Item
        *   Nested List Item
        *   Nested List Item
        *   Nested List Item
    3.  Nested List Item
5.  List Item 4
    1.  Nested List Item
    2.  Nested List Item
    3.  Nested List Item

<small>[All list style types](https://developer.mozilla.org/en-US/docs/Web/CSS/list-style-type)</small>

##### Blockquote

> The value of achievement lies in the achieving. Maecenas faucibus mollis interdum. Aenean lacinia bibendum nulla sed consectetur. <cite>Albert Einstein</cite>

##### Form
<form method="post" action="#">
  <p>Required fields are marked with <strong>*</strong></p>
  <p><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input">Full reference input</a></p>
  <fieldset>
    <legend>Delivery</legend>
    <ol>
      <li>
        <label for="name">name <strong>*</strong></label>
        <input name="name" id="name" type="text" />
      </li>
      <li>
        <label for="address">address <strong>*</strong></label>
        <input name="address" id="address" type="text" />
      </li>
      <li>
        <label for="city">city <strong>*</strong></label>
        <input name="city" id="city" type="text" />
      </li>
      <li>
        <label for="State">State</label>
        <select name="State" id="State">
          <option value="drenthe">Drenthe</option>
          <option value="flevoland">Flevoland</option>
          <option value="friesland">Friesland</option>
          <option value="gelderland">Gelderland</option>
          <option value="groningen">Groningen</option>
          <option value="limburg">Limburg</option>
          <option value="noord-brabant">Noord-Brabant</option>
          <option value="noord-holland">Noord-Holland</option>
          <option value="overijssel">Overijssel</option>
          <option value="utrecht">Utrecht</option>
          <option value="zeeland">Zeeland</option>
          <option value="zuid-holland">Zuid-Holland</option>
        </select>
      </li>
      <li>
        <label for="country">country</label>
        <input name="country" id="country" type="text" />
      </li>
      <li>
        <label for="postalcode">postalcode <strong>*</strong></label>
        <input name="postalcode" id="postalcode" type="text" />
      </li>
      <li>
        <fieldset>
          <legend><span>Billing address? <strong>*</strong></span></legend>
          <input type="radio" name="billing-address" id="bill-yes" value="yes" />
          <label for="bill-yes"> Yes</label>
          <input type="radio" name="billing-address" id="bill-no" value="no" />
          <label for="bill-no"> No</label>
        </fieldset>
      </li>
    </ol>
  </fieldset>
  <fieldset>
    <legend>Account</legend>
    <ol>
      <li>
        <label for="username">username <strong>*</strong></label>
        <input name="username" id="username" type="text" />
      </li>
      <li>
        <label for="password-1">password <strong>*</strong></label>
        <input name="password-1" id="password-1" type="password" />
      </li>
      <li>
        <label for="password-2">Confirm password <strong>*</strong></label>
        <input name="password-2" id="password-2" type="password" />
      </li>
      <li>
        <label for="e-mail-1">E-mail <strong>*</strong></label>
        <input name="e-mail-1" id="e-mail-1" type="email" />
      </li>
      <li>
        <label for="e-mail-2">Confirm e-mail <strong>*</strong></label>
        <input name="e-mail-2" id="e-mail-2" type="email" />
      </li>
    </ol>
  </fieldset>
  <fieldset>
    <legend>Quiz</legend>
    <ol>
      <li>
        <fieldset>
          <legend><span>Birthday</span></legend>
          <label for="dag">day <strong>*</strong></label>
          <select name="day" id="day">
            <option value="1">1</option>
            <option value="2">2</option>
            <option value="3">3</option>
            <option value="4">4</option>
            <option value="5">5</option>
            <option value="6">6</option>
            <option value="7">7</option>
            <option value="8">8</option>
            <option value="9">9</option>
            <option value="10">10</option>
            <option value="11">11</option>
            <option value="12">12</option>
            <option value="13">13</option>
            <option value="14">4</option>
            <option value="15">15</option>
            <option value="16">16</option>
            <option value="17">17</option>
            <option value="18">18</option>
            <option value="19">19</option>
            <option value="20">20</option>
            <option value="21">21</option>
            <option value="22">22</option>
            <option value="23">23</option>
            <option value="24">24</option>
            <option value="25">25</option>
            <option value="26">26</option>
            <option value="27">27</option>
            <option value="28">28</option>
            <option value="29">29</option>
            <option value="30">30</option>
            <option value="31">31</option>
          </select>
          <label for="maand">month <strong>*</strong></label>
          <select name="month" id="month">
            <option value="1">Januari</option>
            <option value="2">Februari</option>
            <option value="3">Maart</option>
            <option value="4">April</option>
            <option value="5">Mei</option>
            <option value="6">Juni</option>
            <option value="7">Juli</option>
            <option value="8">Augustus</option>
            <option value="9">September</option>
            <option value="10">Oktober</option>
            <option value="11">November</option>
            <option value="12">December</option>
          </select>
          <label for="jaar">year <strong>*</strong></label>
          <select name="year" id="year">
            <optgroup label="1940-1949">
              <option value="1940">1940</option>
              <option value="1941">1941</option>
              <option value="1942">1942</option>
              <option value="1943">1943</option>
              <option value="1944">1944</option>
              <option value="1945">1945</option>
              <option value="1946">1946</option>
              <option value="1947">1947</option>
              <option value="1948">1948</option>
              <option value="1949">1949</option>
            </optgroup>
            <optgroup label="1950-1959">
              <option value="1950">1950</option>
              <option value="1951">1951</option>
              <option value="1952">1952</option>
              <option value="1953">1953</option>
              <option value="1954">1954</option>
              <option value="1955">1955</option>
              <option value="1956">1956</option>
              <option value="1957">1957</option>
              <option value="1958">1958</option>
              <option value="1959">1959</option>
            </optgroup>
            <optgroup label="1960-1969">
              <option value="1960">1960</option>
              <option value="1961">1961</option>
              <option value="1962">1962</option>
              <option value="1963">1963</option>
              <option value="1964">1964</option>
              <option value="1965">1965</option>
              <option value="1966">1966</option>
              <option value="1967">1967</option>
              <option value="1968">1968</option>
              <option value="1969">1969</option>
            </optgroup>
            <optgroup label="1970-1979">
              <option value="1970">1970</option>
              <option value="1971">1971</option>
              <option value="1972">1972</option>
              <option value="1973">1973</option>
              <option value="1974">1974</option>
              <option value="1975">1975</option>
              <option value="1976">1976</option>
              <option value="1977">1977</option>
              <option value="1978">1978</option>
              <option value="1979">1979</option>
            </optgroup>
            <optgroup label="1980-1989">
              <option value="1980">1980</option>
              <option value="1981">1981</option>
              <option value="1982">1982</option>
              <option value="1983">1983</option>
              <option value="1984">1984</option>
              <option value="1985">1985</option>
              <option value="1986">1986</option>
              <option value="1987">1987</option>
              <option value="1988">1988</option>
              <option value="1989">1989</option>
            </optgroup>
          </select>
        </fieldset>
      </li>
      <li>
        <fieldset>
          <legend><span>Gender</span></legend>
          <input type="radio" name="gender" id="male" value="male" />
          <label for="male"> male</label>
          <input type="radio" name="gender" id="female" value="female" />
          <label for="female"> female</label>
        </fieldset>
      </li>
      <li>
        <fieldset>
          <legend><span>Favorite color(s)?</span></legend>
          <input name="blauw" id="blauw" type="checkbox" />
          <label for="blauw"> Blauw</label>
          <input name="rood" id="rood" type="checkbox" />
          <label for="rood"> Rood</label>
          <input name="oranje" id="oranje" type="checkbox" />
          <label for="oranje"> Oranje</label>
          <input name="paars" id="paars" type="checkbox" />
          <label for="paars"> Paars</label>
          <input name="wid" id="wit" type="checkbox" />
          <label for="wit"> Wit</label>
          <input name="groen" id="groen" type="checkbox" />
          <label for="groen"> Groen</label>
          <input name="pimpelpaars" id="pimpelpaars" type="checkbox" />
          <label for="pimpelpaars"> Pimpelpaars</label>
        </fieldset>
      </li>
      <li>
        <label for="file">file</label>
        <input name="file" id="file" type="file" />
      </li>
      <li>
        <label for="text">your message to us</label>
        <textarea name="text" id="text" rows="7" cols="40"></textarea>
      </li>
    </ol>
  </fieldset>
  <fieldset>
    <legend>HTML5 elements</legend>
    <ol>
      <li>
        <label for="color">color</label>
        <input name="color" id="color" type="color" />
      </li>
      <li>
        <label for="date">date</label>
        <input name="date" id="date" type="date" />
      </li>
      <li>
        <label for="datetime-local">datetime-local</label>
        <input name="datetime-local" id="datetime-local" type="datetime-local" />
      </li>
      <li>
        <label for="email">email</label>
        <input name="email" id="email" type="email" />
      </li>
      <li>
        <label for="month">month</label>
        <input name="month" id="month" type="month" />
      </li>
      <li>
        <label for="number">number</label>
        <input name="number" id="number" type="number" />
      </li>
      <li>
        <label for="range">range</label>
        <input name="range" id="range" type="range" />
      </li>
      <li>
        <label for="search">search</label>
        <input name="search" id="search" type="search" />
      </li>
      <li>
        <label for="tel">tel</label>
        <input name="tel" id="tel" type="tel" />
      </li>
      <li>
        <label for="time">time</label>
        <input name="time" id="time" type="time" />
      </li>
      <li>
        <label for="url">url</label>
        <input name="url" id="url" type="url" />
      </li>
      <li>
        <label for="week">week</label>
        <input name="week" id="week" type="week" />
      </li>
    </ol>
  </fieldset>
  <p>
    <input type="submit" name="submit" value="submit" />
  </p>
  <p>
    <input type="reset" name="resetsearch" value="reset" />
  </p>
  <p>Graphical submit
    <br/>
    <input type="image" name="image" src="https://mdn.mozillademos.org/files/2917/fxlogo.png" width="50">
  </p>
  </p>
</form>
