<template>
  <div class="home">
    <form id="access-code-form" role="application" class="form-horizontal">
        <div class="pagelevel-main-content">
            <div class="pagelevel-content-header">
                <h2 class="heading-reset-bottom" id="access-heading">Access Code Entry</h2>
            </div>
            <div class="access-content">
                <p id="access-paragraph">Please enter your access code to begin registration</p>
                <input type="text" id="access-code" class="form-element-padding-md" autocomplete="new-password" placeholder="Access Code">
                <button id="verify-access-code" class="btn btn-primary form-element-padding full-width">Go</button>
                <a id="need-help" href="#">Need Help?</a>
            </div>
        </div>
    </form>
  </div>
</template>

<script>
// @ is an alias to /src
import "@/assets/static/site.css";

export default {
  name: 'Access',
  components: {
  }
}
</script>