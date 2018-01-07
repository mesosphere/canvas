<!-- =================================================
BEGIN: Dropdown Dividers
================================================== -->

<section id="dropdowns-dividers">

  <h1>

    Menu Dividers

  </h1>

  <p>

    Dividers are a simple and effective way to break up a dropdown menu and create obvious separate between sets of dropdown menu lists.  Adding the class <code>.dropdown-menu-divider</code> to an empty <code>span</code> element is the fastest way to create a dropdown menu divider.

  </p>

  <!-- =================================================
  BEGIN: Example
  ================================================== -->

  <div class="panel flush-bottom">

    <div class="panel-cell">

      <div class="button-collection button-collection-align-vertical-center flush-bottom">

        <div class="dropdown force-open">

          <button type="button" class="button dropdown-toggle" data-toggle="dropdown" aria-expanded="false">

            Dropdown

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

            <span class="dropdown-menu-divider">
            </span>

            <ul class="dropdown-menu-list">

              <li>

                <a href="#">

                  Seperated Link

                </a>

              </li>

            </ul>

          </span>

        </div>

      </div>

    </div>

    <div class="panel-cell panel-cell-light panel-cell-code-block">

<pre class="prettyprint transparent flush lang-html">
&lt;span class="dropdown-menu" role="menu"&gt;
  &lt;span class="dropdown-menu-divider"&gt;
  &lt;/span&gt;
&lt;/span&gt;
</pre>

    </div>

  </div>

  <!-- =================================================
  END: Example
  ================================================== -->

</section>

<!-- =================================================
END: Dropdown Dividers
================================================== -->