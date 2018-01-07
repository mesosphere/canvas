<!-- =================================================
BEGIN: Panel Structure
================================================== -->

<section id="panels-cells">

  <h1>

    Panel Cell

  </h1>

  <p>

    The panel cell (<code>.panel-cell</code>) is the basic building block of panels. Any number of panel cells can be used in a panel.  Panel cells offer a variety of spacing and styling options.

  </p>

  <!-- =================================================
  BEGIN: Example
  ================================================== -->

  <div class="panel flush-bottom">

    <div class="panel-cell">

      <div class="panel panel-inline">

        <div class="panel-cell text-align-center">

          <code>.panel-cell</code>

        </div>

        <div class="panel-cell text-align-center">

          <code>.panel-cell</code>

        </div>

        <div class="panel-cell text-align-center">

          <code>.panel-cell</code>

        </div>

      </div>

    </div>

    <div class="panel-cell panel-cell-light panel-cell-code-block">

<pre class="prettyprint transparent flush lang-html">
&lt;div class="panel"&gt;
  &lt;div class="panel-cell"&gt;
    &hellip;
  &lt;/div&gt;
  &lt;div class="panel-cell"&gt;
    &hellip;
  &lt;/div&gt;
  &lt;div class="panel-cell"&gt;
    &hellip;
  &lt;/div&gt;
&lt;/div&gt;
</pre>

    </div>

  </div>

  <!-- =================================================
  END: Example
  ================================================== -->

  <!-- =================================================
  BEGIN: Panel Cell Size Modifiers
  ================================================== -->

  <section id="panels-cells-size-modifiers">

    <h2>

      Size Modifiers

    </h2>

    <p>

      To adjust the inner padding applied to a panel cell, use one of the available panel-specific size classes. For example, simply using the class <code>.panel-cell-short</code> will reduce padding evenly above and below the panel cell.  Use of these modifiers allows you the ability to create unique panel layouts to meet your specific project needs.

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

              .panel-cell-shorter

            </code>

          </td>

          <td>

            Reduce the vertical margins to 25%.

          </td>

        </tr>

        <tr>

          <td>

            <code>

              .panel-cell-short

            </code>

          </td>

          <td>

            Reduce the vertical margins to 50%.

          </td>

        </tr>

        <tr>

          <td>

            <code>

              .panel-cell-tall

            </code>

          </td>

          <td>

            Increase the vertical margins by 150%.

          </td>

        </tr>

        <tr>

          <td>

            <code>

              .panel-cell-taller

            </code>

          </td>

          <td>

            Increase the vertical margins by 200%.

          </td>

        </tr>

        <tr>

          <td>

            <code>

              .panel-cell-narrower

            </code>

          </td>

          <td>

            Reduce the horizontal margins to 25%.

          </td>

        </tr>

        <tr>

          <td>

            <code>

              .panel-cell-narrow

            </code>

          </td>

          <td>

            Reduce the horizontal margins to 50%.

          </td>

        </tr>

        <tr>

          <td>

            <code>

              .panel-cell-wide

            </code>

          </td>

          <td>

            Increase the horizontal margins by 150%.

          </td>

        </tr>

        <tr>

          <td>

            <code>

              .panel-cell-wider

            </code>

          </td>

          <td>

            Increase the horizontal margins by 200%.

          </td>

        </tr>

      </tbody>

    </table>

    <!-- =================================================
    BEGIN: Example
    ================================================== -->

    <div class="panel flush-bottom">

      <div class="panel-cell">

        <div class="row">

          <div class="column-12 column-small-6 column-medium-6 column-large-6 column-jumbo-5 column-jumbo-offset-1">

            <div class="panel">

              <div class="panel-cell">

                <h3 class="flush-top">

                  Event Name

                </h3>

                <p class="flush-bottom">

                  Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Maecenas sed diam eget risus varius blandit sit amet non magna. Duis mollis, est non commodo luctus.

                </p>

              </div>

              <div class="panel-cell panel-cell-short text-align-center">

                <a href="#" class="button button-primary">

                  Learn More &rarr;

                </a>

              </div>

            </div>

          </div>

          <div class="column-12 column-small-6 column-medium-6 column-large-6 column-jumbo-5">

            <div class="panel">

              <div class="layout-box pods-options-size-direction-modifier">

                <div class="layout-box-item layout-box-item-margin">

                  <div class="layout-box-item layout-box-item-padding panel-cell">

                    <div class="layout-box-item layout-box-item-content">

                      <h3 class="flush-top">

                        Event Name

                      </h3>

                      <p class="flush-bottom">

                        Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Maecenas sed diam eget risus varius blandit sit amet non magna. Duis mollis, est non commodo luctus.

                      </p>

                    </div>

                  </div>

                </div>

              </div>

              <div class="layout-box pods-options-size-direction-modifier">

                <div class="layout-box-item layout-box-item-margin">

                  <div class="layout-box-item layout-box-item-padding panel-cell panel-cell-short">

                    <div class="layout-box-item layout-box-item-content text-align-center">

                      <a href="#" class="button button-primary">

                        Learn More &rarr;

                      </a>

                    </div>

                  </div>

                </div>

              </div>

            </div>

          </div>

        </div>

      </div>

      <div class="panel-cell panel-cell-light panel-cell-code-block">

