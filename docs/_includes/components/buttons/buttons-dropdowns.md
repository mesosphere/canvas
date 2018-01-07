<!-- =================================================
BEGIN: Button Dropdowns
================================================== -->

<section id="buttons-dropdowns">

  <h1>

    Button Dropdowns

  </h1>

  <p>

    Use any button to trigger a dropdown menu by placing it within a <code>.btn-group</code> and providing the proper menu markup.

  </p>

  <!-- =================================================
  BEGIN: Single Button Dropdown
  ================================================== -->

  <section id="buttons-dropdowns-single-button">

    <h2>

      Single Button Dropdowns

    </h2>

    <p>

      Turn a button into a dropdown toggle with some basic markup changes.

    </p>

    <!-- =================================================
    BEGIN: Example
    ================================================== -->

    <div class="panel panel-overflow">

      <div class="panel-cell">

        <div class="button-group">

          <button type="button" class="button dropdown-toggle" data-toggle="dropdown" aria-expanded="false">

            Toggle Button

          </button>

          <span class="dropdown-menu" role="menu">

            <ul class="dropdown-menu-list">

              <li>

                <a href="#">

                  Action

                </a>

              </li>

              <li>

                <a href="#">

                  Another action

                </a>

              </li>

              <li>

                <a href="#">

                  Something else here

                </a>

              </li>

            </ul>

          </span>

        </div>

      </div>

      <div class="panel-cell panel-cell-light panel-cell-code-block">

<pre class="prettyprint transparent flush lang-html">
&lt;div class="button-group"&gt;
  &lt;button type="button" class="button dropdown-toggle" data-toggle="dropdown" aria-expanded="false"&gt;
    Toggle Button
  &lt;/button&gt;
  &lt;span class="dropdown-menu" role="menu"&gt;
    &lt;ul class="dropdown-menu-list"&gt;
      &lt;li&gt;
        &lt;a href="#"&gt;
          Action
        &lt;/a&gt;
      &lt;/li&gt;
      &lt;li&gt;
        &lt;a href="#"&gt;
          Another action
        &lt;/a&gt;
      &lt;/li&gt;
      &lt;li&gt;
        &lt;a href="#"&gt;
          Something else here
        &lt;/a&gt;
      &lt;/li&gt;
    &lt;/ul&gt;
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
  END: Single Button Dropdowns
  ================================================== -->

  <!-- =================================================
  BEGIN: Sizing
  ================================================== -->

  <section id="buttons-dropdowns-sizing">

    <h2>

      Button Dropdown Sizes

    </h2>

    <p>

      Button dropdowns work with buttons of all sizes.

    </p>

    <!-- =================================================
    BEGIN: Example
    ================================================== -->

    <div class="panel panel-overflow">

      <div class="panel-cell">

        <div class="button-collection button-collection-align-vertical-center flush-bottom">

          <div class="button-group">

            <button type="button" class="button button-jumbo dropdown-toggle" data-toggle="dropdown" aria-expanded="false">

              Jumbo

            </button>

            <span class="dropdown-menu" role="menu">

              <ul class="dropdown-menu-list">

                <li>

                  <a href="#">

                    Action

                  </a>

                </li>

                <li>

                  <a href="#">

                    Another action

                  </a>

                </li>

                <li>

                  <a href="#">

                    Something else here

                  </a>

                </li>

              </ul>

            </span>

          </div>

          <div class="button-group">

            <button type="button" class="button button-large dropdown-toggle" data-toggle="dropdown" aria-expanded="false">

              Large

            </button>

            <span class="dropdown-menu" role="menu">

              <ul class="dropdown-menu-list">

                <li>

                  <a href="#">

                    Action

                  </a>

                </li>

                <li>

                  <a href="#">

                    Another action

                  </a>

                </li>

                <li>

                  <a href="#">

                    Something else here

                  </a>

                </li>

              </ul>

            </span>

          </div>

          <div class="button-group">

            <button type="button" class="button dropdown-toggle" data-toggle="dropdown" aria-expanded="false">

              Medium

            </button>

            <span class="dropdown-menu" role="menu">

              <ul class="dropdown-menu-list">

                <li>

                  <a href="#">

                    Action

                  </a>

                </li>

                <li>

                  <a href="#">

                    Another action

                  </a>

                </li>

                <li>

                  <a href="#">

                    Something else here

                  </a>

                </li>

              </ul>

            </span>

          </div>

          <div class="button-group">

            <button type="button" class="button button-small dropdown-toggle" data-toggle="dropdown" aria-expanded="false">

              Small

            </button>

            <span class="dropdown-menu" role="menu">

              <ul class="dropdown-menu-list">

                <li>

                  <a href="#">

                    Action

                  </a>

                </li>

                <li>

                  <a href="#">

                    Another action

                  </a>

                </li>

                <li>

                  <a href="#">

                    Something else here

                  </a>

                </li>

              </ul>

            </span>

          </div>

          <div class="button-group">

            <button type="button" class="button button-mini dropdown-toggle" data-toggle="dropdown" aria-expanded="false">

              Mini

            </button>

            <span class="dropdown-menu" role="menu">

              <ul class="dropdown-menu-list">

                <li>

                  <a href="#">

                    Action

                  </a>

                </li>

                <li>

                  <a href="#">

                    Another action

                  </a>

                </li>

                <li>

                  <a href="#">

                    Something else here

                  </a>

                </li>

              </ul>

            </span>

          </div>

        </div>

      </div>

      <div class="panel-cell panel-cell-light panel-cell-code-block">

