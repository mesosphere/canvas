<!-- =================================================
BEGIN: Form Control Groups
================================================== -->

<section id="forms-form-control-groups">

  <h1>

    Form Control Groups

  </h1>

  <p>

    Align elements alongside or inside <code>.form-control</code> elements by wrapping them in a <code>.form-control-group</code> element. Use the <code>.form-control-group-add-on</code> element to position elements.  If you add <code>.form-control</code> to the wrapping <code>.form-control-group</code> the <code>.form-control-group-add-on</code> will live inside the <code>.form-control</code> rather than outside it.

  </p>

  <!-- =================================================
  BEGIN: Example
  ================================================== -->

  <div class="panel flush-bottom">

    <div class="panel-cell">

      <form class="form flush-bottom">

        <div class="form-group">

          <label>

            Input With Add On (Before)

          </label>

          <div class="form-control-group">

            <div class="form-control-group-add-on">

              <button class="button">

                Test

              </button>

            </div>

            <input type="text" class="form-control" placeholder="Placeholder">

          </div>

        </div>

        <div class="form-group">

          <label>

            Input With Add On (After)

          </label>

          <div class="form-control-group">

            <input type="text" class="form-control" placeholder="Placeholder">

            <div class="form-control-group-add-on">

              <button class="button">

                Test

              </button>

            </div>

          </div>

        </div>

        <div class="form-group">

          <label>

            Input With Nested Add On (Before)

          </label>

          <div class="form-control-group form-control">

            <span class="form-control-group-add-on form-control-group-add-on-prepend">

              <span style="display: block; background: black; width: 16px; height: 16px;"></span>

            </span>

            <input type="text" class="form-control" placeholder="Placeholder">

          </div>

        </div>

        <div class="form-group">

          <label>

            Input With Nested Add On (After)

          </label>

          <div class="form-control-group form-control">

            <input type="text" class="form-control" placeholder="Placeholder">

            <span class="form-control-group-add-on form-control-group-add-on-append">

              <span style="display: block; background: black; width: 16px; height: 16px;"></span>

            </span>

          </div>

        </div>

        <div class="form-group flush-bottom">

          <label>

            Input With Nested Add On (Before &amp; After)

          </label>

          <div class="form-control-group form-control">

            <span class="form-control-group-add-on form-control-group-add-on-prepend">

              <span style="display: block; background: black; width: 16px; height: 16px;"></span>

            </span>

            <input type="text" class="form-control" placeholder="Placeholder">

            <span class="form-control-group-add-on form-control-group-add-on-append">

              <span style="display: block; background: black; width: 16px; height: 16px;"></span>

            </span>

          </div>

        </div>

      </form>

    </div>

    <div class="panel-cell panel-cell-light panel-cell-code-block">

<pre class="prettyprint transparent flush lang-html">
&lt;!-- Input With Add On Before --&gt;

&lt;div class="form-control-group"&gt;
  &lt;div class="form-control-group-add-on"&gt;
    &hellip;
  &lt;/div&gt;
  &lt;input type="text" class="form-control" placeholder="Placeholder"&gt;
&lt;/div&gt;

&lt;!-- Input With Add On After --&gt;

&lt;div class="form-control-group"&gt;
  &lt;input type="text" class="form-control" placeholder="Placeholder"&gt;
  &lt;div class="form-control-group-add-on"&gt;
    &hellip;
  &lt;/div&gt;
&lt;/div&gt;

&lt;!-- Input With Nested Add On Before --&gt;

&lt;div class="form-control-group form-control"&gt;
  &lt;span class="form-control-group-add-on form-control-group-add-on-prepend"&gt;
    &hellip;
  &lt;/span&gt;
  &lt;input type="text" class="form-control" placeholder="Placeholder"&gt;
&lt;/div&gt;

&lt;!-- Input With Nested Add On After --&gt;

&lt;div class="form-control-group form-control"&gt;
  &lt;input type="text" class="form-control" placeholder="Placeholder"&gt;
  &lt;span class="form-control-group-add-on form-control-group-add-on-append"&gt;
    &hellip;
  &lt;/span&gt;
&lt;/div&gt;

&lt;!-- Input With Nested Add On Before &amp; After --&gt;

&lt;div class="form-control-group form-control"&gt;
  &lt;span class="form-control-group-add-on form-control-group-add-on-prepend"&gt;
    &hellip;
  &lt;/span&gt;
  &lt;input type="text" class="form-control" placeholder="Placeholder"&gt;
  &lt;span class="form-control-group-add-on form-control-group-add-on-append"&gt;
    &hellip;
  &lt;/span&gt;
&lt;/div&gt;
</pre>

    </div>

  </div>

  <!-- =================================================
  END: Example
  ================================================== -->




</section>

<!-- =================================================
END: Form Control Groups
================================================== -->