<pre class="prettyprint transparent flush lang-html">
&lt;div class="panel"&gt;
  &lt;div class="panel-cell"&gt;
    &hellip;
  &lt;/div&gt;
  &lt;div class="panel-cell panel-cell-short"&gt;
    &hellip;
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
  END: Panel Cell Size Modifiers
  ================================================== -->

  <!-- =================================================
  BEGIN: Panel Cell Size Direction Modifiers
  ================================================== -->

  <section id="panels-cells-size-direction-modifiers">

    <h2>

      Size Direction Modifiers

    </h2>

    <p>

      Add <code>-top</code>, <code>-right</code>, <code>-bottom</code>, or <code>-left</code> to the end of the size modifier class to adjust margin only in the direction implied by the direction modifier.

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

              .panel-cell-*-top

            </code>

          </td>

          <td>

            Adjust margin above the panel-cell.

          </td>

        </tr>

        <tr>

          <td>

            <code>

              .panel-cell-*-right

            </code>

          </td>

          <td>

            Adjust margin to the right of the panel-cell.

          </td>

        </tr>

        <tr>

          <td>

            <code>

              .panel-cell-*-bottom

            </code>

          </td>

          <td>

            Adjust margin below the panel-cell.

          </td>

        </tr>

        <tr>

          <td>

            <code>

              .panel-cell-*-left

            </code>

          </td>

          <td>

            Adjust margin to the left of the panel-cell.

          </td>

        </tr>

      </tbody>

    </table>

    <!-- =================================================
    BEGIN: Example
    ================================================== -->

    <div class="panel flush-bottom">

      <div class="panel-cell">

        <div class="row">

          <div class="column-12 column-small-6 column-medium-6 column-large-6 column-jumbo-5 column-jumbo-offset-1">

            <div class="panel">

              <div class="panel-cell panel-cell-taller-bottom panel-cell-wider-right">

                <h3 class="flush-top">

                  Event Name

                </h3>

                <p class="flush-bottom">

                  Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Maecenas sed diam eget risus varius blandit sit amet non magna. Duis mollis, est non commodo luctus.

                </p>

              </div>

            </div>

          </div>

          <div class="column-12 column-small-6 column-medium-6 column-large-6 column-jumbo-5">

            <div class="panel">

              <div class="layout-box pods-options-size-direction-modifier">

                <div class="layout-box-item layout-box-item-margin">

                  <div class="layout-box-item layout-box-item-padding panel-cell panel-cell-taller-bottom panel-cell-wider-right">

                    <div class="layout-box-item layout-box-item-content">

                      <h3 class="flush-top">

                        Event Name

                      </h3>

                      <p class="flush-bottom">

                        Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Maecenas sed diam eget risus varius blandit sit amet non magna. Duis mollis, est non commodo luctus.

                      </p>

                    </div>

                  </div>

                </div>

              </div>

            </div>

          </div>

        </div>

      </div>

      <div class="panel-cell panel-cell-light panel-cell-code-block">

<pre class="prettyprint transparent flush lang-html">
&lt;div class="panel"&gt;
  &lt;div class="panel-cell panel-cell-taller-bottom panel-cell-wider-right"&gt;
    &hellip;
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
  END: panels-cell Size Direction Modifiers
  ================================================== -->

</section>

<!-- =================================================
END: Panel Structure
================================================== -->
