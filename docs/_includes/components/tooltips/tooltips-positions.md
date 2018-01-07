<!-- =================================================
BEGIN: Tooltip Positions
================================================== -->

<section id="tooltips-positions">

  <h1>

    Tooltip Positions

  </h1>

  <p>

    You can include more than body text in a message. Messages can support any HTML content. All type styling will be retained. However, if you add the class <code>.message-type-styling</code> to any typographic element, the preferred message type color and styling will be applied. For links, add the class <code>.message-link</code> to any <code>&lt;a&gt;</code>.

  </p>

  <table class="table short">

    <thead>

      <tr>

        <th>

          Class

        </th>

        <th>

          Description

        </th>

      </tr>

    </thead>

    <tbody>

      <tr>

        <td>

          <code>

            .tooltip-below

          </code>

        </td>

        <td>

          Style tooltip to position below reference element.

        </td>

      </tr>

      <tr>

        <td>

          <code>

            .tooltip-right

          </code>

        </td>

        <td>

          Style tooltip to position right of reference element.

        </td>

      </tr>

      <tr>

        <td>

          <code>

            .tooltip-left

          </code>

        </td>

        <td>

          Style tooltip to position left of reference element.

        </td>

      </tr>

    </tbody>

  </table>

  <!-- =================================================
  BEGIN: Example
  ================================================== -->

  <div class="panel flush-bottom">

    <div class="panel-cell">

      <div class="tooltip">

        Tooltip <a href="#">above</a> element

      </div>

      <div class="tooltip tooltip-bottom">

        Tooltop below element

      </div>

      <div class="tooltip tooltip-right">

        Tooltip to right of element

      </div>

      <div class="tooltip tooltip-left">

        Tooltip to left of element

      </div>

    </div>

    <div class="panel-cell panel-cell-light panel-cell-code-block">

<pre class="prettyprint transparent flush lang-html">
&lt;div class="tooltip tooltip-bottom"&gt;
  This is a simple tooltip
&lt;/div&gt;
</pre>

    </div>

  </div>

</section>

<!-- =================================================
END: Tooltip Positions
================================================== -->