<pre class="prettyprint transparent flush lang-html">
&lt;div class="button-collection"&gt;
  &lt;div class="button-group"&gt;
    &lt;button type="button" class="button button-jumbo dropdown-toggle" data-toggle="dropdown" aria-expanded="false"&gt;
      Jumbo
    &lt;/button&gt;
    &lt;span class="dropdown-menu" role="menu"&gt;
      &hellip;
    &lt;/span&gt;
  &lt;/div&gt;

  &lt;div class="button-group"&gt;
    &lt;button type="button" class="button button-large dropdown-toggle" data-toggle="dropdown" aria-expanded="false"&gt;
      Large
    &lt;/button&gt;
    &lt;span class="dropdown-menu" role="menu"&gt;
      &hellip;
    &lt;/span&gt;
  &lt;/div&gt;

  &lt;div class="button-group"&gt;
    &lt;button type="button" class="button dropdown-toggle" data-toggle="dropdown" aria-expanded="false"&gt;
      Medium
    &lt;/button&gt;
    &lt;span class="dropdown-menu" role="menu"&gt;
      &hellip;
    &lt;/span&gt;
  &lt;/div&gt;

  &lt;div class="button-group"&gt;
    &lt;button type="button" class="button button-small dropdown-toggle" data-toggle="dropdown" aria-expanded="false"&gt;
      Small
    &lt;/button&gt;
    &lt;span class="dropdown-menu" role="menu"&gt;
      &hellip;
    &lt;/span&gt;
  &lt;/div&gt;

  &lt;div class="button-group"&gt;
    &lt;button type="button" class="button button-mini dropdown-toggle" data-toggle="dropdown" aria-expanded="false"&gt;
      Mini
    &lt;/button&gt;
    &lt;span class="dropdown-menu" role="menu"&gt;
      &hellip;
    &lt;/span&gt;
  &lt;/div&gt;
