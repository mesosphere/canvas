---
layout: post
id: page-forms
title: Forms
page-header:
  headline: Forms
toc: true
---

<p>

  Individual form controls automatically receive some global styling. All textual <code>&lt;input&gt;</code>, <code>&lt;textarea&gt;</code>, and <code>&lt;select&gt;</code> elements with <code>.form-control</code> are set to <code>width: 100%;</code> by default. Wrap labels and controls in <code>.form-group</code> for optimum spacing.

</p>

<!-- =================================================
BEGIN: EXAMPLE
================================================== -->

<div class="panel flush-bottom">

  <div class="panel-cell">

    <form class="form flush-bottom">

      <div class="row">

        <div class="column-small-6">

          <div class="form-group">

            <label>

              First Name

            </label>

            <input type="text" class="form-control" placeholder="">

          </div>

        </div>

        <div class="column-small-6">

          <div class="form-group">

            <label>

              Last Name

            </label>

            <input type="text" class="form-control" placeholder="">

          </div>

        </div>

        <div class="column-small-6">

          <div class="form-group">

            <label>

              Email address

            </label>

            <input type="email" class="form-control" placeholder="email@domain.com">

            <p class="form-control-feedback">

              Please provide a valid email.

            </p>

          </div>

        </div>

        <div class="column-small-6">

          <div class="form-group">

            <label>

              Password

            </label>

            <input type="password" class="form-control" placeholder="">

            <p class="form-control-feedback">

              Must include at least 1 number and 1 symbol.

            </p>

          </div>

        </div>

        <div class="column-small-12">

          <div class="form-group">

            <label>

              About Me

            </label>

            <textarea class="form-control" rows="3"></textarea>

          </div>

        </div>

        <div class="column-small-12">

          <div class="form-group">

            <label>

              I am a...

            </label>

            <label class="form-control-toggle form-control-toggle-custom">

              <input type="radio" name="radio-group-a" checked="checked">

              <span class="form-control-toggle-indicator"></span>

              Man

            </label>

            <label class="form-control-toggle form-control-toggle-custom">

              <input type="radio" name="radio-group-a">

              <span class="form-control-toggle-indicator"></span>

              Woman

            </label>

            <label class="form-control-toggle form-control-toggle-custom">

              <input type="radio" name="radio-group-a">

              <span class="form-control-toggle-indicator"></span>

              Unicorn

            </label>

          </div>

        </div>

      </div>

      <div class="button-collection flush-bottom">

        <button type="submit" class="button button-primary">

          Submit

        </button>

      </div>

    </form>

  </div>

  <div class="panel-cell panel-cell-light panel-cell-code-block">

<pre class="prettyprint transparent flush lang-html">
&lt;form class="form flush-bottom"&gt;
&lt;div class="row"&gt;
  &lt;div class="column-small-6"&gt;
    &lt;div class="form-group"&gt;
      &lt;label&gt;
        First Name
      &lt;/label&gt;
      &lt;input type="text" class="form-control" placeholder=""&gt;
    &lt;/div&gt;
  &lt;/div&gt;
  &lt;div class="column-small-6"&gt;
    &lt;div class="form-group"&gt;
      &lt;label&gt;
        Last Name
      &lt;/label&gt;
      &lt;input type="text" class="form-control" placeholder=""&gt;
    &lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;
&hellip;
&lt;div class="button-collection flush-bottom"&gt;
  &lt;button type="submit" class="button button-primary"&gt;
    Submit
  &lt;/button&gt;
&lt;/div&gt;
&lt;/form&gt;
</pre>

  </div>

</div>

{% include components/forms/forms-controls.md %}
{% include components/forms/forms-controls-sizes.md %}
{% include components/forms/forms-controls-states.md %}
{% include components/forms/forms-controls-inverse-styling.md %}
{% include components/forms/forms-controls-feedback.md %}
{% include components/forms/forms-form-control-groups.md %}
