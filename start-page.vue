<template>    
  <div class="umb-grid">
    <div class="grid-section">
      <div class='dark'>
        <div class='container'>
          <div class="row clearfix">
            <div class="col-md-12 column">
              <div style='margin-bottom:60px;'>
                <h1 style='font-size:62px;text-align:center'>Välkommen till #K9forfun</h1>
                <h2 style='font-weight: 100; font-size: 40px;text-align:center'>Vi gillar hundar!<br>
                  Vi gillar att träna och tävla hund!<br>
                  Vi gillar att lära ut hur vi tränar hund för tävling!</h2>
              </div>
            </div>
            
            <div class="col-md-4 column">
              <div >
                <h2>Om oss</h2>
                <p>Här kan du läsa lite <router-link to="om">Om oss</router-link> i K9forfun</p>
                <p> </p>
              </div>
            </div>            
            
            <div class="col-md-4 column">
              <div >
                <h2>Boka oss</h2>
                <p>Vi erbjuder olika alternativ till träning.</p>
                <p>Om ni vill att vi ska komma ut till er klubb, eller annan plats, så har vi lite olika erbjudanden.</p>
                <p>Läs mer <router-link to="boka">här</router-link>. </p>
              </div>
            </div>            
            
            <div class="col-md-4 column">
              <div >
                <h2>Tips &amp; Tricks</h2>
                <p>Är ni nyfikna på oss. <router-link to="tips">Här</router-link> hittar du lite inspiration</p>
              </div>
            </div>    

          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
module.exports = {
  data: function() {
    return {
      who: "world"
    };
  }
};
</script>

<style>
.hello {
  background-color: #ffe;
}
</style>