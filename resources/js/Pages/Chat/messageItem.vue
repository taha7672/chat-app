<template>
  <div> 
  {{message.user.name}}<b>:</b>   {{ message.message}}

  </div>
</template>

<script>
export default {
props:['message'],
}
</script>

<style>

</style>