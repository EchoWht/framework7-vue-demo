<template>
  <f7-page>
    <f7-navbar title="Not found" back-link="Back"></f7-navbar>
    <f7-block strong>
      <p>Sorry</p>
      <p>Requested content not found.</p>
    </f7-block>
    <f7-block strong>
      <ul>
        <li><b>Url:</b> {{$f7route.url}}</li>
      </ul>
    </f7-block>
  </f7-page>
</template>
<script>
  export default {
    data(){
      return {
        
      }
    }
  };
</script>
