<template>
  <CFooter>
    <div>
      <a href="https://www.linkedin.com/in/sarahsahdas/" target="_blank"
        >Sarah Sahda Shabirah</a
      >
      <span class="ms-1"
        >&copy; {{ new Date().getFullYear() }} Universitas Brawijaya.</span
      >
    </div>
    <div class="ms-auto">
      <span class="me-1" target="_blank">Powered by</span>
      <a href="https://coreui.io/vue">
        <img src="@/assets/images/logo.png" />
      </a>
    </div>
  </CFooter>
</template>

<script>
export default {
  name: 'AppFooter',
}
</script>