&lt;/div&gt;
</pre>

      </div>

    </div>

    <!-- =================================================
    END: Example
    ================================================== -->

  </section>

  <!-- =================================================
  END: Sizing
  ================================================== -->

  <!-- =================================================
  BEGIN: Styled button dropdowns
  ================================================== -->

  <section id="buttons-dropdowns-styled">

    <h2>

      Styled Button Dropdown

    </h2>

    <p>

      Button dropdowns work with all supported button styles. Add .button-stroke or any other included button style class to your button dropdown element. You can even combine styles.

    </p>

    <!-- =================================================
    BEGIN: Example
    ================================================== -->

    <div class="panel panel-overflow">

      <div class="panel-cell">

        <div class="button-collection button-collection-align-vertical-center flush-bottom">

          <div class="button-group">

            <button type="button" class="button dropdown-toggle" data-toggle="dropdown" aria-expanded="false">

              Button

            </button>

            <span class="dropdown-menu" role="menu">

              <ul class="dropdown-menu-list">

                <li>

                  <a href="#">

                    Action

                  </a>

                </li>

                <li>

                  <a href="#">

                    Another action

                  </a>

                </li>

                <li>

                  <a href="#">

                    Something else here

                  </a>

                </li>

              </ul>

            </span>

          </div>

          <div class="button-group">

            <button type="button" class="button button-stroke dropdown-toggle" data-toggle="dropdown" aria-expanded="false">

              Button

            </button>

            <span class="dropdown-menu" role="menu">

              <ul class="dropdown-menu-list">

                <li>

                  <a href="#">

                    Action

                  </a>

                </li>

                <li>

                  <a href="#">

                    Another action

                  </a>

                </li>

                <li>

                  <a href="#">

                    Something else here

                  </a>

                </li>

              </ul>

            </span>

          </div>

          <div class="button-group">

            <button type="button" class="button button-rounded dropdown-toggle" data-toggle="dropdown" aria-expanded="false">

              Button

            </button>

            <span class="dropdown-menu" role="menu">

              <ul class="dropdown-menu-list">

                <li>

                  <a href="#">

                    Action

                  </a>

                </li>

                <li>

                  <a href="#">

                    Another action

                  </a>

                </li>

                <li>

                  <a href="#">

                    Something else here

                  </a>

                </li>

              </ul>

            </span>

          </div>

          <div class="button-group">

            <button type="button" class="button button-stroke button-rounded dropdown-toggle" data-toggle="dropdown" aria-expanded="false">

              Button

            </button>

            <span class="dropdown-menu" role="menu">

              <ul class="dropdown-menu-list">

                <li>

                  <a href="#">

                    Action

                  </a>

                </li>

                <li>

                  <a href="#">

                    Another action

                  </a>

                </li>

                <li>

                  <a href="#">

                    Something else here

                  </a>

                </li>

              </ul>

            </span>

          </div>

          <div class="button-group">

            <button type="button" class="button button-primary dropdown-toggle" data-toggle="dropdown" aria-expanded="false">

              Button

            </button>

            <span class="dropdown-menu" role="menu">

              <ul class="dropdown-menu-list">

                <li>

                  <a href="#">

                    Action

                  </a>

                </li>

                <li>

                  <a href="#">

                    Another action

                  </a>

                </li>

                <li>

                  <a href="#">

                    Something else here

                  </a>

                </li>

              </ul>

            </span>

          </div>

          <div class="button-group">

            <button type="button" class="button button-success button-rounded dropdown-toggle" data-toggle="dropdown" aria-expanded="false">

              Button

            </button>

            <span class="dropdown-menu" role="menu">

              <ul class="dropdown-menu-list">

                <li>

                  <a href="#">

                    Action

                  </a>

                </li>

                <li>

                  <a href="#">

                    Another action

                  </a>

                </li>

                <li>

                  <a href="#">

                    Something else here

                  </a>

                </li>

              </ul>

            </span>

          </div>

          <div class="button-group">

            <button type="button" class="button button-danger button-rounded button-stroke dropdown-toggle" data-toggle="dropdown" aria-expanded="false">

              Button

            </button>

            <span class="dropdown-menu" role="menu">

              <ul class="dropdown-menu-list">

                <li>

                  <a href="#">

                    Action

                  </a>

                </li>

                <li>

                  <a href="#">

                    Another action

                  </a>

                </li>

                <li>

                  <a href="#">

                    Something else here

                  </a>

                </li>

              </ul>

            </span>

          </div>

        </div>

      </div>

    </div>

    <!-- =================================================
    END: Example
    ================================================== -->

  </section>

  <!-- =================================================
  END: Styled button dropdowns
  ================================================== -->

</section>

<!-- =================================================
END: Button Dropdowns
================================================== -->
