<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Here you can browse the latest on all the top social media feeds</h2>
    <br>
    <br>

    <div class="grid">

      <div class="item">
        <div class="item-content">
          <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/Instagram_logo_2016.svg/220px-Instagram_logo_2016.svg.png" alt="Instagram" height="150px" width="150px">
        </div>
      </div>
      <div class="item">
        <div class="item-content">
          <img src="http://www.alftanesskoli.is/library/Myndir/Merki-skolans/facebook-icon.png" alt="Facebook" height="150px" width="150px">
        </div>
      </div>
       <div class="item">
        <div class="item-content">
          <img src="http://ugab-jeunes.fr/wp-content/uploads/2015/07/icon320x320-300x300.jpeg" alt="Snapchat" height="150px" width="150px">
        </div>
      </div>
      <div class="item">
        <div class="item-content">
          <img src="https://seeklogo.com/images/T/twitter-2012-negative-logo-5C6C1F1521-seeklogo.com.png" alt="Twitter" height="150px" width="150px">
        </div>
      </div>
      <div class="item">
        <div class="item-content">
          <img src="https://pmcvariety.files.wordpress.com/2018/05/discord-logo.jpg?w=600&h=563&crop=1" alt="Discord" height="150px" width="150px">
        </div>
      </div>
      <div class="item">
        <div class="item-content">
          <img src="../assets/linkedin_png.png" alt="LinkedIn" height="150px" width="150px">
        </div>
      </div>
      
    </div>
  </div>
</template>


<script>

export default {
  name: 'Grid',
  props: {
    msg: String
  }
}
</script>

<style scoped>
.grid {
  position: relative;
}
.item {
  display: block;
  position: absolute;
  width: 150px;
  height: 150px;
  margin: 5px;
  z-index: 1;
}
img{
    border-radius: 25px;
}
.item.muuri-item-dragging {
  z-index: 3;
}
.item.muuri-item-releasing {
  z-index: 2;
}
.item.muuri-item-hidden {
  z-index: 0;
}
.item-content {
  position: relative;
  width: 100%;
  height: 100%;
}
</style>
