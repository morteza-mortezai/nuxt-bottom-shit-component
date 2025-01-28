<template>
  <div class="container">
    <LayoutsDefaultAppHeader />
    <div class="content">
      <LayoutsDefaultAppSide />
      <slot />
    </div>
    <AppFooter />
  </div>
</template>
<style scoped >
.container{
  @apply mx-auto  min-h-screen flex flex-col ;
}
.container .content{
  @apply grow flex   ;
}
</style>